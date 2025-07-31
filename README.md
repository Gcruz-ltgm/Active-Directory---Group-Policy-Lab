# Active-Directory---Group-Policy-Lab

## Description

# This is a lab that simulates a basic enterprise IT environment using Windows Server 2022 and Windows 10 in a virtual environment. It demonstrates key IT skills including setting up Active Directory, managing users and OUs to enforece system policies across a domain.

##Tools Used
- Oracle VirtualBox
- Windows Server 2022
- Active Directory Domain Services
- Group Policy Management Console
- Local Network Management

  ## Lab Setup

### Domain Configuration
| VM Name | OS               | Role                 | IP Address    |
|---------|------------------|----------------------|---------------|
| `DC01`  | Windows Server    | Domain Controller    | 192.168.x.x  |
| `CLIENT1` | Windows 10 Pro | Domain-Joined Client | 192.168.x.x  |

-*Domain name: 'lab.local'
-*Forest Functional lebel: Windows Server 2022
-*Network Type: Internal

## Steps Performed:
1. Installed a Windows Server and set a static IP address.
2. Installed AD DS (Active Directory Domain Services) and DNS roles onto the Server
3. Promoted the server to a Domain controller for 'lab.local'

## Active Directory
- Created OUs
  -'HR'
  -'IT'
  -'Sales
- Created sample Users:
  - John
  - James
  - Maria
  - Karen
-  Assigned Users to corresponding OUs
