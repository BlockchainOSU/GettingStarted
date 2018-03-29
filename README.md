# GettingStarted
This repository is meant to onboard any new club members to the development workflow through Git and Trello.

## What do I do?
First find your corresponding task in Trello in the Getting Started board. When you are ready to begin that task, move it to in progress.

Before starting, make sure you downloaded the github for command line tool. To
check if you have it installed, open a terminal or command line window and type
the following:
```
git --version
```

To download a copy of this repository on your local machine, type:
```
git clone https://github.com/BlockchainOSU/GettingStarted
```

**Here are some other useful commands.**

To create a branch you can use a command or the Github create branch tool,
as seen in the image:
```
git checkout -b amend-my-name
```

![alt text](https://i.imgur.com/stIU8hW.png "Create new branch")

To add a new track a new file you can use 'git add' with the 'i' parameter
for an interactive menu:
```
git add -i
```
Once in this menu, type 'a' for adding untracked files. Find the number corresponding
to your file, type it and hit enter. Afterwards, type enter again to return to
the interactive menu and type 'q' to quit the menu.

To commit a change, use:
```
git commit -m Give brief explanation of commit
```
The commit message should come after the '-m'. This message should be brief
(less than 75 words) and written in the imperative mood.

Once you have made your commit, push your changes to the remote repository:
```
git push
```

Afterwards, use the web interface corresponding with this repository and create
a new pull request to merge your branch into the master one. Then, move your
Trello task to in review and wait for a reviewer. Once it is reviewed,
it will be merged in and added to live code!
