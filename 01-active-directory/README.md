# Lab Project 1: Active Directory & Enterprise IAM Setup

## 1. Overview & Objective
Demonstrating centralized identity and access management (IAM) by setting up an Active Directory domain controller, creating user groups and Organizational Units (OUs), enforcing security policies via Group Policy Objects (GPOs), and joining client endpoints.

## 2. Tools & Environment
* **Hypervisor:** VirtualBox
* **Operating Systems:** Windows Server 2022 Evaluation, Windows 10/11 Enterprise
* **Core Roles & Tools:** Active Directory Domain Services (AD DS), Group Policy Management Console (GPMC)

## 3. Network & Architecture Diagram
* `[Domain Controller: Windows Server 2022]` <---> `[Client Workstation: Windows 10]`

## 4. Implementation Steps
* [ ] Install Windows Server 2022 VM and promote to Domain Controller (`lab.local`).
* [ ] Create OUs for Departments, Users, and Service Accounts.
* [ ] Configure GPO to enforce account lockout and password complexity rules.
* [ ] Join Windows 10 workstation VM to the domain and verify user login.

## 5. Security Findings & Verification
*(Screenshots showing AD structure, GPO configuration, and successful domain join will be added here as the lab is completed)*

## 6. Key Takeaways & Security Insights
*(Summary of key learning points and security implications will be added here)*
