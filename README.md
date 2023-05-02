<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/VaJKvYe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The first step in the process of setting up the osTicket ticketing system is to utilize Microsoft Azure to create a secure lab environment. This picture shows the creation of an Azure virtual machine. A resource group was created along with the virtual machine: VM-OSTICKET. A virtual network (Vnet) was also created in this process.
</p>
<br />

<p>
<img src="https://i.imgur.com/dijEsv0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In order to connect to the virtual machine, a Remote Desktop Connection will need to be established using the public IP address of the virtual machine (20.172.246.188).
</p>
<br />

<p>
<img src="https://i.imgur.com/zkXYfAc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Internet Information Services (IIS) was installed and enabled with CGI.
</p>
<br />

<p>
<img src="https://i.imgur.com/ZrDhtLW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
PHP Manager for IIS was installed.
</p>
<br />

<p>
<img src="https://i.imgur.com/hGuPE4t.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The IIS URL Rewrite Module 2 was installed.
</p>
<br />

<p>
<img src="https://i.imgur.com/To2dn0j.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After the creaiton of the PHP file on the C: drive (C:\PHP), the PHP 7.3.8 zip file was downloaded. The contents of the file were extracted and placed in the C:\PHP file.
</p>
<br />

<p>
<img src="https://i.imgur.com/Cz6lROw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Microsoft Visual C++ was installed.
</p>
<br />

<p>
<img src="https://i.imgur.com/2tjiyPS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
MySQL Server was installed and configured.
</p>
<br />

<p>
<img src="https://i.imgur.com/5lZAkIv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
IIS was opened as an Administrator.
</p>
<br />

<p>
<img src="https://i.imgur.com/l9k0y1N.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
c:\PHP\php-cgi.exe (PHP) was registered within IIS.
</p>
<br />

<p>
<img src="https://i.imgur.com/RajKHWv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After downloading osTicket, this picture shows the upload folder being extracted and copied to c:\inetpub\wwwroot.
</p>
<br />

<p>
<img src="https://i.imgur.com/A6ASwvq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The upload file was renamed to osTicket.
</p>
<br />

<p>
<img src="https://i.imgur.com/SrWMEEq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After reloading IIS, this process was followed: Sites --> Default --> osTicket. On the right of the picture, Browse *:80 was selected.
</p>
<br />

<p>
<img src="https://i.imgur.com/KZxfy8S.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/EOSI1Xd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/ipf9TS3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/D0oncUh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/mPSZJzE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/tCuj9FF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/Lx6E3ho.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/zWBzFm1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/UAQvzSO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/47S4r0z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
