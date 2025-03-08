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

- Install / Enable IIS in Windows WITH CGI
- Install PHP Manager for IIS
- Install the Rewrite Module
- Install VC_redist.x86.exe
- Install MySQL
- Configure MySQL security settings


<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/hjTEyCR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
World Wide Web Services -> Application Development Features -> [X] CGI.
</p>
<br />

<p>
<img src="https://i.imgur.com/7hYHqx2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
From the “osTicket-Installation-Files” folder, install PHP Manager for IIS (PHPManagerForIIS_V1.5.0.msi).
</p>
<br />

<p>
<img src="https://i.imgur.com/sIIt0GE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
From the “osTicket-Installation-Files” folder install the Rewrite Module (rewrite_amd64_en-US.msi).
</p>
<br />

<p>
<img src="https://i.imgur.com/zQXQCJ4.pngg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
From the “osTicket-Installation-Files” folder, unzip PHP 7.3.8 (php-7.3.8-nts-Win32-VC15-x86.zip) into the “C:\PHP” folder.
</p>
<br />

<p>
<img src="https://i.imgur.com/nyKCj0T.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
From the “osTicket-Installation-Files” folder, install VC_redist.x86.exe.
</p>
<br />

<p>
<img src="https://i.imgur.com/KFsz1GN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
From the “osTicket-Installation-Files” folder, install MySQL 5.5.62 (mysql-5.5.62-win32.msi)
Typical Setup ->
Launch Configuration Wizard (after install) ->
Standard Configuration ->.
</p>
<br />

<p>
<img src="https://i.imgur.com/lQORZ9l.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Set a strong password in MySQL security options.
</p>
<br />
