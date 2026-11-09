# Active Directory Configuration (Windows Server)

## Project Overview

This project demonstrates the configuration and administration of **Active Directory Domain Services (AD DS)** in a Windows Server lab environment. The objective was to establish a domain-based environment, manage user accounts and organizational units, and apply Group Policy settings to control user access to applications.

## Objectives

- Configure a static IP address for the Windows Server.
- Install and configure Active Directory Domain Services.
- Set up an Active Directory domain environment.
- Create and manage Organizational Units (OUs) and user accounts.
- Configure Group Policy Objects (GPOs).
- Apply application restrictions to a selected organizational unit.

## Tools & Technologies

- Windows Server
- Active Directory Domain Services (AD DS)
- Active Directory Users and Computers
- Group Policy Management
- Group Policy Management Editor
- Server Manager
- Windows networking and IP configuration

## Tasks Performed

### 1. Static IP Configuration
Configured a static IP address on the Windows Server to establish a consistent network identity for the server.

### 2. Active Directory Domain Services
Used Server Manager to install the Active Directory Domain Services role and configure the server as an Active Directory domain controller.

### 3. User and Organizational Unit Management
Used Active Directory Users and Computers to manage directory objects.

- Created an organizational unit named `Client-Test`.
- Created a user account within the organizational unit.
- Verified the user account in the Active Directory management console.

### 4. Group Policy Management
Used Group Policy Management to create and configure a Group Policy Object named `Block Browser`.

- Linked the GPO to the `Client-Test` organizational unit.
- Opened the Group Policy Management Editor.
- Configured the policy **Don't run specified Windows applications**.
- Added `msedge.exe` to the list of disallowed applications.

This demonstrates how Group Policy can be used to apply application restrictions to users within a specific organizational unit.

## Skills Demonstrated

- Windows Server administration
- Active Directory configuration
- User and OU management
- Group Policy configuration
- Application restriction policies
- Basic network configuration
- Windows domain administration

## Key Learning Outcomes

Through this practical exercise, I gained experience with centralized user management, domain administration, and Group Policy configuration. I also learned how organizational units and GPOs can be used to manage and enforce specific settings within a Windows domain environment.

## Project Evidence

The accompanying demonstration video documents the configuration process and the administrative tools used throughout this lab.

---

**Project Type:** Hands-on Windows Server / Active Directory Lab  
**Focus:** System Administration, Identity Management, and Group Policy
