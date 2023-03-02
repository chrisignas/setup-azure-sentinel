<p align="center">
<img src="https://i.imgur.com/sZVzrrQ.png" alt="Azure Sentinel Logo"/>
</p>

<h1>Azure Sentinel (SIEM) Tutorial with Map of Live Cyber Attacks</h1>
This tutorial outlines the implementation of a SIEM within Azure Virtual Machines.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure Sentinel (Virtual Machines/Compute)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1
- Step 2
- Step 3
- Step 4

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/Y1wnBlJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a Resource Group and VM
</p>
<br />

<p>
<img src="https://i.imgur.com/3gntJtQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a new NIC by clicking advanced
</p>
<br />

<p>
<img src="https://i.imgur.com/SW0mXPc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Remove the default NIC
</p>
<br />

<p>
<img src="https://i.imgur.com/SW0mXPc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Add Inbound Rules
</p>
<br />

<p>
<img src="https://i.imgur.com/NiW5unD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create the VM
</p>
<br />

<p>
<img src="https://i.imgur.com/KtjmMF2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a Logs Analytics Workspace
</p>
<br />

<p>
<img src="https://i.imgur.com/K83UwFs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Name the Analytics Workspace
</p>
<br />

<p>
<img src="https://i.imgur.com/MVFhzlQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Turn on Microsoft Defender
</p>
<br />

<p>
<img src="https://i.imgur.com/NrOjt6w.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Turn SQL Servers Off for the honeypot and click save
</p>
<br />

<p>
<img src="https://i.imgur.com/FFGq3uD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Refresh the page and install Data Collections
</p>
<br />

<p>
<img src="https://i.imgur.com/P7KTU79.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to environment settings and open Azure Subscription and click on the honeypot
</p>
<br />

<p>
<img src="https://i.imgur.com/HD3YAOY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click on Data Collection and select All Events and save
</p>
<br />

<p>
<img src="https://i.imgur.com/QWGI6uI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go back to log analytics workspace to connect it to the VM
</p>
<br />

<p>
<img src="https://i.imgur.com/Coft8wn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open the log analytics workspace and click on virtual machines on the left
</p>
<br />

<p>
<img src="https://i.imgur.com/0KVE0oD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click on the VM created in the beginning
</p>
<br />

<p>
<img src="https://i.imgur.com/o0XjLew.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click connect
</p>
<br />

<p>
<img src="https://i.imgur.com/P0qYph1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Setup Sentinel
</p>
<br />

<p>
<img src="https://i.imgur.com/bqvgDTn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Choose the honeypot
</p>
<br />

