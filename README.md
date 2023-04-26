<p align="center">
<img src="https://i.imgur.com/vPpllPV.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Creating and using Virutal Machines in Microsoft Azure</h1>
This project outlines the implementation of building a Virtual Machine (VM) within Azure. The tools within Azure will allow you to create and access the necessary tools for operating Virtual Machines. <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop


<h2>Operating Systems Used</h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Create Azure account
- Create Resource Group
- Create Virtual Machine
- Access Virtual Machine with Remote Desktop

<h2>Deployment and Configuration Steps</h2>

<p align="center">
Visit azure.microsoft.com, select start free, enter account and payment details for free trial:<br/>
<img src="https://i.imgur.com/89Que0W.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
In portal.azure.com, navigate to Resource groups, select Create:  <br/>
<img src="https://i.imgur.com/GE9mjOM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
Name your resource group and select the region closest to you: <br/>
<img src="https://i.imgur.com/xsHoaxF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Navigate to Virtual Machines, select Create and then Azure Virtual Machine: <br/>
<img src="https://i.imgur.com/4kMk4m1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the previously created resource group, name the VM, select Windows 10 Pro, choose a size with 2 vcpus: <br/>
<img src="https://i.imgur.com/HlxMmxM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create a username and password that you will remember, check the Licensing box at the end, and select review & create: <br/>
<img src="https://i.imgur.com/z2WigCC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Find your new virtual muchine from the Azure portal menu, in your windows search bar type and launch remote desktop, <br/>
enter the I.P. address listed in your VM and click connect, if a security propmt appears select accept: <br/>
<img src="https://i.imgur.com/AyXISF5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
You should now be in your VM which is set up like a normal windows PC, recognize the bar at the top, <br/>
this should list the I.P. you have entered and controls to exit the VM and return to your desktop: <br/>
<img src="https://i.imgur.com/JYr2clN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
