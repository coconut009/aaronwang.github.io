<h1>Ubuntu To Do List</h1>
I start using ubuntu since 2019, kinda fresh to the linux family
As a beginner like me, I highly recommend people to use this to do
list as a guide line. <br> I do hope it can help you 😁😁😁

<!-- more --> 

<h4>There are couple things needs to do after a fresh ubuntu install</h4>

1. get **UPDATE** through Update Manager<br>
The most easy way to access the software update manager is by pressing superkey/ (windows key) <img src="https://easykey.uk/images/help/windows/windows-key.png" alt="Superkey" width="45"/> 
and type _update_. <br><br>
<img src="https://assets.ubuntu.com/v1/de3da8d8-download-desktop-upgrade-1.jpg" alt="Ubuntu Software Update Manager" width="250"/><br><br>
Once the software starts running, it will check the updats for the current version of Ubuntu that need to be installed 
If it does find any, install these first and run Update Manager again if you need to restart your machine.
Alternativly you can open the ubuntu terminal prompt and enter the following command:
```bash
sudo apt-get update
sudo apt-get dist-upgrade
``` 
after following the requirement/ enter the root password, the system will start decting the essential update for the machine
<br>


2. make sure you have **ALL Graphic Drivers** <br>
Most of the drivers come pre-built in the linux kernel, due to the dependency on proprietary restricted products,some of the graphic drivers (😒😒😒 ==> Nvidia GPU Driver) need to be manually installed especially the distro before the Ubuntu 20.04 buid  <br><br><center><img src="https://i2.wp.com/itsfoss.com/wp-content/uploads/2012/09/Linus-Torvalds-Fuck-You-Nvidia.jpg?w=600&ssl=1" alt="Ubuntu Software Update Manager" width="250"/></center> 
In Ubuntu 20.04, it really easy to install the graphic driver. Simply click the Software & Updates icon,the system will scan for essential driver/ software updats, after the scan finsh click "setting & Livepatch" then click the Addition Drivers. 
First, the system will search for the available drivers, after the search finished the system will provide a list of avaliable drivers for the device could be installed. After select the needed driver package, simply click "Apply Changes" the system will do all the works. 👍👍👍
After the dirver install finished dont forget to reboote the system, once the system backs online type ndidia the system shall display the green logo.👇👇👇


