## Basic commands with Git
These are some of the basic commands you can use with Git in order to get started

Git task | Notes | Git commands
| :---: | :---: | :---: 
Config | Configure your name and email to be used with your commits | git config --global user.name "Alex Náger"\n git config --global user.email alex@example.com
Init | Create new local repo in order to work with git | git init
Clone | Create a working copy of a local repo | git clone /path/to/repo
Clone | For a remote server | git clone <repository-url>
Remote | Connect your local repo to a remote one in order to be able to push to it | git remote add origin <server>
Remote | List all currently configured remote repos | git remote -v
Add | Add one or more files | git add \<filename1\> \<filename2\>
Add | Add all files in your current directory | git add .
Commit | Commit changes to head (not yet to repo) | git commit -m "Commit message"
Commit | Commit any files you've added with ***git add***, and also commit any files you've change since then | git commit -a
Push | Send changes to the master branch of the remote repo | git push origin master
Status | List the files you've change and those you still need to add or commit | git status
Pull | Fetch and merge changes on remote server to your working dir | git pull
Merge | To marge a different branch into your active branch | git merge <branchname>
