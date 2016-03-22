Unix Commands:

NEVER TYPE THIS IN TERMINAL:   "rm -rf /"
     - It will destroy all the contents in your computer.

Relative Path vs Absolute:
     - Relative is using the ‘.’ , which is next to the file.
     - Absolute is using the ‘/‘ to get directly to the file

What is a Directory?
     - It is essentially a folder

To Go Home: cd ~

To Change Directory: cd <filename>

To Go Back a Directory: Relative Path cd.. Absolute cd/

To Go Back Twice to a Directory: cd../..

To See Which Directory You Are In: pwd

To List the Contents of a Directory: ls

To Create a File: touch <filename>

To Create a Directory: mkdir <filename>

To Clear All of the Info on Terminal: clear

To See the Contents of a File: cat <filename>

To Delete a File: rm <filename>

To Delete a Directory: rm -rf <filename>

To Open a File in Atom: atom <filename>

To Open a File: open <filename>

To Autofill: tab after typing in a letter

To Open a Manual: man

To Open a Manual for a Specific Command: man <command>

To Move a File: mv
     - ex: mv <absolutpath of file> “Space” <absolutepathofnewfilepathofchoice>

To Rename: mv
     -ex: mv <absolutpath of file> “Space” <absolutepathofnewfilepathofchoice>

For Git:

To Create a Branch: git branch <filename>

To See Branches: git branch

To Switch Branch: git checkout <filename>

To ReAssign a Branch to a commit: git branch -f

To Delete a Branch: git branch -d <branch name>

To Merge: git merge <branch name>

To Unstage Commits: git reset

To Reverse changes in a Remote Branch: git revert

To See all your Commits: git log

To Make a Branch your Default: git push -u origin marys-feature

To Add a Feature Branch and Switch Branch: git checkout -b <name>

To move/detach yo HEAD: git checkout “Hash"

Ways to detach yo HEAD — Relative Refs:

- Moving upwards one commit at a time with ^
- Moving upwards a number of times with ~<num>


ex.) master^^ references grandparent versus master^ references parent
ex.) HEAD~5, moves 5 times up

To Specify a new feature branch to master: git checkout -b <newbranchname> <master branch>
- Pull from Remote to have it track remotely
- You can also push it to the remote master

Way #2:

git branch -u o/master foo

if you already checked out in branch do:

git branch -u o/master

Push Arguments:
git push <remote> <place>

Pushing one branch to another branch:
git push origin <source>:<destination>

Fetching from a remote branch: git fetch <place>
Fetching to an Explicit Place: git branch <source>:<destination>

Additional Commands: Reference Here: https://github.com/0nn0/terminal-mac-cheatsheet/wiki/Terminal-Cheatsheet-for-Mac-(-basics-)
