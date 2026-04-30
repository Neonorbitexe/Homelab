My goal is to set up:
-Kali Linux as the attacker
-Windows 11 as the SOC analyst machine
-A Windows system as the end user
-All connected on a private virtual network

Right now, I’m learning the tools and planning the environment. I haven’t started running attacks or fully built out my Splunk dashboard yet, but that’s the next step.

I’m focusing on understanding how SOC tools work, how logs are generated, and how analysts detect and investigate activity.

Here are the steps to build a home lab:
Step 1, you need to download a VM virtual machine  I picked VirtualBox (you can pick your own) 
vurtal box: https://www.virtualbox.org 
![image alt](https://github.com/Neonorbitexe/Soc-Homelab/blob/main/Screenshot%202026-04-30%20140027.png%20vm.png)


Step 2: when it done installing you will need to the Iso for kali liunx and windows 11. 
Kali Iso: https://www.kali.org/get-kali/#kali-installer-images
![image alt](https://github.com/Neonorbitexe/Homelab/blob/main/Screenshot%202026-04-30%20140313.png%20kali%20iso%20.png)

Windows Iso: https://www.microsoft.com/en-us/software-download/windows11
![image alt](https://github.com/Neonorbitexe/Homelab/blob/main/Screenshot%202026-04-30%20140216.png%20windows%20iso.png)

When have evering open you can open your vvm from there theyu wil be new opention to create kali or windows vm it doesnot mater the order you make first. 

Step 3: I will show you how to make a Kali VM 
to make one you need to open the new tab show in the screenshot 
![image alt](https://github.com/Neonorbitexe/Homelab/blob/main/Screenshot%202026-04-30%20141005.png%20make1.png)

it will open a windows that will allow you to set up the setting for the kali like hardware and networking and name ect. you will need to make sure you name the Vm and add the Iso for kali in the Iso dropdown. i will reacomenad adding the vm not to you main hdd to save storege space 
The screenshot shows what it should look like 
MAKE SURE YOU CHECK THE SKIP UATTTACHED INSTALLMENT 
![image alt](https://github.com/Neonorbitexe/Homelab/blob/main/s.png)

Step 4: when finish installing just follow the step on in stallong kali 

Step 4: Setting up Windows Vm 
To make one it will be the same with the opeining the new tap. the screensshot show what need to be add its the same as kali but jut wishtch it with windows Iso and name it windows vm 
MAKE SURE YOU CHECK SKIP UNATTENDED INSTALLINATION 
![image alt](https://github.com/Neonorbitexe/Homelab/blob/main/Screenshot%202026-04-30%20164658.png%20win%20setup.png)

Step 5: windows hardware I would reacomand give window more ram and cpu. 8g ram and 4 proccsres work great if able to run 
![image alt](https://github.com/Neonorbitexe/Homelab/blob/main/image_2026-04-30_170553455.png)

Step 4: when finish installing just follow the step on in stallong kali 


