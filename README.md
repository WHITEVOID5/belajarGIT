# belajarGIT
Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject

Daftar perintah GiT
Miracle@Miracle MINGW64 /d/GIT
$ git clone https://github.com/WHITEVOID5/belajarGIT
Cloning into 'belajarGIT'...
remote: Enumerating objects: 19, done.
remote: Counting objects: 100% (19/19), done.
remote: Compressing objects: 100% (12/12), done.
remote: Total 19 (delta 4), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (19/19), 6.30 KiB | 1.26 MiB/s, done.
Resolving deltas: 100% (4/4), done.

Miracle@Miracle MINGW64 /d/GIT
$ git init
Initialized empty Git repository in D:/GIT/.git/
Initialized empty Git repository in D:/GIT/.git/
bash: Initialized: command not found

Miracle@Miracle MINGW64 /d/GIT (master)
$ cd belajarGIT

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (main)
$ git branch Tugas-git

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git add Tugas-Git.txt

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-Git.txt


Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git config --global user.email"miraclelendo@gmail.com"

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git config --global user.name"WHITEVOID5"

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git commit -m "tugasgit"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Miracle@Miracle.(none)')

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git config --global user.email "miraclelendo@gmail.com"

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git config --global user.name "WHITEVOID5"

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git commit -m "tugasgit"
[Tugas-git 34d55e8] tugasgit
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
nothing to commit, working tree clean

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (main)
$ git merge Tugas-git
Updating f4b9604..34d55e8
Fast-forward
 Tugas-Git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 297 bytes | 297.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/WHITEVOID5/belajarGIT
   f4b9604..34d55e8  main -> main

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (main)
$ git branch Tugas-html

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-html)
$ git add Tugas-Html.txt

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-html)
$ git config --global user.email "miraclelendo@gmail.com"

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-html)
$ git config --global user.name "WHITEVOID5"

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-html)
$ git commit -m "tugashtml"
[Tugas-html 943baca] tugashtml
 1 file changed, 54 insertions(+)
 create mode 100644 Tugas-Html.txt

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
nothing to commit, working tree clean

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (main)
$ git merge Tugas-html
Updating 34d55e8..943baca
Fast-forward
 Tugas-Html.txt | 54 ++++++++++++++++++++++++++++++++++++++++++++++++++++++
 1 file changed, 54 insertions(+)
 create mode 100644 Tugas-Html.txt

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 916 bytes | 916.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/WHITEVOID5/belajarGIT
   34d55e8..943baca  main -> main

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (main)
$ git branch Tugas-css

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-css)
$ git add Tugas-Css.txt

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-css)
$ git config --global user.email "miraclelendo@gmail.com"

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-css)
$ git config --global user.name "WHITEVOID5"

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-css)
$ git commit -m "tugascss"
[Tugas-css 0e20580] tugascss
 1 file changed, 70 insertions(+)
 create mode 100644 Tugas-Css.txt

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-css)
$ git status
On branch Tugas-css
nothing to commit, working tree clean

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (main)
$ git merge Tugas-css
Updating 943baca..0e20580
Fast-forward
 Tugas-Css.txt | 70 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 1 file changed, 70 insertions(+)
 create mode 100644 Tugas-Css.txt

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.22 KiB | 1.22 MiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/WHITEVOID5/belajarGIT
   943baca..0e20580  main -> main

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (main)
$ git branch Tugas-js

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-js)
$ git add Tugas-Js.txt

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-js)
$ git config --global user.email "miraclelendo@gmail.com"

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-js)
$ git config --global user.name "WHITEVOID5"

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-js)
$ git commit -m "tugasjs"
[Tugas-js 9f2ec73] tugasjs
 1 file changed, 57 insertions(+)
 create mode 100644 Tugas-Js.txt

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-js)
$ git status
On branch Tugas-js
nothing to commit, working tree clean

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (main)
$ git merge Tugas-js
Updating 0e20580..9f2ec73
Fast-forward
 Tugas-Js.txt | 57 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 1 file changed, 57 insertions(+)
 create mode 100644 Tugas-Js.txt

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 900 bytes | 900.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/WHITEVOID5/belajarGIT
   0e20580..9f2ec73  main -> main

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (main)
$ git branch Tugas-midProject

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-midProject)
$ git add Tugas-MidProject.txt

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-midProject)
$ git config --global user.email "miraclelendo@gmail.com"

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-midProject)
$ git config --global user.email "miraclelendo@gmail.com"
Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-midProject)
$ git config --global user.email "miraclelendo@gmail.com"
Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-midProject)
$ git config --global user.name "WHITEVOID5"


Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-midProject)
$ git commit -m "tugasmidproject"
[Tugas-midProject 80f3e4e] tugasmidproject
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-MidProject.txt

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-midProject)
$ git status
On branch Tugas-midProject
nothing to commit, working tree clean

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (main)
$ git merge Tugas-midProject
Updating 9f2ec73..80f3e4e
Fast-forward
 Tugas-MidProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-MidProject.txt

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 700 bytes | 700.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/WHITEVOID5/belajarGIT
   9f2ec73..80f3e4e  main -> main

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (main)
$ git branch Tugas-php

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-php)
$ git add Tugas-Php.txt

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-php)
$ git config --global user.email "miraclelendo@gmail.com"

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-php)
$ git config --global user.name "WHITEVOID5"

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-php)
$ git commit -m "tugasphp"
[Tugas-php 4fd9038] tugasphp
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Php.txt

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-php)
$ git status
On branch Tugas-php
nothing to commit, working tree clean

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (main)
$ git merge Tugas-php
Updating 80f3e4e..4fd9038
Fast-forward
 Tugas-Php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Php.txt

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 300 bytes | 100.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/WHITEVOID5/belajarGIT
   80f3e4e..4fd9038  main -> main

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (main)
$ git branch Tugas-finalProject


Miracle@Miracle MINGW64 /d/GIT/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-finalProject)
$ git add Tugas-FinalProject.txt

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-finalProject)
$ git config --global user.email "miraclelendo@gmail.com"

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-finalProject)
$ git config --global user.name "WHITEVOID5"

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-finalProject)
$ git commit -m "tugasfinalproject"
[Tugas-finalProject d15f13e] tugasfinalproject
 1 file changed, 3 insertions(+)
 create mode 100644 Tugas-FinalProject.txt

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-finalProject)
$ git status
On branch Tugas-finalProject
nothing to commit, working tree clean

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (main)
$ git merge Tugas-finalProject
Updating 4fd9038..d15f13e
Fast-forward
 Tugas-FinalProject.txt | 3 +++
 1 file changed, 3 insertions(+)
 create mode 100644 Tugas-FinalProject.txt

Miracle@Miracle MINGW64 /d/GIT/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 295 bytes | 295.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/WHITEVOID5/belajarGIT
   4fd9038..d15f13e  main -> main

