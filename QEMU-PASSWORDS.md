<div align="center">

# 🔑 EVE-NG Qemu Images — Default Credentials

**EVE-NG Qemu Images Passwords Reference**

[![Platform](https://img.shields.io/badge/Platform-EVE--NG-blue?style=flat-square)](https://www.eve-ng.net)
[![Type](https://img.shields.io/badge/Type-Qemu%20Images-orange?style=flat-square)](#)
[![Status](https://img.shields.io/badge/status-maintained-brightgreen?style=flat-square)](#)

> Default usernames and passwords for EVE-NG Qemu image appliances.  
> Some images have multiple credential sets or alternative web access methods — see the Notes column.

</div>

---

## Table of Contents

- [Legend](#legend)
- [Cisco Images](#cisco-images)
- [Juniper Images](#juniper-images)
- [VMware Images](#vmware-images)
- [F5 Networks](#f5-networks)
- [Palo Alto / OpenWRT / Firewall Vendors](#palo-alto--openwrt--firewall-vendors)
- [Fortinet](#fortinet)
- [Check Point](#check-point)
- [Aruba Networks](#aruba-networks)
- [Arista Networks](#arista-networks)
- [Huawei Images](#huawei-images)
- [Other Network Vendors](#other-network-vendors)
- [Linux / BSD / OS Images](#linux--bsd--os-images)

---

## Legend

| Symbol | Meaning |
|:------:|---------|
| `—` | Not required / not applicable / not shown |
| `N/A` | No password set — press **Enter** to continue |
| `(multi)` | Multiple credential sets — see individual rows |
| *Notes* | Web UI URL or alternative access method |

---

## Cisco Images

| # | Image Name | Username | Password | Notes |
|:-:|-----------|:--------:|:--------:|-------|
| 1 | Cisco ASAv | — | — | — |
| 2 | Cisco ACS 5.8.1 (Licensed) | `admin` | `Test123` | CLI access |
| 3 | Cisco ACS 5.8.1 (Licensed) | `ACSAdmin` | `Test123` | Web admin access |
| 4 | Cisco CSR1000v 16.x | — | — | — |
| 5 | Cisco CSRv1000 (SD-WAN) | — | — | — |
| 6 | Cisco DCNM | — | — | — |
| 7 | Cisco ESA | `admin` | `ironport` | — |
| 8 | Cisco FirePOWER6 | `admin` | `Admin123` | — |
| 9 | Cisco ISE | — | — | — |
| 10 | Cisco Nexus 9000v switch | `admin` | N/A | — |
| 11 | Cisco Prime Infra | — | — | — |
| 12 | Cisco StealthWatch | `root` | `lan1cope` | — |
| 13 | Cisco StealthWatch | `sysadmin` | `lan1cope` | — |
| 14 | Cisco StealthWatch | `admin` | `lan411cope` | Web / alternate |
| 15 | Cisco TRex | `root` | `root` | — |
| 16 | Cisco vIOS | — | — | — |
| 17 | Cisco Viptela SD-WAN | `admin` | `admin` | — |
| 18 | Cisco vWAAS | `admin` | `default` | — |
| 19 | Cisco vWLC | — | — | — |
| 20 | Cisco Wireless C9800-CL | — | — | — |
| 21 | Cisco WSA | `admin` | `ironport` | — |
| 22 | Cisco XRv | — | — | — |
| 23 | Cisco XRv9000 | — | — | — |

---

## Juniper Images

| # | Image Name | Username | Password | Notes |
|:-:|-----------|:--------:|:--------:|-------|
| 1 | Juniper cRPD | `root` | `Password1!` | — |
| 2 | Juniper J-Space | `admin` | `abc123` | CLI |
| 3 | Juniper J-Space | `super` | `juniper123` | Web / alternate |
| 4 | Juniper vMX | `root` | N/A | — |
| 5 | Juniper vQFX (PFE) | `root` | N/A | Packet Forwarding Engine |
| 6 | Juniper vQFX (RE) | `root` | `Juniper` | Routing Engine |
| 7 | Juniper vRR | `root` | N/A | — |
| 8 | Juniper vSRX-NG | `root` | N/A | — |
| 9 | Juniper vSRX3.0 | `root` | N/A | — |

---

## VMware Images

| # | Image Name | Username | Password | Notes |
|:-:|-----------|:--------:|:--------:|-------|
| 1 | VMware ESXi | `root` | `VMware1!` | — |
| 2 | VMware NSX-T | `admin` | `EmulatedLab@123` | CLI |
| 3 | VMware NSX-T | `admin` | `EmulatedLab@123` | `https://<nsx-manager-ip-address>` |
| 4 | VMware vCenter | `root` | — | — |
| 5 | VMware Velocloud SD-WAN | `root` | `velocloud` | — |
| 6 | VMware Velocloud SD-WAN | `super@velocloud.net` | `vcadm!n` | veloorch access |

---

## F5 Networks

| # | Image Name | Username | Password | Notes |
|:-:|-----------|:--------:|:--------:|-------|
| 1 | F5 BIGIP | `root` | `default` | CLI |
| 2 | F5 BIGIP | `admin` | `admin` | Web UI |

---

## Palo Alto / OpenWRT / Firewall Vendors

| # | Image Name | Username | Password | Notes |
|:-:|-----------|:--------:|:--------:|-------|
| 1 | Palo Alto | `admin` | `admin` | — |
| 2 | OpenWRT | `root` | `Test@123` | `http://192.168.0.1` |
| 3 | OPNsense | `root` | `opnsense` | CLI / Web |
| 4 | pfSense FW | `admin` | `pfsense` | — |
| 5 | Sophos FW | N/A | `admin` | CLI |
| 6 | Sophos FW | `admin` | N/A | `https://ip:4444` |
| 7 | Sophos UTM | `admin` | N/A | CLI |
| 8 | Sophos UTM | `admin` | N/A | `https://ip:4444` |
| 9 | Kerio Control FW | — | — | — |
| 10 | WatchGuard FireboxV | `admin` | `readwrite` | `https://<External_IP>:8080` or `https://10.0.1.1:8080` |
| 11 | Sangfor | — | — | — |
| 12 | Silver Peak | — | — | — |
| 13 | qaxvfw-73585-standard | `admin` | `!1fw@2soc#3vpn` | CLI / Web |

---

## Fortinet

| # | Image Name | Username | Password | Notes |
|:-:|-----------|:--------:|:--------:|-------|
| 1 | Fortinet | `admin` | N/A | CLI |
| 2 | Fortinet | `admin` | N/A | Web UI |

---

## Check Point

| # | Image Name | Username | Password | Notes |
|:-:|-----------|:--------:|:--------:|-------|
| 1 | Check Point (R81) | `admin` | `admin` | CLI |
| 2 | Check Point (R81) | `admin` | `admin123` | CLI |
| 3 | Check Point (R81) | `admin` | `admin` | `https://192.168.0.1` |
| 4 | Check Point (R81) | `admin` | `admin123` | Web UI |

---

## Aruba Networks

| # | Image Name | Username | Password | Notes |
|:-:|-----------|:--------:|:--------:|-------|
| 1 | Aruba ClearPass | `appadmin` | `eTIPS123` | — |
| 2 | Aruba CX Switch | `admin` | N/A | — |
| 3 | Aruba Mobility Controller | — | — | — |

---

## Arista Networks

| # | Image Name | Username | Password | Notes |
|:-:|-----------|:--------:|:--------:|-------|
| 1 | Arista CloudVision Portal | `cvpadmin` | — | CLI |
| 2 | Arista CloudVision Portal | `cvpadmin` | `cvpadmin` | `https://<eth0's ip>` |
| 3 | Arista vEOS | `admin` | N/A | — |

---

## Huawei Images

| # | Image Name | Username | Password | Notes |
|:-:|-----------|:--------:|:--------:|-------|
| 1 | Huawei AR1000v | `super` | `super` | — |
| 2 | Huawei AR1k (5.170-V300R019C00SPC300) | `admin` | `admin@huawei.com` | — |
| 3 | Huawei USG6000v | `admin` | `admin` | CLI |
| 4 | Huawei USG6000v | `admin` | `Admin@123` | Web UI |

---

## Other Network Vendors

| # | Image Name | Username | Password | Notes |
|:-:|-----------|:--------:|:--------:|-------|
| 1 | 6Wind Turbo | `admin` | `admin` | — |
| 2 | 6Wind Turbo | `viewer` | `viewer` | — |
| 3 | 6Wind Turbo | `root` | `6windos` | — |
| 4 | A10 vThunder | `admin` | `a10` | — |
| 5 | Alcatel & Nokia VSR 7550 | — | — | — |
| 6 | Apple macOS osx-10 | — | `eve` | — |
| 7 | Citrix Netscaler | `nsroot` | `nsroot` | — |
| 8 | Citrix SD-WAN | — | — | — |
| 9 | Cumulus VX | `cumulus` | `CumulusLinux!` | — |
| 10 | DANOS vRouter | `admin` | `admin123` | — |
| 11 | Extreme EXOS | `admin` | N/A | — |
| 12 | H3C | — | — | — |
| 13 | Hillstone | `hillstone` | `hillstone` | — |
| 14 | iKuai | `admin` | `admin` | — |
| 15 | Infoblox DDI | `admin` | `infoblox` | — |
| 16 | Jumpserver | `root` | `Test@123` | CLI |
| 17 | Jumpserver | `admin` | `admin` | `http://<ip>:80` |
| 18 | kali | `epiol` | `123456` | — |
| 19 | Mikrotik Cloud Router | `admin` | N/A | — |
| 20 | Netgate TNSR (Web) | `admin` | `admin123` | Web UI |
| 21 | Netgate TNSR (CLI) | `tnsr` | `tnsr-default` | CLI |
| 22 | Panabit | `root` | `panaos` | CLI |
| 23 | Panabit | `admin` | `panabit` | `http://192.168.1.100` |
| 24 | Pi-hole (DNS) | `root` | `root` | CLI |
| 25 | Pi-hole (DNS) | — | `admin` | `https://[ip]/admin` |
| 26 | Plixer Scrutinizer | `root` | `scrutinizer` | — |
| 27 | proxmox-ve611 | — | — | — |
| 28 | Radware Alteon | `radware` | `radware` | CLI |
| 29 | Radware Alteon | `admin` | `admin` | Web UI |
| 30 | Riverbed SteelHead Virtual CX | `admin` | `password` | — |
| 31 | ruijieswitch-RG-NSE-V1.03 | `admin` | `ruijie` | — |
| 32 | TrueNAS | `root` | `root` | — |
| 33 | Versa Networks SD-WAN (Director CLI) | `admin` | `versa123` | CLI |
| 34 | Versa Networks SD-WAN (Director GUI) | `Administrator` | `versa123` | Web UI |
| 35 | Versa Networks SD-WAN (Controller/FlexVNF) | `versa` | `versa123` | — |
| 36 | VPP | `root` | `vpp` | — |
| 37 | VyOS vRouter | `vyos` | `vyos` | — |
| 38 | Windows | — | `Test123` | — |
| 39 | vWAC | `admin` | `admin` | `https://10.252.252.252` |

---

## Linux / BSD / OS Images

| # | Image Name | Username | Password | Notes |
|:-:|-----------|:--------:|:--------:|-------|
| 1 | FreeBSD | — | `Test123` | — |
| 2 | FreeNAS | `root` | `root` | CLI / Web |
| 3 | Linux | `root` | `root` | — |
| 4 | Linux (CentOS) | `root` | `eve@123` | — |
| 5 | Zabbix3.4 | `root` | `zabbix-eve` | CLI |

---

## Acknowledgments

Credential list referenced and compiled from publicly available community resources, including:

- <a href="https://github.com/hegdepavankumar/Cisco-Images-for-GNS3-and-EVE-NG" target="_blank"><strong>hegdepavankumar/Cisco-Images-for-GNS3-and-EVE-NG</strong></a>

> **Disclaimer:** This information is provided for educational and lab purposes only.  
> All vendor software and trademarks belong to their respective owners.  
> Always change default credentials before deploying in any non-lab environment.

---

<div align="center">
  <a href="README.md">← Back to Main README</a>
  &nbsp;|&nbsp;
  <a href="PASSWORDS.md">📋 GNS3 / EVE-NG All Images Passwords</a>
</div>
