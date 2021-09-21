1. What is the difference between git reset and git revert. When would you use one over the other? 
* **git reset: move the entire (HEAD -> branch) to the specified commit-hash and remove commits from git history. Use when you made a few commits that should not have been made and have not pushed the changes to the public repo**
* **git revert: creates a new commit that undoes the changes from a previous commit and keep the commit history. Use when a commit has been made somewhere in the project's history, and you later decide that the commit is wrong and should not have been done**
2. What is the difference between git merge and git rebase. When would you use one over the other?
* **git merge: a commit, that combines all changes of a different branch into the current. merge produces a new generated commit. Use merge whenever you want to add changes of a branched out branch back into the base branch.**
* **git rebase: re-comitting all commits of the current branch onto a different base commit. Use rebase whenever you want to add changes of a base branch back to a branched out branch**
3. What is the difference between git stash pop and git stash apply. When would you use one over the other?
* **git stash apply: apply the top stashed changes in the current working tree but leaves the stash history. Use stash pop if you are want to apply your top stashed changes to current non-staged change without deleting it**
* **git stash pop: apply the top stashed changes and delete it from git stash area. Use stash pop if you don't need the stash again**
4. What kinds of things can you do in interactive mode when rebasing? **Interactive rebasing can be used for changing commits in many ways such as editing, deleting, and squashing**