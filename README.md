<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system, osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Internet Information Services
- Microsoft Web Platform Installer
- osTicket v1.15.8
- PHP Manager
- My SQL 5.5 Database
- HeidiSQL Client
- Microsoft Visual C++ 2009 Redistributable
- Link to Downloads: https://drive.google.com/drive/u/1/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6

<h2>Installation Steps</h2>

**Step 1:** Create a Windows 10</b> (21H2) Virtual Machine in your Microsoft Azure portal and connect via Remote Desktop.

**Step 2:** After it's up and running, go to Control Center >> Uninstall or change a Program >> Turn Windows Features on or of >> enable Internet Information Services.

<p>
<img src="https://imgur.com/Pp3YiGv.png" height="60%" width="60%" alt="osTicket Prereqs and Installation"/>
</p>
<p>

  
**Step 3:** Download and install Web Platform Installer from Google Drive download links.
  
Search, add, and install the following through Web Platform Installer: MySQL 5.5 database, PHP 5.6.31, and all simple versions of PHP (x86) 7.0 through 7.3.

<p>
<img src="https://i.imgur.com/UfPy9AD.png" height="50%" width="50%" alt="osTicket Prereqs and Installation"/>
</p>
<p>
<img src="https://i.imgur.com/tEfOjy9.png" height="50%" width="50%" alt="osTicket Prereqs and Installation"/>
</p>
<p>

MySQL 5.5 will require name and password, *root* and *Password1* respectively when you try to install. Make note of the name / password in a text file as you will need it again later on in the installation process.

  
**Step 4:** Fix any failures in the installation by going to Google Drive to download and install *PHP 7.3.8*, *PHP Manager*, and *Microsoft Visual C++ 2009 Redistributable Package*.

<p>
<img src="https://i.imgur.com/I4hZg17.png" height="40%" width="40%" alt="osTicket Prereqs and Installation"/>
</p>
<p>


**Step 5:** Download osTicket v1.15.8 from Google Drive and *Extract All*.
  
<p>
<img src="https://i.imgur.com/gHFPoqP.png" height="50%" width="50%" alt="osTicket Prereqs and Installation"/>
</p>
<p>

  
Copy the "upload" folder into c:\inetpubt\wwwroot and *Rename* it "osTicket".

<p>
<img src="https://i.imgur.com/E12aErK.png" height="40%" width="40%" alt="osTicket Prereqs and Installation"/>
</p>
<p>

  
**Step 6:** Open Internet Information Services and *Restart* the server on the right hand side.
  
<p>
<img src="https://i.imgur.com/0gqTw9Z.png" height="70%" width="70%" alt="osTicket Prereqs and Installation"/>
</p>
<p>


Go to Sites >> Default >> osTicket and click "Browse *:80" on the right hand side. A window should open in your browser.

<p>
<img src="https://i.imgur.com/iqCf28W.png" height="70%" width="70%" alt="osTicket Prereqs and Installation"/>
</p>
<p>
<img src="https://i.imgur.com/zVq0ZCi.png" height="40%" width="40%" alt="osTicket Prereqs and Installation"/>
</p>
<p>




<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="60%" width="60%" alt="osTicket Prereqs and Installation"/>
</p>
<p>

  

  
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="60%" width="60%" alt="osTicket Prereqs and Installation"/>
</p>
<p>

