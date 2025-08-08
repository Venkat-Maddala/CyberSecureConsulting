# Networking Documentation – CyberSecureConsulting Lab

## Purpose
This section documents the full network architecture for the simulated consulting company, both in **Azure cloud** and the **local hybrid components**.

---

## Lab Network Topology
**Cloud Segment (Azure):**
- **VNet:** 10.0.0.0/16
  - Subnet-DC: 10.0.1.0/24 (Domain Controller)
  - Subnet-Clients: 10.0.2.0/24 (Windows endpoints)
  - Subnet-SIEM: 10.0.3.0/24 (SIEM / Monitoring tools)
- **NSGs:** Restrict inbound RDP/SSH to my public IP only.
- **Azure Bastion:** Secure remote access to VMs without exposing RDP to the internet.

**Local Segment (Hybrid Option):**
- VirtualBox/VMware VMs for Red Team machines (Kali Linux).
- Site-to-Site VPN (optional) for hybrid identity experiments.

---

## Goals
- Secure segmentation between Red Team and Blue Team machines.
- Proper firewall rules for SOC monitoring.
- Documentation of every NSG rule, subnet, and IP assignment.

---

## Next Steps
1. Deploy Azure VNet + subnets.
2. Create Domain Controller VM in Subnet-DC.
3. Document network diagram (Visio or draw.io) and upload here.
