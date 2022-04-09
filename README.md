# Git-notebook
Learning the proper use of git

**Clone a repository to local system**

```
git clone <repo directory>
```

**Get the status of a local repository**

```
git status
```

**Display the commited history of an origin**

```
git log
```

**Move changes from working directory to Git staging area**

```
git add <file>
```

**Commit snapshots from Git staging area to project history with a commit message**

```
git commit -m "<commit message>"
```

**Push project history to origin**

```
git push origin <branch name>
```

**Pulling ALL changes from origin**

**(In more complex branching workflows, pulling and merging all changes might not be appropriate .)**

```
git pull --all
```

**Create a new branch**
```
git branch <branch name>
```

**Checkout and switch to the new branch**
```
git checkout <branch name>
```

**fast foward merge branch**

```
git checkout <main branch>
git merge <branch name>
git branch -d <branch name>
