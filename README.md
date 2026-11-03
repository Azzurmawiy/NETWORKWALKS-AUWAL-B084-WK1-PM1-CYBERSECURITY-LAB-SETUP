# NETWORKWALKS-AUWAL-B084-WK1-PM1-CYBERSECURITY-LAB-SETUP
# Week 1 - Project Module 1: Cybersecurity Lab Environment Setup

## Objective
Set up a Cybersecurity testing lab environment on a host machine using VirtualBox and Kali Linux as the attacking virtual machine. 

## Requirements Met
- VirtualBox installed as the base hypervisor.
- Kali Linux imported and configured as a Virtual Machine.
- NATNetwork created with the `10.0.0.0/24` subnet.
- Clipboard & file drag/drop enabled in Virtual Machine settings.
- Kali Linux IP Address configured properly within the subnet.
- Full Internet access verified inside the Kali Linux VM.

## Setup Steps & Verification

### 1. VirtualBox Network Configuration
Created a custom NATNetwork to ensure the virtual machine operates on the required `10.0.0.0/24` subnet while remaining isolated from the host's primary network.

[Drag and drop your VirtualBox NATNetwork settings screenshot (3.png) here]

### 2. Kali Linux VM Settings
Imported the Kali Linux VM and assigned it to the custom NATNetwork. Verified system requirements (Base Memory, Processors) and enabled bidirectional shared clipboard features.

[Drag and drop your Kali Linux VM General/Network settings screenshot (1.png or 2.png) here]

### 3. Verification of Internet Connectivity
Launched the Kali Linux VM and successfully accessed the internet through the web browser, confirming the network adapter is functioning correctly and routing traffic out.

[Drag and drop your Kali Linux running browser screenshot (6.png) here]

## Conclusion
The base lab environment is successfully deployed and ready for future Capture The Flag (CTF) practical labs and vulnerability assessments.
