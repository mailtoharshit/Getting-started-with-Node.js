# Node.js - Server Side Javascript

cover_small.jpg

Node.js is a server-side technology that's based on Google's V8 JavaScript engine. It's a highly scalable system that uses asynchronous event-driven I/O (input/output), rather than threads or separate processes.

It's ideal for web applications that are frequently accessed, but computationally simple. If you're using a traditional web server, such as Apache, each time a web resource is requested, Apache creates a separate thread or invokes a new process in order to process the request.

Even though Apache responds quickly to requests, and cleans up after the request has been satisfied, this approach can still tie up a lot of resources. A popular web application is going to have serious performance issues. Node, on the other hand, doesn't create a new thread or process for every request. Instead, it listens for
specific events, and when the event happens, responds accordingly.

Node doesn't block any other request while waiting for the event functionality to complete, and events are processed, first come, first served, in a relatively uncomplicated event loop. Node applications are created with JavaScript (or alternative language that compiles to JavaScript). The JavaScript is the same as you'd use in your client-side applications. However, unlike JavaScript in a
browser, you have to set up a development environment for Node.

Node can be installed in a Unix/Linux, Mac OS, or Windows environment This chapter is going to walk you through setting up a development environment for Node in Windows 7 and Linux (Ubuntu). Installation on a Mac should be similar to installation on Linux. I'm also covering any requirements or preparation you need to take before installing the application.

Once your development environment is operational, I'm going to demonstrate a basic Node application and walk you through the important bits, the event loop I mentioned earlier, so you can try Node yourself.
