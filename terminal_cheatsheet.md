# H1
## H2
### H3
#### H4
Text
**Bold**

*Italics*

`CODE`

```
hello
```

🤣 - ctrl + cmd + space

> blockquote

1. First item
2. Second item
3. Third item

- First item
- Second item
- Third item

---

[title](https://www.example.com)

![alt text](image.jpg)

Navigation
--
pwd: Print Working Directory - shows current location in file system
cd path/to/location: Change Directory - move to the specified directory
cd ..: Move up one directory

-cd: Move back to the home directory
ls: List contents of current directory
ls -a: List contents and include hidden files and folders
ls -l: List contents with full details
Creation
--
mkdir myDirectory: Make Directory - create a directory called myDirectory
touch myFile.txt: Create a new file called myFile.txt
rm myFile.txt: Delete a file called myFile.txt
rm -rf myDirectory: Delete a directory called myDirectoy including all of its contents
Manipulating Files
---
mv file.txt path/to/new/location: Move file.txt to a new location
mv file.txt renamed.txt: Rename file.txt to renamed.txt
cp file.txt path/to/new/location: Copy file.txt to a new location
cp -r directory path/to/new/location: Copy directory to a new location
Git Commands
---
mkdir newProject - creates a new directory
cd newProject - moves into our new directory
git init - initialises a new Git repository
touch newFile.txt - creates a new text file
open newFile.txt - allows us to edit our text file in an editor
---
git add newFile.txt / git add . - tells Git to track this new file. . will select all modified files.
git commit -m "our commit message" - commits our staged changes
Create a repository on GitHub
git remote add origin <GIT URI of new remote repository> - connects our local and remote repositories
git push origin main - pushes the local changes to the remote
To commit changes to the local repository and to push changes to a remote once everything is set up:

git add ... - stage the changes we want to commit (. specifies all files, git status will show all modified files)
git commit -m "..." - commits the staged changes to teh local repository
git push origin main - pushes the changes to the remote