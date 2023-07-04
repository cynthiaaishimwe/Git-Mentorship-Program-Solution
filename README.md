# Bundle 1  
## Exercise 1



`student@student-ThinkPad-X250:~/Documents/git-practise$ git branch
student@student-ThinkPad-X250:~/Documents/git-practise$ git init
Initialized empty Git repository in /home/student/Documents/git-practise/.git/
student@student-ThinkPad-X250:~/Documents/git-practise$ git add .
student@student-ThinkPad-X250:~/Documents/git-practise$ git commit -m "added 3 files"
[master (root-commit) 5322552] added 3 files
 3 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 index.css
 create mode 100644 index.html
 create mode 100644 index.js
student@student-ThinkPad-X250:~/Documents/git-practise$ git branch -m main
student@student-ThinkPad-X250:~/Documents/git-practise$ git branch -M main
student@student-ThinkPad-X250:~/Documents/git-practise$ git remote add origin https://github.com/cynthiaaishimwe/Git-Mentorship-Program.git
student@student-ThinkPad-X250:~/Documents/git-practise$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 230 bytes | 230.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/cynthiaaishimwe/Git-Mentorship-Program.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.
student@student-ThinkPad-X250:~/Documents/git-practise$ git clone https://github.com/cynthiaaishimwe/Git-Mentorship-Program.git
Cloning into 'Git-Mentorship-Program'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 3 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 210 bytes | 210.00 KiB/s, done.
student@student-ThinkPad-X250:~/Documents/git-practise$ git branch
* main
student@student-ThinkPad-X250:~/Documents/git-practise$ git checkout -b dev
Switched to a new branch 'dev'
student@student-ThinkPad-X250:~/Documents/git-practise$ cd dev
bash: cd: dev: No such file or directory
student@student-ThinkPad-X250:~/Documents/git-practise$ git branch
* dev
  main
student@student-ThinkPad-X250:~/Documents/git-practise$ git checkout -b test
Switched to a new branch 'test'
student@student-ThinkPad-X250:~/Documents/git-practise$ git branch
  dev
  main
* test
student@student-ThinkPad-X250:~/Documents/git-practise$ git checkout dev
Switched to branch 'dev'
student@student-ThinkPad-X250:~/Documents/git-practise$ git branch
* dev
  main
  test
student@student-ThinkPad-X250:~/Documents/git-practise$ git branch -d test
Deleted branch test (was 5322552).
student@student-ThinkPad-X250:~/Documents/git-practise$ 
 *  History restored 

`


