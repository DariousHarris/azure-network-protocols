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


<h2>Resource Setup</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In an Azure lab, I skillfully managed resources by creating a dedicated Resource Group, deploying Windows 10 and Ubuntu VMs, and configuring networking components like Virtual Networks and Subnets. I showcased my proficiency by actively observing the virtual network using Azure's Network Watcher.

</p>
<br />

<h2>ICMP Traffic Analysis</h2>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The second phase focused on ICMP traffic analysis. Leveraging Remote Desktop, I monitored ping requests from the Windows 10 VM to the Ubuntu VM using Wireshark. Practical exploration of Network Security Groups involved disabling and re-enabling ICMP traffic, offering valuable insights into network security configurations.

</p>
<br />

<h2>Exploring Various Protocols</h2>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The third segment delved into SSH, DHCP, DNS, and RDP traffic. Wireshark was used to analyze SSH traffic as I initiated a connection to the Ubuntu VM. I explored DHCP operations by attempting to renew the Windows 10 VM's IP address, and DNS traffic was scrutinized through nslookup queries. The lab concluded with an examination of the constant stream inherent in RDP traffic.

</p>
<br />

<h2>Lab Conclusion and Cleanup</h2>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Culminating the lab, I reflected on insights gained from each protocol analysis, ensuring responsible resource management. The meticulous cleanup process involved terminating the Remote Desktop connection and deleting the Azure Resource Group. Verification of Resource Group deletion marked the successful completion of this complex Azure network analysis lab.

</p>
<br />
