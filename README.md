# **Azure Compute and Networking**

![image](https://github.com/Domenick-Ranfone/Wireshark/assets/138722554/645b0330-16a9-4fda-bd63-34709cfb74d0)

# **Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines**
  In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups.

![image](https://github.com/Domenick-Ranfone/Wireshark/assets/138722554/0abf6952-9cd3-4cd8-95b8-0ae1d40aca80)

# **Environments and Technologies Used**
 - Microsoft Azure (Virtual Machines/Compute)
 - Remote Desktop Protocol (Port 3389) 
 - Network Security Groups 
 - Wireshark (Protocol Analyzer)
 - Various Network Protocols (ICMP, SSH, DHCP, DNS)
 - Windows PowerShell
 - Various Command-Line Tools

# **Operatings Systems Used**
 - Windows 10 (21H2)
 - Linux (Ubuntu Server) 20.04

# **Actions and Observations**

![CC-Lab2-Network Security Group](https://github.com/Domenick-Ranfone/Wireshark/assets/138722554/a9faa3fc-89b9-4ae3-8fba-52b630912f7c)
 - Adjusted NSG's on Ubuntu VM to disable/enable incoming (inbound) ICMP Traffic from Windows VM





![CC-Lab2-Observing ICMP Traffic](https://github.com/Domenick-Ranfone/Wireshark/assets/138722554/90d9dadb-bfda-4fa5-bf8e-d4803ce9be40)
 - Observed the ICMP Traffic in Wireshark and the command line Ping activity in PowerShell





![CC-Lab2-Observing DNS Traffic](https://github.com/Domenick-Ranfone/Wireshark/assets/138722554/2f4387d6-8e7b-4f0c-83b1-1771fafd3f9c)
 - Utilized nslookup to find IP addresses of google.com and disney.com
 - Observed the DNS Traffic being shown in Wireshark and PowerShell





![CC-Lab2-Observing RDP Traffic](https://github.com/Domenick-Ranfone/Wireshark/assets/138722554/68636b98-535f-48de-ade8-712fe9b2e761)
 - Observed the immediate non-stop spam of traffic because the Remote Desktop Protocol is constantly showing a live stream from one computer to another, therefore traffic is always being transmitted
