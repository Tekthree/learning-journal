### Understanding Git 
To be able to freely collaborate with teams of developers you need a powerful system that can organize local and cloud databases as well as organize and track versions and changes made to those databases. **Git** is just that. Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.

- Local version control - database on your hard disk
- Centralized version control - Colloaboration within a developer team on a single file or set of files. sigle server
- Distributed Version control - Multiple mirrored repositories.

## Loss of Data
Git minimizes the chances of lossing files or accidentally deleting. You can always recall previous versions

workflow for using git locally in terminal
1. git clone (url)
2. cd (filename)
3. code .
4. work on file in visual studio
5. git add .
6. git status
7. git commit -m"comment"
8. git push origin master


[more info on Git](https://www.udemy.com/blog/git-tutorial-a-comprehensive-guide/#7_4)

