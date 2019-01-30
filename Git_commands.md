Most Basic Git Commands with Examples – a Welcome Introduction to Git

### …or create a new repository on the command line

echo "\# GitCode" \>\> README.md

git init

git add README.md

git commit -m "first commit"

git remote add origin git\@github.com:pkmedu/GitCode.git

git push -u origin master

### …or push an existing repository from the command line

git remote add origin git\@github.com:pkmedu/GitCode.git

git push -u origin master

**Example – Git cloning**

Pradip Muhuri\@Lenovo-PC MINGW64 \~ (master)

\$ git clone https://github.com/SAS-Class/LearnSAS.git

Cloning into 'LearnSAS'...

remote: Counting objects: 18, done.

remote: Compressing objects: 100% (15/15), done.

remote: Total 18 (delta 2), reused 0 (delta 0), pack-reused 0

Unpacking objects: 100% (18/18), done.

PMuhuri\@CCASTA-HWJP0G2 MINGW64 /c/sascourse/week2 (master)

\$ git mv Ex_put_putlog.sas Ex_put_putlog34.sas

PMuhuri\@CCASTA-HWJP0G2 MINGW64 /c/sascourse/week2 (master)

\$ git rm -f SASPy_test.sas

rm 'Week2/SASPy_test.sas'

PMuhuri\@CCASTA-HWJP0G2 MINGW64 /c/sascourse/week2 (master)

\$ git rm -f SASPy_test3.py

rm 'Week2/SASPy_test3.py'

[Removing files/folders in
Git](https://www.jquery-az.com/remove-file-directory-git/)

Scenarios/example commands:

-   Remove a file after a commit

-   Remove the file from the working tree or index only while keeping it in the
    file system

-   Remove the file only from the Git repository and not remove it from the
    filesystem, use:

git rm --cached file1.txt

git commit -m "remove file1.txt"

And to push changes to remote repo

git push origin branch_name

-   Remove a directory from the local repo and the remote rep (example below)

    git rm -r Week12

    git commit -m "Removed"

    git push

**Deleting multiple files example**

Suppose, we have a folder name “del-demo” that contains five text files
(tst1.txt, tst2.txt tst3.txt tst4.txt tst5.txt). We want to remove three files
by the single command and upload the changes. This is how it can be done:

\$ git rm del-demo/tst2.txt del-demo/tst3.txt del-demo/tst4.txt

**The output should be:**

rm ‘del-demo/tst2.txt’

rm ‘del-demo/tst3.txt’

rm ‘del-demo/tst4.txt’

Now run the commit command:

\$ git commit -m “Removed three text files”

Now you are good to go for making a push and making changes online.

[How to remove a file from the remote repo
(GitHub)?](https://stackoverflow.com/questions/2047465/how-can-i-delete-a-file-from-git-repo)

[Most Basic Git Commands with Examples – a Welcome Introduction to
Git](https://rubygarage.org/blog/most-basic-git-commands-with-examples)

PMuhuri\@CCASTA-HWJP0G2 MINGW64 /

\$ cd /c/sascourse

PMuhuri\@CCASTA-HWJP0G2 MINGW64 /c/sascourse (master)

\$ git branch -m backup_folders SASCourse_rev

PMuhuri\@CCASTA-HWJP0G2 MINGW64 /c/sascourse (master)

\$ git push origin :backup_folders

PMuhuri\@CCASTA-HWJP0G2 MINGW64 /c/sascourse (master)

\$ git push --set-upstream origin SASCourse_rev

PMuhuri\@CCASTA-HWJP0G2 MIN

![](media/604ef7104113f0cb7b1dc8a832d16f5b.png)
