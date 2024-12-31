# Creating a Virtual Machine

![images](https://github.com/user-attachments/assets/98e24602-2476-4a4d-b6b3-d617a6de2cf5)

## Virtual Machine - Prerequisites and Installation
This tutorial outlines the prerequisites and how to install a VM.

### Environment Used
- Hyper-V Manager

### Operating System Used
- Windows 10 2022 Update | Version 22H2

### Steps Included
- Turn on window features (Hyper-V)
- Download ISO for operating system of choice
- Install Virtual Machine
- Test connectivity

## Installation Steps

### STEP 1: Turn on Window Features (Hyper-V)
Not every Windows edition comes with Hyper-V, so Pro and above is a must. You will turn on Windows features, click on the Hyper-V folder, and the system will update and restart installing the feature.

<div align="center">
  <img src="https://github.com/user-attachments/assets/ef8ee58b-a8bc-4dc0-a74f-4ea60dc9a6fc" alt="Hyper-V Installation">
</div>

Next, we will download the ISO file.

### STEP 2: Download ISO File
Finding the ISO file is the easiest part, as Microsoft provides it for free. Go to [www.microsoft.com/en-us/software-download/windows10](https://www.microsoft.com/en-us/software-download/windows10). Then, create an installation media for another PC.

<div align="center">
  <img src="https://github.com/user-attachments/assets/82b774e4-c21e-4ebc-bd14-af8144b594ef" alt="ISO Download">
</div>

### STEP 3: Install the Virtual Machine on Hyper-V
Start by opening Hyper-V and clicking on New. You will see three options: Virtual Machine, Hard Disk, and Floppy Disk. Select Virtual Machine.

<div align="center">
  <img src="https://github.com/user-attachments/assets/2a00db8e-b240-45c1-a9b2-bd1598857602" alt="New Virtual Machine">
</div>

Name your virtual machine.

<div align="center">
  <img src="https://github.com/user-attachments/assets/b75012bc-0cd0-449a-85dd-99d7c8c24339" alt="Naming Virtual Machine">
</div>

Adjust the amount of virtual memory you would like your machine to have. 4096MB is the minimum.

<div align="center">
  <img src="https://github.com/user-attachments/assets/e9511e37-1220-4d35-9f84-8d7e1bbe4af0" alt="Virtual Machine RAM">
</div>

Configure the internet for your virtual machine using a Virtual Switch, which is the internet your VM will run on.

<div align="center">
  <img src="https://github.com/user-attachments/assets/60bc3e58-3585-467d-8515-2e0bd68b8505" alt="Virtual Switch Setup">
</div>

Finally, connect a virtual hard disk with your desired amount of storage.

<div align="center">
  <img src="https://github.com/user-attachments/assets/d4413a43-08d7-4172-8305-fa7096292b01" alt="Virtual Hard Disk Setup">
</div>

You can now open your virtual machine and begin the installation.

<div align="center">
  <img src="https://github.com/user-attachments/assets/f20dcf73-fd1b-409e-9d53-18b5cc5b1c66" alt="VM Installation">
</div>
