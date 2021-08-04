## Version Control System
- We use VCSs to collaborate as a team of programmars, track changes, do code review and much more...
- This can be of 2 types
	- Distributed VCS
		- Github, BitBucket, Gitlab etc...
	- Centralized VCS
		- TFS, VSTS, SVN


![alt text](https://github.com/EMraan619/Neosoft-dotnet/blob/main/01/Images/1VCS%20.png?raw=true)
# Git
## Basic Git and commands
- `cd 'path'` -> change directory
- `cd ..` -> moves a level up
	- use arrow keys to see history of previously use commands
	- history -> gives a track of all commands you have used in the current session
- `cd ./ tab key` -> gives the auto-completion of the file/directory
- `ls` -> list all the files and directories
- `mkdir 'directory name'` -> make directory
- `touch 'file name.extension'` -> creates a file
- `git clone 'url'` -> adds the local workspace in your machine
- `git add` -> adds the file you target to add to git
- `git add -A` -> adds all the file
- `git commit -m 'message'` -> Stage changes and commit to git as a new node
- `git push` -> push changes to git server
- `git status` -> see the new tracks/ changes made in local workspace
- `git pull` -> retrieve changes from the git server (updates your workspace with latest code)
- `pwd` -> print where directory

### Demo	
- `cd C:/Training`   - to navigate to a directory
- `cd Neosoft/`
- `git clone https://github.com/Tech-Training-2021/Neosoft-dotnet` - to make a local copy of the repo
- `cd training-code/`
- `mkdir 01` - create a folder/directory
- `cd 01/`
- `touch Notes.md` - create a file
- `notepad Notes.md` - open the file with notepad
	- add some content
- `git status` - to check changes if any
- `git add` . - stage the changes in all the file(s)
- `git commit -m 'add notes for git basics'` - create a tracking node
- `git push` - add changes to git origin/server
- `git pull` - to get changes from the server
- `git branch` - tells you how many branches you have and which branch are you current;y pointing to.
- `git checkout -b feature-pushpinder` - creates a new branch `feature-pushpinder` and switch it as a working branch.
- git add -> commit -> git push
- make a Pull Request for code review

#Benefits of VCS

1. A complete long-term change history of every file. This means every change made by many individuals over the years. Changes include the creation and deletion of files as well as edits to their contents. Different VCS tools differ on how well they handle renaming and moving of files. This history should also include the author, date and written notes on the purpose of each change. Having the complete history enables going back to previous versions to help in root cause analysis for bugs and it is crucial when needing to fix problems in older versions of software. If the software is being actively worked on, almost everything can be considered an "older version" of the software.

2. Branching and merging. Having team members work concurrently is a no-brainer, but even individuals working on their own can benefit from the ability to work on independent streams of changes. Creating a "branch" in VCS tools keeps multiple streams of work independent from each other while also providing the facility to merge that work back together, enabling developers to verify that the changes on each branch do not conflict. Many software teams adopt a practice of branching for each feature or perhaps branching for each release, or both. There are many different workflows that teams can choose from when they decide how to make use of branching and merging facilities in VCS.

3. Traceability. Being able to trace each change made to the software and connect it to project management and bug tracking software such as Jira, and being able to annotate each change with a message describing the purpose and intent of the change can help not only with root cause analysis and other forensics. Having the annotated history of the code at your fingertips when you are reading the code, trying to understand what it is doing and why it is so designed can enable developers to make correct and harmonious changes that are in accord with the intended long-term design of the system. This can be especially important for working effectively with legacy code and is crucial in enabling developers to estimate future work with any accuracy.
