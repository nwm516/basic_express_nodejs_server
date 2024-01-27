# Basic Express NodeJS Server
This was for an assignment in my Web Applications &amp; Development class to "Create a simple web server using Express in NodeJS, which will respond to different routes with text responses."

# Running the Server

I have found two ways in going about this:

<ins>Altering package.json:</ins> 
Including a "type" : "module" designation, and then additionally "start": "node express0.js" within the "scripts" identifier of the package.json file allowed me to run "express0.js" without needing to alter the filename.

"node express0.js" would successfully run the code with these alterations.

<ins>Running server as is:</ins>
Running "express0.js" as "express0.mjs" allowed the program to proceed and the server to run successfully. Otherwise, importing express caused errors to occur, citing issues with importing modules from outside.

"node express0.mjs" would successfully run the code with these alterations.
