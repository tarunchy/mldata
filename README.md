# mldata

# Remove Git Commit History

git checkout --orphan latest_branch

Add all the files

git add -A

Commit the changes

git commit -am "commit message"

Delete the branch

git branch -D main

Rename the current branch to main

git branch -m main

Finally, force update your repository

git push -f origin main
