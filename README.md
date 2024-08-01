# Establishing a Virtual Machine using Azure
Practical Final for the CC IT Certificate Course



## Establishing a Virtual Machine in Microsoft Azure


 This tutorial outlines the creation and access of a Virtual Machine using Microsoft Azure Services

### Environments and Technologies Used
Microsoft Azure (Virtual Machines/Compute)
Remote Desktop


### Operating Systems Used
Windows 10 (21H2)

### High-Level Deployment and Configuration Steps

Step 1 - Go to azure.portal.com

Step 2 - 

Step 3

Step 4


### Deployment and Configuration Steps

First, go to Azure.Portal.com, and make sure you have an active subscription, free or paid. Your screen should display like this.
![image](https://github.com/user-attachments/assets/172e51da-fecd-4cbf-9f67-9233e42c1301)

From here, click on the Resource Group tab, and create a new Resource Group to house your Virtual Machine and all relevant files.
![image](https://github.com/user-attachments/assets/cd0f5052-aef8-4245-81f2-09bcdef6dd17)
![image](https://github.com/user-attachments/assets/0e13e1c0-8ea0-4f44-87b5-2b28dea4bb9d)

When creating your Resource Group, make sure it is filed under your active subscription. Also be sure to select the same region for all of your content, as to ensure maximum cohesion.
![image](https://github.com/user-attachments/assets/475c07ba-767a-42ae-8e63-39ae2065a5ea)


Once your RG is established, go to the Virtual Machines tab on the portal homepage, and select Create Azure Virtual Machine
![image](https://github.com/user-attachments/assets/996e1bcc-a19e-4c7b-8ed4-1cb3eb2a4238)
![image](https://github.com/user-attachments/assets/7dfc53d7-0c9a-4104-a6a6-0a8897685759)
![image](https://github.com/user-attachments/assets/12e2d798-b677-4078-976e-2fa2a333013e)


Once you have started the creation, make sure to select the Resource Group you made for this project as the storage point for this VM.
![image](https://github.com/user-attachments/assets/6a1ac3e4-b47a-4e37-b292-497552c34322)

Name your VM whatever is relevant to your project, and then scroll down to "Image", and select the Operating System you wish to use for your VM. In this case, I will be using Windows 10
![image](https://github.com/user-attachments/assets/fb9abbba-cc99-4462-b327-454f18a04842)


As for VM Size, the price per month will vary depending on the amount of memory and size of the Virtual CPU [VCPU] that you have chosen. The size and memory will dictate how fast your VM will run.For this, I have chosen the Standard_E2s_v3, with 16 GB of memory, and 2 VCPUs.
![image](https://github.com/user-attachments/assets/c4941e9f-097d-466b-ae98-38d5ce11987e)


Next, create an Administrator account and password. This will be the username and password you log in to the VM with. I have chosen my classic username, CrimmyJ.
![image](https://github.com/user-attachments/assets/6946be30-589b-4093-b0ae-1d6c9ee3417e)


Be sure to check this box at the bottom of the creation page, as Azure will not let you create the VM until you do.
![image](https://github.com/user-attachments/assets/fccefea9-947c-41ce-884e-b23b1e1e0042)

Once you have everything set up, named, and your username/password chosen, click on "Review + Create" at the bottom of the screen.
![image](https://github.com/user-attachments/assets/3da45da4-4c53-4897-a007-35445ebc32e2)

Continue through until you can click "Create", and wait for your VM to initialize and deploy.
![image](https://github.com/user-attachments/assets/fbd474a8-da6d-489d-91b4-303c65c170b8)

Once it has deployed, you have a few different ways to access your VM and its information. First, you can click on it from your resources tab on the main portal page. You can also click into your resource group and access it there, or navigate to the "Virtual Machines" tab from earlier.
![image](https://github.com/user-attachments/assets/7c442e92-8f17-4153-8e2f-d43044eabc4c)
![image](https://github.com/user-attachments/assets/578361dd-a09b-441b-868b-dac50f0cdc68)
![image](https://github.com/user-attachments/assets/0b08e904-a054-49f4-b442-3d54b372953e)


To log on to your now-created VM, find and copy the public IP address, which is listen in the essentials tab on your VM Overview.
![image](https://github.com/user-attachments/assets/1e907871-798d-49af-8539-489cb19cac99)
![image](https://github.com/user-attachments/assets/cde87852-8e45-45ca-ada9-59484d4afade)
![image](https://github.com/user-attachments/assets/57baaa56-ab9a-4ea6-93af-9935785d6084)


Once you have the IP address copied, go to your start menu and open Remote Desktop Connection. Here you will be asked to enter the public IP address from before, and once a connection is established, you will be asked to log in to the computer. Here is where you will use the username and password that you set up before.

![image](https://github.com/user-attachments/assets/ce5f00d1-b0cc-4de3-8c5f-b7e241f13f6e)
![image](https://github.com/user-attachments/assets/9af7962f-9f62-4aa4-96d2-f447ce557285)
![image](https://github.com/user-attachments/assets/e90e4dbb-2482-4c35-9105-f90c6e59aafa)

Once you have done all this, you are now able to access your virtual machine!
![image](https://github.com/user-attachments/assets/ef8ef1f4-9d88-49e7-8a47-a0bed43d46b3)

To log out and leave your virtual machine, simply click the "X" on the bar at the top of the VM.
![image](https://github.com/user-attachments/assets/e4fdef1e-64c1-4149-814b-b431f4b77aa4)








