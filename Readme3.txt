Microsoft Windows [Version 10.0.10240]
(c) 2015 Microsoft Corporation. All rights reserved.

C:\Users\TYSS>e:

E:\>cd MyFiles

E:\MyFiles>cd..

E:\>cd Mygit

E:\Mygit>git init
Initialized empty Git repository in E:/Mygit/.git/

E:\Mygit>git add E:\MyFiles\ReadMe.txt
fatal: E:\MyFiles\ReadMe.txt: 'E:\MyFiles\ReadMe.txt' is outside repository

E:\Mygit>git add ReadMe.txt

E:\Mygit>git add ReadMe.txt

E:\Mygit>git commit -m "My First Message"

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'TYSS@TYSS-TR-0011.(none)')

E:\Mygit>git remote add origin https://github.com/DheerajThakur41/githubPractice.git

E:\Mygit>git push -u origin master
error: src refspec master does not match any.
error: failed to push some refs to 'https://github.com/DheerajThakur41/githubPractice.git'

E:\Mygit>

E:\Mygit> git config --global user.email "you@example.com"

E:\Mygit> git config --global user.name "DheerajThakur41"

E:\Mygit>git push -u origin master
error: src refspec master does not match any.
error: failed to push some refs to 'https://github.com/DheerajThakur41/githubPractice.git'

E:\Mygit>git remote add origin https://github.com/DheerajThakur41/githubPractice.git
fatal: remote origin already exists.

E:\Mygit>git push -u origin master
error: src refspec master does not match any.
error: failed to push some refs to 'https://github.com/DheerajThakur41/githubPractice.git'

E:\Mygit> git config --global user.email "dheerajthakur64@yahoo.in"

E:\Mygit> git config --global user.name "DheerajThakur41"

E:\Mygit>git push -u origin master
error: src refspec master does not match any.
error: failed to push some refs to 'https://github.com/DheerajThakur41/githubPractice.git'

E:\Mygit>git commit -m "My First Message"
[master (root-commit) 9cc0aa8] My First Message
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 ReadMe.txt

E:\Mygit>git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 225 bytes | 225.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/DheerajThakur41/githubPractice.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

E:\Mygit>git commit -m "Do Changes"
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
        modified:   ReadMe.txt

no changes added to commit

E:\Mygit>git push -u origin master
Everything up-to-date
Branch 'master' set up to track remote branch 'master' from 'origin'.

E:\Mygit>git commit -m "My First"
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
        modified:   ReadMe.txt

no changes added to commit

E:\Mygit>git commit -m "Do Chang"
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
        modified:   ReadMe.txt

no changes added to commit

E:\Mygit>git add * commit -m "My First"
error: unknown switch `m'
usage: git add [<options>] [--] <pathspec>...

    -n, --dry-run         dry run
    -v, --verbose         be verbose

    -i, --interactive     interactive picking
    -p, --patch           select hunks interactively
    -e, --edit            edit current diff and apply
    -f, --force           allow adding otherwise ignored files
    -u, --update          update tracked files
    --renormalize         renormalize EOL of tracked files (implies -u)
    -N, --intent-to-add   record only the fact that the path will be added later
    -A, --all             add changes from all tracked and untracked files
    --ignore-removal      ignore paths removed in the working tree (same as --no-all)
    --refresh             don't add, only refresh the index
    --ignore-errors       just skip files which cannot be added because of errors
    --ignore-missing      check if - even missing - files are ignored in dry run
    --chmod <(+/-)x>      override the executable bit of the listed files


E:\Mygit>git add *

E:\Mygit>git commit -m "Do Chang"
[master 8e89fc0] Do Chang
 1 file changed, 2 insertions(+)

E:\Mygit>git push -u origin master
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 263 bytes | 263.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/DheerajThakur41/githubPractice.git
   9cc0aa8..8e89fc0  master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

E:\Mygit>git add *

E:\Mygit>git commit -m "New file"
[master ea90bb9] New file
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 readme2.txt

E:\Mygit>git push -u origin master
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 280 bytes | 280.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/DheerajThakur41/githubPractice.git
   8e89fc0..ea90bb9  master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

E:\Mygit>git add *

E:\Mygit>git commit -m "New"
[master e052d75] New
 1 file changed, 0 insertions(+), 0 deletions(-)
 delete mode 100644 readme2.txt

E:\Mygit>git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads.
Compressing objects: 100% (1/1), done.
Writing objects: 100% (2/2), 238 bytes | 238.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0)
To https://github.com/DheerajThakur41/githubPractice.git
   ea90bb9..e052d75  master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

E:\Mygit>git pull  origin
remote: Counting objects: 3, done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From https://github.com/DheerajThakur41/githubPractice
   e052d75..cae00b3  master     -> origin/master
Updating e052d75..cae00b3
Fast-forward
 Readme3.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Readme3.txt
