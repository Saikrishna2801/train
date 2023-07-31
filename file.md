this is first file created through remote repo to main repo
the commands are below
$ git add file.md

SAPABAP@DESKTOP-5BT497O MINGW64 ~/Gitpractice (master)
$ git commit -m "file"
[master (root-commit) 52d997e] file
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 file.md


SAPABAP@DESKTOP-5BT497O MINGW64 ~/Gitpractice (master)
$ git branch -M main


SAPABAP@DESKTOP-5BT497O MINGW64 ~/Gitpractice (main)
$ git remote add origin https://github.com/Saikrishna2801/train.git


SAPABAP@DESKTOP-5BT497O MINGW64 ~/Gitpractice (main)
$ git push -u origin main

SAPABAP@DESKTOP-5BT497O MINGW64 ~/Gitpractice (main)
$ ls
file.md  train/

