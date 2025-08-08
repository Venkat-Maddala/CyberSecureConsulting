# Privileged Access Management Documentation

## Purpose
Simulate enterprise-grade controls for privileged accounts to protect sensitive systems.

---

## PAM Strategies in the Lab
- **Tiered Admin Model:**
  - Tier 0: Domain Admins
  - Tier 1: Server Admins
  - Tier 2: Workstation Admins
- **Just-in-Time (JIT) Access** for administrative accounts.
- **Just Enough Administration (JEA)** for role-limited PowerShell access.

---

## Monitoring & Auditing
- Track logins by privileged accounts.
- Alert on abnormal privileged actions in SIEM.

---

## Next Steps
1. Create separate admin accounts per tier.
2. Implement JIT/JEA for key tasks.
3. Set up alert rules in SIEM for high-privilege activity.
