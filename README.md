# bandit
## 1. bandit0

login into ssh via the host and port number
// enter level 1

## 2.bandit2
 first login by enetering bandit1 
 i.e  ssh bandit1@bandit.labs.overthewire.org -p 2220

 use the cat command to get the password

## 3.bandit3

login into level2
use cat command but with./      
i.e cat ./-

## 4. bandit4

login into level 3
now the file name contain spaces 
so after every space use a '/'
i.e cat spaes/ in/ the/ file

## 5. bandit5

login into level 5 

use the cd command in here like cd inhere
and use ls command to list the file

## 6. bandit6
for this use the file command and check which file is in the ASCII format for example if file07 is in the formatg then use cat file07 to get the password

## 7.bandit07
use the find -size 1033c to find the file of required bytes
and check the human reable format with the help of the the previoys level 

## 8. bandit8
use the grep command like 
grep millionth data.txt

## 9. bandit9
use the uniq -u command for this

## 10 bandit 10

use grep ==

## 11 bandiot11
cat data.txt|base64 -d
use -d for decoding the ifle

## 12 bandit12
use the cat command and get the text and use the online rot13 neter the text and get the password

## 13 bandit13
 several steps are to be followed for this stage

mkdir /tmp/ashwin
cp data.txt /tmp/ashwin

#xxd -r data.txt

mv data data.gz
(renames and changes the extension)
gzip -d data.gz

mv data data.bz
(renames and changes the extension)
bzip2 -d data.bz


mv data data.tar
tar xf data.tar
(creates a new file which is extracted from it)

## 14 bandit14

in this upon enterin the stage now login inot the provate host
 ssh -i sshkey.private bandit14@localhost -p 2220

 now use the cat command foe the given file /etc/bandit_pass/bandit14

 now for the local host thing use 

 nc localhost 3000
 upon entering this 
 the password obatined upon entering cat command is now used upon using the nc command after this u will get he correct password and login into next stage

 





