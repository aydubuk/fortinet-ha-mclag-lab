# fortinet-ha-mclag-lab
Enterprise-grade High Availability network infrastructure implemented on physical FortiGate 100E and FortiSwitch 1048E devices using FortiLink and MC-LAG.
<div align="center">

# 🚀 FortiGate High Availability with FortiLink Managed MC-LAG

### Physical Laboratory Implementation

Enterprise-grade High Availability Network Infrastructure using Fortinet Technologies

![Fortinet](https://img.shields.io/badge/Fortinet-EE3124?style=for-the-badge&logo=fortinet&logoColor=white)
![FortiOS](https://img.shields.io/badge/FortiOS-7.2.13-red?style=for-the-badge)
![High Availability](https://img.shields.io/badge/High_Availability-Active--Passive-success?style=for-the-badge)
![MC-LAG](https://img.shields.io/badge/MC--LAG-Enabled-blue?style=for-the-badge)
![FortiLink](https://img.shields.io/badge/FortiLink-Managed-orange?style=for-the-badge)

</div>

---

# 📖 Overview

This project demonstrates the design and implementation of a highly available enterprise network infrastructure using physical Fortinet hardware.

Unlike simulation-based environments, every stage of this project was performed on real devices, including installation, configuration, verification, troubleshooting, and documentation.

The project was completed during our internship at **Ultron Bilişim**.

---

# 👥 Team

- **Ayşe Gül Pekgöz**
- **İsmail Taşinen**
- **Ramazan Erten**

### Mentor

**Fatih Turan**

---

# 🎯 Objectives

- Eliminate single points of failure
- Deploy Active-Passive firewall redundancy
- Implement centralized switch management
- Configure chassis-level switch redundancy
- Verify failover functionality
- Gain real-world troubleshooting experience

---

# 🖥 Hardware

| Device | Quantity |
|---------|---------|
| FortiGate 100E | 2 |
| FortiSwitch 1048E | 2 |

---

# ⚙ Technologies

- FortiGate High Availability
- FortiLink
- MC-LAG
- Inter-Chassis Link (ICL)
- IEEE 802.3ad
- Link Aggregation
- Session Pickup
- CLI Verification
- GUI Verification

---

# 🗺 Network Topology

![Topology](images/topology.png)

---

# 🏗 Architecture

- Active-Passive FortiGate Cluster
- Dedicated HA Heartbeat
- FortiLink Aggregate
- Managed FortiSwitch Infrastructure
- MC-LAG Peer Group
- Inter-Chassis Link
- Dual Firewall Connections
- Redundant Server Connectivity

---

# 🚀 Deployment Steps

- Physical installation
- Device initialization
- HA Cluster creation
- Heartbeat configuration
- FortiLink deployment
- FortiSwitch authorization
- MC-LAG configuration
- ICL establishment
- Validation
- Troubleshooting

---

# ✅ Validation

The following components were successfully verified:

- HA Synchronization
- Primary / Secondary Roles
- Session Pickup
- FortiLink Connectivity
- FortiSwitch Authorization
- MC-LAG Status
- ICL Status
- Link Aggregation
- Interface Monitoring

---

# 🔧 Troubleshooting

Real-world issues encountered during deployment included:

- FortiLink discovery
- Switch authorization
- Firmware recovery via TFTP
- Fiber uplink issues
- HA synchronization
- Interface failures
- Aggregate configuration
- Connectivity verification

---

# 📸 Project Gallery

| Laboratory Setup |
|------------------|
| ![](images/lab.jpg) |

| FortiGate HA | FortiSwitch MC-LAG |
|--------------|--------------------|
| ![](images/fortigate.jpg) | ![](images/fortiswitch.jpg) |

| Verification |
|--------------|
| ![](images/verification.jpg) |

---

# 📄 Documentation

- Engineering Report (Turkish)
- Engineering Report (English)

---

# 📁 Repository Structure

```text
fortigate-ha-mclag-lab
│
├── README.md
├── docs
│   ├── Engineering_Report_TR.pdf
│   └── Engineering_Report_EN.pdf
│
├── images
│   ├── topology.png
│   ├── lab.jpg
│   ├── fortigate.jpg
│   ├── fortiswitch.jpg
│   └── verification.jpg
│
└── LICENSE
```

---

# 🎓 Skills Demonstrated

- Enterprise Networking
- High Availability
- Layer 2 Redundancy
- Network Design
- Physical Deployment
- Network Troubleshooting
- Fortinet Security
- Infrastructure Documentation

---

# 🙏 Acknowledgements

Special thanks to **Ultron Bilişim** and our mentor **Fatih Turan** for their guidance and support throughout this project.
