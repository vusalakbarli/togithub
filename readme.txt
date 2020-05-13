
Admin@PC001 MINGW64 ~/Desktop/togithub (master)
$ git commit -m "first"
On branch master
nothing to commit, working tree clean

Admin@PC001 MINGW64 ~/Desktop/togithub (master)
$ git status
On branch master
nothing to commit, working tree clean

Admin@PC001 MINGW64 ~/Desktop/togithub (master)
$ git init
Reinitialized existing Git repository in C:/Users/Admin/Desktop/togithub/.git/

Admin@PC001 MINGW64 ~/Desktop/togithub (master)
$ git status
On branch master
nothing to commit, working tree clean

Admin@PC001 MINGW64 ~/Desktop/togithub (master)
$ git log
commit 1952bcd739b0fbdd69fadb7ac141e2e2e5649beb (HEAD -> master)
Author: Vusal <Vusal>
Date:   Wed May 13 10:10:28 2020 +0400

    first

Admin@PC001 MINGW64 ~/Desktop/togithub (master)
$ git status
On branch master
nothing to commit, working tree clean

Admin@PC001 MINGW64 ~/Desktop/togithub (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        2.txt

nothing added to commit but untracked files present (use "git add" to track)

Admin@PC001 MINGW64 ~/Desktop/togithub (master)
$  git add .

Admin@PC001 MINGW64 ~/Desktop/togithub (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   2.txt


Admin@PC001 MINGW64 ~/Desktop/togithub (master)
$ git commit -m "second"
[master f7055e4] second
 1 file changed, 1 insertion(+)
 create mode 100644 2.txt

Admin@PC001 MINGW64 ~/Desktop/togithub (master)
$ git status
On branch master
nothing to commit, working tree clean

Admin@PC001 MINGW64 ~/Desktop/togithub (master)
$ git remote add origin https://github.com/vusalakbarli/togithub.git
fatal: remote origin already exists.

Admin@PC001 MINGW64 ~/Desktop/togithub (master)
$ git push -u origin master
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (6/6), 418 bytes | 418.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/vusalakbarli/togithub.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

Admin@PC001 MINGW64 ~/Desktop/togithub (master)
$
