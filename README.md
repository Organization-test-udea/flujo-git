# Flujo de trabajo git
Documentación de flujo de trabajo remoto con github

## Organizacion
Se recomienda crear una organizacion a partir de la cual se generen los forks hacia sus cuentas personales

## Comandos branches and remote
1. GIT BRANCHES AND REMOTE
2. git checkout -b <branch name>			    -- Creates a new branch and set is as active branch 
3. git push origin <branch name>                       -- Pushes the branch to the project
4. git remote -v 					    -- Shows the available remote sources
5. git remote add <name> <url>			    -- Adds another remote repository
6. git remote remove <name>			    -- Removes the connection with the remote repository
7. git fetch <remote name>                             -- Download objects and refs from another repository

## Comandos unbdoing stuff
git rm <file>			           	    -- Deletes the file from the git directory
git rm --cached <file>			            -- Stops tracking a file
git mv <filename> <newname>			    -- Changes the name of the file and even could change the location of the file 
git checkout <filename>				    -- Comes back to the status of the file in the last commit or staging
git checkout -p <filename>			    -- Adds the differences between the current status and the last status in the staging or commit
git checkout 'branch'			            -- Switches the current branch
git reset HEAD <filename>			    -- Unstages the changes of the file
git reset -p HEAD <filename>			    -- Unstages the changes of the file showing the changes that will be unstaged
git revert HEAD					    -- Creates a commit with the inverse changes in the last commmit to fix problems
