# Home-Lab-and-Projects

This is my home lab virtual setup using VirtualBox:

<img width="692" height="525" alt="image" src="https://github.com/user-attachments/assets/14497f44-4895-4853-bf26-fac041d75aba" />

Installed VirtualBox

Installed Win Server 2019 and 2022 VMs

Promoted Win Servers to Domain Controllers

Installed and configured Active Directory Domain Services

Created new Active Directory domains

Assigned static IP for Server stability

Installed three Win 11 VMs 

Added two Win 11 VMs to 2022 Server domain

Added one Win 11 VM to 2019 Server domain

Organized users and computers with Organizational Units

Created Users and Groups

Password Management: Implemented secure temporary credentials and forced password changes at logon.

Account Security: Unlocking users and identifying credential-stuffing risks.

User Lifecycle: Efficiently disabling and enabling accounts for corporate compliance.

Installed Ubuntu Linux VM

Installed standalone Win 11 VM

TRUST RELATIONSHIP FAILED ISSUE EXERCISE

Error message: “Trust Relationship between this workstation and the primary domain failed”

Actions taken:

Logged into user’s computer using local administrator account

Verified network connectivity to domain

Located computer object in Active Directory

Reset computer account in Active Directory

Removed computer from domain and joined to Workgroup

Rebooted computer

Rejoined computer to domain

Rebooted computer

Resolved issue:

Domain trust relationship successfully restored

User now able to log in with domain credentials





