# hoodfuture.com
repository for the hoodfuture website!

We're building this thing from the ground up.

[jm](http://github.com/jermainemontiel) wrote a blog post [here](http://www.jermaine.fyi/posts/2016/09/the-tools) to explain the tools we'll be using to build it:

 - [Ghost](http://ghost.org) - an open-source blogging platform. We'll be using this as a CMS for the blog portion of the site. Ghost uses templates to serve up the content, so getting a design should be fairly painless.
 - [DigitalOcean](http://digitalocean.com) - this is where our site will be hosted. It's a VPS (virtual private server), which we'll need since Ghost is an app and will need a server to run -- which is different from normal web hosting.
 - [GitHub](http://github.com) - we're gonna do something special here that could have a lot of potential going forward as far as workflow. We'll use GitHub as our version control system and interface, and using webhooks we'll be able to quickly pull down changes to our production environment (our host server). This will cut down any friction we'd have when deploying changes to our site. 
 
After the server is set up and things are working correctly, we move into the design phase.
