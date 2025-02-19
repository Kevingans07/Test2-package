This is readme file to create git file

First, I put all the file in 1 folder called "Test2-package" inside my repo folder on mac

Secondly, I made header file for both system.h and disk.h

Then, I completed the missing code such as 
- include statement
- formula for distance in disk.cpp
- definition for system class called uniform

After all works, i tried to compile the code
g++ main.cpp disk.cpp system.cpp -o result      --> result here can be named anything
./ result

now, i checked my result in the view.py by typing "python view.py" in terminal

then for initializing git
1. type "git init"
2. then, you can see in your folder, there is a ".git" hidden file
3. I then made .gitignore by typing "touch .gitignore" to ignore unwanted file such as .DS_Store and confs/
4. Then, I typed git add, followed by git commit to commit all the updated changes

Then, i want to add all this files in my github
1. use gh auth login
2. create gh repo create Test2-package --public --source=. --remote=origin (to create new repo in github to store all my local files)
3. check git status
    type git add .
    type git commit -m "Initial commit"
4. i checked git branch to see whether it is main or master
    since it doesnt show anything, it means I havent created it yet
    i type "git checkout -b main"
5. since I already connected with my remote repository, then I type git push -u origin main
6. all my files are in github already


The result of the code is there are 9999 confs that produces balls moving randomly