# How to clone the project
1. Download git using this link: [git version control](https://git-scm.com/downloads)
2. After the installation is completed for your machine, open a terminal/command line
3. Type in the terminal 

```markdown
$cd Desktop
$mkdir project_moviedb
$cd project_moviedb
$git clone https://github.com/vinamramunot-tech/Movies_Database.git
$cd Movies_Database
$git branch "your name"
$git checkout rohan
```

4. open the Movies_Database folder in vscode.
7. start the live server that you downloaded from the vscode marketplace. [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
8. Now in the vscode, start editing your file. 
9. Once you are satisfied with changes you have made, you can run these command in the terminal in the vscode to push your updates:

```markdown
$git add .
$git commit -m "completed phase 1, pushing"
$git checkout master
$git merge rohan
$git branch -d rohan
$git push origin master
```
after updating repeat the process from 
```markdown
$git checkout -b rohan
....
```
