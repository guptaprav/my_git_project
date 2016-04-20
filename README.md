git init
git config --global user.name "guptaprav"
git config --global user.email "guptaprav@gmail.com"
git config --global color.ui "auto"

git status

# Add some files
git add README.md #first file
git add first_file file_2 #multiple files

# Remove files
# git rm --cached [file_name]

# Commit changes
git commit -m "My first commit" #commits added files to git

# Change file
git status

# Track changes
git diff
#git diff <filename>

# Prepare git to save changes in tracked files for next commit
git add -u
