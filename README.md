# 4Geeks-Academy-Terminal-Challenge-Key

this readme.md file is to be used in conjunction with [4Geeks Academy](https://github.com/4GeeksAcademy)'s [exercise-terminal-challenge](https://github.com/breatheco-de/exercise-terminal-challenge) repo, but only when you're *really* stumped.

## General Command Hints
* `[pwd]` Print current directory path
* `[ls -a]` List all the files from the current directory including the hidden ones
* `[ls -R]` Now list all the files inside the workspace, recursively (all files in the hierarchy)
* `[cd, cat]` Go to the last level below the small-name folder and write in the console the content of the trophy.txt file
* `[cd, ls]` Move back to the root and List all files with the JavaScript typical extension
* `[mkdir]` create a new folder inside `funcode/the-most-funny/` called "not-that-funny"
* `[mv, cp]` Create a copy of the last file you can find below the /boringfolder/ childs (the-mostboring-text.txt)
* `[rmdir]` remove the "remove-me" folder from the funcode directory
* `[cd, cat]` print in the screen the-ultimate-joke.txt
* `[rm]` remove all the contents from the boringfolder, they are extremely boring

### 

## Step by Step Terminal Commands
### Start the Instructions
```console
your@githubhandle ➜ /workspaces/your-repo-name (master):~$ npm install
your@githubhandle ➜ /workspaces/your-repo-name (master):~$ npm run start
```

Leave that terminal running and create a new terminal using the plus button on the top right of your terminal window.

### 1. Get inside the thecmdchallenge/ directory
```console
your@githubhandle ➜ /workspaces/your-repo-name (master):~$ cd thecmdchallenge/
your@githubhandle ➜ /workspaces/your-repo-name/thecmdchallenge (master) $ 
```
### 2. Print current directory path
```console
your@githubhandle ➜ /workspaces/your-repo-name/thecmdchallenge (master):~$ pwd
```
### 3. List all the files from the current directory including the hidden ones
```console
your@githubhandle ➜ /workspaces/your-repo-name/thecmdchallenge (master):~$ ls -a
.  ..  boringfolder  console_master.md  funcode  kamehameha  small-name
```
### 4. Now list all the files inside the project, recursively (all files in the hierarchy)
```console
your@githubhandle ➜ /workspaces/your-repo-name/thecmdchallenge (master):~$ ls -R
```
### 5. Clear all the clutter from the command line
```console
your@githubhandle ➜ /workspaces/your-repo-name/thecmdchallenge (master):~$ clear
```
### 6. Go to the last level below the small-name folder and show on the console the content of the trophy.txt file
```console
your@githubhandle ➜ /workspaces/your-repo-name/thecmdchallenge (master):~$ cat small-name/bigger-name-than-before/omg-this-folder-has-a-huuuuuuge-name-and-i-tired-to-type/this-is-probably-the-longest-folder-name-you-have-ever-seen-but-believe--im-sure-there-are-other-folder-bigger-than-this-one-because-people-sometimes-like-to-assign-huge-names-to-their-personal-stuff-supercalifragilisticexpialidocious/trophy.txt
```
> **👋** Hint: Hit tab after typing '/' to autofill the full name of the path.
### 7. Move one level up and get to the funcode directory and list all files with the JavaScript typical extension
```console
your@githubhandle ➜ /workspaces/your-repo-name/thecmdchallenge (master):~$ cd funcode/
your@githubhandle ➜ /workspaces/your-repo-name/thecmdchallenge/funcode (master):~$ ls *.js
```
### 8. Create a new directory inside funcode/the-most-funny/ called “not-that-funny“
```console
your@githubhandle ➜ /workspaces/your-repo-name/thecmdchallenge (master):~$ cd the-most-funny
your@githubhandle ➜ /workspaces/your-repo-name/thecmdchallenge/the-most-funny (master):~$ mkdir not-that-funny
```
### 9. Create a copy of the-mostboring-text.txt (you can find it within /boringfolder/‘s children) and name it lol.txt
```console
your@githubhandle ➜ /workspaces/your-repo-name/thecmdchallenge/the-most-funny (master):~$ ../..
your@githubhandle ➜ /workspaces/your-repo-name/thecmdchallenge (master):~$ cp boringfolder/even-more-boring/i-cant-believe-how-boring/the-ultimate-boring-inception/the-mostboring-text.txt boringfolder/even-more-boring/i-cant-believe-how-boring/the-ultimate-boring-inception/lol.txt
```
### 10. Move funcode/kids.jpg inside funcode/images/hello/
```console
your@githubhandle ➜ /workspaces/your-repo-name/thecmdchallenge (master):~$ mv funcode/kids.jpg funcode/images/hello/
```
### 11. Remove the “small-name“ directory
```console
your@githubhandle ➜ /workspaces/your-repo-name/thecmdchallenge (master):~$ rm -r small-name
foo
```
### 12. Print in the command line the content of the-ultimate-joke.txt
```console
your@githubhandle ➜ /workspaces/your-repo-name/thecmdchallenge (master):~$ cat funcode/the-most-funny/lol/the-ultimate-joke.txt
foo
```
### 13. Remove all the contents from the boringfolder, they are extremely boring…
```console 
your@githubhandle ➜ /workspaces/your-repo-name/thecmdchallenge (master):~$ rm -r boringfolder/*
```
### 14. Open the file kamehameha/dragon-ball-jokes.md using the VI command line text editor
```console 
your@githubhandle ➜ /workspaces/your-repo-name/thecmdchallenge (master):~$ vi kamehameha/dragon-ball-jokes.md
```
### 15. Update the file kamehameha/dragon-ball-jokes.md by removing the first joke you read on the file, finally save and close the text editor
```console
1. In vi command mode, navigate to the line containing the first joke.
2. Delete the line by positioning the cursor on it and typing 'dd'.
3. Save and exit by typing 'Esc', then ':wq' and Enter.
```
## The End 🎉
