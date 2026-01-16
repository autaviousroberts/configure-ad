# configure-ad
<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>
[
](https://www.youtube.com/watch?v=RR2FhJ1w4XM)
<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1
- Step 2


<h2>Deployment and Configuration Steps</h2>

<p>
<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/d81371a3-0e7e-4b11-942a-90298d7ec201" />
</p>
<p>
This screenshot shows the Active Directory Users and Computers console open on the domain controller, displaying the properties of a domain user account. The “Member Of” tab is selected, showing that the user is a member of the Domain Users group, which is the default security group assigned to standard users in an Active Directory domain. This confirms that the user account was successfully created and properly integrated into the domain. The presence of organizational units in the directory structure also demonstrates the use of Active Directory best practices for organizing users and managing permissions within the mydomain.com environment.</p>
<br />

<p>
<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/716ea61d-f208-4fb6-a94b-2e448b1a93ec" />
</p>
<p>
This screenshot shows the Active Directory Users and Computers (ADUC) console open on a Windows Server domain controller during the creation and management of Active Directory objects. The domain mydomain.com is expanded in the left pane, displaying several Organizational Units such as ADMINS, CLIENTS, EMPLOYEES, Computers, and Users, which are used to logically organize accounts and resources. In the right pane, a list of user accounts is visible, indicating that multiple domain users have been created. This stage demonstrates the administrative process of setting up Active Directory by defining a domain structure and adding user objects, which is essential for centralized authentication, authorization, and management of users within a Windows network environment.</p>
<br />

