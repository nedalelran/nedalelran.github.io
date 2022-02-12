C:\Users\nelran>cd E:\MYWEBSITE

C:\Users\nelran>pwd
Der Befehl "pwd" ist entweder falsch geschrieben oder
konnte nicht gefunden werden.

C:\Users\nelran>e:

E:\MYWEBSITE>git ---version


E:\MYWEBSITE>git --version
git version 2.35.1.windows.2

E:\MYWEBSITE>dir
 Datenträger in Laufwerk E: ist Data
 Volumeseriennummer: E592-FD52

 Verzeichnis von E:\MYWEBSITE

12.02.2022  13:28    <DIR>          .
12.02.2022  13:28    <DIR>          ..
12.02.2022  13:28    <DIR>          css
12.02.2022  13:28    <DIR>          images
18.01.2022  13:17             8.406 index.html
12.02.2022  13:28    <DIR>          www
               1 Datei(en),          8.406 Bytes
               5 Verzeichnis(se), 63.303.245.824 Bytes frei

E:\MYWEBSITE>git init
Initialized empty Git repository in E:/MYWEBSITE/.git/

E:\MYWEBSITE>git add .

E:\MYWEBSITE>git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   css/style.css
        new file:   css/timeline.css
        new file:   images/div2.PNG
        new file:   images/div3.PNG
        new file:   images/profile.PNG
        new file:   index.html
        new file:   www/css/style.css
        new file:   www/function.js
        new file:   www/images
        new file:   www/index.html


E:\MYWEBSITE>git commit -m "first commit"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'nelran@Ibo.(none)')

E:\MYWEBSITE>git config --list
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
gui.recentrepo=E:/github/github-repo
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true

E:\MYWEBSITE>git config --global user.name "Nedal Elran"

E:\MYWEBSITE>git config --global user.email nelran_99@yahoo.com

E:\MYWEBSITE>git config --list
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
gui.recentrepo=E:/github/github-repo
user.name=Nedal Elran
user.email=nelran_99@yahoo.com
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true

E:\MYWEBSITE>git commit -m "first commit"
[master (root-commit) 9fe555c] first commit
 10 files changed, 705 insertions(+)
 create mode 100644 css/style.css
 create mode 100644 css/timeline.css
 create mode 100644 images/div2.PNG
 create mode 100644 images/div3.PNG
 create mode 100644 images/profile.PNG
 create mode 100644 index.html
 create mode 100644 www/css/style.css
 create mode 100644 www/function.js
 create mode 100644 www/images
 create mode 100644 www/index.html


E:\MYWEBSITE>git remote add origin https://github.com/nedalelran/nedalelran.github.io.git

E:\MYWEBSITE>git remote -v
origin  https://github.com/nedalelran/nedalelran.github.io.git (fetch)
origin  https://github.com/nedalelran/nedalelran.github.io.git (push)

E:\MYWEBSITE>git push -u origin mater
error: src refspec mater does not match any
error: failed to push some refs to 'https://github.com/nedalelran/nedalelran.github.io.git'

E:\MYWEBSITE>git push -u origin master
info: please complete authentication in your browser...
Enumerating objects: 15, done.
Counting objects: 100% (15/15), done.
Delta compression using up to 4 threads
Compressing objects: 100% (13/13), done.
Writing objects: 100% (15/15), 201.39 KiB | 16.78 MiB/s, done.
Total 15 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/nedalelran/nedalelran.github.io.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

E:\MYWEBSITE>