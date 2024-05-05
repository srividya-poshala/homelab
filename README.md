# Cybersecurity Homelab for Monitoring and Alerting

This project demonstrates the setup of a cybersecurity homelab focused on monitoring and detecting logs and alerts with a variety of tools and technologies.

`#Cybersecurity` `#Homelab` `#Monitoring` `#Splunk` `#VMware` `#KaliLinux` `#pfSense` `#SecurityOnion` `#WindowsServer2019` `#Windows10`

![pfSense Logo](Images/pfSenseLogo.png) ![Security Onion Logo](Images/SecurityOnionLogo.png) ![Splunk Logo](Images/SplunkLogo.png)

## Overview
A Homelab is a personal lab environment used to learn and experiment with different technologies in a controlled setting. This homelab is designed to explore monitoring and security practices using advanced configurations and custom setups.

## Tools Used
- **Attacker** - Kali Linux
- **Firewall** - pfSense
- **IDS** - Security Onion
- **SIEM** - Splunk
- **Hypervisor** - VMWare
- **Domain Controller** - Windows Active Directory
- **Vulnerable Machines** - Ubuntu, Windows



## Architecture
Here is a network diagram that illustrates the configuration and interaction between the different components within the homelab:

![Homelab Network Diagram](<Insert Network Diagram Here>)

## Components
### Virtualization Platform
- **VMware Workstation 17 Pro:** Acts as the hypervisor hosting all other virtual machines.

### Network Security
- **pfSense Firewall:**
  - Serves as the firewall to segment the private homelab network.
- **Security Onion as IDS/Security:**
  - Used for intrusion detection and security monitoring.

### Penetration Testing
- **Kali Linux:**
  - Deployed as the attack machine for security testing.

### Network Management
- **Windows Server 2019 as a Domain Controller:**
  - Manages user authentication and domain management.
- **Windows 10 Desktops:**
  - Configured for typical workstation operations within the network.

### Monitoring
- **Splunk:**
  - Integrated to monitor and log the entire homelab environment.

## Configuration Steps

1. **Installation of VMware Workstation:**
   - Install VMware Workstation 17 Pro to serve as the platform for all virtual machines.

2. **Setup and Configuration of pfSense:**
   - Install pfSense on a VM to function as a dedicated firewall. Configure network interfaces and firewall rules.

3. **Deploying Security Onion:**
   - Install Security Onion to monitor network traffic and capture intrusion alerts.

4. **Configuring Kali Linux:**
   - Setup Kali Linux for conducting security tests and penetration testing.

5. **Setting up Windows Server 2019:**
   - Install and configure Windows Server 2019 as a Domain Controller.

6. **Configuring Windows 10 Desktops:**
   - Setup multiple Windows 10 VMs to simulate user interaction within the network.

7. **Integrating Splunk for Monitoring:**
   - Install Splunk to aggregate and analyze logs from various sources within the homelab.

## Conclusion
This project demonstrates the setup and integration of a complex homelab designed for security testing and network management. It provides a practical learning environment for exploring the capabilities of various security tools and techniques.
