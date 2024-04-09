# DominCyber Scanning an Active Directory Domain Controller for Vulnerabilities
## Objective
Saint Leo University Course work intended to familiarize undergraduates with scanning Active Directory Domain Controller for Vulnerabilities. This practical guided project presents a simulated environment that explores methodologies and applications to conduct and analyze indepth vulnerability scans. The scenario details SMBv1 vulnerabilities post-scan, namely unauthenticated remote access or denial of service attacks from improper handling of external requests to a targeted Active Directory server.

### Skills Learned
<p>-Vulnerability Scanning Methodolgy</p>
<p>-Common AD vulnerabilities</p>
<p>-Nmap port scanning, operating system and service version detection switches</p>
<p>-Zenmap GUI familiarization and port scanning switches</p>
<p>-Nessus basic scanning configuration</p>
<p>-PowerShell</p>
<p>-CVE threat assessment</p>
<li>-Cyber Kill Chain applications to vulnerability scanning</li>


### Tools Used
-Laptop
<p>-Cengage eLearning</p>
<p>-Nmap</p>
<p>-Zenmap</p>
<p>-Nessus</p>
<p>-PowerShell</p>

### Steps
<img src="https://i.imgur.com/p2ZtoHR.png" style="width: 100%;" alt="1">
<p><i>Ref 1: Example of Nmap common port scan (Nmap -p target IP). Reveals potential attack surfaces.</i></p>
<img src="https://i.imgur.com/EDmowxI.png" style="width: 100%;" alt="1">
<p><i>Ref 2: Example of Nmap operating system scan (Nmap -O target IP). Can potentially reveal interal vulnerabilitiies for exploitation.</i></p>
<img src="https://i.imgur.com/pDfl115.png" style="width: 100%;" alt="1">
<p><i>Ref 3: Example of Nmap service version detection scan (Nmap -sV target IP). Can potentially reveal interal vulnerabilities for exploitation.</i></p>
<img src="https://i.imgur.com/CODjYuf.jpg" style="width: 100%;" alt="1">
<p><i>Ref 4: Zenmap results for a regular scan.</i></p>
<img src="https://i.imgur.com/NNYA7b3.jpg" style="width: 100%;" alt="1">
<p><i>Ref 5: Zenmap results for a scan results for an intense TCP port scan (nmap -p port range -T4 -A -v target IP).</i></p>
<img src="https://i.imgur.com/1SCFv6m.jpg" style="width: 100%;" alt="1">
<p><i>Ref 6: Nessus scan configuration, scan results, and high vulnability selected. An SMBv1 vulnerability was discovered.</i></p>
<img src="https://i.imgur.com/rRnRMrQ.jpg" style="width: 100%;" alt="1">
<p><i>Ref 7: PowerShell command line search for services reveals SMBv1 Protocol enabled. Then the prompt disabling of the service.</i></p>
