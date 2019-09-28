# GitCheatSheet

**Please adhere to the below mentioned format while opening pull requests, else your pull requests be marked as spam.**
**Usage of command** - `Command on Git Bash` (Optional Description)


**Git Installation On Linux OS** - `sudo apt install git-all`</li>
**Configuring Username And EMail Id:-**

`git config --global user.name "John Doe"`

`git config --global user.email johndoe@example.com`
**Check Configuartion Settings** - `git config --list`
**Checking Specific Configurations** - `git config user.name`

<br><br>
**Initializing A Git Repository** - `git init`
**Add Files to the staging area** - `git add`
**Adding a particular file** - `git add fileName followed by extension`
**Cloning a repository from GitHub** - `git clone https://github.com/userName/repoName`
If you want the repository to be named something else on your local computer,

`git clone https://github.com/userName/repoName repoNameOnYourSystem`

**Checking the status of the repository** - `git status`

<br><br>
#### Adding a .gitignore file ignores certain file extensions for tracking

**Ignore all .a files** - `*.a`
**Track lib.a, even though you're ignoring .a files above** - `!lib.a`
**Only ignore the TODO file in the current directory, not subdir/TODO** - `/TODO`
**Ignore all files in any directory named build** - `build/`
**Ignore doc/notes.txt, but not doc/server/arch.txt** - `doc/*.txt`
<br><br>

**See the differences between the edits** - `git diff`
**Difference in files after the staging process** - `git diff --staged` 
**Commiting a file** - `git commit -m "Type in your commit"`
**Committing and staging the file in one command** - `git commit -a -m "Type in your commit"`
**Staging the removal of a file** - `git rm <fileName>`
**Staging the renaming of a file** - `git mv <oldFileName> <newFileName>`
**Viewing the Commit History of A Dierectory** - `git log`
**To view the changes in the file in the commit history** - `git log -p`
**To view the last n changes only** - `git log -n`
**To view the statistics of each commit change** - `git log -stat`
**Amending a commit** - `git commit --amend` (Effectively, this is as if the previous commit never occured)
**Unstaging a file** - `git reset HEAD <fileName>`
**Unmodifying a modified file** - `git checkout --<fileName>`

<br><br>
**Listing the name of your remote repository** - `git remote -v`
**Adding a remote** - `git remote add <remoteName> <repositoryURL>`
**Fetching from a remote** - `git fetch <remoteName>`
**Fetching and merging at the same time** - `git pull <remoteName>`
**Pushing to a remote server** - `git push <remoteName> <branchName>`
**Get information about a remote branch** - `git remote show <remoteName>`
**Renaming a remote server** - `git remote rename <oldName> <newName>`
**Removing a remote server** - `git remote remove <remoteName>`
<br><br>
