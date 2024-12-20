# Reference

[Documentation for Git and GitHub](https://docs.chaicode.com/git-and-github/)

# Git, GitHub, and Version Control System (VCS) Definition

# Basic Terminology

- `git --version`
- `git status`
- `git init` (Creating a git repository)
- `git add .` (Add all files at once in the git repository)
- `git add <filename>` (Add a particular file)
- `git commit -m "[message]"` (Message should be in present tense and imperative, i.e., an order to git)
- `git log` (Show details of all commits)
- `git log --oneline` (Show details of all commits in a single line)
- `git push` (Push to remote [origin] repository)

# Git Ignore.
- `use to prevent track specified files and folder.`

# Git Behind the Scene.

# .gitkeep
- `git bydefault dont track a empty folder.but if we want to track a empty folder for that we add some content or file in future , then by now you have to add .gitkeep file in that folder for track by git`


# Branched in Git.
- `git branch` (This command lists all the branches in the current repository.)
- `git branch bug-fix` (This command creates a new branch called bug-fix.)
- `git switch bug-fix` (This command switches to the bug-fix branch.)
- `git log` ( This command shows the commit history for the current branch.)
- `git switch master` (This command switches to the master branch.)
- `git switch -c dark-mode` ( This command creates a new branch called dark-mode. the -c flag is used to create a new branch.)
- `git checkout orange-mode` (This command switches to the orange-mode branch.)
- `git merge bug-fix`(merge bug-fix branch into main branch. here we get all the content from bug-fix branch into main brnach)(during merge stay in main branch)
-  `fast forward merge , not fast forward merge(Managing conflicts) both way are same`(during conflict merge just manually remove external thing and add the file and commit it.)



# git diff 
# git stash
# git tag

# rebase and reflog
# getting start with github and open source

# Thank You❤❤