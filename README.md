
 📌 Overview
Built a Windows Server lab using Active Directory to manage users, groups, and file permissions.
---
##What I Did
- Created domain: `homelab.local`
- Created user: `jdoe`
- Created security group: `IT`
- Added user to group
- Created shared folder: \\WIN-2UUDQ76C8Q4\Shared
- Configured share permissions
- Configured NTFS permissions
---

##Permissions Setup

##IT Folder
- IT group → Modify access

##HR Folder
- Access restricted (non-members denied)
---

##Testing
- Logged in as domain user (`jdoe`)
- Verified access to IT folder (read/write works)
- Verified HR folder shows access denied
---

##What I Learned
- Difference between Share vs NTFS permissions
- Using security groups instead of users
- Applying least privilege access control
- Practiced troubleshooting permission issues when access did not initially work.
---

##Screenshots

## Active Directory setup
![AD User](ad-user.png)
![IT Group](IT-group.png)

## Permissions configuration
![NTFS Permissions](ntfs-permissions.png)
![Share Permissions](share-permissions.png)

## Testing Access
![IT Access](IT-access.png)
![HR Denied](hr-denied.png)
