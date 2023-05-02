# TXT
lmaxi@MSI MINGW64 /d/QA/TXT/TXT (main)
$ ls
LICENSE  README.md

lmaxi@MSI MINGW64 /d/QA/TXT/TXT (main)
$ touch new.txt

lmaxi@MSI MINGW64 /d/QA/TXT/TXT (main)
$ ls
LICENSE  README.md  new.txt

lmaxi@MSI MINGW64 /d/QA/TXT/TXT (main)
$ git add new.txt

lmaxi@MSI MINGW64 /d/QA/TXT/TXT (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   new.txt


lmaxi@MSI MINGW64 /d/QA/TXT/TXT (main)
$ git commit -m
error: switch `m' requires a value

lmaxi@MSI MINGW64 /d/QA/TXT/TXT (main)
$ git commit -m "cool"
[main 6172d85] cool
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 new.txt
 cat > new.txt
Maksimova Lyubov Pavlovna
49 years
I have 2 cats)
desired salary 200000 rubles
$ ls
LICENSE  README.md  new.txt

lmaxi@MSI MINGW64 /d/QA/TXT/TXT (main)
$ cat > preferences.txt
Guardians of the galaxy
and almost all the films of the Marvell Universe
I'm fond of Japanese, Georgian and Mediterranean cuisine
I like every season of the year.
I'd like to visit USA, Austria, France, UK, Germany and so on.

lmaxi@MSI MINGW64 /d/QA/TXT/TXT (main)
$ cat > skills.txt
My soft skills:
responsibility
enthusiasm
curiosity
decisiveness
sociability
attentiveness
My hard skills:
Terminal
Github
SQL
Devtools
Postman
Jmeter
Fidler
Charles
Mobile testing
Veb testing
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        preferences.txt
        skills.txt

nothing added to commit but untracked files present (use "git add" to track)

lmaxi@MSI MINGW64 /d/QA/TXT/TXT (main)
$ git add .
warning: in the working copy of 'preferences.txt', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'skills.txt', LF will be replaced by CRLF the next time Git touches it

lmaxi@MSI MINGW64 /d/QA/TXT/TXT (main)
$ git commit -m "else about me"
[main b3be640] else about me
 2 files changed, 25 insertions(+)
 create mode 100644 preferences.txt
 create mode 100644 skills.txt

lmaxi@MSI MINGW64 /d/QA/TXT/TXT (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

lmaxi@MSI MINGW64 /d/QA/TXT/TXT (main)
$ git push
Enter passphrase for key '/c/Users/lmaxi/.ssh/id_rsa':
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 722 bytes | 722.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:Lyubov-Maksimova/TXT.git
   c2a2910..b3be640  main -> main


