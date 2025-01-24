# osticket-prereqs
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

- Item 1 Install and enable ISS (internet information services) on windows with CGI. This action enables the installation of the web server. 
- Item 2- From the osticket installation folder we will install:
- PHP manager for ISS, rewrite module, visual c++ redistributable, and My SQL 5.5.62 🖥️
- Item 3- Configure ISS 
- Item 4- installing osTicket
- Item 5- Setting up configurations on osTicket

<h2>Installation Steps</h2>


<p>
<img src="https://i.imgur.com/ZgRFUve.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install and enable IIS (Internet Information Services) on Windows.
Go to World Wide Web Services, Application Development Features, and enable the CGI feature.

</p>
<br />

<p>
<img src="https://i.imgur.com/fy1PTju.png" height="80%" width="80%" alt=/>
<img src="https://i.imgur.com/LK1agin.png" height="80%" width="80%" alt=/>
<img src="https://imgur.com/QF8clgs" height="80%" width="80%" alt=/>
<img src="https://imgur.com/Y662nUV" height="80%" width="80%" alt=/>
<img src="https://i.imgur.com/QQp3lL0.png" height="80%" width="80%" alt=/>
<img src="https://i.imgur.com/jaDUQbX.png" height="80%" width="80%" alt=/>  
</p>
<p>
From the osTicket-Installation-Files folder:

  Install PHP Manager for IIS
Install the Rewrite Module 
Create the directory: C:\PHP.
Extract the PHP 7.3.8 into C:\PHP.
Install the Visual C++ Redistributable
Install MySQL 5.5.62 with: Typical Setup, then standard configuration, then apply username and password. 🧑‍💻

</p>
<br />

<p>
<img src="https://imgur.com/Y662nUV" alt=/>
</p>
<p>
We will open IIS as Administrator.
Register PHP in IIS (PHP Manager → Register New PHP Version → C:\PHP\php-cgi.exe).
Restart IIS (Stop and Start the server).
</p>
<br />

<p>
<img src="https://imgur.com/XunS4np" height="80%" width="80%" alt=/>
<img src="https://imgur.com/63te02v" height="80%" width="80%" alt=/>
</p>
<p>
From the osTicket-Installation-Files folder:

To install osTicket we must now extract osTicket-v1.15.8.zip.
Copy the upload folder to C:\inetpub\wwwroot.
Rename the upload folder to osTicket.
Restart IIS again.
</p>
<br />
