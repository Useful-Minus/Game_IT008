* START
- echo "# Game_IT008" >> README.md
- create git_folder: git init
- download & create clone: git clone <url>
- check source control: git status
- git add <file/folder>
- add all folder: git add .
- commit with message: git commit -m "first commit"
- git branch -M main
- git remote add origin https://github.com/Useful-Minus/Game_IT008.git
- git push -u origin main
- view history: git log

* PULL
- download without modifying: git fetch
- fetch & merge: git pull
- merge 2 branch: git merge <branch_name>

* PUSH
- git remote add origin https://github.com/Useful-Minus/Game_IT008.git
- git branch -M main
- git push -u origin main

* BRANCH
- list branch: git branch
- create branch: git branch <name>
- switch branch: git checkout <branch_name> / git switch <branch_name>
- push branch: git push -u origin <branch_name>



…or create a new repository on the command line

echo "# Game_IT008" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Useful-Minus/Game_IT008.git
git push -u origin main

…or push an existing repository from the command line

git remote add origin https://github.com/Useful-Minus/Game_IT008.git
git branch -M main
git push -u origin main
