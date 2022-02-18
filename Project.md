[Visit repositary!](https://github.com/OsamaShaikh0300/OSLAB-Project.git)
# Project Members :
* Osama Shaikh CS201252
* Owais Ali CS192005
# Project Details :
#### 1st step :
download putty
#### 2nd step :
Go to virtual box and install ssh in ubuntu 
Command for update ssh:
sudo apt-get update
Command for install ssh:
sudo apt-get install ssh
#### 3rd step :
Make a keypair file:
Command:
ssh-keygen
Note the location of the file
#### 4th step :
Go to that location and email  files somebody then come to windows and download those files in windows
#### 5th step :
Open putty key generator and convert those files you download and save them with private key
#### 6th step :
Now open putty go to Auth open the file you save earlier as a private key then go to session and type your ip address.
Command for ip address:
hostname -I
Set the port to 22 then click on the connect button you will see the black screen and it will say connection timeout
#### 7th step :
Now we have to resolve the IP go to the virtual box setting go to the network and change the NAT to Bridged Adapter
#### 8th step :
Now open the ubuntu terminal again and check the ip address
Command for ip address:
hostname -I
Now you see the ip address is changed put that ip address in putty and connect it then the black screen will appair put your ubuntu id password in it ten you will see it will run perfectly
#### 9th step :
For checking you did the right thing make a sample folder from putty and you will see it's automatically appear in linux as well
##### Finished!!
