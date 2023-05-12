# Solution

Complete each task. Then, follow the instructions as to what to copy and paste into the empty code block.

> **Note:** Carefully read the instructions for each task. Sometimes you will be asked to record the _command(s)_ you wrote while other times you will be asked to record the _output_ of the command you wrote.

## 1

Create a new directory called `git-lab/`. Then, navigate inside of that directory.

Copy and paste _the command(s)_ you used into the code block below.

```
# pursuit @ Pursuits-Air in ~/desktop [4:21:54]
$ mkdir git-lab

# pursuit @ Pursuits-Air in ~/desktop [4:22:04]
$ cd git-lab
```

## 2

Initialize the directory as a git repository.

Copy and paste the _output_ of the command(s) you ran into the code block below.

```
Initialized empty Git repository in /Users/pursuit/Desktop/git-lab/.git/

# pursuit @ Pursuits-Air in ~/desktop/git-lab on git:master o [4:23:02]
```

## 3

Check the current status of the git repository.

Copy and paste the _output_ of the command(s) you ran into the code block below.

```

```

## 4

Create a new file called `readme.md`. Then stage that file.

Copy and paste _the command(s)_ you used into the code block below.

```
# pursuit @ Pursuits-Air in ~/desktop/git-lab on git:master o [4:23:02]
$ touch readme.md

# pursuit @ Pursuits-Air in ~/desktop/git-lab on git:master x [4:25:49]
$ git add readme.md
```

## 5

Check the current status of the git repository.

Copy and paste the _output_ of the command(s) you ran into the code block below.

```
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   readme.md

```

## 6

Add the following text to your `readme.md` file.

```
I am learning to use git.
```

Then, check the current status of the git repository.

Copy and paste the _output_ of the command(s) you ran into the code block below.

```
# pursuit @ Pursuits-Air in ~/desktop/git-lab on git:master x [4:28:33]
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   readme.md

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   readme.md
```

## 7

Commit your changes and include a sensible commit message. Then, check your repository's history.

Copy and paste _the command(s)_ you used into the code block below.

```
  288  git add readme.md
  289  git commit -m "Added readme.md to git-lab"
  290  git history
```

## 8

Check the current status of the git repository.

Copy and paste the _output_ of the command(s) you ran into the code block below.

```
On branch master
nothing to commit, working tree clean
```

## 9

Stage your changes and then make another commit with a sensible commit message.

Copy and paste _the command(s)_ you used into the code block below.

```
git add readme.md
git commit -m "Second commit for readme.md in git-lab"
```
