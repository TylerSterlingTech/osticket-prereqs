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
<img src="https://i.imgur.com/VaJKvYe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The first step in the process of setting up the osTicket ticketing system is to utilize Microsoft Azure to create a secure lab environment. This picture shows the creation of an Azure virtual machine. A resource group was created along with the virtual machine "VM-OSTICKET". A virtual network (Vnet) was also created in this process.
</p>
<br />

<p>
<img src="https://i.imgur.com/dijEsv0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To connect to the virtual machine, a Remote Desktop Connection was established using the public IP address of the virtual machine (20.172.246.188).
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
C:\PHP\php-cgi.exe (PHP) was registered within IIS.
</p>
<br />

<p>
<img src="https://i.imgur.com/RajKHWv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After downloading osTicket, this picture shows the upload folder being extracted and copied to C:\inetpub\wwwroot.
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
After reloading IIS, this process was followed: Sites --> Default --> osTicket. On the right of the picture, "Browse *:80" was selected, leading to the osTicket Installer.
</p>
<br />

<p>
<img src="https://i.imgur.com/KZxfy8S.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The osTicket Installer page is displayed, yet not all of the proper extensions have been enabled.
</p>
<br />

<p>
<img src="https://i.imgur.com/EOSI1Xd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Within IIS, php_imap.dll, php_intl.dll, and php_opcache.dll were enabled.
</p>
<br />

<p>
<img src="https://i.imgur.com/ipf9TS3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The osTicket Installer page now displayed the proper extensions.
</p>
<br />

<p>
<img src="https://i.imgur.com/D0oncUh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Within the file "ost-config.php", the inheritance was disabled and the permissions were set for everyone to have full control, modify, read & execute, read, and write permissions.
</p>
<br />

<p>
<img src="https://i.imgur.com/mPSZJzE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The helpdesk was named and the proper information was filled in.
</p>
<br />

<p>
<img src="https://i.imgur.com/tCuj9FF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Heidi SQL was installed.
</p>
<br />

<p>
<img src="https://i.imgur.com/Lx6E3ho.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Within Heidi SQL, a new session was created with the username and password were set.
</p>
<br />

<p>
<img src="https://i.imgur.com/zWBzFm1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Connection to the session was established, and a database called "osTicket" was created.
</p>
<br />

<p>
<img src="https://i.imgur.com/UAQvzSO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Returning to the osTicket Installer, the database, username, and password were filled in. The Install Now button was selected.
</p>
<br />

<p>
<img src="https://i.imgur.com/47S4r0z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The osTicket installation has been successfully completed.
</p>
<br />
