# WIP
# 4Geeks-Academy-Terminal-Challenge-Key

## General Command Hints
[pwd] Print current directory path
[ls -a] List all the files from the current directory including the hidden ones
[ls -R] Now list all the files inside the workspace, recursively (all files in the hierarchy)
[cd, cat] Go to the last level below the small-name folder and write in the console the content of the trophy.txt file
[cd, ls] Move back to the root and List all files with the JavaScript typical extension
[mkdir] create a new folder inside funcode/the-most-funny/ called "not-that-funny"
[mv, cp] Create a copy of the last file you can find below the /boringfolder/ childs (the-mostboring-text.txt)
[rmdir] remove the "remove-me" folder from the funcode directory
[cd, cat] print in the screen the-ultimate-joke.txt
[rm] remove all the contents from the boringfolder, they are extremely boring

### 

## Step by Step Terminal Commands
### Start the Instructions
```console
your@githubhandle ➜ /workspaces/your-repo-name (master):~$ npm install
your@githubhandle ➜ /workspaces/your-repo-name (master):~$ npm run start
```

Leave that terminal running and create a new terminal using the plus button on the top right of your terminal window.

### Get inside the thecmdchallenge/ directory
```console
your@githubhandle ➜ /workspaces/your-repo-name (master):~$ cd thecmdchallenge/
your@githubhandle ➜ /workspaces/your-repo-name/thecmdchallenge (master) $ 
```
### Print current directory path
```console
your@githubhandle ➜ /workspaces/your-repo-name/thecmdchallenge (master):~$ pwd
```
### List all the files from the current directory including the hidden ones
```console
your@githubhandle ➜ /workspaces/your-repo-name/thecmdchallenge (master):~$ ls -a
.  ..  boringfolder  console_master.md  funcode  kamehameha  small-name
```
### Now list all the files inside the project, recursively (all files in the hierarchy)
```console
your@githubhandle ➜ /workspaces/your-repo-name/thecmdchallenge (master):~$ ls -R
```
### Clear all the clutter from the command line
```console
your@githubhandle ➜ /workspaces/your-repo-name/thecmdchallenge (master):~$ clear
```
### Go to the last level below the small-name folder and show on the console the content of the trophy.txt file
```console
your@githubhandle ➜ /workspaces/your-repo-name/thecmdchallenge (master):~$ cat cat small-name/bigger-name-than-before/omg-this-folder-has-a-huuuuuuge-name-and-i-tired-to-type/this-is-probably-the-longest-folder-name-you-have-ever-seen-but-believe--im-sure-there-are-other-folder-bigger-than-this-one-because-people-sometimes-like-to-assign-huge-names-to-their-personal-stuff-supercalifragilisticexpialidocious/trophy.txt
```
> **👋** Hint: Hit tab after typing / to autofill the full name of the path.
### Move one level up and get to the funcode directory and list all files with the JavaScript typical extension
```console
your@githubhandle ➜ /workspaces/your-repo-name/thecmdchallenge (master):~$ cd funcode/
your@githubhandle ➜ /workspaces/your-repo-name/thecmdchallenge/funcode (master):~$ ls *.js
```
### Create a new directory inside funcode/the-most-funny/ called “not-that-funny“

```console
your@githubhandle ➜ /workspaces/your-repo-name/thecmdchallenge (master):~$ makedir not-that-funny/
foo
```

### Create a copy of the-mostboring-text.txt (you can find it within /boringfolder/'s children) and name it lol.txt
```console
foo@bar:~$ cp the-mostboring-text.txt lol.txt
foo
```
<!-- edit above command -->
