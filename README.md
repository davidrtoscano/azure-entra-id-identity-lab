# Enterprise Cloud Identity & Access Management (IAM) Lab

## Project Overview
This project simulates an enterprise-level IT Support environment using **Microsoft Entra ID** and the **Microsoft 365 Admin Center**. The lab focuses on the full user lifecycle, role-based access controls (RBAC), tenant-wide security hardening, and incident response protocols typical of a Tier 1/2 IT Service Desk.

---

## Skills Demonstrated
* **User Lifecycle Management:** Provisioning users, configuring attributes, and implementing secure decommissioning.
* **Access Control (RBAC):** Creating security groups and mapping memberships based on departmental roles.
* **Security Hardening:** Implementing tenant-wide Self-Service Password Reset (SSPR) policies and multi-factor registration baselines.
* **Incident Response:** Managing account suspensions and lockouts during active security events.

---

## Lab Environments & Executions

### Phase 1: Identity Provisioning & Role Mapping
* Onboarded corporate identities into the cloud tenant directory, enforcing password change protocols on initial sign-in.
* Created isolated departmental Security Groups (`HR-Department`) to enforce the principle of least privilege.

### Phase 2: Tenant Security Hardening (SSPR)
* Configured and deployed a tenant-wide Self-Service Password Reset (SSPR) policy.
* Restricted legacy authentication protocols and enabled multi-factor authentication registration vectors (SMS/Email OTP) to lower help desk ticket volume and secure identities.

### Phase 3: Incident Response & Account Lockout
* Simulated an active account compromise protocol by revoking user sign-in capabilities, freezing the directory identity instantly via administrative override.
