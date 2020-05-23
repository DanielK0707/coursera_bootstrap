### git commands
ls - show all folders in your current folder
cd blabla - change to a specific folder in your current folder
cd + first letter of designated folder + TAB to choose - same
cd .. - go one folder backwards
cd .. && cd .. - go two folders back (Apple only)
cd ../.. - same but viable for windows
mkdir + name - create new folder
git init - initialize current folder as your git repository
git clone + weblink - copy your online git folder into current folder
git branch - show current branch you're in
git checkout master - go back to your master from wherever you are
git checkout master -b newbranchname - go from your master into another branch, if non existent before it creates a new one
git branch -d branchname - deletes existing branch
git config - ?
git remote add origin (repository url) - add the remote online repository
git status - show pending changes made local but not on git yet
git add + file name - add the file to git
git add . - add all files of your current folder
git commit -m "something" - confirm the made changes to git and include a message
git push - upload the changed file to git
git log --oneline - shows all previous commits
git log - same but with more details
git checkout <commit> <file> - checkout the file from an older commit
git reset <file> - unstage a staged file, but leave working directory unchanged
git reset - reset the staging area to the last commit without disturbing the working directory