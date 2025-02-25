# <h1>Detecting Malicious Traffic in Wireshark </h1>

<h2>Description</h2>
In this project, I use Wireshark to detect and inspect captured malicious traffic. Subsequently, I analyze the affected files associated with suspicious IP addresses to identify the nature and origin of the threats.

<br />


<h2>Languages and Utilities Used</h2>

- <b>Wireshark</b> (4.4.3)
- <b>Malware Traffic Analysis</b> (https://malware-traffic-analysis.net/)
- <b>VirusTotal</b> (https://www.virustotal.com/gui/home/upload)


<h2>Environments Used </h2>

- <b>PfSense</b> (Version 2.7.2)
- <b>Ubuntu</b> (24.04.1 LTS)
- <b>VirtualBox</b> (7.1.6)


<h2>Program walk-through:</h2>

<p align="center">
Launch Wireshark: <br/>
<img src="https://i.imgur.com/eJ51pOW.png" height="80%" width="80%" alt="Launch Wireshark"/>
<br />
<br />
Analyze the PCAP File in Wireshark & Apply Filters: <br/>
<img src="https://i.imgur.com/inmq7Z5.png" height="80%" width="80%" alt="Analyzing PCAP File"/>
<br />
<br />
Select a Suspicious IP (Source & Destination): <br/>
<img src="https://i.imgur.com/46O5b0f.png" height="80%" width="80%" alt="Select a Suspicious IP"/>
<br />
<br />
Investigate Suspicious IP Addresses on VirusTotal: <br/>
<img src="https://i.imgur.com/MOcUcQb.png" height="80%" width="80%" alt="Investigate Suspicious IP"/>
<br />
<br />
Analyze TCP Streams for Malicious Behavior:  <br/>
<img src="https://i.imgur.com/Z9cjLEj.png" height="80%" width="80%" alt="Analyze TCP Streams"/>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
