1. What does git clean do?. **cleans the working tree by recursively removing files that are not under version control, starting from the current directory.**
2. What do the -d and -f flags for git clean do? **-d flag: stands for directory, will remove untracked directories in addition to untracked files; -f flag: stands for force, will delete and clean files/folder by force**
3. What git command creates a branch? **git branch [branch-name]**
4. What is the difference between a fast-forward and recursive merge? **fast-forward merge: give a straight line of history;  recursive merge: give multiples lines of history**
5. What git command changes to another branch? **git checkout [branch-name]**
6. How do you remove modified or deleted files from the working directory? **git add -u [directory-path]**
7. What git command deletes a branch? **git branch -d [branch_name]**
8. What does the git diff command do? **show changes between commits, commit and working tree, etc that not staged**
9. How do you remove files from the staging area? **git restore --staged [filename]**
10. How do merge conflicts happen? **Merge conflict generally arise when two people have changed the same lines in a file, or if one developer deleted a file while another developer was modifying it and subsequently merged. Git can't know which of the changes to keep, and thus needs human intervention to resolve the conflict.**