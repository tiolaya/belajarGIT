# Daftar Tugas / Branch
Tugas-git
Tugas-html
Tugas-css
Tugas-js
Tugas-midProject
Tugas-php
Tugas-finalProject
ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (main)
$ cd "C:\tugas git,github"

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github
$ git clone https://github.com/tiolaya/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github
$ cd belajarGIT

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (main)
$ git checkout -b Tugas-git
Switched to a new branch 'Tugas-git'

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (Tugas-git)
$ touch Tugas-Git.txt

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (Tugas-git)
$ git config --global user.email "mrdrthio@gmail.com"

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (Tugas-git)
$ git add Tugas-Git.txt

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan Tugas-Git.txt"
[Tugas-git 608fde9] Menambahkan Tugas-Git.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (main)
$ git merge Tugas-git
Updating c8c6951..608fde9
Fast-forward
 Tugas-Git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 304 bytes | 304.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/tiolaya/belajarGIT.git
   c8c6951..608fde9  main -> main

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (main)
$ git checkout -b Tugas-html
Switched to a new branch 'Tugas-html'

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (Tugas-html)
$ touch Tugas-Html.txt

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (Tugas-html)
$ git add Tugas-Html.txt

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan Tugas-Html.txt"
[Tugas-html 5c01d5d] Menambahkan Tugas-Html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Html.txt

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (main)
$ git merge Tugas-html
Updating 608fde9..5c01d5d
Fast-forward
 Tugas-Html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Html.txt

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 341 bytes | 341.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/tiolaya/belajarGIT.git
   608fde9..5c01d5d  main -> main

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (main)
$ git checkout -b Tugas-css
Switched to a new branch 'Tugas-css'

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (Tugas-css)
$ touch Tugas-Css.txt

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (Tugas-css)
$ git add Tugas-Css.txt

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan Tugas-Css.txt"
[Tugas-css 4708367] Menambahkan Tugas-Css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Css.txt

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (main)
$ git merge Tugas-css
Updating 5c01d5d..4708367
Fast-forward
 Tugas-Css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Css.txt

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 352 bytes | 352.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/tiolaya/belajarGIT.git
   5c01d5d..4708367  main -> main

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (main)
$ git checkout -b Tugas-js
Switched to a new branch 'Tugas-js'

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (Tugas-js)
$ touch Tugas-Js.txt

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (Tugas-js)
$ git add Tugas-Js.txt

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan Tugas-Js.txt"
[Tugas-js 8c1d1a5] Menambahkan Tugas-Js.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Js.txt

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (main)
$ git merge Tugas-js
Updating 4708367..8c1d1a5
Fast-forward
 Tugas-Js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Js.txt

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 302 bytes | 302.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/tiolaya/belajarGIT.git
   4708367..8c1d1a5  main -> main

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (main)
$ git checkout -b Tugas-midProject
Switched to a new branch 'Tugas-midProject'

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (Tugas-midProject)
$ touch Tugas-MidProject.txt

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (Tugas-midProject)
$ git add Tugas-MidProject.txt

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan Tugas-MidProject.txt"
[Tugas-midProject be3dc0d] Menambahkan Tugas-MidProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-MidProject.txt

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (main)
$ git merge Tugas-midProject
Updating 8c1d1a5..be3dc0d
Fast-forward
 Tugas-MidProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-MidProject.txt

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 304 bytes | 304.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/tiolaya/belajarGIT.git
   8c1d1a5..be3dc0d  main -> main

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (main)
$ git checkout -b Tugas-php
Switched to a new branch 'Tugas-php'

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (Tugas-php)
$ touch Tugas-Php.txt

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (Tugas-php)
$ git add Tugas-Php.txt

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan Tugas-Php.txt"
[Tugas-php 0636f4b] Menambahkan Tugas-Php.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Php.txt

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (main)
$ git merge Tugas-php
Updating be3dc0d..0636f4b
Fast-forward
 Tugas-Php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Php.txt

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 291 bytes | 291.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/tiolaya/belajarGIT.git
   be3dc0d..0636f4b  main -> main

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (main)
$ git checkout -b Tugas-finalProject
Switched to a new branch 'Tugas-finalProject'

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (Tugas-finalProject)
$ touch Tugas-FinalProject.txt

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (Tugas-finalProject)
$ git add Tugas-FinalProject.txt

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan Tugas-FinalProject.txt"
[Tugas-finalProject 5a16c62] Menambahkan Tugas-FinalProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-FinalProject.txt

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (main)
$ git merge Tugas-finalProject
Updating 0636f4b..5a16c62
Fast-forward
 Tugas-FinalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-FinalProject.txt

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 298 bytes | 298.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/tiolaya/belajarGIT.git
   0636f4b..5a16c62  main -> main

ASUS@DESKTOP-86BI2FJ MINGW64 /c/tugas git,github/belajarGIT (main)
$
