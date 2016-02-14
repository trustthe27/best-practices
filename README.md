# Best practices #

This repository is about my preferred coding best practices.

### Starting a new project ###

* Open MAC OS Terminal and navigate to favorite development folder
* Create a new folder with `mkdir PROJECT_NAME`
* Go to folder with `cd PROJECT_NAME`
* Init a local Git repository with `git init`
* Add a new uplink with `git remote add origin https://andreashoffmann@github.com/andreashoffmann/PROJECT_NAME.git`
* Check new remote with `Check new uplink with: git remote -v`
* Create a new readme file with `touch README.md` and insert some content, e.g.
```markdown
# PROJECT_NAME #

This repository is about PROJECT_NAME.
```
* Initialize NPM with `npm init`
* Confirm all settings with `ENTER` (for now)
* Create ignore file for node_modules `echo 'node_modules' > .gitignore`
* Add all currently created files with `git add .` to the stagin area
* Commit your changes to local Git repository with `git commit -m "Initial commit."`
* Create a new repository named PROJECT_NAME at GitHub 
* Push your local changes to GitHub with `git push --set-upstream origin master`
