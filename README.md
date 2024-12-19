<img src=https://github.com/user-attachments/assets/b0b2b2d4-c2ed-47b6-b59c-9da1d87514c6>
<br />
<br />

<h1>Creating Users with PowerShell</h1>

With Active Directory deployed, we can now use PowerShell to automate the creation of multiple user accounts within the "_EMPLOYEES" OU. This provides hands-on experience with scripting and user management within AD.<br />
<br />
<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Remote Desktop
- Active Directory Domain Services
- PowerShell
<br />
<br />

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)
<br />
<br />

<h2>Walkthrough Steps</h2>

1. Enable Remote Desktop for Domain Users:
  - Log into Client-1 as "jane_admin" and allow "Domain Users" access to Remote Desktop.
<br />
<br />

2. Use PowerShell to Create Users:
  - Log into DC-1 as "jane_admin."
  - Open PowerShell_ise, paste the provided script, and execute it.
  - Verify that new users are created in the "_EMPLOYEES" OU using ADUC.
<br />
<br />

3. Test User Login:
  - Attempt to log into Client-1 with one of the newly created accounts.
<br />
<br />
