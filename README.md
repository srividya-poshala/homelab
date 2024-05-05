# Cybersecurity Homelab for Monitoring and Alerting

## Overview
A homelab is a personal lab environment used to learn and experiment with different technologies in a controlled setting. This project specifically focuses on monitoring and detecting logs and alerts using various cybersecurity tools integrated through VMware Workstation.

## Components

### Virtualization Platform
- **VMware Workstation 17 Pro:** Acts as the hypervisor hosting all other virtual machines.
  - ![VMware Logo](<Insert Image Here>)

### Network Security
- **pfSense Firewall:**
  - Serves as the firewall to segment the private homelab network. Configured to manage network traffic and enhance security.
  - ![pfSense Logo](<Insert Image Here>)
- **Security Onion as IDS/Security:**
  - Utilized for intrusion detection and security monitoring to analyze network security.
  - ![Security Onion Logo](<Insert Image Here>)

### Penetration Testing
- **Kali Linux:**
  - Deployed as the attack machine for penetration testing and security assessments.
  - ![Kali Linux Logo](<Insert Image Here>)

### Network Management
- **Windows Server 2019 as a Domain Controller:**
  - Manages user authentication and domain management.
  - ![Windows Server Logo](<Insert Image Here>)
- **Windows 10 Desktops:**
  - Configured for typical workstation operations within the network.
  - ![Windows 10 Logo](<Insert Image Here>)

### Monitoring
- **Splunk:**
  - Integrated for logging and monitoring the entire homelab environment to capture and analyze data.
  - ![Splunk Logo](<Insert Image Here>)

## Configuration Steps

1. **Installation of VMware Workstation:**
   - Install VMware Workstation 17 Pro to serve as the platform for all virtual machines.

2. **Setup and Configuration of pfSense:**
   - Install pfSense on a VM to function as a dedicated firewall.
   - Configure network interfaces and firewall rules to manage and secure network traffic.

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

## System Architecture

- **Homelab Network Diagram:**
  - ![Homelab Network Diagram](<Insert Image Here>)
  - This diagram illustrates the configuration and interaction between different components within the homelab.

## Conclusion

This project demonstrates the setup and integration of a complex homelab designed for security testing and network management. It provides a practical learning environment for exploring the capabilities of various security tools and techniques.

## Tags
`#Cybersecurity` `#Homelab` `#Monitoring` `#Splunk` `#VMware` `#KaliLinux` `#pfSense` `#SecurityOnion` `#WindowsServer2019` `#Windows10`
