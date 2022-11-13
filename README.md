# osTicket-Prerequisites-
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Item 1: Setup a Virtual Machine in Azure
- Item 2: Install the osticket requirments
- Item 3: Install osTicket itself
- Item 4:  Do the after-installation configuration of os ticket

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/Qy2J7O6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open Microsoft Azure and navigate to the search bar at the top of the page and type resource group. Once on that page you will want to click the Add + button in the top left hand corner. You will be taken to this screen to input the information for the resource group, as you see in the image above.
</p>
<br />

<p>
<img src="https://i.imgur.com/gGfFkGf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/M60rpeD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
<img src="https://i.imgur.com/bVqNQnT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
After creating the resource group, navigate back to the same search bar and type Virtual Machine. Once again you want to click Add + new in the top left hand corner and fill out the information as follows in the image above. After inputting all data, Click Review and Create.
</p>
<br />

<p>
<img src<img src="https://i.imgur.com/feiEwo0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>="https://i.imgur.com/feiEwo0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/YkLUzOR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>Once you have created the virtual machine, copy the public ip address and paste into remote desktop, where you will be able to begin our process installing OSTicket on our new virtual machine. You will be prompted for your Username and Password that we setup in the previous section.
</p>
<br />

<p>
<img src="https://i.imgur.com/7wcClkd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The Next step once your actually in the Virtual Machine, is to enable IIS or (Internet Information Systems) you must navigate to the control panel. In control panel click add or remove program. From there, in the top left hand corner, click Turn windows features on or off. From that point find internet information systems like in the image above and check the box to enable.
</p>
<br />

<p>
<img src="https://i.imgur.com/wO1wy4r.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After Enabling IIS, you will need to download and install Web Platform Installer 5.1 which we will need to help us install the rest of the necessary programs needed for OSTicket. As Shown in the image above.
</p>
<br />

<p>
<img src="https://i.imgur.com/Uu9vOqV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Shown in the image above are the files needed to be installed with Web Platform Installer
</p>
<br />

<p>
<img src="https://i.imgur.com/DgnxEV0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Use This Link to Google Drive where the OSTicket download can be found https://drive.google.com/drive/u/0/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6 
</p>
<br />


<p>
<img src="https://i.imgur.com/cPYQc6K.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once you have downloaded the zip file, extract all contents in same folder. Copy the upload file and paste into the wwwroot folder found in my pc. Once Completed, rename folder OSTicket as shown. 
</p>
<br />

<p>
<img src="https://i.imgur.com/0kQ88F4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open IIS, and click the restart option in the upper right hand corner. Then browse to site,default,OSTicket. Once in OSTicket on the far right side click Browse*:80(http)
</p>
<br />

<p>
<img src="https://i.imgur.com/a2RVON2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open IIS back and click PHP manager, scroll to the bottom and click add or change extension. Make sure php_intl.dll and php_opache.dll is enabled 
</p>
<br />

<p>
<img src="https://i.imgur.com/UXumk23.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Once you have enabled all the following PHP files, refresh browser and observe the changes 
<p>

</p>
<br />

<p>
<img src="https://i.imgur.com/GHqpfwX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Finally continue setting up the browser with chosen usernames and passwords and Congradulations you have installed OSTicket on a Virtual Machine.
<p>
  
  <p>
<img src="https://i.imgur.com/UkHCoT4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
