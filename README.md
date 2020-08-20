
C:\Users\z00435ra>git status
fatal: not a git repository (or any of the parent directories): .git

C:\Users\z00435ra>cd ctec1305_GIT/test_GIT_Project

C:\Users\z00435ra\ctec1305_GIT\test_GIT_Project>git init
Reinitialized existing Git repository in C:/Users/z00435ra/ctec1305_GIT/test_GIT_Project/.git/

C:\Users\z00435ra\ctec1305_GIT\test_GIT_Project>git add readme.nd
fatal: pathspec 'readme.nd' did not match any files

C:\Users\z00435ra\ctec1305_GIT\test_GIT_Project>git remote add origin https://github.com/xoxoxx/CTEC22312

C:\Users\z00435ra\ctec1305_GIT\test_GIT_Project>git push
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master


C:\Users\z00435ra\ctec1305_GIT\test_GIT_Project>git push origin master
To https://github.com/xoxoxx/CTEC22312
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/xoxoxx/CTEC22312'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

C:\Users\z00435ra\ctec1305_GIT\test_GIT_Project>git add helloWorld.txt
fatal: pathspec 'helloWorld.txt' did not match any files

C:\Users\z00435ra\ctec1305_GIT\test_GIT_Project>cd CTEC22312

C:\Users\z00435ra\ctec1305_GIT\test_GIT_Project\CTEC22312>git add helloWorld.txt

C:\Users\z00435ra\ctec1305_GIT\test_GIT_Project\CTEC22312>git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

C:\Users\z00435ra\ctec1305_GIT\test_GIT_Project\CTEC22312>git commit -a -m "introduced a third line"
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

C:\Users\z00435ra\ctec1305_GIT\test_GIT_Project\CTEC22312>git push origin master
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 292 bytes | 97.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/xoxoxx/CTEC22312
   9083da8..24d3822  master -> master

C:\Users\z00435ra\ctec1305_GIT\test_GIT_Project\CTEC22312>git commit -a -m "introduced a third line"
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

C:\Users\z00435ra\ctec1305_GIT\test_GIT_Project\CTEC22312>git clone https://github.com/xoxoxx/NewFold
Cloning into 'NewFold'...
remote: Repository not found.
fatal: repository 'https://github.com/xoxoxx/NewFold/' not found

C:\Users\z00435ra\ctec1305_GIT\test_GIT_Project\CTEC22312>git clone https://github.com/xoxoxx/NewFold
Cloning into 'NewFold'...
remote: Repository not found.
fatal: repository 'https://github.com/xoxoxx/NewFold/' not found

C:\Users\z00435ra\ctec1305_GIT\test_GIT_Project\CTEC22312>
