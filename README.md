# osticket-prereqs
<p align="center">
<img src= "https://i.imgur.com/cA6hRPV.png"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
In this tutorial we will go through the full installation for osTicket and the prerequisites required to meet installation. I will install osTicket on an Azure VM(Virtual Machine). This tutorial will assume you have a VM ready and are logged into it using remote desktop connection. If you have not created a VM do that before continuing onto next step. To get started click here for <a href="https://drive.google.com/drive/u/2/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6">INSTALLATION FILES!</a>

<h2>
<p>
<img src= "https://i.imgur.com/GlMff8v.png"/>
</p>
 <h/2>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- MySQL

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Installation Steps</h2>
First to install/enable IIS Go to Control Panel > Programs > Turn Windows Features On or OFF > Click and Expand Internet Information Services > click and expand Web Managment Tools > Check IIS Managment Console > Click and expand World Wide Web Services > Click and expand Application Development Features > Check CGI > Click OK
<p>

</p>
<br />

<p>
<img src="https://i.imgur.com/0heoYEy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next Download/Install PHP Manager for IIS (PHPManagerForIIS_V1.5.0.msi) from INSTALLATION FILES
</p>
<br />

<p>
<img src="https://i.imgur.com/4lQoWJ5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next Download/Install Rewrite Module (rewrite_amd64_en-US.msi) from INSTALLATION FILES
</p>
<br />
<p>
<img src="https://i.imgur.com/rEOJqkY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next Create the directory C:\PHP 
 <P>Open File Explorer > This PC > Windows (C:) Drive > Right Click to add NEW FOLDER > name it "PHP"</P>
</p>
<br />

<p>
<img src="https://i.imgur.com/f9VwzAH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next unzip PHP 7.3.8 (php-7.3.8-nts-Win32-VC15-x86.zip) into C:\PHP From the installation files
</p>
 <p> Double-click on PHP-7.3.8 > Right Click to EXTRACT ALL > Click BROWSE > This PC > Windows (C:)> Click PHP > EXTRACT</p>
<br />
<p>
<img src="https://i.imgur.com/FEmn7wh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
 <img src="https://i.imgur.com/Rk2nAjp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/oC4HYF8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next Download/Install VC_redist.x86.exe. from the INSTALLATION FILES
</p>
<P> Double-click and Install</P>
<br />
<p>
<img src="https://i.imgur.com/4W1slB9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next Dowload/Install MySQL 5.5.62 (mysql-5.5.62-win32.msi)

<P> Double-click MySQL 5.5.62 > select TYPICAL > Install</P>
 
<img src="https://i.imgur.com/k1zeOyg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next Download/Install
</p>
<br />
