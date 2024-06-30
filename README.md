# Welcome to the kotlin Code Repository😊

Here I have been recording each and every step-by-step process of kotlin programming language learning process that i have chose and following. 

what are the softwares I am using :

IntelliJ Idea for coding 
git and github for version control and repository services

i'll try to update everything i learn so that coding lovers like me can be happier to see the  progress of kotlin programming language. 

so far in my first steps i have  learned the following things :
1.git clone 
2.git status
3.git add
5.git commit "commit""description" or git commit -am "desc"
4.git push -u origin master 
5.ssh-keygen -t  rsa -b 4096 -C "your_email@example.com"
after this use 
clip  < ~/.ssh/id_rsa.pub
add this to the ssh keys at github

eval  "$(ssh-agent -s)" 
ssh-add ~/testkey

#branching in git

git branch

To create  a new branch use :
    git checkout -b  <branch-name>
    git branch

#checking whether all are addded

in order to remove untracked files 
make a dry run :
git clean -n
make a pemanent removal :
git clean -f


pushing a new branch  to github
git push --set-upstream(-u) origin new-feature

restoration:
git restore <filename>

if you need to see the difference  between the files use :
git diff <filename>

this will show the difference between the files but also it wont be terminating the way either.When this happens use any of the options below:
 q + enter/return key(worked for me)
 ctrl + c to quit  
"hello World"

if you need to delete the code  use :
git branch -d branch-name
 