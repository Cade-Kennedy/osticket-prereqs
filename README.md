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

- Enable Internet Information Services (IIS)
- Install PHP to configure IIS
- Install MySQL / Create databse user / password
- Download OSticket

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/PsHUdMo.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this step of the proccess, we are going to be enabling IIS along with CGI. Which is required as a dependancy for OsTicket webserver. To locate these steps we will follow these steps. controlPanel/Programs/TurnWindowsFeaturesOnOrOff/InternetInformationServices. For the next step for enabling CGI follow these steps: World Wide Web Services -> Application Development Features -> [X] CGI

</p>
<br />

<p>
<img src="https://i.imgur.com/r5wZtBc.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we are going to install and configure MYSQL. To do this follow these steps: (These are example steps, do not configure with similar username and password) 

  From the “osTicket-Installation-Files” folder, install MySQL 5.5.62 (mysql-5.5.62-win32.msi)
Typical Setup ->
Launch Configuration Wizard (after install) ->
Standard Configuration ->
Username: root
Password: root

</p>
<br />

<p>
<img src="https://i.imgur.com/QWQkjk3.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lastly after the installation of IIS and configuration of MYSQL. You will be set up with a basic OsTicket layout. You can access OsTicket through a web browser and sign in with the details you created early. 
</p>
<br />
