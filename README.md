# Commands for in terminal/cmd
A collection of terminal commands of Linux and windows that are related to github

## Linux commands

change directory:

    $cd [the path of the directory]
   
check the contents of a directory:
   
    $ls [-a][-l]
    
create a directory:

    $mkdir [name of the directory]
    
delete a file/directory:

    $rm [file_name]
    
## For those Windows guys
todo:

    
## github commands
Here is the github structure:![github_structure](https://github.com/hogwild/github-Commands/blob/master/githubstructure.jpg) 

Copy the repository from the remote to the local:
 
    $git clone [url][name of local directory(optional)]

Operations for the remote:

    $git remote
    $git remote show [name of the remote]
    $git remote add [name of the remote] [url]
    $git remote rm [name of the remote]
    $git remote rename [old name of the remote] [new name of the remote]
    
Fetch branches and/or tags from one or more other repositories, along with the objects necessary to complete their histories. 

    $git fetch [name of the remote] [name of the branch(optimal)]

Pull back the updates of the branches from the remote, then merge them with the local branches.

    $git pull [name of the remote][name of the branch on remote]:[name of the local branch]

examples1: pull back the branch1 on the remote named origin to local and merge it with a local branch named branch2

    $git pull origin branch1:branch2 

example2: pull back the branch1 on the remote named origin to local and merge it with the current branch

    $ git pull origin branch1

    $git push
    $git checkout
    $git branch
    $git git status
    $git add
    $git commit
    $git merge
   
