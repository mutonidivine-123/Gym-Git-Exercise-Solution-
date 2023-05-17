# Gym-Git-Exercise-Solution-
# git exercise
## bundle 1 
## ex 1
***bash


jerom@DESKTOP-DNB8MV2 MINGW64 ~
$ git config --global user.name "divine"

jerom@DESKTOP-DNB8MV2 MINGW64 ~
$ git config --global user.email "divmutoni44@gmail.com"

jerom@DESKTOP-DNB8MV2 MINGW64 ~
$ cd g:/gittrain

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain
$ git config --global init.default branch master

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain
$ git init
Initialized empty Git repository in G:/gittrain/.git/

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (master)
$ git brancch
git: 'brancch' is not a git command. See 'git --help'.

The most similar command is
        branch

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (master)
$ git branch status
fatal: not a valid object name: 'master'

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        fabdiv.html

nothing added to commit but untracked files present (use "git add" to track)

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (master)
$ git branch -N main
error: unknown switch `N'
usage: git branch [<options>] [-r | -a] [--merged] [--no-merged]
   or: git branch [<options>] [-f] [--recurse-submodules] <branch-name> [<start-point>]
   or: git branch [<options>] [-l] [<pattern>...]
   or: git branch [<options>] [-r] (-d | -D) <branch-name>...
   or: git branch [<options>] (-m | -M) [<old-branch>] <new-branch>
   or: git branch [<options>] (-c | -C) [<old-branch>] <new-branch>
   or: git branch [<options>] [-r | -a] [--points-at]
   or: git branch [<options>] [-r | -a] [--format]

Generic options
    -v, --verbose         show hash and subject, give twice for upstream branch
    -q, --quiet           suppress informational messages
    -t, --track[=(direct|inherit)]
                          set branch tracking configuration
    -u, --set-upstream-to <upstream>
                          change the upstream info
    --unset-upstream      unset the upstream info
    --color[=<when>]      use colored output
    -r, --remotes         act on remote-tracking branches
    --contains <commit>   print only branches that contain the commit
    --no-contains <commit>
                          print only branches that don't contain the commit
    --abbrev[=<n>]        use <n> digits to display object names

Specific git-branch actions:
    -a, --all             list both remote-tracking and local branches
    -d, --delete          delete fully merged branch
    -D                    delete branch (even if not merged)
    -m, --move            move/rename a branch and its reflog
    -M                    move/rename a branch, even if target exists
    -c, --copy            copy a branch and its reflog
    -C                    copy a branch, even if target exists
    -l, --list            list branch names
    --show-current        show current branch name
    --create-reflog       create the branch's reflog
    --edit-description    edit the description for the branch
    -f, --force           force creation, move/rename, deletion
    --merged <commit>     print only branches that are merged
    --no-merged <commit>  print only branches that are not merged
    --column[=<style>]    list branches in columns
    --sort <key>          field name to sort on
    --points-at <object>  print only branches of the object
    -i, --ignore-case     sorting and filtering are case insensitive
    --recurse-submodules  recurse through submodules
    --format <format>     format to use for the output


jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (master)
$ git branch -m "master" "main"

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        fabdiv.html

nothing added to commit but untracked files present (use "git add" to track)

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git add fabdiv.html

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   fabdiv.html


jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   fabdiv.html


jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   fabdiv.html


jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   fabdiv.html


jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   fabdiv.html


jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   fabdiv.html


jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   fabdiv.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   fabdiv.html


jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git add fabdiv.html

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   fabdiv.html


jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git commit "my first commit"
error: pathspec 'my first commit' did not match any file(s) known to git

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git commit -m "my first commit"
[main (root-commit) 4b1eeb3] my first commit
 1 file changed, 42 insertions(+)
 create mode 100644 fabdiv.html

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git status
On branch main
nothing to commit, working tree clean

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git log --oneline
4b1eeb3 (HEAD -> main) my first commit

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git remote add origin https://github.com/mutonidivine-123/Gym-Git-Exercise-Solution-

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git branch -M main

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git push -u origin main
git status
Q
:x
$ git status


jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git push -u origin main
To https://github.com/mutonidivine-123/Gym-Git-Exercise-Solution-
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/mutonidivine-123/Gym-Git-Exercise-Solution-'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git remote add origin https://github.com/mutonidivine-123/Gym-Git-Exercise-Solution-
error: remote origin already exists.

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git branch -M main

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git push -u origin main
To https://github.com/mutonidivine-123/Gym-Git-Exercise-Solution-
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/mutonidivine-123/Gym-Git-Exercise-Solution-'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git status
On branch main
nothing to commit, working tree clean

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git log
commit 4b1eeb3bf0936ef96404dcd9059ece649f0e5aeb (HEAD -> main)
Author: divine <divmutoni44@gmail.com>
Date:   Wed May 17 18:54:52 2023 +0200

    my first commit

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git push --help

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git push --all
To https://github.com/mutonidivine-123/Gym-Git-Exercise-Solution-
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/mutonidivine-123/Gym-Git-Exercise-Solution-'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git fetch
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 617 bytes | 4.00 KiB/s, done.
From https://github.com/mutonidivine-123/Gym-Git-Exercise-Solution-
 * [new branch]      main       -> origin/main

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git status
On branch main
nothing to commit, working tree clean

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git push --all
To https://github.com/mutonidivine-123/Gym-Git-Exercise-Solution-
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/mutonidivine-123/Gym-Git-Exercise-Solution-'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git push -u origin main
fatal: unable to access 'https://github.com/mutonidivine-123/Gym-Git-Exercise-Solution-/': Recv failure: Connection was reset

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git push --all
To https://github.com/mutonidivine-123/Gym-Git-Exercise-Solution-
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/mutonidivine-123/Gym-Git-Exercise-Solution-'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git pull
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> main


jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git push -u origin main
To https://github.com/mutonidivine-123/Gym-Git-Exercise-Solution-
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/mutonidivine-123/Gym-Git-Exercise-Solution-'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git remote add origin https://github.com/mutonidivine-123/Gym-Git-Exercise-Solution-
error: remote origin already exists.

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git branch dev

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git branch
  dev
* main

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git switch dev
Switched to branch 'dev'

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (dev)
$ git branch test

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (dev)
$ git branch
* dev
  main
  test

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (dev)
$ git switch test
Switched to branch 'test'

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (test)
$ git switch dev
Switched to branch 'dev'

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (dev)
$ git branch -d test
Deleted branch test (was 4b1eeb3).

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (dev)
$ git brach
git: 'brach' is not a git command. See 'git --help'.

The most similar command is
        branch

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (dev)
$ git branch
* dev
  main

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (dev)
$ ^C

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (dev)
$

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (dev)
$ git switch main
Switched to branch 'main'

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git switch main
Already on 'main'

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git pull --rebase origin main
From https://github.com/mutonidivine-123/Gym-Git-Exercise-Solution-
 * branch            main       -> FETCH_HEAD
Successfully rebased and updated refs/heads/main.

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ git push -u origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.28 KiB | 131.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/mutonidivine-123/Gym-Git-Exercise-Solution-
   cc2e99f..aee3035  main -> main
branch 'main' set up to track 'origin/main'.

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)
$ ^C

jerom@DESKTOP-DNB8MV2 MINGW64 /g/gittrain (main)

***
