# ET0735 – Lab 1 (Introduction to Git and GitHub)

git init
- initialise the local repo

git status
- check any change in the repository.

git add <fiename>
- add the file to staging.

git commit -m <comment/remark>
- commit the files in the staging to the local repository.

git diff
- to show the differences between old and new files

=====================================================

git branch
- list the branches in a repository.

git branch <new name>
- create a new branch.

git checkout <branch to switch to>
- switch to a branch.

git merge <from which branch>
- merge from a branch to the current branch.

=====================================================

git remote add origin <GitHub repository URL>
- specify the URL of the remote GitHub repository, e.g.
https://github.com/tankweeteck-ichat/Lab1new.git

git remote -v
- to check whether the remote repository correctly configured.

git push --set-upstream origin master
git push -u origin master
- setup the remote upstream branch (the ‘master’ branch in the GitHub repository).

git push origin
- push files from Git repository to the GitHub remote repository.

git remote set-url origin <new URL>
- change the URL of the remote GitHub repository to a new URL

=====================================================

git tag –a <tag> –m <comment>
- create a new Git tag on the current file versions in the current branch.

git push origin <tag>
- push the tag from the local git repository to the remote GitHub repository.


==========================================================

git log
- show the commits done.

git log --oneline
- show the commits done, one commit per line.

git tag -n
- Show the tags created and the associated message.

git tag -n --sort=creatordate
- Show the tags created in chronological order.





