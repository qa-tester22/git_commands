# Testing

We are here to test you website, app with best practices.

# This is git commands

git --version
git config --global user.name "qa-tester22"
git config --global user.email "wavenlondon@gmail.com"
mkdir myproject
cd myproject
git init
ls
git status
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
git commit -m "added new image"
git checkout main
git merge hello-devs-images
