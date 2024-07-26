<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com/xsv5qDsYZKI)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Enabled IIS on my osTicketwindows-vm RDP.
- Downloaded PHP Manager for IIS 
- Downloaded Rewrite
- Created a directory called C:\PHP
- Downloaded PHP and extract unto the directory file created.
- Downloaded Visual codes
- Downloaded SQL 
- Open IIS on the start menu, click PHP Manager and register new version of php, and upload php-cgi.exe.
- Download osTicket, extract and copy “upload” to c:\inetpub\wwwroot
- Within c:\inetpub\wwwroot, Rename “upload” to “osTicket”

<h2>Installation Steps</h2>

<p>
<img src="https://github.com/user-attachments/assets/b56c06a7-a1b3-4ba7-984d-20d1bb9da6fe" height="80%" width="80%" />

</p>
<p>
Visualization on what I created on my osTicketwindows-VM RDP on Azure.
</p>
<br />

<p>

  <img src="https://github.com/user-attachments/assets/cb76e84a-10be-4318-90c0-c4d4f27c4af0" height="80%" width="80%" />

</p>
<p>
Enabled IIS through the windows-vm RDP with CGI and Common HTTP Features. Also enabling IIS Management Console. Enabling IIS will let me install the web server and host sites and web apps. CGI is going to allow me to run scripts and programs on my server. 
  Common HTTP Features allows my server to handle things like static web pgs, showing directory contents, and handling errors. IIS Management Console provides a user-friendly interface to easily manage and configure your websites and server settings,
</p>
<br />

<p>
  <img src="https://github.com/user-attachments/assets/c22d9de4-00f7-4d74-8b24-203489cc48f7" height="80%" width="80%" />

</p>
<p>
Downloaded PHP Manager for IIS tool that'll make the setup and management of PHP on an IIS web server much easier without manually configuring everything.
</p>
<br />



<p>
  <img src="https://github.com/user-attachments/assets/a426401a-651c-4da9-b3bb-19b658ca859d" height="80%" width="80%" />

</p>
<p>
Downloaded Rewrite Module for IIS tool that'll helps manage and modify URLs on my IIS web server.
</p>
<br />


<p>
  <img src="https://github.com/user-attachments/assets/9e1e3133-fcce-44f5-8603-e58b041378e4" height="80%" width="80%" />

</p>
<p>
Created a PHP folder then downloaded PHP into the folder.
</p>
<br />


<p>
  <img src="https://github.com/user-attachments/assets/231d67c9-d2bf-4fc2-97cc-3b52b2c29fad" height="80%" width="80%" />


</p>
<p>
Downloaded Visual C++ so I can work with databases and develop web services. 
</p>
<br />


<p>
  <img src="https://github.com/user-attachments/assets/78f1b78b-bd91-41f8-8a13-702e0cefb0b9" height="80%" width="80%" />

</p>
<p>
Downloaed MySQL to store data and manage databases whether modifying, structuring user accounts, etc.
</p>
<br />


<p>
  <img src="https://github.com/user-attachments/assets/16f1f845-4e7f-4198-9879-f6c23830a04a" height="80%" width="80%" />

</p>
<p>
Downloaed osTicket and extracted and copied "upload" folder to c:\inetpub\wwwroot and renamed it osTicket.
</p>
<br />


<p>
  <img src="https://github.com/user-attachments/assets/73546503-6be8-4765-bd1f-f917e8726653" height="80%" width="80%" />

</p>
<p>
Enabled  php_imap.dll, php_intl.dll, php_opcache.dll

</p>
<br />


<p>
  <img src="https://github.com/user-attachments/assets/750b5592-1d33-47dd-89f1-b53a245e31a1" height="80%" width="80%" />
  <img src="https://github.com/user-attachments/assets/20d6d1b8-f59f-406a-b77b-871b8d9fc1a4" height="80%" width="80%" />
  <img src="https://github.com/user-attachments/assets/50337465-d669-4d40-b3c5-b8485259d786" height="80%" width="80%" />
  

</p>
<p>
created a database in HeidiSQL for my osTicket.

</p>
<br />




<p>
  <img src="https://github.com/user-attachments/assets/91e5c069-3e60-4107-8eb2-58880a13d385" height="80%" width="80%" />
 <img src="https://github.com/user-attachments/assets/4131490a-74ee-468b-bc51-ca568d9e8717" height="80%" width="80%" />

</p>
<p>
able to set up my osTicket in my browser and create it.

</p>
<br />
