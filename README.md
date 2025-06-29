<h1>Vulnerability Assessment Lab - Nessus</h1>

<h2>Description</h2>
Nessus is a powerful vulnerability scanning tool used by security professionals to identify weaknesses, misconfigurations, and vulnerabilities across endpoints and services.

In this project, Nessus Essentials was installed on a Windows 10 VM to scan other systems in the lab network, including Linux servers and Windows workstations. The scans identify outdated software, misconfigured services, and common CVEs.

<h2>Tools and Technologies Used</h2>
- <b>Nessus Essentials</b>
- <b>Windows 10</b>
- <b>Vulnerability Scanning</b>

<h2>Environments Used</h2>
- <b>Windows 10 VM (with Nessus)</b>
- <b>Target VMs: pfSense, Wazuh, Ubuntu Server</b>

<h2>Scan Walk-through</h2>

<p align="center">
Nessus Web Interface - Dashboard <br/>
<img src="LINK_TO_IMAGE_nessus_dashboard.png" height="80%" width="80%" />

<br /><br />
Creating a New Scan Profile <br/>
<img src="LINK_TO_IMAGE_nessus_new_scan.png" height="80%" width="80%" />

<br /><br />
Scan Results Summary <br/>
<img src="LINK_TO_IMAGE_nessus_results.png" height="80%" width="80%" />

<br /><br />
Detected Vulnerabilities Example (Ubuntu) <br/>
<img src="LINK_TO_IMAGE_nessus_ubuntu_vuln.png" height="80%" width="80%" />
</p>
