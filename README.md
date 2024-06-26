Some notes on installing OSTicket within an Azure VM.

**some issues choosing regions and availability zones for a VM. VM not validating reliably.
Solution: create more than one resource group so this is available already as an option rather than having to go back and delete/recreate.

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This project covers the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- PHP Manager
- MySQL
- HeidiSQL

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>List of Prerequisites</h2>

- IIS
- PHP Manager
- "rewrite module"
- "redistributable"
- MySQL
- HeidiSQL (DB client)


<h2>Installation Steps</h2>

![image](https://github.com/lcccodes/osticket-install/assets/171904823/a18f124b-b556-48cc-b05f-a47f8918f77b)

<p>
Installing and configuring IIS (Internet Information Services) which will act as the webserver on which osTicket will run.
</p>
<br />

<p>

  ![image](https://github.com/lcccodes/osticket-install/assets/171904823/ceeba0a8-a85a-4d69-b1ec-c4724ed48dff)

</p>
<p>
Choose "standard configuration" when installing MySQL server.
</p>
<br />
