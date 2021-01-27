1. git version 2.30.0.windows.2

2. diff.astextplain.textconv=astextplain
   filter.lfs.clean=git-lfs clean -- %f
   filter.lfs.smudge=git-lfs smudge -- %f
   filter.lfs.process=git-lfs filter-process
   filter.lfs.required=true
   http.sslbackend=openssl
   http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
   core.autocrlf=true
   core.fscache=true
   core.symlinks=false
   pull.rebase=false
   credential.helper=manager-core
   credential.https://dev.azure.com.usehttppath=true
   init.defaultbranch=master
   user.name=Connor Sperdute
   user.email=cs357317@ohio.edu

3.usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone             Clone a repository into a new directory
   init              Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add               Add file contents to the index
   mv                Move or rename a file, a directory, or a symlink
   restore           Restore working tree files
   rm                Remove files from the working tree and from the index
   sparse-checkout   Initialize and modify the sparse-checkout

examine the history and state (see also: git help revisions)
   bisect            Use binary search to find the commit that introduced a bug
   diff              Show changes between commits, commit and working tree, etc
   grep              Print lines matching a pattern
   log               Show commit logs
   show              Show various types of objects
   status            Show the working tree status

grow, mark and tweak your common history
   branch            List, create, or delete branches
   commit            Record changes to the repository
   merge             Join two or more development histories together
   rebase            Reapply commits on top of another base tip
   reset             Reset current HEAD to the specified state
   switch            Switch branches
   tag               Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch             Download objects and refs from another repository
   pull              Fetch from and integrate with another repository or a local branch
   push              Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.

4. On branch master

 No commits yet

  Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        answers.md

 nothing added to commit but untracked files present (use "git add" to track)

5. On branch master

 No commits yet

 Changes to be committed:
   (use "git rm --cached <file>..." to unstage)
         new file:   README.md

 Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md

6. On branch master

 No commits yet

 Changes to be committed:
   (use "git rm --cached <file>..." to unstage)
         new file:   README.md
         new file:   answers.md

7. On branch master
 nothing to commit, working tree clean

8.On branch master
nothing to commit, working tree clean
PS C:\Users\conno\desktop\cs2400\git-lab> git log
commit 7e8a93f00d3c6c860db2851276c6513976faac64 (HEAD -> master)
Author: Connor Sperdute <cs357317@ohio.edu>
Date:   Wed Jan 27 16:30:53 2021 -0500

    Initial commit

9. On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

10.commit 9904067a08d063476e4a8de55a89e32380d057ee (HEAD -> main, origin/main)
Author: Connor Sperdute <77755349+cs357317@users.noreply.github.com>
Date:   Wed Jan 27 16:44:34 2021 -0500

    Update README.md

commit 7e8a93f00d3c6c860db2851276c6513976faac64
Author: Connor Sperdute <cs357317@ohio.edu>
Date:   Wed Jan 27 16:30:53 2021 -0500

    Initial commit
11.Everything up-to-date

12. ��

 CS 2400 Class Section 103

13.d-----         1/27/2021   4:45 PM                git-lab
   d-----         1/27/2021   5:06 PM                git-lab-2
   d-----         1/20/2021   4:14 PM                hw
   d-----         1/20/2021   4:36 PM                labs
   -a----         1/27/2021   4:57 PM           4604 answers.md
   -a----         1/27/2021   4:40 PM            138 README.md


