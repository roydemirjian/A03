
***Setup:***
```
1. Create a folder for your project file on your local machine
2. Initialize git repostitory using 'git init' command
3. Create a remote repostitory on GitHub
4. Add remote repostiory using 'git remote add origin [RepositoryName]'
5. Push your local to remote using 'git push -u origin master'
```

***Usage:***
```
- Changes made to a file can be added to the next commit using 'git add [file]'
- Once changes are finalized to a file you can commit them using 'git commit -m'
- When you are ready to push your local changes to your remote you can use 'git push'
- If you want to keep your local repository synced to the latest changes on your remote repository you can use 'git pull'
- A new branch can be made using the 'git branch' command.
- Switching between branches can be done using the 'git checkout' command
- A merge can be done by switching to the branch that you want the changes to be merged onto and running the 'git merge [branch]' command

```
***Definitions:***
```
GIT - An open source version control system

GITHUB - A GIT repository hosting service

Repository - Akin to a project folder. Contains all the project files and stores revision history

Clone - A copy of a repository. A clone allows you to edit files and use git to keep track of your changes and then sync changes with remote versions

Commit - When you are done with your changes to a file you can commit you file, which is akin to saving. Each commit has a unqiue hash attached to it that allows git to keep a record of what changes were made and by who.

Push - When you send your commited changes on a local repository to the remote repository.

Pull - When you pull changes from a remote repository into your local repository. 

Branch - A parallel version of a repository. This allows to to work on changes without affect the master branch. Changes can then be merged back into the master branch.

Merge - Taking changes from one branch and then applying them to another.

Merge Conflict - When a merge can not take place because of various conflicts between the files trying to be merged

Fetch - Getting the lastest changes from a remote repository without mergeing them

Remote - A remote repository is a repository that is hosted on a server. 
```
