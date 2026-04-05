## 🔹 Project Description

This project implements a production-style hybrid identity architecture by integrating on-premises Active Directory Domain Services (AD DS) with Microsoft Entra ID using Microsoft Entra Connect Sync.

It establishes a **single, unified identity** across on-prem and cloud environments, incorporating advanced capabilities such as scoped synchronization, seamless Single Sign-On (SSO), Conditional Access, and writeback features.

---

![Architecture](Image/Architecture.png)

---
## 🔹 Core Capabilities

### Directory Synchronization
- On-prem AD users synchronized to Microsoft Entra ID  
- OU-based filtering for scoped identity sync  

### Unified Identity Model
- Single identity across hybrid infrastructure  
- Consistent identity lifecycle (create, update, delete)  

### Seamless Single Sign-On (SSO)
- Automatic sign-in for domain-joined devices  
- Reduced authentication friction  

### Conditional Access
- Policy-based access control for cloud resources  
- Foundation for Zero Trust security  

### Writeback Features
- Password writeback for Self-Service Password Reset (SSPR)  
- Enables bidirectional identity management  

---

## 🔹 Architecture Components

- On-Premises Active Directory Domain Services (AD DS)  
- Microsoft Entra ID  
- Microsoft Entra Connect Sync  
- Domain-joined devices (for SSO)  
- Conditional Access policies  

---

## 🔹 Objective

To demonstrate how organizations can extend traditional identity systems into the cloud while enforcing security controls, minimizing user friction, and enabling hybrid access to applications.

This project highlights key identity design considerations, including synchronization scope, authentication experience, and access governance.
