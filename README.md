# Active-Directory-Home-Lab-Azure-

**Role:** Self-directed project · **Timeframe:** [November] – [2026]
**Tools:**  Microsoft Azure, Windows Server 2022, Windows 11 Pro, Active Directory Domain Services, DNS, Group Policy, PowerShell

## Overview

I built a small Windows domain environment in Azure with a domain controller (**DC-1**) and a client PC (**Client-1**) to simulate a small-business network. I created shared folders, set permissions for different groups, and tested access as a standard user.

## What I Did

- Built a Windows domain environment in Azure with a domain controller and a client PC.
- Created and shared network folders and configured share and NTFS permissions for Domain Users, Domain Admins, and a custom security group.
- Created an **ACCOUNTANTS** security group in Active Directory Users and Computers and granted folder access through group membership instead of per-user permissions.
- Tested access from a standard user account, confirmed the expected allow and deny results, and troubleshot access issues involving permission inheritance, DNS, and sign-in refresh.
