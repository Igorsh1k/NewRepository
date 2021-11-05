# NewRepository

igork@DESKTOP-TVSASS1 MINGW64 /e/Ne ye repositiriem
$ git clone https://github.com/IrynaVovk/Site.git
Cloning into 'Site'...
remote: Enumerating objects: 20, done.
remote: Total 20 (delta 0), reused 0 (delta 0), pack-reused 20
Receiving objects: 100% (20/20), 593.88 KiB | 2.15 MiB/s, done.
Resolving deltas: 100% (3/3), done.

igork@DESKTOP-TVSASS1 MINGW64 /e/Ne ye repositiriem
$ git init
Initialized empty Git repository in E:/Ne ye repositiriem/.git/

igork@DESKTOP-TVSASS1 MINGW64 /e/Ne ye repositiriem (master)
$ cd ./GitTutorial
bash: cd: ./GitTutorial: No such file or directory

igork@DESKTOP-TVSASS1 MINGW64 /e/Ne ye repositiriem (master)
$ cd ./Site

igork@DESKTOP-TVSASS1 MINGW64 /e/Ne ye repositiriem/Site (master)
$ cd ./Site.git
bash: cd: ./Site.git: No such file or directory

igork@DESKTOP-TVSASS1 MINGW64 /e/Ne ye repositiriem/Site (master)
$ cd ./Site
bash: cd: ./Site: No such file or directory

igork@DESKTOP-TVSASS1 MINGW64 /e/Ne ye repositiriem/Site (master)
$ cd ./Site
bash: cd: ./Site: No such file or directory

igork@DESKTOP-TVSASS1 MINGW64 /e/Ne ye repositiriem/Site (master)
$ echo


igork@DESKTOP-TVSASS1 MINGW64 /e/Ne ye repositiriem/Site (master)
$ echo "example text 1" >>site

igork@DESKTOP-TVSASS1 MINGW64 /e/Ne ye repositiriem/Site (master)
$ touch 2.rb

igork@DESKTOP-TVSASS1 MINGW64 /e/Ne ye repositiriem/Site (master)
$ echo "example text 2" >>2.rb

igork@DESKTOP-TVSASS1 MINGW64 /e/Ne ye repositiriem/Site (master)
$ git commit -m"Second commit"
On branch master
Your branch is up to date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        2.rb
        site

nothing added to commit but untracked files present (use "git add" to track)

igork@DESKTOP-TVSASS1 MINGW64 /e/Ne ye repositiriem/Site (master)
$ git add .
warning: LF will be replaced by CRLF in 2.rb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in site.
The file will have its original line endings in your working directory

igork@DESKTOP-TVSASS1 MINGW64 /e/Ne ye repositiriem/Site (master)
$ git commit -m"Second commit"
[master 4eb4fae] Second commit
 2 files changed, 2 insertions(+)
 create mode 100644 2.rb
 create mode 100644 site

igork@DESKTOP-TVSASS1 MINGW64 /e/Ne ye repositiriem/Site (master)
$ git push
remote: Permission to IrynaVovk/Site.git denied to Igorsh1k.
fatal: unable to access 'https://github.com/IrynaVovk/Site.git/': The requested URL returned error: 403

igork@DESKTOP-TVSASS1 MINGW64 /e/Ne ye repositiriem/Site (master)
$ git push https://github.com/Igorsh1k/NewRepository.git
Enumerating objects: 24, done.
Counting objects: 100% (24/24), done.
Delta compression using up to 12 threads
Compressing objects: 100% (18/18), done.
Writing objects: 100% (24/24), 594.15 KiB | 198.05 MiB/s, done.
Total 24 (delta 4), reused 19 (delta 3), pack-reused 0
remote: Resolving deltas: 100% (4/4), done.
To https://github.com/Igorsh1k/NewRepository.git
 * [new branch]      master -> master

igork@DESKTOP-TVSASS1 MINGW64 /e/Ne ye repositiriem/Site (master)
$ git log
commit 4eb4faee11f782a257c49f054781c772d75f57d0 (HEAD -> master)
Author: Igorsh1k <igorkrasavshuk@gmail.com>
Date:   Fri Nov 5 22:05:10 2021 +0200

    Second commit

commit 426fefb944eb9af526ae21e336e1822c250582bc (origin/master, origin/HEAD)
Author: IrynaVovk <iryna.vovk.kep@gmail.com>
Date:   Fri Nov 17 19:33:33 2017 +0200

    Second commit

commit 4cf56e61788e24e684cdb04ba7571107b654fb55
Author: IrynaVovk <iryna.vovk.kep@gmail.com>
Date:   Fri Nov 17 19:13:47 2017 +0200

    First commit

igork@DESKTOP-TVSASS1 MINGW64 /e/Ne ye repositiriem/Site (master)
$
