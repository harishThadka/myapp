# myapp

## About Express:
Read the code & explore the "hello, world!" app at https://expressjs.com/en/starter/hello-world.html 
https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction

Look up JavaScript Template Literals. Read about them (preferably on MDN).  
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals

Why do we use backticks for the log string (instead of single or double quotes)?  
https://medium.com/better-programming/javascript-how-backticks-work-de269e0fb8ba

## Express Generator:

Read about the Express Generator at https://expressjs.com/en/starter/generator.html  
run `npx express-generator --git` 
The --git flag will automatically create the .gitignore we mention below. If you don't use the flag, just add it below.  
Run `npm install` to automatically fetch all the dependencies listed in package.json and store them in the node_modules folder.  Follow any suggestions to run `npm audit fix` if requested.   
Follow the instructions and use `npm start` to start the app locally.

## Git Source Control:

Initialize a git project in your local folder by opening GitBash and running `git init`  
Set origin alias by running your custom  git remote add origin <URL> command shown after Step 1.   
Add 2 important files  
.gitignore: - add a new file in the root folder named .gitignore  
README.md - add a new file in the root folder named README.md
In your .gitignore add one line:  node_modules  
Create a short, professional README.md.   
Add all files (note the space dot at the end of the command!) with git add   
Commit your changes locally with git commit -m "first commit"  
Push changes to your empty cloud repo with git push -u origin master  
*The .gitignore file tells git which files should NOT be committed to the repo.  In this case, we don't want the node_modules folder to be included (we can regenerate all this easily).*

The README.md is part of every professional repository.

Always add these two files to every Express project.

## jade vs pug:
link:  https://www.stackshare.io/stackups/jade-language-vs-pug

## Heroku:

https://devcenter.heroku.com/articles/getting-started-with-nodejs  

Updating Git app name:
https://devcenter.heroku.com/articles/renaming-apps#updating-git-remotes

## References:

https://www.sitepoint.com/jade-tutorial-for-beginners/  
https://expressjs.com/en/starter/generator.html  


