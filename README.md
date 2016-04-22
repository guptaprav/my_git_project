# Learning git
### login
git init
git config --global user.name "guptaprav"
git config --global user.email "guptaprav@gmail.com"
git config --global color.ui "auto"

### Status
git status

### Add some files
git add README.md #first file
git add first_file file_2 #multiple files

### Remove files
.. git rm --cached [file_name]

### Commit changes
git commit -m "My first commit" #commits added files to git

### Change file
git status

### Track changes
git diff
#git diff <filename>

### Stage changes in tracked files for next commit
git add -u
git commit

### Stage and commit in one command
git commit -a -m "Stage and commit" #with message

### Check history of git project
git log

### Details of last commit and file changes
git show
### git show <hash> # Details of particular commit

pwd
/Users/pgupta/work/my_git_project

git remote add origin https://github.com/guptaprav/my_git_project.git

git push -u origin master
Username for 'https://github.com': guptaprav
Password for 'https://guptaprav@github.com': 
remote: Repository not found.
fatal: repository 'https://github.com/guptaprav/my_git_project.git/' not found

git remote add origin https://github.com/guptaprav/my_git_project.git
fatal: remote origin already exists.

git push -u origin master
Username for 'https://github.com': guptaprav
Password for 'https://guptaprav@github.com': 
Counting objects: 11, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (9/9), done.
Writing objects: 100% (11/11), 1.18 KiB | 0 bytes/s, done.
Total 11 (delta 2), reused 0 (delta 0)
To https://github.com/guptaprav/my_git_project.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.

