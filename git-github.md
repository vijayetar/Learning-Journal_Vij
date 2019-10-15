# Git vs GitHub
## Introduction
 - Git is the software while GitHub is the cloud
 - Git is also version control software that is distributed (vs others that are centralized or localized)
 - GitHub allows sharing of files and editing between users while actively keeping track of changes
 - Github is open sourced - ie anyone can make changes and available to all 
 - They both together allow coders to work simultaneously while Git keeps history of all the changes
 - Git allows team members to sync while being remote
 - Git keeps all files in one repository
 
 ## How does Git work?
 - Simply, Git takes snapshots (or commits) in time. This is done with the "add" and "commit", where each commit represents each version of the file. These commits are stored and data is not lost each time. They are stored locally until they are "pushed".
 - To Keep track of the snapshots
   - Each commit (snapshot) has labels
   - HEAD = The label meaning "You Are Here"
   - Use messages to write captions on your commits, that allows us to track changes.
   
## What is GitHub?
- It is online place to store code
- It uses Git to make the repositories accessible locally and remotely

## Commands you will frequently use
- Copy repo into the desktop
  - git clone *add the url of the repo from GitHub* 
- Get into the actual file 
  - command cd (filename)
  - confirm with pwd
- See the hidden git file
  - ls -a
- Open VS code and edit file
  - code .
  - make changes on the file through VS code
  - add file in the same repo using the (*add file* icon) 
  - save file with changes on the VS code
 - In terminal, start to add/commit/push these repo
  - git add (file name)
  - git commit -m"message to yourself"
  - git push origin master
 - Confirm git status each time
  - git status (red means it needs to be added, green means it needs to be commited)
 - Confirm change on GitHub
   - Get into the repo and then dont forget to refresh
   - You can view the changes on the commits tab 
  
[Return to homepage](README.md)