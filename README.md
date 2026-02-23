# vpn 🛜🌐☁️
vpn : High-throughput VPN | Networks, VPN, iperf, VPC  |


## Objectives
- To build a high-throughput VPN between two simulated networks, a cloud VPC and an on-premises VPC
- Create VPN
  - Create custom Virtual Private Cloud (VPC) named cloud to simulate Google Cloud network & VPC named on-prem (on-premises) to simulate an external network.
  - Create & configure VPN gateways, forwarding rules & addresses for cloud VPC.
  - Form a secure IPsec tunnel for the new VPN & route traffic through it.
  - Repeat the VPN creation process for the on-prem VPC, creating a second VPN.
- Test VPNs
  - Create virtual machine (VM) using Compute Engine for throughput load testing.
  - Test throughput speed of a single VPN using iperf.


## Building High-throughput VPN 
