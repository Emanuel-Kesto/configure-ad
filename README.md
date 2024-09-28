# configure-ad<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1> Active Directory Deployed in the Cloud (Azure)</h1>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Creating one Windows server and one Windows 10 virtual machine
- Downloading and installing Active Directory 
- Creating a domain controller 
- Creating users within Active Directory 

<h2>Deployment and Configuration Steps</h2>

<p>
<img width="746" alt="AD DS" src="https://github.com/user-attachments/assets/e4df1c07-5c82-4945-8429-f9fc63fe061b"></p>
<img width="741" alt="dns" src="https://github.com/user-attachments/assets/b6207844-1077-498b-a19e-5b29ef37eb1e">

<p>
Create your two virtual machines, a windows server and a windows 10 within azure. The server will house active directory and  the windows 10 will act as your client. Make sure both vm's are on the same subnet. The server is named dc-1 and the windows 10 vm is named client-1. Dc-1 will also act as your DNS server, go into azure and make dc-1's private ip-address static. Then go to client-1 and set the dns server to dc-1 private ip-address. 
</p>
<br />

<p>
<img width="748" alt="new forest" src="https://github.com/user-attachments/assets/a7543ae8-9bd8-4548-8796-9577dce66371">

</p>
<p>
The windows server is named dc-1, and it has active directory 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
