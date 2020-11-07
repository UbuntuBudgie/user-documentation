# Introduction

Thanks for choosing to use Ubuntu Budgie as distro of your choice. This guide is here to ease your journey of learning how Ubuntu Budgie works, its features, and how to troubleshoot any problem that may arise.

### **What is Ubuntu Budgie?**

Ubuntu Budgie is a distro that combines the Ubuntu as its base and Budgie Desktop Environment made by Solus team. 

### Where do I get Ubuntu Budgie?

You can get Ubuntu Budgie ISO by visiting https://ubuntubudgie.org/downloads/. You can either download the ISO directly or by using torrent file that is another option when selecting Download button. Aside from Direct Download and Torrent Download button there is also a readme notes button that contains list of changes in the latest version. 

The page offers 3 versions for the release, LTS version, standard release version and current LTS version if it is available.

What is the difference between LTS and Standard version? Long Term Support or LTS for short are versions that have its packages upgraded and the new features are not implemented until the next LTS version. This way, it offers more stability, predictability when compared to the standard version. 

Starting from version 19.04, there are no 32bit versions of the ISO with default being 64bit.  

Whatever option you choose after you finish downloading ISO be sure to check md5 or sha1 file checksum. This is important since if the has does not match the ISO is not original and the installation could fail or the install could be instable since the files got corrupted during the download. 

It is recommended that you use download manager when downloading ISO which offer far more features than default browser download manager and even allow you to pause download if needed without affecting the ISO. 

When the download is done you can check the hash checksum. If you are using Windows, you can download HashTab which integrates with Windows Explorer and allows you to check by right clicking and going to Properties of ISO or any other file.

If you are using any linux distro the fastest way would be to use md5sum command. 

```
md5sum ubuntu-budgie-20.04-desktop-amd64.iso
```

which then returns

```
0947e4bb34c2c8bd0e6458da17228e1e  ubuntu-budgie-20.04-desktop-amd64.iso
```

as a value. 

If there is sha256 value available on the website, you can also use it to check verity of ISO, instead of md5sum. 

In case you are using Windows, you can user PowerShell to check those values.

Open PowerShell - We recommend working with Windows PowerShell ISE because the handling is a little bit easier!

Navigate to your downloads folder (normally this should be C:\Users\$Username\Downloads) 

Inside the downloads folder you type the following:

```powershell
powershell Get-FileHash .\ubuntu-budgie-20.04.1-desktop-amd64.iso -Algorithm SHA256 | Format-List
```

Get-FileHash .\ubuntu-budgie-20.04.1-desktop-amd64.iso -Algorithm SHA256 is getting the information we are looking for (the file hash); but PowerShell does have several hash sums we could be checking so with "-Algorithm SHA256" we are telling the computer which sum needs to be generated.

Compare the hash you got with the has on the web page. The best way to do this is to open any text editor, paste the value from the website and then the value you got when comparing. 

### Preparing installation media

To install Ubuntu Budgie, you will need to get yourself USB that is around 4GB or more. Depending on what system are you using at the moment you have various option on how to create bootable USB drive.

In Windows, you can simply use Rufus. Rufus is portable program that you can download from rufus.ie . Once you download it, you can simply run it by double clicking, without any installation.

Select your USB Drive from ,,Device,, section under Driver Properties headline. Make sure that you have selected the correct drive. Under boot selection option, it will show you the ISO you have selected to load. Click SELECT button, locate the iso, and open it. 

In regards to partition scheme you can select GPT or MBR one. The GPT is newer one and has been use for quite some time. MBR  is older one and mostly used in system Windows XP-7. If you have hard disk that is larger than 2TB you must use GPT since the MBR scheme doesn't support it. You will usually find GPT with associated with UEFI, so if you are installing Ubuntu Budgie on Laptop, make sure to check if UEFI/UEFI-CSM is your current booting method. When you are ready, you can click start and it will extract Ubuntu Budgie ISO and make bootable USB drive.

If you are using some other Linux distro the easiest way to create Ubuntu Budgie ISO is to download Etcher.io

