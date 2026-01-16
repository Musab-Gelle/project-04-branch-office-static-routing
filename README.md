# project-04-branch-office-static-routing
Head Office and Branch Office network connected using static routing over a WAN link

# Scenario
A company connects a branch office to its head office network using a point-to-point WAN link. Static routing is used to enable communication between all departmental VLANs and the branch LAN.

# Network Design
- Head Office VLANs:
  - HR – 192.168.10.0/24
  - IT – 192.168.20.0/24
  - Finance – 192.168.30.0/24
- Branch Office LAN – 192.168.40.0/24
- WAN Link – 10.0.0.0/30

# Technologies Used
- Inter-VLAN routing (Router-on-a-Stick)
- Static routing
- WAN point-to-point link
- IPv4 addressing
- Network troubleshooting

# Verification
- Successful router-to-router connectivity
- End-to-end ping from branch PC to head office PCs
- Correct routing table entries on both routers

# Key Learning Outcomes
- Understanding routing tables and return paths
- Troubleshooting Layer 1–3 connectivity issues
- Designing multi-site enterprise networks
