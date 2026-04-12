# home-lab-it-project
Building an Enterprise IT Lab: Windows-Linux Integration, Networking, and Web Hosting.
Objective
To design and deploy a secure virtual network environment simulating a corporate branch office, focusing on cross-platform connectivity and service management.

Technical Stack
Hypervisor: Oracle VirtualBox

Operating Systems: Ubuntu Server 22.04 LTS (Linux), Windows 10/11 (Client)

Services: Apache2 Web Server, SSH

Networking: Static IPv4, NAT, Internal Networking

# My actual Netplan Config
network:
  version: 2
  ethernets:
    enp0s3:
      addresses: [192.168.10.20/24]
