git branch starfish
git branch -d starfish
git add note.txt
git commit -m "second commit"
git stash
git stash list
git log
git reset --hard fa33c66ae2a
git commit --amend -m "updated commit message"
git commit --amend --no-edit
git revert fa33c66ae2a
git reset HEAD*
git reflog
git blame README.md
git cherry-pick d356440 fe988d6