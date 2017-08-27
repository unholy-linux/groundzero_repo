# unholy_repo

Add and remove packages if you want

How to use:

To download use: git clone https://github.com/unholy-linux/unholy_repo

Navigate to to the x86_64 folder and add your packages

Open a terminal in the folder repo-add gz_repo.db.tar.gz *.tar.xz

Note...
Be sure to edit your pacman.conf at the bottom change

[unholy_repo]
SigLevel = Never
Server = https://unholy-linux.github.io/unholy_repo//$arch

to 

[unholy_repo]
SigLevel = Never
Server = file:///home/<username>/unholy_repo//$arch# unholy_repo
