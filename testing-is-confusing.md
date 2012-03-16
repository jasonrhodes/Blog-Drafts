## Adventures / Testing / #1 
# I have no clue how to start testing

We're getting better at this "website" stuff at Johns Hopkins. We use version control. We use a staging server for QA. We use Capistrano recipes to automate builds and deployments. We file bug reports and prioritize them into bugs vs. feature requests. We schedule releases. And nobody ever touches production. 

But we don't test a damn thing.

I mean, we click things. And we ask people to "email us if you see anything weird". The standard process. But in the weeks following every production deployment, I'm haunted by that familiar scent of dread that any untester knows so well. I really want to write tests, and run them during deployment.

The way testing evangelists talk, it's easy to get started with testing and Test Driven Development. I pretty much disagree. I've found it extremely difficult to break into the process, especially since most of the "how-to" is focused on how to write a test. That's fine, but I need to understand _what to test_, and how to decide. How to break a codebase down into testable units, and what parameters to use. 

I still know very little about how to get this started, but I'm going to write about it along the way.