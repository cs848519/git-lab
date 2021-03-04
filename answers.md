1. git version 2.30.0.windows.2 is the output
2. diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager-core
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
user.name=Colin Schuster
user.email=cs848519@ohio.edu
(END)
3. It opened up a new window for a git-add(1)Manual Page
4. On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        answers.md
        git-lab.cpp

nothing added to commit but untracked files present (use "git add" to track)
5. On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md
        git-lab.cpp
6. On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        git-lab.cpp
7.  On branch master
    Untracked files:
        (use "git add <file>..." to include in what will be committed)
              git-lab.cpp

    nothing added to commit but untracked files present (use "git add" to track)
8. commit cce24570c4deb02250986bde3738849d648895a0 (HEAD -> master)
    Author: Colin Schuster <cs848519@ohio.edu>
    Date:   Sat Feb 27 12:16:48 2021 -0500

        Initial commit
9.  On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   answers.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        git-lab.cpp

no changes added to commit (use "git add" and/or "git commit -a")
10. No the changes i made online weren't reflected in my local copy
11. To https://github.com/cs848519/git-lab.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/cs848519/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
12. yes the changes i made online were reflected in my local copy
13.  Directory: C:\Users\cschuster\desktop\cs2400\git-lab-2

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----          3/4/2021   2:38 PM            302 .gitignore
-a----          3/4/2021   2:38 PM             11 README.md
