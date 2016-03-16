#bin
A repository to store my shell scripts.

#ABOUT: 
This shell script will automatically create the following directories where you run Diamond:
<br>- js
<br>- css
<br>- scss
<br>It will also run the commands that you need to install "Bourbon" followed by "Neat".

The following files will also be created and stored in their respective folders.:
<br>-  "index.html" with the basic skeleton of an HTML file.
<br>-  "index.scss" with the text "@import bourbon; @import neat;" already written.
<br>-  "app.js" 

#INSTALL:
I stored this program in a folder "bin" within my User folder. Whichever folder you use, you want to edit your $PATH so that your shell will know to look in your folder for the Diamond script. 

export PATH=$PATH:~/bin/ with ~/bin/ being where you want to store this script. (Make sure that this directory exists already)
Verify this directory has been added by running echo $PATH and seeing your new directory added at the end.
Go to the directory and clone the repo




