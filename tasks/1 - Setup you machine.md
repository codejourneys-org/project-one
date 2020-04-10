# Task 1 - Setup your machine

## Instructions
1) Read the slides (https://slides.com/raffaelepizzari/deck-50cfc6)
2) Install GIT
3) Join the CodeJourneys team on GitHub
4) Star&Watch the "Project One" repository (https://github.com/codejourneys-org/project-one) 
5) Play with Git and have fun :)

## Objective:

1) Create a new branch from "master" called feature/add-name, where "name" is your name.
(my branch will be feature/add-raffaele).

2) There's a file in the root folder of yor code called "authors.json".
Add a new object to the array using your data.

3) Push your branch to origin

4) Create a "Pull Request" on GitHub

5) Write in the channel when you are done


## Help

Here you can find the most important git commands: 

### "Project One" repo
https://github.com/codejourneys-org/project-one.git

### COMMIT CHANGES TO THE HEAD
git commit -m "Commit message"

### ADD FILE TO THE INDEX
git add <filename>

### CHECK DIFF BETWEEN 2 BRANCHES
git diff <source_branch> <target_branch>

### PULL CHANGES
git pull

### MERGE A BRANCH ON THE CURRENT BRANCH
git merge <branch name>

### REPLACE LOCAL FILE
git checkout -- <filename>

### REPLACE LOCAL CHANGES
git fetch origin
git reset --hard origin/<branch name>


### LOG
git log

git log --author=bob

git log --pretty=oneline

git log --graph --oneline --decorate --all

git log --name-status

### CREATE A NEW BRANCH
git checkout -b <branch name>

### SWITCH BRANCH
git checkout <branch name>

### DELETE LOCAL BRANCH
git branch -d <branch name>

### PUSH A LOCAL BRANCH TO ORIGIN
git push origin <branch name>
