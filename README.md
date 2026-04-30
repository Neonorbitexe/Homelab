Here are the steps to build a basic SOC home lab. I included screenshots and links that helped me during setup.

Step 1: Download a Virtual Machine Software

First, you need to download a virtual machine software. I picked VirtualBox, but you can use any VM software you prefer.

VirtualBox: https://www.virtualbox.org
![image alt](https://github.com/Neonorbitexe/Soc-Homelab/blob/main/Screenshot%202026-04-30%20140027.png%20vm.png)

Step 2: Download the ISO Files

After installing VirtualBox, you will need ISO files for Kali Linux and Windows 11.

Kali Linux ISO:
[https://www.kali.org/get-kali/#kali-installer-images]
![image alt](https://github.com/Neonorbitexe/Homelab/blob/main/Screenshot%202026-04-30%20140313.png%20kali%20iso%20.png)

Windows Iso: https://www.microsoft.com/en-us/software-download/windows11
![image alt](https://github.com/Neonorbitexe/Homelab/blob/main/Screenshot%202026-04-30%20140216.png%20windows%20iso.png)

Once everything is downloaded, open VirtualBox. From there, you will have the option to create either a Kali Linux VM or a Windows VM. The order does not matter.

Step 3: Creating the Kali Linux VM

To create a new VM, click the "New" button shown in the screenshot below.
![image alt](https://github.com/Neonorbitexe/Homelab/blob/main/Screenshot%202026-04-30%20141005.png%20make1.png)

A new window will open where you can configure:

VM name
Hardware settings
Networking
ISO file location

Make sure you:

Name the VM
Select the Kali Linux ISO in the ISO dropdown
Save the VM to a different drive if possible to save storage space on your main drive

The screenshot below shows what the setup should look like.

IMPORTANT: Make sure you check "Skip Unattended Installation."
![image alt](https://github.com/Neonorbitexe/Homelab/blob/main/s.png)

After setup is complete, start the VM and follow the Kali Linux installation steps.

Step 4: Creating the Windows 11 VM

Creating the Windows VM is almost the same process as Kali Linux.

Click the "New" button and:

Select the Windows 11 ISO
Name the VM
Configure the hardware settings

Again, make sure you check "Skip Unattended Installation."
![image alt](https://github.com/Neonorbitexe/Homelab/blob/main/Screenshot%202026-04-30%20164658.png%20win%20setup.png)

Step 5: Recommended Windows Hardware Settings

I recommend giving the Windows VM more resources if your PC can handle it.

Recommended:

8 GB RAM
4 CPU processors

These settings worked well for me.
![image alt](https://github.com/Neonorbitexe/Homelab/blob/main/image_2026-04-30_170553455.png)

After setup is complete, start the VM and follow the Windows installation process.

The End

