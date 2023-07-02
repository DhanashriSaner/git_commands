# git_commands


## Three-stage Architecture of git

![areas](https://github.com/DhanashriSaner/git_commands/assets/88526990/2db1b30f-5542-44b3-8775-64c54f4af283)

#### 1) Set global Username and email to git(locally)
```
git config --global user.name "<username>"
```

```
git config --global user.email "<email>"
```
#### 2) Clone an existing Git repository
```
git clone <repository_URL>
```

#### 3) Initialized empty Git repository
```
git init
```
#### 4) Show the status of the git repository
```
git status
```
#### 5) Add the file from the working directory into the staging area.
```
git add <filename>
```

#### 6) Add all current directory files into the staging area.
```
git add .
```
#### 7) Commit all the stage files to git
```
git commit -m "<Commit_message>"
```

#### 8) Restore the file from being modified to Tracked (2 options are available)

```
git restore <filename>
```
```
git checkout <filename>
```

#### 9) Add remote origin URL
```
git remote add origin <Your_remote_git_URL>
```
#### 10) Remove remote origin URL
```
git remote remove origin
```

#### 11) Push your local changes to the remote branch
```
git push origin <branch_name>
```
