## How to Push or Commit Code from VS Code

**Step 1:** Create a repo<br>
**Step 2:** Open a folder in VS Code and then open the terminal<br>
**Step 3:** `git init` (initialize git)<br>
**Step 4:** `git add .` (add all files present in the folder to git)<br>
**Step 5:** `git commit -m "commit message"` (commit the files)<br>
**Step 6:** `git branch -M main` (specify which branch to push code on)<br>
**Step 7:** `git remote add origin "link of repo"`<br>
**Step 8:** `git push origin main` (specify which branch to push)<br>
**Step 9:** Sign in to let know who is pushing the code.<br>

## How to Push or Commit Code from GitHub Desktop

**Step 1:** Click on "Add an existing repo" in GitHub Desktop<br>
**Step 2:** Open the folder where all the code files are present<br>
**Step 3:** It will say no such repo is present on GitHub, so create a new repo<br>
**Step 4:** Then fetch origin / push all the code to GitHub<br>

## How to Clone GitHub Repo in VS Code

**Step 1:** Copy the HTTP link of the repo<br>
**Step 2:** Open the folder in VS Code where you want to clone the repo<br>
**Step 3:** Either click on Source Control (Ctrl + Shift + G) and clone the repo or open the terminal and write `git clone "link of the repo"`<br>

## What is Git?

- It is a version control system tool that helps to track changes in code.
- Git is a version control system.
- It is popular, free & open source, fast & scalable.

## What is GitHub?

- It is a website that allows developers to store and manage their code using Git.
- Code is stored here in the form of folders, which are called repositories.

## Commands in Git

- `git status`: Display the state of the code.
- Untracked: New files that Git doesn't yet track.
- Modified: Changed.
- Staged: File is ready to be committed.
- Unmodified: Unchanged.
- `git add` / `git add .`: Adds new or changed files in your working directory to the Git staging area.
- `git commit`: It is the record of changes.
- `git push`: Upload local repo content to remote (GitHub) repo.
- `git remote -v`: To verify which remote you are.
- `git branch`: To check branches.
- `git init`: Used to create a new Git repo.

## Branch Commands

- `git branch`: To check branches.
- `git branch -M main`: To rename a branch.
- `git checkout <branch name>`: To navigate or switch to a different branch.
- `git checkout -b <new branch name>`: To create a new branch.
- `git branch -d <branch name>`: To delete a branch.

## Merge Code

**Method 1:**

- `git diff <branch name>`: To compare commits, branches, files & more.
- `git merge <branch name>`: To merge two branches.

**Method 2:**

- Create a PR (pull request).

## What is Pull Request?

- It lets you tell others about changes you have pushed to a branch in a repo on GitHub.

## Pull Command

- `git pull origin main`: Used to fetch and download content from a remote repo and immediately update the local repo to match that content.

## Resolving Merge Conflicts

- An event that takes place when Git is unable to automatically resolve differences in code between two commits.

## Undoing Changes

**Case 1: Staged Changes**

- `git reset <filename>`
- `git reset` (to reset all changes)

**Case 2: Committed Changes (for one commit)**

- `git reset HEAD~1` (here HEAD means last commit)

**Case 3: Committed Changes (for many commits)**

- `git reset <commit hash>`
- `git reset --hard <commit hash>`

## Fork

- A fork is a new repo that shares code and visibility settings with the original upstream repo.
- It is a rough copy.

# GitHub Gists

In GitHub, a Gist is a service that allows you to share snippets of code or text quickly and easily. 

