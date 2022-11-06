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
<img src="https://i.imgur.com/ovhNgMx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Disabling firewall on VM: <br/>
<img src="https://i.imgur.com/DtmSv82.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Performing uncredentialed Nessus Scan:  <br/>
<img src="https://i.imgur.com/hzQcijm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Performing credentialed Nessus Scan with no installed vulnerablities:  <br/>
<img src="https://i.imgur.com/sUPUStd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Installing vulnerable version of FireFox:  <br/>
<img src="https://i.imgur.com/UsAgeoz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Nessus Scan with known vulnerabiltites:  <br/>
<img src="https://i.imgur.com/Q01PP0P.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Remediating Vulnerabilities (Uninstalling Firefox and updating Windows:  <br/>
<img src="https://i.imgur.com/d1blgKr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Performing last credential scan to ensure most critical vulnerabilties are remediated:  <br/>
<img src="https://i.imgur.com/2GgII9W.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
