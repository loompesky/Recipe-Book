INTRODUCTION
Welcome to our collaborative recipe book project! In this project, you will work in a team of 5 to create a recipe book containing each member's favorite recipe.

To manage the version control of the recipe book, we will be using Git and GitHub. Each team member will be responsible for creating their own branch and adding their recipe to the book. This will allow us to collaborate efficiently while keeping track of all changes made to the project.

GOAL
Throughout the project, you will learn how to use Git and GitHub to create, commit, and push changes to your own branches. You will also learn how to merge changes from other branches and resolve conflicts that may arise during the process.

EVALUATIONS
Once the recipe book is completed, teams will share the final version on GitHub for others to view and enjoy. This will not only showcase your collaboration and technical skills but also your creativity and passion for good food.

So, get ready to work as a team, learn new skills, and create a mouthwatering recipe book that everyone will love!

Steps
1. create a repo in your github account giving it a Name 'Recipe Book'
2. Go to your local machine and launch Git CLI or Git Bash
3. cd (change directory to the a folder created on your local machine) eg cd D: , ls -ltr(to see the content ie when using Bash) or dir to see the folders if using CMD
4. cd D: then cd "Recipe Book" , double quote because there is space between
5.  create your README.md file using vi on bash this is to talk about the project discription and the steps
6.  create your fist recipe food in the master branch ie git init, git add . ,git commit -m 'mymessage' , git remote add origin https://github.com/loompesky/Recipe-Book.git, git push
7.  git branch -a[to see the list of branches in your working space], git branch Yam [to create a new branch without switching to the new branch]/git checkout Yam{to switch to this branch called Yam}, or git checkout Yam{this will switch automatically to the new branch created}
8.  vi a file called 'Yam' and then write your recipe then save the file
9.  Now in the Yam branch, git add ., git commit -m 'Yam recipe', git push will throw this error "fatal: The current branch Yam has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin Yam

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'."
10. git push --set-upstream origin Yam


This project was created by Prince Frimpong
Reachout and lets collaborate
WhatsApp +233241324413
LinkedIn: www.linkedin.com/in/frimpong-prince
