# Command

## basic command
- git status
- git commit -m "message"
- git status
- git log
- git push
- git pull 
- gitk                        : branches interface
- git add .                   : add everything that has been changed
- git add command.md          : add new file / changed file
- git commit -am "message     : add changed file and commit

- git branch
- git checkout -b mybranch
- git push origin schedule    : push to origin (github), in branch "schedule"
- (origin)                    : origin (default) repository, can be multiple repository other than github


## sync original repository and forked repository
- git remote show
- git remote show origin
- git remote add upstream https://github.com/mulinnuha/Git-Intro.git    : add new remote "upstream" with latest version
- git pull upstream master    : pull from upstream/master 
- git merge upstream/master

- git merge mybranch          : merging pull request
- git push origin master      : 


## pull request
pull request is done from the web

- git checkout -b work (edit everything here, local branch)
- git checkout master (change to branch master)
- git pull origin master (pull from github to branch master)
- git checkout work (change to branch work)
- git merge master (merge files from branch to master)
