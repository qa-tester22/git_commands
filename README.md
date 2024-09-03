# Testing

We are here to test you website, app with best practices.

## This is git commands

git --version
git config --global user.name "qa-tester22"
git config --global user.email "wavenlondon@gmail.com"
mkdir myproject
cd myproject
git init
ls
git status

# Create a file and add the file to Git

git add index.html
git add --all

# The shorthand command for git add --all is git add -A

git commit -m "First release of Testing"
git status --short

# Note: Short status flags are:

?? - Untracked files
A - Files added to stage
M - Modified files
D - Deleted files

git commit -a -m "Updated index.html with a new line"
git log
git command -help - See all the available options for the specific command
git help --all - See all possible commands

# If you find yourself stuck in the list view, SHIFT + G to jump the end of the list, then q to exit the view.

git branch hello-devs-images
git branch
git checkout hello-devs-images
git add -all
git commit -m "added new images"
git checkout main
git merge hello-devs-images
git branch -d hello-devs-images

## GitHub

git remote add origin https://github.com/qa-tester22/git_commands.git
git push --set-upstream origin main
git fetch origin
git status
git log origin/main
git diff origin/main

# merge
git merge origin/main
git status

git pull // equal fetch + merge

# push
git commit -a -m "Updated index.html. Resized image"
get status
git push origin

