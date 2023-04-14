# osTicket-Prerequisites-and-Installation
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



<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/RhdSmPn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
L1. Install and enable IIS with Windows CGI.

</p>
<br />

<p>
<img src="https://i.imgur.com/UlteVLr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install PHP Manager and Rewrite Mod.
</p>
<br />

<p>
<img src="https://i.imgur.com/3S0OWA1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
From your documents folder go to C Drive and create a PHP Folder.
</p>
<br />

<p>
<img src="https://i.imgur.com/OvGHhMa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Unzip Extracted files into PHP folder and Download C++.
</p>
<br />

<p>
<img src="https://i.imgur.com/doA8rQT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download My SQL Server
</p>
<br />

<p>
<img src="https://i.imgur.com/dxB2dvr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to ISS and Run as Administrator 
</p>
<br />

<p>
<img src="https://i.imgur.com/zwrpg0E.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
You will see all the programs you just downloaded. Double click PHP Manager
</p>
<br />

<p>
<img src="https://i.imgur.com/0OJKPXh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
You will notice that it says "Register New PHP Version to Enable or Disable PHP extension" Click the "Register new PHP version" Hyperlink. After you click the hyperlink you will browse to your C: drive and select from the PHP folder phpcgi ( which we enabled earlier). Once you have selected the file zip file phpcgi go back to th main admin screen and restart IIS. 
</p>
<br />

<p>
<img src="https://i.imgur.com/TiwDPYM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Restart is located in the right hand corner. 
</p>
<br />

<p>
<img src="https://i.imgur.com/iqYlbEe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now we will download OS Ticket, move the zipfile to our C: drive and test it in IIS to see if we are successful. If we are we should get a screen that looks like this!
</p>
<br />

<p>
<img src="https://i.imgur.com/dj2lZV1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We were successful! Now we have a few extensions that need to be enabled ( the red x's on the prior image) Back to IIS we go!  ClickSites, Default sites, OS Ticket, PHP manager. We will enable all extensions. Click the enable button in the left hand corner of the screen and enable all disabled components. 
</p>
<br />
<p>
<img src="https://i.imgur.com/CnwDZw6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

</p>
<br />
<p>
<img src="https://i.imgur.com/tXqVzwF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Now we are ready to select " Continue" at the bottom of the screen and set up OS Ticket.
</p>
<br />
<p>
<img src="https://i.imgur.com/A4w0OXM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
