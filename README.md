### .nvmrc

Ok, I'm using Node 17.x or 18.x. How do I use Node 16.x for this project?
The easiest way is to use nvm. The course projects each have a .nvmrc file, so typing nvm use from the command line at the top level of the project will select the correct Node version for the project.

You may have to remove the node_modules folder and package-lock.json file, and run npm install again after switching node versions.


