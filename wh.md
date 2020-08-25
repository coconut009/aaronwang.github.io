---
title: Ubuntu Common Instruction Set
date: 2018-05-18 16:47:33
tags: [Ref_Page, Ubuntu, Linux]
---
## Ubuntu To Do List 
I start using ubuntu since 2019, kinda fresh to the linux family
As a beginner like me, I highly recommend people to use this to do
list as a guide line. <br> I do hope it can help you 😁😁😁

<!-- more --> 

#### There are couple things needs to do after a fresh ubuntu install 

1. get **UPDATE** through Update Manager<br>
The most easy way to access the software update manager is by pressing superkey/ (windows key)
 <img src="https://easykey.uk/images/help/windows/windows-key.png" alt="Superkey" width="45"/> 
and type _update_. <br><br> 
<center><img src="https://i.ibb.co/MPjN9ZY/Ubuntu20041.png" alt = "software & Update_1" width = "500"> <img src=" https://i.ibb.co/qxnzBNx/Ubuntu20045.png" alt = "Software & Updates_2" width = "400"></center><br>
Once the software starts running, it will check the updates for the current version of Ubuntu that need to be installed 
If it does find any, install these first and run Update Manager again if you need to restart your machine.
Alternatively you can open the ubuntu terminal prompt and enter the following command, after following the requirement/ enter the root password, the system will start decking the essential update for the machine. <br><br>

```bash
sudo apt-get update
sudo apt-get dist-upgrade
```

2. make sure you have **ALL Graphic Drivers** <br>
Most of the drivers come pre-built in the linux kernel, due to the dependency on proprietary restricted products,some of the graphic drivers (😒😒😒 ==> Nvidia GPU Driver) need to be manually installed especially the distro before the Ubuntu 20.04 buid  <br><br><center><img src="https://i2.wp.com/itsfoss.com/wp-content/uploads/2012/09/Linus-Torvalds-Fuck-You-Nvidia.jpg?w=600&ssl=1" alt="Ubuntu Software Update Manager" width="250"/></center> 
In Ubuntu 20.04, it really easy to install the graphic driver. Simply click the Software & Updates icon,the system will scan for essential driver/ software updates, after the scan finished click "setting & Live patch" then click the Addition Drivers.<br><br><center> <img src="https://i.ibb.co/8xHdRSL/Ubuntu20042.png" alt ="software & Update_4" width = 600><br> <img src="https://i.ibb.co/nrHZ4Pn/Ubuntu20046.png" alt ="software & Update_4" width = 600><br> <img src="https://i.ibb.co/jLzJsP8/Ubuntu20047.png" alt ="nvidia logo" width = 600></center><br> 
First, the system will search for the available drivers, after the search finished the system will provide a list of available drivers for the device could be installed. After select the needed driver package, simply click "Apply Changes" the system will do all the works. 👍👍👍<br>
After the driver install finished don't forget to reboot the system, once the system backs online type nvidia the system shall display the green logo.👇👇👇
<center> <img src="https://i.ibb.co/71S4hcH/Ubuntu20048.png" ale ="nvidia logo"></center><br>
 
3. Enable Firewall<br>UFW is the ubuntu built-in firewall and it is highly recommended to turned on. By default it is not enabled and user shall manually enable it.<br><br>
``` bash
# To Enable:
sudo ufw enable
# To Disable:
sudo ufw disable
# If you want ot manage the firewall in GUI you can install the gufw
sudo apt-get install gufw
```

4. Install Multimedia Codecs<br>
Some multimedia codes are not pre loaded on Ubuntu and the codecs are the essential elements when playing multimedia files. Install the multimedia codecs with the following command:
``` bash
sudo apt-get install ubuntu-restricted-extras
```

5. Remove the Apport<br>
Ubuntu pop-window shows up randomly and tells you there is crash report and asks you to send the report even when there is no crash 😵😵😵 In order to terminate it, we can remove the apport with the following command :
```bash
sudo apt remove apport apport-gtk
```

6. Install Java<br>
Java is necessary pillar for many programs especially for website. The easiest way to install Java on linux system is using the apt package management tool, to install Java using the following command:
```bash
# jdk ==> Java Development Kit
sudo apt-get install default-jdk
```
Once the package finished installing don't forget to verify it
```bash
java -version
```
you should get the similar outputs:
```bash
openjdk version "11.0.5" 2019-10-15
OpenJDK Runtime Environment (build 11.0.5+10-Ubuntu-0ubuntu119.04)
OpenJDK 64-Bit Server VM (build 11.0.5+10-Ubuntu-0ubuntu119.04, mixed mode,sharing)
```
7. Configure the keyboard shortcuts<br>
To configure the keyboard shortcuts just follow the path **Setting => Device => keyboard**

8. Install git<br>
personally I prefer to put some setup file into my personal github repository, in oder to install git ( also through apt package management tool) with the following command:
```bash
sudo apt install git
```
after the installation finish check the version of git
```bash
git --version
```

