# Installing Node.js on Mac

Go to, http://nodejs.org/#download and downloadthenode-v*.pkg
Macintoshinstaller by clicking on the link.

Once the download is finished, click on the downloaded file to run it. You will then get the first wizard dialog box


# Running Node
Now you are ready to start using Node. First you can simply experiment running Node as a command-line interface (CLI). For that you need only to call the Node executable with no argu- ments like this:
$ node
This will start the CLI, which will then wait for you to input an expression. Just to test the installa- tion and see Node actually doing something, you can type:
> console.log('Hello World!'); Hello World!
> undefined
You can also run a JavaScript script from a file. For instance, if you create a file with this content:
console.log('Hello World!');
Name the file hello_world.js. Then run the file by passing the file path as first argument to the
Node executable while inside a shell prompt. For example: $ node hello_world.js
Hello World!
You can quit the CLI by typing Ctrl+D or Ctrl+C.
