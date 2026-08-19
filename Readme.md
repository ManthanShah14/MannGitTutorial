git status
git config --global user.email "manthanshah140206@gmail.com"
git config --global user.name "ManthanShah14"
git branch
git add .
git commit -m "initial commit"
echo "creating new file" > newFile.txt
git log --oneline
git restore --staged Readme.md
.gitignore
.gitkeep
git switch <branch>
git checkout <branch>
git switch -c feature_manthan_1
git checkout -b feature_manthan_1
git merge <branch>
to delete branch first switch to branch main then run command : git branch -D <branch>
git merge --abort
git rebase <branch>
git reflog 
git reset --hard HEAD~1
git reset --hard commitid
git diff