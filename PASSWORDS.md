<div align="center">

# 🔑 Default Credentials Reference

**EVE-NG & GNS3 — All Images Username / Password**

[![Images](https://img.shields.io/badge/Platforms-EVE--NG%20%7C%20GNS3-blue?style=flat-square)](https://www.eve-ng.net)
[![Entries](https://img.shields.io/badge/Entries-95%2B-informational?style=flat-square)](#)
[![Status](https://img.shields.io/badge/status-maintained-brightgreen?style=flat-square)](#)

> Default usernames, passwords, and console access methods for network simulation images.  
> Use this reference when first booting an image in your lab environment.

</div>

---

## Table of Contents

- [Legend](#legend)
- [Cisco Images](#cisco-images)
- [F5 Networks](#f5-networks)
- [Juniper Images](#juniper-images)
- [Palo Alto Networks](#palo-alto-networks)
- [Check Point](#check-point)
- [Fortinet](#fortinet)
- [Aruba Networks](#aruba-networks)
- [Other Network Vendors](#other-network-vendors)
- [Linux Images](#linux-images)
- [Windows Images](#windows-images)

---

## Legend

| Symbol | Meaning |
|:------:|---------|
| `—` | Not required / not applicable |
| `no pass` | No password set — press **Enter** to continue |
| `no passwd` | No password set — press **Enter** to continue |
| `(multi)` | Multiple credential sets — see individual rows |

---

## Cisco Images

| # | Image Name | Username | Password | Admin Access Console |
|:-:|-----------|:--------:|:--------:|:--------------------:|
| 1 | Cisco ASA 802 | — | no pass | telnet |
| 2 | Cisco ASA 8.4.2, 9.1.5 | — | no pass | telnet |
| 3 | Cisco ASAv | — | no pass | telnet |
| 4 | Cisco IPS | `cisco` | `ciscoips123` | telnet |
| 5 | Cisco WSA | `admin` | `ironport` | telnet / http://ip:8080 |
| 6 | Cisco ESA | `admin` | `ironport` | telnet / https |
| 7 | Cisco WAAS | `admin` | `default` | telnet |
| 8 | Cisco FirePower 6.x | — | — | — |
| 9 | FMC (Firepower Management Center) | `admin` | `Admin123` | vnc |
| 10 | NGIPSv | `admin` | `Admin123` | vnc |
| 11 | FTD (Firepower Threat Defense) | `admin` | `Admin123` | vnc |
| 12 | Cisco WSA *(variant)* | `admin` | `ironport` | telnet / https |
| 13 | Cisco ESA *(variant)* | `admin` | `ironport` | telnet / https |
| 14 | Cisco vNAM | `root` | `root` | vnc |
| 15 | Cisco Titanium | `admin` | `admin` | telnet |
| 16 | Cisco XR9K 6 | `cisco` | `cisco` | telnet |
| 17 | Cisco NX9K 7 | `admin` | `admin` | telnet |
| 18 | Cisco ISE 2.2 | `admin` | `Test123` | cli / https |
| 19 | Cisco ISE 2.7, 3.0 | `setup` | — | Use `setup` command for initial config |
| 20 | Cisco CUCM | `admin` | `eve4cisco` | vnc / https |

---

## F5 Networks

| # | Image Name | Username | Password | Admin Access Console |
|:-:|-----------|:--------:|:--------:|:--------------------:|
| 1 | F5 | `root` | `default` | cli |
| 2 | F5 | `admin` | `admin` | https |

---

## Juniper Images

| # | Image Name | Username | Password | Admin Access Console |
|:-:|-----------|:--------:|:--------:|:--------------------:|
| 1 | Juniper vSRX | `root` | no pass | telnet |
| 2 | Juniper vSRX *(variant)* | `root` | no pass | telnet |
| 3 | Juniper Oliv | `root` | no pass | telnet |
| 4 | Juniper vMX | `root` | `root123` | telnet |
| 5 | Juniper vMX *(variant)* | `root` | `root` | telnet |
| 6 | Juniper vMX *(variant)* | `root` | no pass | telnet |
| 7 | Juniper vMX *(variant)* | `root` | `root` | telnet |
| 8 | Juniper vQF | `root` | `Juniper` | telnet |
| 9 | Juniper vQF *(variant)* | `root` | no pass | vnc |
| 10 | Juniper RR | `root` | no pass | telnet |
| 11 | Juniper Linux | `admin` | `abc123` | vnc |
| 12 | Juniper Linux *(super)* | `super` | `juniper123` | https |

---

## Palo Alto Networks

| # | Image Name | Username | Password | Admin Access Console |
|:-:|-----------|:--------:|:--------:|:--------------------:|
| 1 | PaloAlto 8.0 | `admin` | `admin` | vnc |
| 2 | PaloAlto 9.0 | `admin` | `admin` | vnc |
| 3 | Palo WANOS | `tc` | `ChangeM3` | vnc |
| 4 | Palo WANOS *(variant)* | `wanos` | `wanos` | https |
| 5 | Palo Panorama | `admin` | `admin` | telnet / https |

---

## Check Point

| # | Image Name | Username | Password | Admin Access Console |
|:-:|-----------|:--------:|:--------:|:--------------------:|
| 1 | CheckPoint | `admin` | `admin` | telnet |
| 2 | CheckPoint *(variant)* | `admin` | `Test123` | telnet |

---

## Fortinet

| # | Image Name | Username | Password | Admin Access Console |
|:-:|-----------|:--------:|:--------:|:--------------------:|
| 1 | FortiGate | `admin` | no pass | telnet |
| 2 | FortiMail | `admin` | no pass | telnet |
| 3 | Forti FAZ (FortiAnalyzer) | `admin` | no pass | telnet |
| 4 | Forti FMG (FortiManager) | `admin` | no pass | telnet / https |

---

## Aruba Networks

| # | Image Name | Username | Password | Admin Access Console |
|:-:|-----------|:--------:|:--------:|:--------------------:|
| 1 | Aruba Clearpass | `appadmin` | `eTIPS123` | telnet / https |
| 2 | Aruba Wireless Controller | — | — | vnc / https |

---

## Other Network Vendors

| # | Image Name | Username | Password | Admin Access Console |
|:-:|-----------|:--------:|:--------:|:--------------------:|
| 1 | Infoblox | `admin` | `infoblox` | https |
| 2 | Citrix Netscaler | `nsroot` | `nsroot` | telnet / https |
| 3 | A10 vThunder | `admin` | `a10` | telnet / https |
| 4 | Alcatel / Nokia | `admin` | `admin` | telnet |
| 5 | Arista vEOS | `admin` | no passwd | telnet |
| 6 | Alteon Radware | `radware` | `radware` | telnet |
| 7 | Alteon Radware *(admin)* | `admin` | `admin` | https |
| 8 | Brocade | `root` | no passwd | telnet |
| 9 | Brocade WE | `admin` | `brocade` | https |
| 10 | Brocade *(variant)* | `root` | no pass | telnet / https |
| 11 | VyOS | `vyos` | `vyos` | telnet |
| 12 | ExtremeOS | `admin` | no passwd | telnet |
| 13 | Cumulus | `cumulus` | `CumulusLin` | vnc |
| 14 | Cumulus *(root)* | `root` | `CumulusLinux!` | vnc |
| 15 | Microtik | `admin` | no pass | telnet |
| 16 | Dell OS10 (10.5.2.3) | `admin` | `admin` | telnet |
| 17 | DELL Sonicwall | `root` | no pass | vnc / https |
| 18 | Huawei USG | `admin` | `Admin@123` | vnc / https |
| 19 | Barracuda | `root` | `ngf1r3wall` | vnc / https |
| 20 | Ostinato 0.8 | `root` | `linux` | telnet |
| 21 | Ostinato 0.8 *(tux)* | `tux` | `linux` | telnet |
| 22 | VMware ESx | `root` | `Test123` | vnc / https |
| 23 | VMware ESx *(variant)* | `root` | `VMware1!` | vnc / https |
| 24 | VMware vCenter | `root` | `vmware` | vnc / https |
| 25 | vRiverbed-9 | `admin` | `password` | vnc |
| 26 | Stealth-SMC-7.3.0 | `admin` | `lan411cope` | — |
| 27 | Stealth-SMC-7.3.0 | `root` | `lan1cope` | — |
| 28 | Stealth-SMC-7.3.0 | `sysadmin` | `lan1cope` | — |

---

## Linux Images

| # | Image Name | Username | Password | Admin Access Console |
|:-:|-----------|:--------:|:--------:|:--------------------:|
| 1 | Linux-kali-large-2019.3 | `root` | `toor` | vnc |
| 2 | Linux-centos-8 | `user` | `Test123` | telnet |
| 3 | Linux-debian-10 | `user` | `Test123` | vnc |
| 4 | Linux-ubuntu-18.04-server | `root` | `eve` | vnc |
| 5 | Linux-ubuntu-18.04-desktop | `eve` | `eve` | vnc / rdp |
| 6 | Linux-tinycore-6.4 | — | — | vnc |
| 7 | Linux-ubuntu-mate-20.04 | `user` | `Test123` | vnc / rdp |
| 8 | Linux-ubuntu-srv-16-webmin | `root` | `root` | telnet / https://ip:10000 |
| 9 | Linux Mint 1 | `user` | `Test123` | vnc |
| 10 | Linux Mint r | `root` | `root` | vnc |
| 11 | Linux Ubuntu | `root` | `Test123` | vnc |
| 12 | Linux Ubuntu *(test)* | `test` | `Test123` | vnc |
| 13 | MAC OSX | `user` | `Test123` | vnc |

---

## Windows Images

| # | Image Name | Username | Password | Admin Access Console |
|:-:|-----------|:--------:|:--------:|:--------------------:|
| 1 | Win2008 RD | `administrator` | `Test123` | vnc / rdp |
| 2 | Win2012 RD | `administrator` | `Test123` | vnc / rdp |
| 3 | Win2016 RD | `administrator` | `Test123` | vnc / rdp |
| 4 | Win2019 RD | `administrator` | `Test123` | vnc / rdp |
| 5 | Win7 RDP | `user` | `Test123` | vnc / rdp |
| 6 | Win10 RDP | `user` | `Test123` | vnc / rdp |

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
  <a href="QEMU-PASSWORDS.md">🖥️ EVE-NG Qemu Images Passwords</a>
</div>
