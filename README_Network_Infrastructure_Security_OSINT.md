# Network Infrastructure, Security & OSINT

**Author:** Pedro Gonçalves  
**Project:** Virtual Network Infrastructure & Security Laboratory  
**Documentation:** Portuguese | **README:** English

## Overview

This hands-on portfolio documents the design, configuration, and troubleshooting of a virtual network infrastructure integrating Windows and Linux services, firewall administration, access controls, and authorized security testing. The report also includes open-source intelligence (OSINT) research exercises, configuration evidence, and screenshots.

## Network architecture

| Component | Role | Lab address |
|---|---|---|
| pfSense CE | Firewall, gateway, HTTPS administration, NAT | `192.168.40.254` |
| Windows Server 2022 (DC1) | Active Directory Domain Services, DNS, DHCP | `192.168.40.1` |
| Red Hat Enterprise Linux | BIND DNS, Kea DHCP, SSH, failover experiments | `192.168.40.2` |
| Kali Linux | Network diagnostics and authorized security assessment | DHCP |

**Lab subnet:** `192.168.40.0/24`  
**Lab domain:** `layer8.pt` (as configured in the exercises)  
**DHCP pool:** `192.168.40.45–192.168.40.89`

## Topics documented

- **Network deployment:** IP addressing, gateway and DNS configuration, connectivity checks.
- **Windows Server:** Active Directory, DNS forwarders, DHCP scopes, client configuration.
- **pfSense:** LAN/WAN interfaces, firewall/NAT rules, internal certificates and HTTPS management.
- **Red Hat Linux:** BIND DNS, Kea DHCP, OpenSSH and systemd administration.
- **Service continuity:** Python-based service monitoring and failover experiments; observed limitations and troubleshooting are included in the report.
- **Security testing:** Network discovery, SSH authentication testing and MITM demonstrations in an authorized lab environment.
- **OSINT:** Public-source research, image geolocation and metadata inspection.

## Technical report

📄 **[View the complete PDF report](Network_Infrastructure_Security_OSINT_Pedro_Goncalves_Formatacao_Compacta.pdf)**

The PDF contains **75 pages** of laboratory documentation, configuration examples and screenshots.

## Key skills

`Network Engineering` · `Windows Server` · `Active Directory` · `DNS` · `DHCP` · `pfSense` · `Red Hat Linux` · `BIND` · `Kea DHCP` · `SSH` · `Python` · `systemd` · `Kali Linux` · `OSINT` · `Troubleshooting`

## Scope and responsible use

This is a personal learning portfolio based on a controlled virtual lab. Security tests are described for authorized educational environments only. Some steps document unsuccessful tests or configurations requiring further validation; they should not be interpreted as proof of production readiness. Lab IPs and hostnames are preserved for reproducibility. Review screenshots and credentials before publishing publicly.

## Author

**Pedro Gonçalves** — Networking & Cybersecurity  
[GitHub profile](https://github.com/PedroGoncalves28286)
