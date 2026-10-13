# Cisco Networking & Network Automation Labs (90-Day Challenge)

This repository documents hands-on enterprise networking topologies, switch/router configurations, and Python network automation scripts built between October 2026 and January 2027.

---

## Lab 1: Enterprise Office Network Design

### Topology Overview
- **Devices:** 4 PCs (`PC0` - `PC3`), 1 Cisco Catalyst 2960 Switch
- **Subnet:** `192.168.1.0/24`
- **Cable Type:** Copper Straight-Through

### IP Addressing Scheme
| Device | Interface | IP Address | Subnet Mask | Status |
| :--- | :--- | :--- | :--- | :--- |
| PC-0 | FastEthernet0 | 192.168.1.10 | 255.255.255.0 | Verified |
| PC-1 | FastEthernet0 | 192.168.1.11 | 255.255.255.0 | Verified |
| PC-2 | FastEthernet0 | 192.168.1.12 | 255.255.255.0 | Verified |
| PC-3 | FastEthernet0 | 192.168.1.13 | 255.255.255.0 | Verified |

### Verification
- Tested end-to-end ICMP connectivity using `ping 192.168.1.11` from `PC0`.
- **Result:** 0% packet loss (4/4 received).