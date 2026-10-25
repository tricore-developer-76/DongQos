# DongQos
/ The official OS repository \
 this is the offcial DongQOS repository

Guide to Using the dongQos Operating System

QoS means Query Operating System. It is a new kind of operating system.
DongQos comes with apps like the Brave web browser, Paint, Notepad, and a terminal that uses RAGS.
RAGS is based on Bash, a Linux shell. DongQos is the operating system, and Qos is the kernel. The original OS was written in Rust and x86 assembly, along with system applications written in C++. It is a 64-bit Operating system; it will not work on 32-bit systems.
It is also open-source, and you can find it on the main GitHub page so you can contribute to it.
The Github Page
The next part of the guide covers installing the DongQos Operating system we discussed.

Installing DongQos

The installation is very easy; just go to the main website of DongQos and download the file called “dongqos.iso”
(note: this documentation was made before the os, so we can’t provide the link)
    • For this, you need at least 8 GB of RAM and a CPU not from before 2015 
    • or else your computer will lag.
After this, we are going to see which Operating system you currently use.
windows

For Windows users, here are the steps you need
A pendrive with at least 16 GB of storage

    • Download the iso called “dongqos.iso”
    • After that, install an application called Rufus or BalenaEtcher.
For Rufus, the website is
Rufus
and for Balena Etcher 
Balena Etcher
    • Then insert the pendrive. After that, open Rufus or Balena Etcher.
    • Rufus or Balena Etcher will automatically detect the USB drive you plugged in.
    • The application will ask for the iso.  
    • Then select the dongqos iso and click Flash. 
    • Wait until it is finished.
    • After that, restart your PC and press and hold the following key, depending on your PC brand.
For Dell users:
The F12 key
For HP users:
The ESC key
For Levono users:
The F12 key
For ASUS users:
The ESC key
For Acer users:
The F12 key
For other computer brands
The Shift key
    • Then click on Troubleshoot.
    • Next, click Advanced options.
    • Then click on UEFI firmware settings.
    • Then click Restart; the computer will open the BIOS settings.
    • Select your flashed pendrive and click.
    • The screen will change to the DongQos installation screen.
    • DongQos will ask for the username, computer name, and password.
    • After that, it will ask for the disk space you want to give it. Give at least 23 GB
    • Then click Install.
    • Wait until it shows the installation is finished, then click Restart computer.
Congrats, you installed the DongQos OS successfully🎉🥳. Now you need to open up the terminal and type. 
“getdata —processor”
to check that everything is fine
Now for Linux users:
Linux users

For Linux users, here are the steps you need
A pendrive with at least 16 GB of storage

    • Download the iso called “dongqos.iso” from the main website.
    • Then install a tool known as Ventoy.
ventoy
    • Download the .tar.gz file.
    • Right-click on the .tar.gz file and select Extract here
    • Then click on the extracted folder and find a program known as “VentoyGUIx86_64”.
    • Then select your pendrive and click Create. Make sure that there is no data on that drive.
    • After that, restart your PC and press and hold the following key, depending on your PC brand.
For Dell users:
The F12 key
For HP users:
The ESC key
For Levono users:
The F12 key
For ASUS users:
The ESC key
For Acer users:
The F12 key
For other computer brands
The Shift key
    • After that, the GRUB bootloader will appear.
    • Then click on UEFI firmware settings.
    • The Ventoy GUI screen will appear; select the DongQos option.
    • The screen will change to the DongQos installation screen.
    • DongQos will ask for the username, computer name, and password.
    • After that, it will ask for the disk space you want to give it. Give at least 23 GB
    • Then click Install.
    • Wait until it shows the installation is finished, then click Restart computer.
Congrats, you installed the DongQos OS successfully🎉🥳. Now you need to open up the terminal and type. 
“getdata —processor”
to check that everything is fine
Now for macOS users:
macOS users

For macOS users, here are the steps you need
A pendrive with at least 16 GB of storage

    • Download the iso called “dongqos.iso” from the main website.
    • Then install a tool known as the Fedora Media Writer.
(Note:  In this guide, we are calling Fedora Media Writer FMW)
FMW
    • Then flash your USB drive with FMW. Ignore all the error messages.
    • Wait until it is finished.
    • After that, restart your PC and press and hold the following key, depending on your PC brand.
For Dell users:
The F12 key
For HP users:
The ESC key
For Levono users:
The F12 key
For ASUS users:
The ESC key
For Acer users:
The F12 key
For other computer brands
The Shift key
    • Then click on Troubleshoot.
    • Next, click Advanced options.
    • Then click on UEFI firmware settings.
    • Then click Restart; the computer will open the BIOS settings.
    • Select your flashed pendrive and click.
    • The screen will change to the DongQos installation screen.
    • DongQos will ask for the username, computer name, and password.
    • After that, it will ask for the disk space you want to give it. Give at least 23 GB
    • Then click Install.
    • Wait until it shows the installation is finished, then click Restart computer.
Congrats, you installed the DongQos OS successfully🎉🥳. Now you need to open up the terminal and type. 
“getdata —processor”
#rust
#osdev
