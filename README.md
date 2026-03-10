<h1>Active Directory Basics - Identity & Access Management Lab </h1>


<h2>Description</h2>
This lab demonstrates foundational identity and access management skills using Microsoft Active Directory in a simulated enterprise environment. A Windows Server domain controller was deployed in VMware Fusion on macOS and configured to manage users, groups, authentication, and access workflows commonly handled by IT Helpdesk and IAM teams.
<br />


<h2>Environments Used </h2>

- <b>macOS host (VMware Fusion)
- Windows Server 2019 (Domain Controller VM)
- Active Directory Domain Services
- Active Directory Users and Computers
- Windows 10/11 domain-joined client VM</b>

<h2>Key Tasks Performed</h2>

Created a custom Windows Server VM in VMware Fusion and installed Windows Server

Installed and configured Active Directory Domain Services and promoted the server to a domain controller

Created Organizational Units (OUs) to structure users and security groups

Created domain user accounts and security groups for role-based access control

Performed password resets and account unlocks using Active Directory Users and Computers

Modified group memberships to simulate permission changes for different roles

<h2>Skills Demonstrated </h2>

- <b>Identity and Access Management (IAM) fundamentals
- User and group lifecycle management in Active Directory
- Password reset and account unlock workflows
- Role-based access control (RBAC) via security groups
- Working with virtualized enterprise environments using VMware Fusion</b>

<h2>Lab walk-through:</h2>

<p align="center">
Windows Server domain controller running inside VMware Fusion on macOS.  <br/>
<img width="80%" height="80%" alt="00-vmware-fusion-dc01" src="https://github.com/user-attachments/assets/d3ecb631-0a6b-4a93-8528-013cddfacc78" />
<br />
<br />  
Windows Server configured as a Domain Controller with Active Directory Domain Services. <br/>
<img width="76%" height="76%" alt="image" src="https://github.com/user-attachments/assets/37d16edd-a523-4ce4-a698-d802b1e1ddeb" />
<br />
<br />
Active Directory domain structure using Organizational Units to separate users and groups. <br/>
<img width="80%" height="80%" alt="image" src="https://github.com/user-attachments/assets/f6576220-dcfa-4732-b748-f68de145bcda" />
<br />
<br />
Domain user accounts created to represent employees in an enterprise environment.  <br/>
<img width="80%" height="80%" alt="image" src="https://github.com/user-attachments/assets/caaf5ccb-0457-44a0-863f-d946c590a9b9" />
<br />
<br />
Security groups created to manage role-based access control.  <br/>
<img width="80%" height="80%" alt="image" src="https://github.com/user-attachments/assets/39d973f9-5e0b-4829-b4c3-d54db6c15918" />
<br />
<br />
User assigned to a security group to inherit role-based permissions. <br/>
<img width="80%" height="80%" alt="image" src="https://github.com/user-attachments/assets/93aa89d5-a466-4bd4-9ad7-0dfba81a8935" />
<br />
<br />
Password reset performed using Active Directory Users and Computers as part of standard helpdesk workflow. <br/>
 <img width="76%" height="76%" alt="image" src="https://github.com/user-attachments/assets/36708ae2-1c97-4a90-923d-82242819a473" />
<br />
<br />
Account unlock process demonstrated after simulated login lockout.<br/>
<img width="80%" height="80%" alt="image" src="https://github.com/user-attachments/assets/0bceb84d-e757-4740-8b7a-9ced7b3038df" />
<br />
<br />
Group membership modified to grant or remove access based on role changes.<br/>
<img width="80%" height="80%" alt="image" src="https://github.com/user-attachments/assets/9068ba9c-8fef-4cc0-9dca-4bd3677f29df" />
<br />
<br />


</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
