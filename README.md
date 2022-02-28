LOCAL
# git-gitHub5


Eleve6@POST000161726 MINGW64 ~/exercice/gitgithub5 (master)
$ git clone git@github.com:Ched1983/git-gitHub5.git
Cloning into 'git-gitHub5'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

Eleve6@POST000161726 MINGW64 ~/exercice/gitgithub5 (master)
$ git add .
warning: adding embedded git repository: exercice/gitgithub5/git-gitHub5
hint: You've added another git repository inside your current repository.
hint: Clones of the outer repository will not contain the contents of
hint: the embedded repository and will not know how to obtain it.
hint: If you meant to add a submodule, use:
hint:
hint:   git submodule add <url> exercice/gitgithub5/git-gitHub5
hint:
hint: If you added this path by mistake, you can remove it from the
hint: index with:
hint:
hint:   git rm --cached exercice/gitgithub5/git-gitHub5
hint:
hint: See "git help submodule" for more information.

Eleve6@POST000161726 MINGW64 ~/exercice/gitgithub5 (master)
$ git commit -m "modif read me"
[master (root-commit) b938156] modif read me
 1 file changed, 1 insertion(+)
 create mode 160000 exercice/gitgithub5/git-gitHub5

Eleve6@POST000161726 MINGW64 ~/exercice/gitgithub5 (master)
$ git push
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>

and then push using the remote name

    git push <name>


Eleve6@POST000161726 MINGW64 ~/exercice/gitgithub5 (master)
$ git push origin master
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

Eleve6@POST000161726 MINGW64 ~/exercice/gitgithub5 (master)
$ git init
Initialized empty Git repository in C:/Users/Eleve6/exercice/gitgithub5/.git/

Eleve6@POST000161726 MINGW64 ~/exercice/gitgithub5 (master)
$ git push origin master
error: src refspec master does not match any
error: failed to push some refs to 'origin'

Eleve6@POST000161726 MINGW64 ~/exercice/gitgithub5 (master)
$ git add .
warning: adding embedded git repository: git-gitHub5
hint: You've added another git repository inside your current repository.
hint: Clones of the outer repository will not contain the contents of
hint: the embedded repository and will not know how to obtain it.
hint: If you meant to add a submodule, use:
hint:
hint:   git submodule add <url> git-gitHub5
hint:
hint: If you added this path by mistake, you can remove it from the
hint: index with:
hint: 
hint:   git rm --cached git-gitHub5
hint:
hint: See "git help submodule" for more information.

Eleve6@POST000161726 MINGW64 ~/exercice/gitgithub5 (master)
$ cd git-gitHub5/

Eleve6@POST000161726 MINGW64 ~/exercice/gitgithub5/git-gitHub5 (main)
$ git add .

Eleve6@POST000161726 MINGW64 ~/exercice/gitgithub5/git-gitHub5 (main)
$ git commit -m "modif read me"
[main e2b4b07] modif read me
 1 file changed, 1 insertion(+)

Eleve6@POST000161726 MINGW64 ~/exercice/gitgithub5/git-gitHub5 (main)
$ git push origin master
error: src refspec master does not match any
error: failed to push some refs to 'github.com:Ched1983/git-gitHub5.git'

Eleve6@POST000161726 MINGW64 ~/exercice/gitgithub5/git-gitHub5 (main)
$ git push origin main
To github.com:Ched1983/git-gitHub5.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'github.com:Ched1983/git-gitHub5.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

Eleve6@POST000161726 MINGW64 ~/exercice/gitgithub5/git-gitHub5 (main)
$ git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 640 bytes | 32.00 KiB/s, done.
From github.com:Ched1983/git-gitHub5
   3946ae1..c5cda3c  main       -> origin/main
Auto-merging README.md
CONFLICT (content): Merge conflict in README.md
Automatic merge failed; fix conflicts and then commit the result.

Eleve6@POST000161726 MINGW64 ~/exercice/gitgithub5/git-gitHub5 (main|MERGING)
$ git add .git@github.com:Ched1983/git-gitHub5.git
fatal: pathspec '.git@github.com:Ched1983/git-gitHub5.git' did not match any files

Eleve6@POST000161726 MINGW64 ~/exercice/gitgithub5/git-gitHub5 (main|MERGING)
$ git add .

Eleve6@POST000161726 MINGW64 ~/exercice/gitgithub5/git-gitHub5 (main|MERGING)
$ git commit -m "modif readme two"
[main 8b6028b] modif readme two

Eleve6@POST000161726 MINGW64 ~/exercice/gitgithub5/git-gitHub5 (main)
$ git push
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (6/6), 498 bytes | 249.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:Ched1983/git-gitHub5.git
   c5cda3c..8b6028b  main -> main

Eleve6@POST000161726 MINGW64 ~/exercice/gitgithub5/git-gitHub5 (main)