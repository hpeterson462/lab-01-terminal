# Git clone
* Copy URL
* Paste into directory in terminal
```
git clone https://github.com/hpeterson462/lab-01-terminal.git
cd/lab-01-terminal
```
## Make directories with files
1) Print working directory
1) Make directory
1) Create files in directory
```
pwd
mkdir src
cd src
mkdir assests
cd assests
touch style.css
touch app.js
..
touch index.html
touch greeting.md
echo "Hello there!!" > greeting.md
```
### Add, commit, push Git
* remember to *comment* on **git commit**
```
git add -A
git commit -m "changes"
git push origin master
```
#### Reference Table

Directory|Sub-Directory|File
---|---|---
src | assests | style.css, app.js
x | x | index.html
x | x | greeting.md

