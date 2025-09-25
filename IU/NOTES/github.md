# WATis

1. Wikipedia 
2. https://docs.github.com/en/get-started/start-your-journey/about-github-and-git

# BASICS

- repo: a tracked folder
- commit: a saved version (with a message)
- push: sending changes 
- pull: getting latest changes
- branch: line of work (can be multiple)
- merge: combining two branches
- staging

# FILE STRUCTURE
.git/
.gitignore
README.md
actual


# DOCS, REFS
https://docs.github.com/en/get-started/using-git/about-git

# FLOW
1. git checkout main
git pull

2. git checkout -b feature/stuff-iam-working-on

3. git add .
git commit -m "message convention"

4. git push -u origin feature/stuff-iam-working-on
(after 1 just git push)

5. pull request 

6. magic>
git checkout main
git pull
git merge feature/stuff-iam-working-on
 tadaaam
 
7. delete 
local:  git branch -d feature/stuff-iam-working-on
github: git push origin --delete feature/my-task

# useful
git status
git add
git commit -m "message here"
git push

git clone {url}
git pull
git branch new-feature
git checkout new-feature
git checkout main -- git merge new-feature
git push -u origin new-feature
git log
git stash
git diff

