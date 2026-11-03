# NETWORKWALKS-AUWAL-B084-WK1-PM1-CYBERSECURITY-LAB-SETUP
# Week 1 - Project Module 1: Cybersecurity Lab Environment Setup
# Objective
Set up a Cybersecurity testing lab environment on a host machine using VirtualBox and Kali Linux as the attacking virtual machine.

Requirements Met
VirtualBox installed as the base hypervisor.
Kali Linux imported and configured as a Virtual Machine.
NATNetwork created with the 10.0.0.0/24 subnet.
Clipboard & file drag/drop enabled in Virtual Machine settings.
Kali Linux IP Address configured properly within the subnet.
Full Internet access verified inside the Kali Linux VM.
Setup Steps & Verification
1. VirtualBox Network Configuration
Created a custom NATNetwork to ensure the virtual machine operates on the required 10.0.0.0/24 subnet while remaining isolated from the host's primary network.

https://github.com/Azzurmawiy/NETWORKWALKS-AUWAL-B084-WK1-PM1-CYBERSECURITY-LAB-SETUP/blob/main/3.png

2. Kali Linux VM Settings
Imported the Kali Linux VM and assigned it to the custom NATNetwork. Verified system requirements (Base Memory, Processors) and enabled bidirectional shared clipboard features.

https://github.com/Azzurmawiy/NETWORKWALKS-AUWAL-B084-WK1-PM1-CYBERSECURITY-LAB-SETUP/blob/main/1.png
https://github.com/Azzurmawiy/NETWORKWALKS-AUWAL-B084-WK1-PM1-CYBERSECURITY-LAB-SETUP/blob/main/2.png

3. Verification of Internet Connectivity
Launched the Kali Linux VM and successfully accessed the internet through the web browser, confirming the network adapter is functioning correctly and routing traffic out.

https://github.com/Azzurmawiy/NETWORKWALKS-AUWAL-B084-WK1-PM1-CYBERSECURITY-LAB-SETUP/blob/main/6.png

Conclusion
The base lab environment is successfully deployed and ready for future Capture The Flag (CTF) practical labs and vulnerability assessments.
