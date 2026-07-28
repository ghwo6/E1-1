터미널 조작 로그
‘’’
Last login: Tue Jul 28 11:44:35 on ttys000
ghwo61351@c4r1s2 ~ % mkdir ~/ghwo6
ghwo61351@c4r1s2 ~ % cd ./ghwo6 
ghwo61351@c4r1s2 ghwo6 % git init                         
Initialized empty Git repository in /Users/ghwo61351/ghwo6/.git/
ghwo61351@c4r1s2 ghwo6 % git config --global user.name "Hojae"
ghwo61351@c4r1s2 ghwo6 % git config --global user.email "ghwo6@naver.com"
ghwo61351@c4r1s2 ghwo6 % git config --global init.defaultBranch main

ghwo61351@c4r1s2 ghwo6 % git config --list
credential.helper=osxkeychain
init.defaultbranch=main
user.name=Hojae
user.email=ghwo6@naver.com
init.defaultbranch=main
core.repositoryformatversion=0
core.filemode=true
core.bare=false
core.logallrefupdates=true
core.ignorecase=true
core.precomposeunicode=true
ghwo61351@c4r1s2 ghwo6 % 

ghwo61351@c4r1s2 ghwo6 % ls 
ghwo61351@c4r1s2 ghwo6 %                                           
ghwo61351@c4r1s2 ghwo6 % cd ~ 
ghwo61351@c4r1s2 ~ % ls
Applications	Downloads	Movies		Pictures
Desktop		ghwo6		Music		Public
Documents	Library		OrbStack
ghwo61351@c4r1s2 ~ % cd ./ghwo6 
ghwo61351@c4r1s2 ghwo6 % mkdir E01-01
ghwo61351@c4r1s2 ghwo6 % cd ./E01-01 
ghwo61351@c4r1s2 E01-01 % pwd
/Users/ghwo61351/ghwo6/E01-01
ghwo61351@c4r1s2 E01-01 % mkdir practice_dir
ghwo61351@c4r1s2 E01-01 % touch practice_dir/test.txt
ghwo61351@c4r1s2 E01-01 % ls ./practice_dir 
test.txt
ghwo61351@c4r1s2 E01-01 % cp practice_dir/test.txt practice_dir/copy.txt
ghwo61351@c4r1s2 E01-01 % mv practice_dir/copy.txt practice_dir/rename.txt
ghwo61351@c4r1s2 E01-01 % ls -la practice_dir 
total 0
drwxr-xr-x  4 ghwo61351  ghwo61351  128  7 28 12:43 .
drwxr-xr-x  3 ghwo61351  ghwo61351   96  7 28 12:42 ..
-rw-r--r--  1 ghwo61351  ghwo61351    0  7 28 12:43 rename.txt
-rw-r--r--  1 ghwo61351  ghwo61351    0  7 28 12:42 test.txt
ghwo61351@c4r1s2 E01-01 % ls -l practice_dir/test.txt
-rw-r--r--  1 ghwo61351  ghwo61351  0  7 28 12:42 practice_dir/test.txt
ghwo61351@c4r1s2 E01-01 % chmod 755 practice_dir/test.txt 
ghwo61351@c4r1s2 E01-01 % ls -l practice_dir/test.txt 
-rwxr-xr-x  1 ghwo61351  ghwo61351  0  7 28 12:42 practice_dir/test.txt
ghwo61351@c4r1s2 E01-01 % 
‘’’

