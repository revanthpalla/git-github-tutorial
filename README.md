# git-github-tutorial

Intro to git
-------------------------------------------------------------------------
git is distributed version control system which allows you create or edit files and make snapsots of versions available to public in central repository(Github)

steps
--------------------------------------------------------------------------
1. create a repo
2. sync repo
3. Making changes
4. Parallel development (1. branching, 2. Merging, 3. Rebasing)
5. git flow

---------------------------------------------------------------------------
1. create a local repository
>> git init

2. Add a link between local repo and central repo using
>> git remote add origin <link> // link of central repository link

3. what are the files in index
>> git status

4. if you want to commit any changes to a file, we need to add it to the index
>> git add gitcommands.txt

5. To add multiples files to staged area for commiting
>> git add -A

6. Similarly to commit multiple files 
>> git commit -a -m "updated version 1.01"

7. To see what are things we done on that branch(here master)
>> git log

8. To create a branch in local Repo
>> git branch Mark1Branch

9. To switch from master(branch) to Current created branch in local repo
>> git checkout Mark1Branch

9. If you want to see what are the files in that branch
>> ls
