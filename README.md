Project: Enterprise Hybrid Lab & Web Hosting
Overview
I developed a virtualized network environment to simulate a corporate infrastructure. This project demonstrates my ability to manage cross-platform connectivity, troubleshoot network routing, and maintain Linux-based web services.

1. Network Architecture
Virtualization: Oracle VirtualBox

Subnet: 192.168.10.0/24 (Static)

Linux Server: Ubuntu 22.04 LTS (IP: 192.168.10.20)

Windows Client: Windows 10/11 (IP: 192.168.10.30)

2. Technical Configurations
Linux Netplan (Static IPv4)
# Actual configuration used for internal host-to-host communication
network:
  version: 2
  ethernets:
    enp0s3:
      addresses:
        - 192.168.10.20/24
        3. Career-Relevant Skills Demonstrated
        
Layer 3 Troubleshooting: Diagnosed and resolved APIPA conflicts using static addressing.

Remote Administration: Configured SSH for secure remote management from Windows to Linux.

Security: Managed UFW (Uncomplicated Firewall) to secure Port 80.

Documentation: Detailed technical procedures for systems replication and disaster recovery.
