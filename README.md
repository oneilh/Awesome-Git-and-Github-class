# GIT AND GITHUB

learning git and github at cybite academy
<br>
<br>
<br>

## Getting Started with Git

### install git -> [Git website](https://git-scm.com/)

### Configure git:

set up your username and email

```
$   git config --global user.name "Your Name"

$   git config --global user.email "your.email@example.com"
```

<br>
<br>

### Clone a git repository

```
$   git clone [url]
```

[url] -> github url

<br>

### Check repository status

```
$   git status
```

<br>

### Add changes

#### to stage a single file changes for the next commit:

```
$   git add <filename>
```

### staging multiple files:

```
$   git add <filename1> <filename2>
```

### staging all files

```
$   git add .
```

<br>
<br>

### Commit changes

```
$   git commit -m "your message"
```

### Display commit history

```
$   git log
```

### Show unstaged changes between your index and working directory

```
$   git diff
```

<br>
<br>
<br>

## Uploading Exiting Repository To GitHub

### Initializing a local git repository

```
$   git init
```

<br>

- initialize the repository
- add the files
- commit the files
- add remote url

```
$   git remote add origin [remote repository URL]
```

```
$   git remote -v
 # Verifies the new remote URL
```

<br>

- push the changes in the local repo to **Github**

```
$   git push origin master
```

- download changes from the remote repository to the local repository

```
$   git pull
```

<br>
<br>
<br>

## Git Branch

### Creating a branch

```
$   git branch  <branch-name>
```

### Switch branch

```
$   git checkout  <branch-name>

$   git checkout -b <branch-name>
#creates the branch and switches to it
```

### List branches

```
$    git branch
```

### Compare branches

```
$   git diff branch1..branch2

$   git diff --color-words branch1..branch2
#see changes in one line colored
```
