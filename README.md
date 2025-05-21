# first-repo
My 1st push
# Documentation
1. Adding to staging area:
git add -A 
(A stands for all) 
2. Commit:
git commit -m "type ur commit msg here"
3. Push:
git push
4. To look at the status: 
git status
5. pull:
git pull
6.revert: (to undo a particular commit)
git revert 067604872408e724c7817d3e5fac0ddc1d4083ad (this commit id is found from git log)

# Examples of above:
PS C:\Users\yaroy\Projects\first-repo> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md
        new file:   index.txt

PS C:\Users\yaroy\Projects\first-repo> git commit -m "chore :first commit"
[main 45cff88] chore :first commit
 Committer: YASH ROY (yaroy) <yaroy@cisco.com>
Your name and email address were configured automatically based
 Committer: YASH ROY (yaroy) <yaroy@cisco.com>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

    git commit --amend --reset-author

 2 files changed, 4 insertions(+), 1 deletion(-)

 2 files changed, 4 insertions(+), 1 deletion(-)
 create mode 100644 index.txt
PS C:\Users\yaroy\Projects\first-repo> git branch
* main
 create mode 100644 index.txt
PS C:\Users\yaroy\Projects\first-repo> git branch
* main
PS C:\Users\yaroy\Projects\first-repo> git branch
* main
* main
PS C:\Users\yaroy\Projects\first-repo> git push
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 22 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (4/4), 385 bytes | 385.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To github.com:yashroy96/first-repo.git
   f47a681..45cff88  main -> main
PS C:\Users\yaroy\Projects\first-repo> git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.js

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\yaroy\Projects\first-repo> git add -A
PS C:\Users\yaroy\Projects\first-repo> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   index.js
        modified:   index.txt

PS C:\Users\yaroy\Projects\first-repo> git commit -m "chore :add functionality"
[main 0ee285e] chore :add functionality
 Committer: YASH ROY (yaroy) <yaroy@cisco.com>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:
following command and follow the instructions in your editor to edit
your configuration file:


    git config --global --edit

    git config --global --edit

After doing this, you may fix the identity used for this commit with:
After doing this, you may fix the identity used for this commit with:


    git commit --amend --reset-author
    git commit --amend --reset-author

 2 files changed, 5 insertions(+), 1 deletion(-)
 create mode 100644 index.js
PS C:\Users\yaroy\Projects\first-repo> history

  Id CommandLine
  -- -----------
   1 try { . "c:\Users\yaroy\AppData\Local\Programs\Microsoft VS Code\resources\app\out\vs\workbench\contrib\term... 
   2 git
   3 git status
   4 git commit -m "chore :first commit"
   5 git branch
   6 git push
   7 git status
   8 git add -A
   9 git status
  10 git commit -m "chore :add functionality"


