# Git Commands
### Initializing git repository
```
git init
# Initializes an empty git repository
# git starts keep tracking of the files in the current directory
```
### To get the modified file names in the working directory
```
git status
# Displays the list of files that are modified
```
### Add files to the staging area from working directory
```
git add file_name1 file_name2
git add . (if we want to add all the modified files to the staging area)
```
### Takes the snapshot with a commit message
```
git commit -m "Commit Message"
git commit --amend (It will add the changes to the previous commit)
```
### To configure the username and email
```
git config --global user.name "name"
git config --global user.email "email"
# if we want to configure it only for a repository, just remove --global
```
### To get the history of git commits
```
git log
```
### Displays the modified data in the working directory from the previous commit
```
git diff
```
### Linking the github repo with the local repo
```
git remote add origin <URL>
```
### To Push the commited code to the github repo(upstream)
```
git push -u origin master
or
git push --set-upstrem origin master
# It will be used for the first time
```










