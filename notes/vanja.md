#vanja

Hello world

_Hello world_
# italics _word_

**Hello world**
# bold **word**

`some code`
# to code `here` -- the key that comes before 1

git config --global user.name "John Doe"
git config --global user.email "johndoe@example.com"
git checkout HEAD
git checkout master
git add notes/vanja.md #add file to a local repos
git status #checks the status of your file

git commit -m "Made a new file" #commits to the remote repos with a message
git log #provides the overview of master and branches

| oh look        | i can make a table     |
| :------------- | :------------- |
| cool 1         | cool 2       |

git remote add upstream https://github.com/kescobo/git_tutorial.git
# added remote upstream masterbranch  --   points to the remote masterbranch

ok -- this is a bit confusing. there are master branches and dev branches.

git merge master vkcdev
#merging vkcdev with master

#GitKraken is a super useful program to keep track of all git tentacles/branches

ORDER  of commands:
- make a branch
- commit to branch
- Pull request to upstream

to  create a new branch:
git checkout -b vkc2dev
