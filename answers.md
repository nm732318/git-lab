Answer 1: git version 2.21.0.windows.1
--------------------------------------------------------------------------
Answer 2: core.symlinks=false
core.autocrlf=true
core.fscache=true
color.diff=auto
color.status=auto
color.branch=auto
color.interactive=true
help.format=html
rebase.autosquash=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
credential.helper=manager
user.name=Nicholas McGuigan
user.email=nm732318@ohio.edu
--------------------------------------------------------------------------
Answer 3: Inputting git --help opens the general help menu, which details
commonally used commands under accordingly grouped topics about git's various
functions.
--------------------------------------------------------------------------
Answer 4: On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        README.md
        README.md~
        answers.md
        answers.md~

nothing added to commit but untracked files present (use "git add" to track)
---------------------------------------------------------------------------
Answer 5: On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        README.md~
        answers.md
        answers.md~
-------------------------------------------------------------------------------
Answer 6: On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   README.md
        new file:   answers.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        README.md~
        answers.md~
---------------------------------------------------------------------------
Answer 7: On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   answers.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        README.md~
        answers.md~

no changes added to commit (use "git add" and/or "git commit -a")
----------------------------------------------------------------------------
Answer 8:
commit 0aa4d4ae3eea254208009ea5faecd1cb68ebb3e4 (HEAD -> master)
Author: Nicholas McGuigan <nm732318@ohio.edu>
Date:   Thu May 16 02:09:24 2019 +0100

    Initial commit
----------------------------------------------------------------------------
Answer 9: 
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   answers.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        README.md~
        answers.md~

no changes added to commit (use "git add" and/or "git commit -a")
-------------------------------------------------------------------------------
Answer 10: After updating and committing README.md on github via the browser,
there was no change to the file in my local directory.
-------------------------------------------------------------------------------
Answer 11: The git push command was rejected, as the remote directory
contained work that my local directory did not. Hence the error message:
To https://github.com/nm732318/git-lab.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/nm732318/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
-----------------------------------------------------------------------------
Answer 12: Upon using git pull, the changes made online were successfully
incorporated into the local copy of README.md.
-----------------------------------------------------------------------------
Answer 13: .  ..  .git  .gitignore  README.md
-----------------------------------------------------------------------------
