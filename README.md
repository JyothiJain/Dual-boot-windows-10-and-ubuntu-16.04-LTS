## Dual-boot-windows-10-and-ubuntu-16.04-LTS
Will help a user have Windows 10 and Ubuntu 16.04LTS on same machine

This article will help you in setting up ubuntu side by side with windows in a machine and it’s called dual-booting. It will help in retaining all the data on windows and side by side creating space for ubuntu as well.



## Prerequisites

OS: Windows 10

USB drive: 4GB(Empty & Formatted)



#### Installation steps


#### Open a web browser and provide the below url to download a program called deluge(An open source bit torrent application and its purpose is to use the torrent protocol to download a large size file quickly without errors)

https://deluge-torrent.org/  




#### Navigate to the download tab and scroll down to the Microsft Windows section and click on the below link

​XP, Vista, 7 – 10



#### From the download page click on the top most exe file and save the file.

deluge-1.3.15-win32-py2.7.exe



#### When the download is complete run the exe file by saysing yes to the windows prompt, click on next, agree to the license by clicking on I agree button, again click on next button, choose the destination folder and click on next button, and finally click on install, wait till completed and click on next button, installer will ask you if you want otional package click on the no button

Click on Next>>Click on I agree>>Click on Next>>Choose the destination folder and click on Next>>Click on Install>>Click on Next



#### Open Deluge 

Click on Start>>In the search-box type deluge and click on the deluge folder and finally the deluge job




#### Windows firewall will appear when you run the program for the first time asking for permission to access the network

Click on allow access button



#### Open a browser and click on the below link 

https://www.ubuntu.com/download




#### Navigate to the Alternative downloads tab and navigate to the bit torrent section click on the below link and click on Open button, windows will open it straight in Deluge

Ubuntu 16.04.5 Desktop (64-bit)




#### In deluge window, click on add from the pop up in deluge and let it download.

#### NOTE: 
After the above download is complete, connect an USB dirve(4GB ) to your machine.




#### Download Rufus(A utility that helps format and create bootable USB flash drives, such as USB keys/pendrives, memory sticks, etc.) from the below link and then navigate to download section and then click on the exe link.

http://rufus.akeo.ie/

Downloads>>Rufus 3.3 



#### Click on the run button>> from security prompt click on yes, and say no to the program applicaion updates online




#### By default rufus should automatically detect the flash drive connected to the machine and now lets set the below configurations

File system: FAT32(Default)

Cluster size: 4096

Create a bootable disk using: Iso Image (Click on the disk button to choose ISO image)




#### From the pop up choose the below file(If not found check in downloads folder) and click on Open 
ubuntu-16.04-desktop-amd64


#### Note: 
Make sure the flash drive does not have anything in it.



#### Click on start in rufus, click on yes from the pop up, check the ISO Image and clik on Ok, again click on Ok from the warning pop up and wait till completed.




#### Close all your opened programs and restart your machine and before windows load in your machine keep clicking on the below from your keyboard
 F12 or Esc or F10 or F9(try one at a time, this is to go to the boot manager)


#### Note: 
Make sure there is only one USB drive or flash drive connected to your machine so that it is easy to choose for booting ubuntu on your machine





#### Now from the Boot Option Menu select the below
USB HDD





#### After it loads the flash drive we can install ubuntu, now click on the below
Install ubuntu




#### Now check the second option  i.e.
Install third party software option




#### Now check the first option i.e. 
Install ubuntu alongside windows 10



#### Click on continue and now make equal distribution of your hard drive by using the slider option present between the two OS and setting the partition as half and half like 16.9GB each




#### Click on Install now button, click on continue, again click on continue to confirm 
Install now>>Continue>>Continue




#### Select your region to set the right time and click on continue button
India-Kolkatta



#### Select language as the below and click on continue buton
English-US




#### Provide the below details and click on continue button
Username: Steve (give your name)

Choose Password: ********* (give the password you will remember)

Confirm Password: *********

Check the Require my password check box 




#### Wait till the installation is complete and then click on restart now button

#### Note: 
Remove the USB drive/ Flash drive from your machine




#### After the machine restarts , select windows option and press enter(to check if windows os did not get affected by ubuntu installation)
Click on the shutdown and restart your system




#### Select ubuntu option and press enter
Provide the password and login, now ubuntu is ready to be used.

