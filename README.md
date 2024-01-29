#  The Panthera(P.)uncia of Cybersecurity 
### Subdomain & Exploit Hunter powered by AI

[![Downloads](https://pepy.tech/badge/puncia)](https://pepy.tech/project/puncia)
<img src="https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat">
<img alt="GitHub stars" src="https://img.shields.io/github/stars/ARPSyndicate/puncia"> 
<br>
<img src="https://raw.githubusercontent.com/ARPSyndicate/puncia/master/puncia.png" width=25%> 
<br>
Puncia utilizes two of our intelligent APIs - [Subdomain Center](https://subdomain.center) & [Exploit Observer](https://exploit.observer), to gather the results. 
**Please note that although these results can sometimes be pretty inaccurate & unreliable, they can greatly differ from time to time due to their self-improvement capabilities.**

## Installation
1. From PyPi - `pip3 install puncia`
2. From Source - `pip3 install .`<br>

## Usage
1. Subdomain - `puncia subdomain <domain> <output>`
2. Exploit - `puncia exploit <eoidentifier> <output>`<br>

## Supported EOIdentifiers
1. Common Vulnerabilities and Exposures (CVE) - [`puncia exploit CVE-2021-3450`](https://api.exploit.observer/?keyword=CVE-2021-3450) 
2. The Japan Vulnerability Notes iPedia (JVNDB) - [`puncia exploit JVNDB-2023-006199`](https://api.exploit.observer/?keyword=JVNDB-2023-006199) 
3. GitHub Security Advisories (GHSA) - [`puncia exploit GHSA-wfh5-x68w-hvw2`](https://api.exploit.observer/?keyword=GHSA-wfh5-x68w-hvw2) 
4. Exploit Database (EDB) - [`puncia exploit EDB-10102`](https://api.exploit.observer/?keyword=EDB-10102)
5. Zero Day Initiative (ZDI) - [`puncia exploit ZDI-23-1714`](https://api.exploit.observer/?keyword=ZDI-23-1714) 
6. Packet Storm Security (PSS) - [`puncia exploit PSS-170615`](https://api.exploit.observer/?keyword=PSS-170615) 
7. World Laboratory of Bugtraq (WLB) - [`puncia exploit WLB-2024010058`](https://api.exploit.observer/?keyword=WLB-2024010058)
8. Metasploit Framework (MSF) - [`puncia exploit MSF/auxiliary_admin/2wire/xslt_password_reset`](https://api.exploit.observer/?keyword=MSF/auxiliary_admin/2wire/xslt_password_reset)
9. ProjectDiscovery Nuclei (PD) - [`puncia exploit PD/http/cves/2020/CVE-2020-12720`](https://api.exploit.observer/?keyword=PD/http/cves/2020/CVE-2020-12720) 
10. Hackerone Hacktivity (H1) - [`puncia exploit H1-2230915`](https://api.exploit.observer/?keyword=H1-2230915)
11. Cisco Talos (TALOS) - [`puncia exploit TALOS-2023-1896`](https://api.exploit.observer/?keyword=TALOS-2023-1896)
12. ProtectAI Huntr (HUNTR) - [`puncia exploit HUNTR-001d1c29-805a-4035-93bb-71a0e81da3e5`](https://api.exploit.observer/?keyword=HUNTR-001d1c29-805a-4035-93bb-71a0e81da3e5)
13. WP Engine WPScan (WPSCAN) - [`puncia exploit WPSCAN-52568abd-c509-411e-8391-c75e7613eb42`](https://api.exploit.observer/?keyword=WPSCAN-52568abd-c509-411e-8391-c75e7613eb42)
14. YouTube (YT) - [`puncia exploit YT/ccqjhUmwLCk`](https://api.exploit.observer/?keyword=YT/ccqjhUmwLCk)
15. Technologies/Keywords (No Prefix) - [`puncia exploit grafana`](https://api.exploit.observer/?keyword=grafana)<br>


## Noteworthy Mentions
- [Introducing Exploit Observer — More than Shodan Exploits, Less than Vulners](https://blog.arpsyndicate.io/introducing-exploit-observer-more-than-shodan-exploits-less-than-vulners-23eaea466e4a)
- [PUNCIA — The Panthera(P.)uncia of Cybersecurity](https://blog.arpsyndicate.io/puncia-the-panthera-p-uncia-of-cybersecurity-ft-puncia-subdomain-center-exploit-observer-9a9d8cca9576)
- [Subdomain Enumeration Tool Face-off - 2023 Edition](https://blog.blacklanternsecurity.com/p/subdomain-enumeration-tool-face-off-4e5)

## More from [A.R.P. Syndicate](https://www.arpsyndicate.io)
- [Attack Surface Management](https://asm.arpsyndicate.io)
- [OSINT Resources](https://asm.arpsyndicate.io/intelligence.html)
- [Subdomain Center](https://subdomain.center)
- [Exploit Observer](https://exploit.observer)
