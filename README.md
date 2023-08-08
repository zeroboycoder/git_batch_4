# Git Commands

```
git config --global user.name zeroboycoder
git config --global user.email exampl@email.com

git init
git add
git commit -m [messages]
git log
git stat

git remote add origin https://github.com/zeroboycoder/git_batch_4.git
git remote remove origin
git remote -v

git branch -M main
git branch -v

git push [remote_name] [branch_name]
git push origin main

git pull [remote_name] [branch_name]
git pull origin main

git switch [branch_name]
git switch dashboard

git checkout [branch_name]

git revert [commit_id]

git reset --hard [commit_id] // Delete both
git reset --soft [commit_id] // Delete just commit, not code

git merge [branch_name] // main --> dashboard,
git merge main

git stash
git stash pop

.gitconfig

git fetch [remote_name] [branch_name]
git fetch origin main
git merge origin/main

```
