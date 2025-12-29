# Kali Linux

## Objective

This project focused on setting up a Kali Linux virtual machine to create a controlled and secure lab environment for cybersecurity testing and learning. The objective was to successfully install and operate Kali Linux within a virtualised environment and configure a VPN to ensure secure network connectivity. Through this project, I strengthened my understanding of Kali Linux, Linux networking fundamentals, and secure lab setup, while gaining hands-on experience working with tools and techniques used in real-world security analysis.

### Skills Learned

- Secure environment setup for security analysis
- Configured and validated VPN connectivity on Linux to ensure secure network communication.
- Managed system updates, packages, and permissions in a Linux environment

### Tools Used

- [Virtualbox](https://www.virtualbox.org) for running the Kali linux VM on.
- [Kali Linux](https://www.kali.org/get-kali/#kali-platforms), the secure environment created.
- [OpenVPN](https://openvpn.net) this was the VPN software configured to secure my environment.

## Steps

<img width="784" height="639" alt="Screenshot 2025-12-28 at 07 12 24" src="https://github.com/user-attachments/assets/3cedace2-bb76-4b12-ac47-2215588ceed7" />

### Reference 1
The screenshot above shows Oracle VirtualBox open on my system, with the Kali Linux virtual machine correctly configured and ready to be launched.
##
<br>
<img width="1442" height="985" alt="Screenshot 2025-12-28 at 07 14 04" src="https://github.com/user-attachments/assets/243b6136-7977-44f0-a210-c21598f83d81" />

### Reference 2
This screenshot confirms the successful initial boot of the Kali Linux operating system running inside the virtual machine on my MacBook.
##
<br>
<img width="664" height="553" alt="Screenshot 2025-12-29 at 18 08 23" src="https://github.com/user-attachments/assets/5fb0d283-ffa2-4d3e-aa6b-256f9aafef97" />

### Reference 3
This image verifies that the Kali Linux VM is properly installed, displaying network connectivity via a basic ping command and the system version number. At this stage, the environment is not yet fully secured, as the VPN has not been installed or configured.
##
<br>
<img width="1445" height="1046" alt="Screenshot 2025-12-28 at 07 30 19" src="https://github.com/user-attachments/assets/892badd6-7d7f-429a-a0a3-d04298cb3e46" />

### Reference 4
For this project, I chose to use a free VPN solution by configuring OpenVPN with VPNBook. To maintain simplicity and usability, I selected the Canadian server, as some other locations (such as Germany) automatically change the Firefox browser language.
##
<br>
<img width="1441" height="995" alt="Screenshot 2025-12-28 at 07 33 43" src="https://github.com/user-attachments/assets/e1e38c11-5d43-404b-82cd-59b5acb49927" />

### Reference 5 
After downloading the VPN configuration files, I navigated to and executed the appropriate file to establish the VPN connection. I selected the TCP Port 443 configuration to enhance security and improve reliability by using standard HTTPS traffic.
##
<br>
<img width="1439" height="1052" alt="Screenshot 2025-12-28 at 07 36 10" src="https://github.com/user-attachments/assets/974cb77a-6a1b-4d65-b317-09914b9f7a2c" />

### Reference 6 
The appearance of the “Initialization Sequence Completed” message confirms that the virtual machine successfully connected to the VPN and was ready for verification.
##
<br>
<img width="1441" height="999" alt="Screenshot 2025-12-28 at 07 40 00" src="https://github.com/user-attachments/assets/251729e7-ab50-4cb8-b7c0-d1deac822990" />

### Reference 7
A quick IP address check confirms that the VPN connection is active, showing that my IP address has changed from the earlier configuration (Ref 3) and is now detected as being located in Canada.
