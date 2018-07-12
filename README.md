# txto

***a GUI versus navigating
pwd تعرف انت فين 
ls القولدرات الموجوده 
ls -a كل الفولدرات حتى المخفى 
start (/open ) افتح 
~ $ open . لفتح مكانك
cd (or “change directory”) تغير الفولدر
.. indicates the parent directory
***creating and removing files
mkdir  new folder 
touch  new file new extantion
rm (or “remove”) 
rmdir ( remove empty folder )
rm -r remove non empty
342

from random import randint

def random_verb():
    # your code here
     num= randint(0,1)
     if num == 0:
         return "run"
     else:
         return "kayak"
             
print random_verb()




input and ouput 
										
randint(0,9)
split()
يتحول الجملة الى مقاطع استرينج 
list in word 
word not in list 
بتشوف لو الكلمة موجوده فى كلمة اخرى ولا لا 

lesson 13 اخر 4 فيديو 
lesson 14 video 14 
22
cd 
star .

git rebase it squash commits together gcollect commits in one 
git rebase -i HEAD~3

mv old .new  to rename 
 git log --oneline
 git log --stat
 git log -p       path
git log -p --stat stae info above path info
$ git log -w ignore whitespace
$ git commit -m "Initial commit"

# to list all branches
$ git branch
***a GUI versus navigating
pwd تعرف انت فين 
ls القولدرات الموجوده 
ls -a كل الفولدرات حتى المخفى 
start (/open ) افتح 
~ $ open . لفتح مكانك
cd (or “change directory”) تغير الفولدر
.. indicates the parent directory
***creating and removing files

In gitignore file , which symbol of the following , matches 0 or more characters
"*"

To change the commit message in the last commit we use the command
git commit --amend

To revert a commit we use the command
git revert commitSHA

To group the commits by author we use the command
git shortlog

Git to commit and add on the same time we use the command
git commit -am “your message”

to print all methods and attributes of a given object 
-- >>>>>>    dir()

How to list all tags in Git **
git tag 

mkdir  new folder 
touch  new file new extantion
rm (or “remove”) 
rmdir ( remove empty folder )
rm -r remove non empty
342
********************************************
from random import randint

def random_verb():
    # your code here
     num= randint(0,1)
     if num == 0:
         return "run"
     else:
         return "kayak"
             
print random_verb()
**************************************************



remote يربط
push يرفع من local ل git
pull ينزل من git لل local
pull = 1/2 fetch + 1/2 merge
fetch pull origin master only left local as it 
*****************************************************************
 n1 = mad_lib.find("NOUN")
    v1 = mad_lib.find("VERB")
    beforen1= mad_lib[:n1]
    aftern1= mad_lib[n1+4:]
    beforev1= mad_lib[:v1]
    afterv1= mad_lib[v1+4:]
    processed = beforen1 + word_transformer("NOUN")+word_transformer("VERB")
ailizing 
14 ---12 
***********************************************************************
# to create a new "footer-fix" branch
$ git branch footer-fix

# to delete the "footer-fix" branch
$ git branch -d footer-fix
y to switch to next branch
$ git checkout master
git checkout -b great and sitch to new branch

git log --oneline --decorate --graph --all
to show the all of changes in this repo 


git commit --amend
Modifying The Last Commit

git revert     
command is used to reverse a previously made commit:

will undo the changes that were made by the provided commit
creates a new commit to record the change

Reverting creates a new commit that reverts or undos a previous commit. Resetting, on the other hand, erases commits!

git reflog command.
 keep track of everything for about 30 days before it completely erases anything.

Recap
The git push command is used to send commits from a local repository to a remote repository.

$ git push origin master
The git push command takes:

the shortname of the remote repository you want to send commits to
the name of the branch that has the commits you want to send
