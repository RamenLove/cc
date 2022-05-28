# cc
Own Cloud

Steps
1)Open terminal
2)sudo apt update
3)sudo apt install openssh-server
4)note ip address of your machine (ifconfig)
5) if 4th step dosent work then sudo apt install net-tools then use step 4
6)sudo apt install apache2


Xampp PHP
Download xampp
Give permission to installer
Go to directory
 Sudo chmod +x filename
Sudo ./filename
go to cc (cd cc)
use command cd /opt/lampp
sudo ./manager-linux-x64.run (to launch xampp control panel)
start apache server and check in browser by typing "localhost/dashboard" in url
in opt/lampp directory cd to htdocs
then create new file index.php(sudo gedit index.php)
write code for index.php
then create a file inside htdocs rss.php
write the code for rss.php
Make both index and rss excecutble by command
sudo chmod +x index.php
sudo chmod+x rss.php
run file in browser "localhost/index.php"
