<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Create two Virtual Machines (VM) Windows 10 and Ubuntu Server, using Azure.
- Use Remote Desktop to access Windows 10 Virtual Machine.
- Install Wireshark on Windows 10 Virtual Machine.
- Utilize Wireshark to observe ICMP, SSH, DHCP, DNS, and RDP traffic.

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/flVt3xS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I started off creating two virtual machines. VM-1 is Windows 10 and VM-2 is Ubuntu Server.
</p>
<br />

<p>
<img src="https://imgur.com/jfAbjvj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I opened up RDP on my physical PC and connected to the VM-1 WIN10 utilizing the public IP.
</p>
<br />

<p>
<img src="https://imgur.com/Gpe6ymQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I then installed Wireshark on the WIN10 VM-1 by going to the download page of wwww.wireshark.org.
</p>
<br />

<p>
<img src="https://imgur.com/DM0fjvm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Utilizing Wireshark, I ran several various -pings running powershell. While running powershell, I then SSH'd into my Linux Ubuntu Server VM-2 and began running various -pings for ICMP, SSH, DHCP, DNS, and RDP traffic.
</p>
<br />
