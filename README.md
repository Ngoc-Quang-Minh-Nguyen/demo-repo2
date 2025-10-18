# Heading
Attempt to make a project andd send them to github
git init will basically add the .git hidden file in this folder. It is now being watched.
then git commit to save the change. Then make a new repository in git hub and them copy those code to create the repository in git hub.

## Subheader
Use git checkout -b (stands for build) to build and change to a newly made branch.
This is a change in the branch called feature. Currently there are two version in demo-repo2: main and feature. 

The git checkout will change branch. EX: git checkout feature.
The git push, if it doesn't have upstream branch, not knowing where to push basically, use this:
#  git push --set-upstream origin <name branch>
That will create a PR for the main branch to check and see if they should approved it or not.

Use git commit -am if: Added ALREADY EXISTED file, when it says "Modified". Newly created files don't count

ALSO THIS IS THE RIGHT VERSION PLEASE PICK ME!!!!

If git merge, the interface is SO GOOD!!! But then you have to commit again, which is still SO GOOD!!! 

CAN YOU UNDO YOUR COMMIT IN GIT????
Yes. git reset file to counterattack git add . 
Use git reset HEAD~1 to undo the even-1-further-away step, so from finished commit --> Stop commit --> Stop add .

NOTE: git reset <commit ID> will unstaged all previous commits leading to this commit. So the changes are still there, just not saved in git.  Use git log to access the commit history.
NOTE: git reset --hard <commit ID> will REMOVE all previous commmits, changes leading to this commit. It is no longer there. Be careful about this.