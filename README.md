# Implementing-Identity-and-Access-Management-IAM-in-Microsoft-Entra-ID

# Objective
The objective of this project was to simulate user provision and directory management within a cloud environment using Microsoft Entra ID (formerly Azure Active Directory). The lab focused on establishing administrative control over identity lifecycles by creating, managing, and preparing to govern distinct user identities within a centralized "Default Directory" tenant to ensure appropriate access controls.


# Tools Used
* Cloud Platform: Microsoft Azure

* Identity Provider (IdP): Microsoft Entra ID (Azure Active Directory)

* Management Interface: Azure Portal (Web Console)

# Steps Executed
Directory Navigation: Accessed the Microsoft Azure Portal and navigated to the Microsoft Entra ID service (indicated by the notification banner: "Azure Active Directory is now Microsoft Entra ID").

User Management Interface: Opened the Users | All users repository view within the active tenant directory.

Identity Provisioning: Provisioned four distinct internal user profiles. For each profile, configured standard parameters including Display Name, User Principal Name (UPN), and User Type (set as native 'Member' accounts).

Identities created:

Adje Gbekou

Alex Kokou

Eric Path

Johana Smith

Attributes Verification: Audited the user table configuration to verify synchronization status (On-premises sync: No), role designations (Is Agent: No), and ensured that all records populated correctly across the tenant database with 4 active users found.

# Key Takeaways
Centralized Identity Governance: Understood how cloud-native directories manage the identity boundary, providing a single plane of glass to audit, add, or offboard user objects efficiently.

Access Control Foundations: Provisioning specific, individual accounts rather than using shared credentials establishes the foundation for enforcing the Principle of Least Privilege (PoLP) and ensures robust Accountability for future audit logs and sign-in telemetry.

Transition awareness: Noted the operational branding transition from Azure AD to Microsoft Entra ID, aligning technical administrative skills with current industry frameworks.

# Project Documentation

<img width="1905" height="898" alt="Azure AIM" src="https://github.com/user-attachments/assets/953bfbcb-e6c7-4119-a4ff-187ba7726a0e" />

<img width="1911" height="909" alt="Azure IAM 2" src="https://github.com/user-attachments/assets/9a164aab-6883-4e28-a3ef-c490518a4316" />


<img width="1790" height="529" alt="Azure IAM" src="https://github.com/user-attachments/assets/d450ace7-5880-4b2e-9b3a-2bc5abbdacb3" />

