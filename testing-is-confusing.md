# I'm really bad at testing

I know testing is important. I'm in the middle of dragging our web processes into 2005 here at Johns Hopkins, and we're making some progress. But now that we're storing our code in version control, developing on local test environments, pushing code to staging servers for QA, putting together comprehensive deployment recipes, and filing bug reports that lead to hotfixes before ever touching the production server code, there's a gaping hole in the middle of the whole thing: we don't test a damn thing.

--

_(eh this first sentence sucks)_ We're getting better at making web stuff at Johns Hopkins. We use version control. We use a staging server for QA. We use Capistrano recipes to automate builds and deployments. We file bug reports and prioritize them into bugs vs. feature requests. We schedule releases. And nobody ever touches production. 

But we don't test a damn thing.

I mean, we click things. And we ask people to "email us if you see anything weird". The standard process. But in the weeks following every production deployment, I'm haunted by that familiar scent of dread that any untester knows so well. I really want to write tests, and run them during deployment.

--vv-- is this P necessary?
I learned Ruby a couple of years ago, and I've played with Rails enough to know that Railsfolk are crazy about testing. It's impressive to watch how a community can get behind something and make it hip. Write a Rails app without RSpec and you'll be laughed out the door like a Github hacker. (see what i did there?)

Using my minimal knowledge of Ruby as a guide, I went after some definitions. First, there are a lot of fucking kinds of tests. 


```php
<?php
  $string = "This is a sample PHP code block.";
?>
```