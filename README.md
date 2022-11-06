<h1>Nessus Vulnerability Scanner: Remediation</h1>


<h2>Description</h2>
Project consists of using VirtualBox to simulate a corporate network which uses domain services and active directory. After the "corporate" enviorment was created, Group Policy Objects were created and linked to the client virtual machine.
<br />


<h2>Languages and Utilities Used</h2>

- <b>VMWare</b> 
- <b>Nessus Vulnerability Scanner</b>

<h2>Environments Used </h2>

- <b>Windows 10 Pro</b> 

<h2>Program walk-through:</h2>

<p align="center">
Creating and configuring Windows 10 VM: <br/>
<img src="https://i.imgur.com/49Bgf2F.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Downloading Nessus:  <br/>
<img src="https://i.imgur.com/qe6iF3P.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Disabling firewall on VM: <br/>
<img src="https://i.imgur.com/yLdFdWp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Performing uncredentialed Nessus Scan:  <br/>
<img src="https://i.imgur.com/saXgCv1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Performing credentialed Nessus Scan wiht no vulnerablities:  <br/>
<img src="https://i.imgur.com/V53vZbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Installing vulnerable version of FireFox:  <br/>
<img src="https://i.imgur.com/AOm5MxG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Remediating Vulnerabilities (Uninstalling Firefox and updating Windows:  <br/>
<img src="https://i.imgur.com/AOm5MxG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Performing last credential scan to ensure vulnerabilties are remediated:  <br/>
<img src="https://i.imgur.com/AOm5MxG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
