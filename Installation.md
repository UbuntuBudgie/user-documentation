# Installing Ubuntu Budgie

Now that you've got Ubuntu Budgie on the USB it is time to start the installation procedure. 

One of the first thing that you need to check is if the proper Boot Mode has been selected. Depending on each case that mode could either be UEFI or UEFI CSM which support UEFI and Legacy BIOS. 

Newer laptop that come in Windows are always preconfigured to boot in UEFI mode.  

In order to start the installation, you need to boot from the USB drive you need to either set up the USB as device that will be first to boot via UEFI BIOS, or to select it as booting device once the device is being powered. 

Booting device list can be selected by pressing one of the buttons from F1-F10. What button will be used depends on the the manufacturer of the board. To find out what is the button being used, feel free to check that models website in case if it is laptop or motherboard website in case we are talking about desktop computer.

Once you boot up you will be presented with Installation screen.

 ![Installation Boot menu](images/2.png)

You can choose to either try Ubuntu Budgie without installation, or you can install Ubuntu Budgie directly.

If you selected to boot Ubuntu Budgie, the Ubuntu Budgie will start checking file integrity. This ensures that installation is not damaged or corrupted.

![File check](images/1.png)



When you are ready to install you can start the installation process. If you have chosen to test Ubuntu Budgie without installation you can always use the Ubuntu Budgie Welcome to install it and start installer. 

![Welcome Screen](images/3.png)

Next screen will allow you to choose the language

![Welcome install](images/4.png)

After you have chosen the language you will be offered to choose the keyboard layout. 

![Keyboard layout](images/5.png)

Let's get on with the installation itself. 

![Updates and Drivers](images/6.png)

Normal installation option installs as it is described a set of different kinds of software for example like full office suite, Libre Office, and different media players.

Minimal installation does not have addition cruft in it, and it has only the necessary minimal stuff needed for system to run. Of course, there is a video player and other stuff, but it is not so heavily packed as normal installation.

Other options

Here we have 2 options that you can check. The first one will try to connect to the Ubuntu mirrors and retrieve the updates that have been released. Remember, you may install Ubuntu Budgie on release day, but if you try to install it later down the road, there will be updates released by that time. That's why, it is better to select this option if you want to have fully updated system after the installation and save the time configuring the updates. Do note that depending on your internet speed, the install time may be a little longer.

The second option will allow you to install the necessary codecs needed for playing media files in different formats. Aside from that it will download and install 3rd party drivers for Wi-Fi and Graphics card. 

The next screen allows you to choose installation type.

![Installation type](images/7.png)

You can either Erase entire disk and Install Ubuntu Budgie or choose Something else. 

Option for something else allows you to manually partition one of the hard drives and create partitions needed to run Ubuntu Budgie.

In case you have another operating system installed on same hard drive, there will be another option that will allow you to Install Ubuntu Budgie alongside Windows for example.

If you choose to install Ubuntu Budgie as only system, do note that your whole hard drive will be automatically set up and formated. Backup any docs or files you have on that drive in case it is not empty. 

![Advanced Features](images/8.png)

Advanced feature option allows you to choose to use LVM for Ubuntu Budgie Installation, Encrypt installation with security key, or use ZFS.

When selecting first option you will be presented with the screen that will tel you more details about the hard disk, as well with other info. The same screen is also used in case you use manual partition option. 

![Installation type](images/9.png)

Near below there is option to select device for boot loader installation. Make sure that the same hard drive that is selected for the installation is also selected for bootloader installation.

When you click install now, the window will pop-up informing which hard drive, partition, will be used to write changes and which of them will be formated.

 ![Confirmation](images/10.png)

The next screen will offer you to choose time zone. You can do it from the menu bellow the map or from the map itself. In some cases it may be selected automatically if there is internet while installation is taking place.

![Time Zone](images/11.png)

After that screen, the installation screen will be presented with slides explaining more about what Ubuntu Budgie is and what it offers. The installation screen contains slides that are controlled by the right and left arrows on the right side. You can always go back or forward and check each of them out while you are waiting for the installation to finish. 

![Progress](images/12.png)

The installation bar shows how far the installation is done. If you click the black arrow next to Copying files, you will have CLI with info about what is going on with installation and which files are being copied at the given moment.

![Installation progress](images/13.png)

As you can see when expanded, the data displayed, reflects the status of the installation. Also on the left side is the Slingshot menu that is enabled by default. We will talk more about it in the next part of this tutorial.

![Progress and Slingshot](images/14.png)

After the installation is offer, you will receive the notification. You can explore the desktop before restarting by clicking ,,Continue Testing" or restart immediately by clicking ,,Restart Now".

![Finished Installation](images/15.png)

After clicking, the distro will restart itself. The next step is to remove USB you used for the installation and press Enter to finish installation.

![Final restart](images/16.png)

Congratulations! You have just installed Ubuntu Budgie.