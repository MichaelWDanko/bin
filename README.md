#Diamond

ABOUT: 
---
#####This shell script will automatically create the following directories where you run Diamond:
- js
- css
- scss
- It will also run the commands that you need to install "Bourbon" followed by "Neat".

#####The following files will also be created and stored in their respective folders.:
-  "index.html" with the basic skeleton of an HTML file.
-  "index.scss" with the text "@import bourbon; @import neat;" already written.
-  "app.js" 


INSTALL:
---
####Edit $PATH
I cloned my repo within my User folder.
Wherever you cloned the repo, you want to edit your $PATH so that your shell will know to look in your folder for the Diamond script. 

<code>export PATH=$PATH:~/bin/</code> 

Verify this directory has been added by running <code>echo $PATH</code> and seeing your new directory added at the end.
Go to the directory and clone the repo</p>

####Adding execute priviledges to file.
While in the bin directory, you need to make the script executable. To do so, use the following shell command:

<code>chmod +x diamond</code>

RUN:
---
Now you can use the diamond script within any given directory to create your skeleton of a new project. To do this, just call on the diamond script like this. <code>~/bin/diamond</code>


Push Files to Git
---
#####This will only work if you've already copied a repo from GitHub!
After you've run the diamond script, you can run another script from the same directory to push your new files to GitHub.

<code>~/bin/diamondgit</code>

It inputs a generic commit message already for you.

