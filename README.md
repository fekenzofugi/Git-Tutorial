# Git Tutorial
VERSION CONTROL: Versions of your code.

VERSION CONTROL USING GIT AND THE COMMAND LINE.
# local repository
```
    TUTORIAL: LOCAL REPOSITORY 

    1. git init //It will initialize a empty git repository inside the directory, called working
    directory.
    2. git status //It will show the untracked files that are not in the STAGING AREA.
    3. git add fileName.txt //It will add the file to the STAGING AREA.
    4. git commit -m "Complete Commit 1" //It will commit all files of the STAGING AREA
    with a message.
    5. git log //It will show all the commits you've made.
    6. git add. //It will add all the working directory files to the STAGING AREA.
    7. git checkout fileName.txt //It will change our local working directory file data with
    the commited file.
    8. git diff fileName.txt //It will show the difference between the old commited Version
    and the new version.
```
# remote repository
```
    TUTORIAL: REMOTE REPOSITORY
    obs: We already create the github repository

    1. git remote add origin https://github.com/fernandofugihara/gitTutorial.git // It will
    create a remote repository.
    2. git branch -M main
    3. git push -u origin main //It will push the local repository to the remote repository
    and all of the progress.
```
    MAIN BRANCH: It is the main progress of the local directory.

## Gitignore: It's a file that has the names of the files that we want git to ignore and not commit to our remote repository.
## git Clone: clone the remote repository using the command:
```
    git clone url
```
## Branching: If we want to add a new feature to our project, we can create a new branch using the command:
```
    git branch name-of-branch
```
## Merging: If our new feature / experiment was fruitfull and the feature that we build is really great, we can merge it back to the main branch using:
```
    git merge name-of-branch
```
    git branching step-by-step:
```
    1. git branch name-of-branch //it will create a new git branch.
    2. git checkout name-of-branch //it will change the current branch to specified branch name
    3. git add . //it will add the files to the STAGING AREA of the new branch
    4. git commit -m "" //it will commit the files the new branch.
    5. git log //it will show the commits made on all bunches.
    6. git branch //it will show which branch you are.
    7. git branch name-of-branch //it will change the current branch and the code will change to the branch specified.
    8. git merge name-of-branch //it will merge the branches open another window then we can add a message or add a :q!
    9. git push -u origin main
```
## Forking and Pull Request

### How to suggest code changes and contribute to an open source project.
Forking: copy of the code on a remote repository (clone copy the code on a local repository)
After forking the code in your remote repository, you can clone the code in your local repository
and make changes. Then you can push to your remote repository. if you want that the owner of the
code make the changes in the offial repository you can make a pull request - if you don't have then
permission. If the suggestion was approved, the code will change on a commit.
