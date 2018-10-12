# primer-deber-de-progra
Al aire libreHP@DESKTOP-C3MM5RA MINGW64 ~/Desktop/master
$ GIT INIT
fatal: cannot handle INIT as a builtin

HP@DESKTOP-C3MM5RA MINGW64 ~/Desktop/master
$ git init
Initialized empty Git repository in C:/Users/HP/Desktop/master/.git/

HP@DESKTOP-C3MM5RA MINGW64 ~/Desktop/master (master)
$ git add .
warning: adding embedded git repository: document
hint: You've added another git repository inside your current repository.
hint: Clones of the outer repository will not contain the contents of
hint: the embedded repository and will not know how to obtain it.
hint: If you meant to add a submodule, use:
hint:
hint:   git submodule add <url> document
hint:
hint: If you added this path by mistake, you can remove it from the
hint: index with:
hint:
hint:   git rm --cached document
hint:
hint: See "git help submodule" for more information.

HP@DESKTOP-C3MM5RA MINGW64 ~/Desktop/master (master)
$

HP@DESKTOP-C3MM5RA MINGW64 ~/Desktop/master (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   book/ALGEBRA LINEAL MOISES LAZARO.pdf
        new file:   book/Hibbeler_Engineering_Mechanics_Dynamics_12th_solucionario - copia.pdf
        new file:   code/1.cpp
        new file:   code/2.cpp
        new file:   code/3.cpp
        new file:   code/4.cpp
        new file:   document
        new file:   link/texto.txt


HP@DESKTOP-C3MM5RA MINGW64 ~/Desktop/master (master)
$ git commit
[master (root-commit) 70eb139] primer deber de progra
 8 files changed, 134 insertions(+)
 create mode 100644 book/ALGEBRA LINEAL MOISES LAZARO.pdf
 create mode 100644 book/Hibbeler_Engineering_Mechanics_Dynamics_12th_solucionario - copia.pdf
 create mode 100644 code/1.cpp
 create mode 100644 code/2.cpp
 create mode 100644 code/3.cpp
 create mode 100644 code/4.cpp
 create mode 160000 document
 create mode 100644 link/texto.txt

HP@DESKTOP-C3MM5RA MINGW64 ~/Desktop/master (master)
$ git log
commit 70eb139a74dde9db19185bc0d11b843d8eeee653 (HEAD -> master)
Author: jostincito <jjmontenegro1@espe.edu.ec>
Date:   Thu Oct 11 22:14:58 2018 -0500

    primer deber de progra

HP@DESKTOP-C3MM5RA MINGW64 ~/Desktop/master (master)
$ git branch jostincito

HP@DESKTOP-C3MM5RA MINGW64 ~/Desktop/master (master)
$ git checkout jostincito
Switched to branch 'jostincito'

HP@DESKTOP-C3MM5RA MINGW64 ~/Desktop/master (jostincito)
$ git log
commit 70eb139a74dde9db19185bc0d11b843d8eeee653 (HEAD -> jostincito, master)
Author: jostincito <jjmontenegro1@espe.edu.ec>
Date:   Thu Oct 11 22:14:58 2018 -0500

    primer deber de progra

HP@DESKTOP-C3MM5RA MINGW64 ~/Desktop/master (jostincito)
$ git remoto agregar origen https://github.com/jostincito/git-master.git
git: 'remoto' is not a git command. See 'git --help'.

The most similar command is
        remote

HP@DESKTOP-C3MM5RA MINGW64 ~/Desktop/master (jostincito)
$ git push -u origin master
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

HP@DESKTOP-C3MM5RA MINGW64 ~/Desktop/master (jostincito)
$ echo "# git-master" >> README.md

HP@DESKTOP-C3MM5RA MINGW64 ~/Desktop/master (jostincito)
$ git init
Reinitialized existing Git repository in C:/Users/HP/Desktop/master/.git/

HP@DESKTOP-C3MM5RA MINGW64 ~/Desktop/master (jostincito)
$ git agregar README.md
git: 'agregar' is not a git command. See 'git --help'.

HP@DESKTOP-C3MM5RA MINGW64 ~/Desktop/master (jostincito)
$ git commit -m "primer commit"
On branch jostincito
Untracked files:
        README.md

nothing added to commit but untracked files present

HP@DESKTOP-C3MM5RA MINGW64 ~/Desktop/master (jostincito)
$ git commit
On branch jostincito
Untracked files:
        README.md

nothing added to commit but untracked files present

HP@DESKTOP-C3MM5RA MINGW64 ~/Desktop/master (jostincito)
$ git remoto agregar origen https://github.com/jostincito/git-master.git
git: 'remoto' is not a git command. See 'git --help'.

The most similar command is
        remote

HP@DESKTOP-C3MM5RA MINGW64 ~/Desktop/master (jostincito)
$  git push -u maestro de origen
error: src refspec de does not match any.
error: src refspec origen does not match any.
error: failed to push some refs to 'maestro'

HP@DESKTOP-C3MM5RA MINGW64 ~/Desktop/master (jostincito)
$ git push -u origin master
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

HP@DESKTOP-C3MM5RA MINGW64 ~/Desktop/master (jostincito)
$ git status
On branch jostincito
Untracked files:
  (use "git add <file>..." to include in what will be committed)

        README.md

nothing added to commit but untracked files present (use "git add" to track)

HP@DESKTOP-C3MM5RA MINGW64 ~/Desktop/master (jostincito)
$ git add .
warning: LF will be replaced by CRLF in README.md.
The file will have its original line endings in your working directory

HP@DESKTOP-C3MM5RA MINGW64 ~/Desktop/master (jostincito)
$ git status
On branch jostincito
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   README.md


HP@DESKTOP-C3MM5RA MINGW64 ~/Desktop/master (jostincito)
$ git commit
[jostincito cce56a2] deber progra
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

HP@DESKTOP-C3MM5RA MINGW64 ~/Desktop/master (jostincito)
$ git log
commit cce56a2a913862c8f0a30677dd0b23e114d7b184 (HEAD -> jostincito)
Author: jostincito <jjmontenegro1@espe.edu.ec>
Date:   Thu Oct 11 22:19:17 2018 -0500

    deber progra

commit 70eb139a74dde9db19185bc0d11b843d8eeee653 (master)
Author: jostincito <jjmontenegro1@espe.edu.ec>
Date:   Thu Oct 11 22:14:58 2018 -0500

    primer deber de progra

HP@DESKTOP-C3MM5RA MINGW64 ~/Desktop/master (jostincito)
$
