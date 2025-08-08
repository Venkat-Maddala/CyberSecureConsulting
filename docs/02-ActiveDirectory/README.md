# Active Directory Documentation

## Purpose
Centralized identity and access management for the lab environment.

---

## Planned AD Structure
- **Domain Name:** cybersecureconsulting.lab
- **Organizational Units (OUs):**
  - _HQ_
    - Admins
    - IT Support
    - HR
  - _Clients_
    - HealthcareDept
    - FinanceDept

---

## Key Configurations
- Group Policy Objects (GPOs) for password policies, screen locks, and software restrictions.
- User lifecycle management: onboarding, modifying roles, offboarding.
- Service accounts with least privilege.

---

## Security Considerations
- Separate standard user and admin accounts for elevated privileges.
- Enable auditing of logon/logoff, account changes, and policy changes.

---

## Next Steps
1. Install AD DS on Windows Server.
2. Create initial OUs and test accounts.
3. Apply baseline security GPOs.
