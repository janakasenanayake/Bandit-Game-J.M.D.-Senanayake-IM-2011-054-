# Bandit-Game-J.M.D.-Senanayake-IM-2011-054-

Materials : https://drive.google.com/folderview?id=0BxliB42HlluDNEh0am9SbTdvOHM&usp=sharing

Level 0
Level Goal

The goal of this level is for you to log into the game using SSH. The host to which you need to connect is bandit.labs.overthewire.org. The username is bandit0 and the password is bandit0. 
Login to the server:

ssh bandit0@bandit.labs.overthewire.org

Enter password:

bandit0


![l0 image 01](https://cloud.githubusercontent.com/assets/18350048/14386694/7d6313e0-fdc3-11e5-913f-d9d5b9f44eb9.PNG)

![l0 image 02](https://cloud.githubusercontent.com/assets/18350048/14386703/8342dc3c-fdc3-11e5-92ce-5bc992e97cfc.PNG)


Level 0 to 1

Level Goal
The password for the next level is stored in a file called readme located in the home directory. Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH to log into that level and continue the game.

List files & directories:
ls

Read the content of the readme file:
cat readme

Password for the next level:
boJ9jbbUNNfktd78OOpsqOltutMc3MY1

![l0_l1](https://cloud.githubusercontent.com/assets/18350048/14386706/83991e1c-fdc3-11e5-80f1-d9e562932231.PNG)


Level 1 to 2

Login to the server:

ssh bandit1@bandit.labs.overthewire.org

Enter password:

boJ9jbbUNNfktd78OOpsqOltutMc3MY1

Level Goal

The password for the next level is stored in a file called - located in the home directory.

List files & directories:

ls

Read the content of the - file:

cat ./-

Password for the next level:

CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9

![l1_l2](https://cloud.githubusercontent.com/assets/18350048/14386707/83b51a22-fdc3-11e5-963b-98c63519a84a.PNG)


Level 2 to 3

Login to the server:

ssh bandit2@bandit.labs.overthewire.org

Enter password:

CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9

Level Goal

The password for the next level is stored in a file called spaces in this filename located in the home directory.

List files & directories:

ls

Read the content of the spaces in this filename file:

cat "space in this filename"

Password for the next level:

UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK

![l2_l3](https://cloud.githubusercontent.com/assets/18350048/14386709/83bb8362-fdc3-11e5-89ef-c39636ef06d6.PNG)


Level 3 to 4

Login to the server:

ssh bandit3@bandit.labs.overthewire.org

Enter password:

UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK

Level Goal

The password for the next level is stored in a hidden file in the inhere directory.

List files & directories:

ls

Go to inhere directory:

cd inhere

List hidden files & directories:

ls .?*

Read the content of hidden file:

cat .hidden

Password for the next level:

pIwrPrtPN36QITSp3EQaw936yaFoFgAB

![l3_l4](https://cloud.githubusercontent.com/assets/18350048/14386710/83c0b5b2-fdc3-11e5-9061-0665810461f8.PNG)


Level 4 to 5

Login to the server:

ssh bandit4@bandit.labs.overthewire.org

Enter password:

pIwrPrtPN36QITSp3EQaw936yaFoFgAB

Level Goal

The password for the next level is stored in the only human-readable file in the inhere directory. Tip: if your terminal is messed up, try the “reset” command.

List files & directories:

ls

Finding the human readable file in inhere directory (Which is in ASCII format)

file inhere/*


Read the content of the human readable file:

cat inhere/-file07

Password for the next level:

koReBOKuIDDepwhWk7jZC0RTdopnAYKh

![l4_l5](https://cloud.githubusercontent.com/assets/18350048/14386711/83c2089a-fdc3-11e5-9637-708f64e27c0f.PNG)

Level 5 to 6

Login to the server:

ssh bandit5@bandit.labs.overthewire.org

Enter password:

koReBOKuIDDepwhWk7jZC0RTdopnAYKh

Level Goal

The password for the next level is stored in a file somewhere under the inhere directory and has all of the following properties: - human-readable - 1033 bytes in size - not executable.

List files & directories:

ls

Go to inhere directory:

cd inhere

Finding the human readable 1033bytes in size not executable file:

find ./ -type f -size 1033c


Read the content of the human readable 1033bytes in size not executable file:

cat ./maybehere07/.file2

Password for the next level:

DXjZPULLxYr17uwoI01bNLQbtFemEgo7

![l5_l6](https://cloud.githubusercontent.com/assets/18350048/14386704/8377b38a-fdc3-11e5-9d0b-d8093478846b.PNG)

Level 6 to 7

Login to the server:

ssh bandit6@bandit.labs.overthewire.org

Enter password:

DXjZPULLxYr17uwoI01bNLQbtFemEgo7

Level Goal

The password for the next level is stored somewhere on the server and has all of the following properties: - owned by user bandit7 - owned by group bandit6 - 33 bytes in size.

Finding the file stored somewhere on the server and owned by user bandit7 - owned by group bandit6 - 33 bytes in size:

find / -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null


Read the content of file:

cat /var/lib/dpkg/info/bandit7.password

Password for the next level:

HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs

![l6_l7](https://cloud.githubusercontent.com/assets/18350048/14386712/83cbf652-fdc3-11e5-8df5-2e60b99bb0a4.PNG)

Level 7 to 8

Login to the server:

ssh bandit7@bandit.labs.overthewire.org

Enter password:

HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs

Level Goal

The password for the next level is stored in the file data.txt next to the word millionth.

List files & directories:

ls


Read the content of file and get data next to the word millionth:

cat /var/lib/dpkg/info/bandit7.password

Password for the next level:

cvX2JJa4CFALtqS87jk27qwqGhBM9plV

![l7_l8](https://cloud.githubusercontent.com/assets/18350048/14386713/83d1845a-fdc3-11e5-9706-af69f1b7e2b3.PNG)

Level 8 to 9

Login to the server:

ssh bandit8@bandit.labs.overthewire.org

Enter password:

cvX2JJa4CFALtqS87jk27qwqGhBM9plV

Level Goal

The password for the next level is stored in the file data.txt and is the only line of text that occurs only once.

Read the content of the only unique line in the file data.txt by doing sort and uniq to find that line:

cat /var/lib/dpkg/info/bandit7.password

Password for the next level:

UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR

![l8_l9](https://cloud.githubusercontent.com/assets/18350048/14386717/84a1f856-fdc3-11e5-9086-290f4114107a.PNG)

Level 9 to 10

Login to the server:

ssh bandit9@bandit.labs.overthewire.org

Enter password:

UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR

Level Goal

The password for the next level is stored in the file data.txt in one of the few human-readable strings, beginning with several ‘=’ characters.

Read the content of the word with few human-readable strings, beginning with several ‘=’ characters:

strings data.txt | grep =

Password for the next level:

truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk

![l9_l10](https://cloud.githubusercontent.com/assets/18350048/14386714/83d82e5e-fdc3-11e5-8b06-fef57b30d8ff.PNG)

Level 10 to 11

Login to the server:

ssh bandit10@bandit.labs.overthewire.org

Enter password:

truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk

Level Goal

The password for the next level is stored in the file data.txt, which contains base64 encoded data.

Read the content of file:

base64 -d data.txt

Password for the next level:

IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR

![l10_l11](https://cloud.githubusercontent.com/assets/18350048/14386718/84aab4a0-fdc3-11e5-9a20-36877d819d80.PNG)

Level 11 to 12

Login to the server:

ssh bandit11@bandit.labs.overthewire.org

Enter password:

IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR

Level Goal

The password for the next level is stored in the file data.txt, where all lowercase (a-z) and uppercase (A-Z) letters have been rotated by 13 positions.

Read the content of file:

cat data.txt | tr '[A-Za-z]' '[N-ZA-Mn-za-m]'

Password for the next level:

5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu

![l11_l12](https://cloud.githubusercontent.com/assets/18350048/14386708/83b62b4c-fdc3-11e5-9a94-5fc9ec19b4c2.PNG)


Level 12 to 13

Login to the server:

ssh bandit12@bandit.labs.overthewire.org

Enter password:

5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu

Level Goal

The password for the next level is stored in the file data.txt, which is a hexdump of a file that has been repeatedly compressed. For this level it may be useful to create a directory under /tmp in which you can work using mkdir. For example: mkdir /tmp/myname123. Then copy the datafile using cp, and rename it using mv (read the manpages!).

Do the operations & Read the content of file:

mkdir /tmp/janaka123

cd /tmp/janaka123

 cat ~/data.txt | xxd -r > ./data
 
 file data 
 
mv data{,.gz}

 gunzip data.gz 
 
 file data 
 
mv data{,.bz2}

 bzip2 -d data.bz2 
 
 file data 
 
mv data{,.gz}

gunzip data.gz 

file data 

 tar xvf data 
 
data5.bin

file data5.bin 

tar xvf data5.bin 

file data6.bin 

mv data6{.bin,.bz2}

bzip2 -d data6.bz2 

 ls
 
file data6

tar xvf data6 

file data8.bin 

mv data8{.bin,.gz} 

gunzip data8.gz 

ls

file data8

cat data8 


Password for the next level:

8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL

![l12_l13](https://cloud.githubusercontent.com/assets/18350048/14386716/845af44c-fdc3-11e5-975a-3c9268cb4913.PNG)
