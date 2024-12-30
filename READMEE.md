# Branch Commands

1. git branch (to check current branch)
2. bit branch -M main (to rename branch to main)
3. git chechout <branch name> (to change branch)
4. git checkout -b <branch name> (to create new branch)
5. git branch -d <branch name> (to delete branch)
6. git push --set--upstream origin <branch name> (pushing to a new branch)

7. git diff main (Difference between main and curret branch)
8. git merge <branch name> (Merge main and another branch)
9. git pull origin main (pull branching from gitHub to local system)

# Fixing Mistakes

# Case 1 : Staged Changes

1. git reset <file name> (unadd all unnecessary git add of a file)
2. git reset (unadd all unnecessary git add of all file)

# Case 2 : Commited Changes (For single commmit)

1. git reset HEAD~1 (uncommit last most git commit of current file)

# Case 3 : Commited Changes (For multiple commmits)

1. git logs (to obtain hashcode of all commits)
2. get reset <commit hash/hash code> (uncommit every commit from that log to end of current file)
3. get reset --hard <commit hash/hash code> (uncommit and delete lines for every commit from that log to end of current file)
