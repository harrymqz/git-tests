# git-tests

This is a simple markdown manual to know how to write it:
https://guides.github.com/features/mastering-markdown/

## Git concepts
* Repository: Project space where files and history of the development are stored
* Working copy: Repository files at your local machine
* Branch: a development path, linked to the repository
* Commit: Picture of the repository files at a given moment
* Checkout: Change your working copy to a given commit or branch
* Push/Pull: Upload/Download to/from repository
* Merge: Incorporate a set of commits of branch A to branch B
* Issue: A problem, bug, new feature, we want/have to work with
* Merge/Pull Request: Request of merging a branch/commit to another branch
* Fork: Unlinked development path, which creates an independent repository

## How to: (All this data is from git page: https://git-scm.com/docs)
* Clone a repository: **git clone {url pointing to repository (.git)}**
* Add file after create it: **git add {file}**
* Commit the local changes: **git commit -am "{message for this commit}"**
* Push the local repository to the remote repository (master branch): **git push origin master**