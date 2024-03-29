# Links
An alternative to linktree in vanilla Javascript. Easily customizable and easily new links can be added.

All the icons in website are from [Icons8](https://icons8.com)

## Steps to follow to contribute :scroll:

```mermaid
flowchart LR
    Fork[Fork the project]-->branch[Create a New Branch]
    branch-->Edit[Edit file]
    Edit-->commit[Commit the changes]
    commit -->|Finally|creatpr((Create a Pull Request))
    
 ```

### 0. Star The Repo :star2:

Star the repo by pressing the topmost-right button to start your wonderful journey.

### 1. Fork it :fork_and_knife:

You can get your own fork/copy of [links](https://github.com/akashrchandran/links) by using the <a href="https://github.com/akashrchandran/links"><kbd><b>Fork</b></kbd></a> button.


### 2. Clone it :busts_in_silhouette:

`NOTE: commands are to be executed on Linux, Mac, and Windows(using Powershell)`

You need to clone or (download) it to a local machine using

```sh
$ git clone https://github.com/{Your_Username}/links.git
```

> This makes a local copy of the repository in your machine.
Once you have cloned the `links` repository in Github, move to that folder first using the change directory command on Linux, Mac, and Windows(PowerShell to be used).
```sh
# This will change the directory to a folder links
$ cd links
```

Move to this folder for all other commands.

### 3. Set it up :arrow_up:

Run the following commands to see that *your local copy* has a reference to *your forked remote repository* in Github :octocat:

```sh
$ git remote -v
origin  https://github.com/Your_Username/links.git (fetch)
origin  https://github.com/Your_Username/links.git (push)
```

Now, let's add a reference to the original [links](https://github.com/akashrchandran/links) repository using

```sh
$ git remote add upstream https://github.com/akashrchandran/links.git
```

> This adds a new remote named ***upstream***.
See the changes using
```sh
$ git remote -v
origin    https://github.com/Your_Username/links.git (fetch)
origin    https://github.com/Your_Username/links.git(push)
upstream  https://github.com/Your_Username/links.git (fetch)
upstream  https://github.com/Your_Username/links.git (push)
```
In your case, you will see
```sh
$ git remote -V
origin    https://github.com/Your_Username/links.git(fetch)
origin    https://github.com/Your_Username/links.git (push)
upstream  https://github.com/Your_Username/links.git (fetch)
upstream  https://github.com/Your_Username/links.git(push)
```

### 4. Sync it :recycle:

Always keep your local copy of the repository updated with the original repository.
Before making any changes and/or in an appropriate interval, run the following commands *carefully* to update your local repository.

```sh
# Fetch all remote repositories and delete any deleted remote branches
$ git fetch --all --prune
# Switch to the `main` branch
$ git checkout main
# Reset the local `main` branch to match the `upstream` repository's `main` branch
$ git reset --hard upstream/main
# Push changes to your forked `links` repo
$ git push origin main
```

### 5. Ready Steady Go... :turtle: :rabbit2:

Once you have completed these steps, you are ready to start contributing by checking our `Good First Issue` Issues and creating [pull requests](https://github.com/akashrchandran/links/pulls).

### 6. Create a new branch :bangbang:

Whenever you are going to contribute. Please create a separate branch using command and keep your `main` branch clean (i.e. synced with remote branch).

```sh
# It will create a new branch with the name Branch_Name and switch to branch Folder_Name
$ git checkout -b BranchName
```

Create a separate branch for contribution and try to use the same name of the branch as of folder.

To switch to the desired branch

```sh
# To switch from one folder to another
$ git checkout branchname
```

To add the changes to the branch. Use

```sh
# To add all files to branch Folder_Name
$ git add.
```

Type in a message relevant to the code reviewer using

```sh
# This message gets associated with all files you have changed
$ git commit -m 'relevant message'
```

Now, Push your awesome work to your remote repository using

```sh
# To push your work to your remote repository
$ git push -u origin BranchName
```

Finally, go to your repository in the browser and click on `compare and pull requests`.
Then add a title and description to your pull request that explains your precious effort.