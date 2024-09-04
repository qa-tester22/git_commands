# Testing

We are here to test you website, app with best practices.

## This is git commands

git --version <br>
git config --global user.name "qa-tester22"<br>
git config --global user.email "wavenlondon@gmail.com"<br>
mkdir myproject<br>
cd myproject<br>
git init<br>
ls<br>
git status<br>

# Create a file and add the file to Git

git add index.html<br>
git add --all<br>

# The shorthand command for git add --all is git add -A

git commit -m "First release of Testing"<br>
git status --short<br>

# Note: Short status flags are:

?? - Untracked files<br>
A - Files added to stage<br>
M - Modified files<br>
D - Deleted files<br>

git commit -a -m "Updated index.html with a new line"<br>
git log<br>
git command -help - See all the available options for the specific command<br>
git help --all - See all possible commands<br>

# If you find yourself stuck in the list view, SHIFT + G to jump the end of the list, then q to exit the view.

# branch

git branch hello-devs-images<br>
git branch<br>
git checkout hello-devs-images<br>
git add -all<br>
git commit -m "added new images"<br>
git checkout main<br>
git merge hello-devs-images<br>
git branch -d hello-devs-images<br>

## GitHub

git remote add origin https://github.com/qa-tester22/git_commands.git<br>
git push --set-upstream origin main<br>
git fetch origin<br>
git status<br>
git log origin/main<br>
git diff origin/main<br>

# merge

git merge origin/main<br>
git status<br>

git pull // equal fetch + merge<br>

# push

git commit -a -m "Updated index.html. Resized image"<br>
get status<br>
git push origin<br>

# branch

git branch<br>
git branch -a // to show all branches<br>
git branch -r // remote branches<br>
git checkout pulling<br>
git checkout -b update-readme<br>
git add README.md<br>
git commit -m "Updated readme for GitHub Branches"<br>
git push origin pulling<br>

# tag

git tag<br>
git tag v1.0.0<br>
git push origin v1.0.0<br>
git tag v1.0.5<br>
git tag v2.0.0<br>
git push origin --tags<br>
git tag -d v1.0.5<br>
git push origin --delete v1.0.5<br>
git checkout v1.0.0<br>
git checkout main<br>
git tag -a v1.6.0 commit_number<br>

# page

git remote add github-page https://github.com/qa-tester22/git_commands.git<br>
git push github-page main<br>

# clone repository

git clone https://github.com/qa-tester22/git_commands.git git_clone_folder<br>
ls<br>
cd git_clone_folder<br>
git status<br>
git log<br>

git remote -v<br>
git remote rename origin upstream<br>
git remote -v<br>
git remote add origin https://github.com/qa-tester22/git_commands.githab.io.git<br>
git remote -v<br>

git push origin<br>