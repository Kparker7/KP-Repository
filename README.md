# KP-Repository
echo "# KP-Repository" > README.md

Administrator@MININT-RMIEPJG MINGW64 ~
$ git --version
git version 2.51.0.windows.1

Administrator@MININT-RMIEPJG MINGW64 ~
$ git config -- global user.name "K Parker"
fatal: not in a git directory

Administrator@MININT-RMIEPJG MINGW64 ~
$ git config --global user.email "kparker70@student.ccc.edu"

git add README.md
git commit -m "updated-branch"
git push -u origin feature-update
