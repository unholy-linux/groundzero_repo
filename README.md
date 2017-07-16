# groundzero_repo

Add and remove packages if you want

How to use:

To download use: git clone https://github.com/GroundZeroLinux/groundzero_repo

Navigate to to the x86_64 folder and add your packages

Open a terminal in the folder repo-add gz_repo.db.tar.gz *.tar.xz

Note...
Be sure to edit your pacman.conf at the bottom change

[gz_repo]
SigLevel = Never
Server = https://groundzerolinux.github.io/groundzero_repo//$arch

to 

[gz_repo]
SigLevel = Never
Server = file:///home/<username>/groundzero_repo//$arch# groundzero_repo
