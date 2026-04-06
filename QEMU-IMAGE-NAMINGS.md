<div align="center">

# 📁 EVE-NG Qemu Image Namings

**Correct Folder Names and Image File Names for EVE-NG Qemu Appliances**

[![Platform](https://img.shields.io/badge/Platform-EVE--NG-blue?style=flat-square)](https://www.eve-ng.net)
[![Type](https://img.shields.io/badge/Type-Qemu%20Naming%20Reference-orange?style=flat-square)](#)
[![Status](https://img.shields.io/badge/status-maintained-brightgreen?style=flat-square)](#)

</div>

---

## Overview

EVE-NG stores Qemu images in a specific directory with strict naming conventions.  
Following these conventions ensures images are detected and loaded correctly.

**Base path for all Qemu images:**

```
/opt/unetlab/addons/qemu/
```

**Folder naming rule:**

Each image folder name starts with the **prefix** listed in the table below, followed by a dash (`-`) and then your chosen image name and version.

```
<prefix>-<name>-<version>/
```

**Examples:**

```
/opt/unetlab/addons/qemu/firepower6-FTD-6.2.1/
/opt/unetlab/addons/qemu/acs-5.8.1.4/
```

**Inside each folder**, place the HDD image with the exact filename specified in the table:

```
/opt/unetlab/addons/qemu/acs-5.8.1.4/hda.qcow2
```

> **Note:** If an image has more than one HDD, the last letter increments alphabetically:  
> `hda`, `hdb`, `hdc` … or `virtioa`, `virtiob`, `virtioc` …

---

## Supported HDD Image Formats

| Format Pattern | Example Filename |
|----------------|:----------------:|
| `lsi[a-z]+.qcow2` | `lsia.qcow2` |
| `hd[a-z]+.qcow2` | `hda.qcow2` |
| `virtide[a-z]+.qcow2` | `virtidea.qcow2` |
| `virtio[a-z]+.qcow2` | `virtioa.qcow2` |
| `scsi[a-z]+.qcow2` | `scsia.qcow2` |
| `sata[a-z]+.qcow2` | `sataa.qcow2` |
| `megasas[a-z]+.qcow2` | `megasasa.qcow2` |

---

## Qemu Image Naming Reference

| # | Folder Prefix | Vendor / Product | Image File(s) |
|:-:|:-------------:|-----------------|:-------------:|
| 1 | `a10-` | A10 vThunder | `hda.qcow2` |
| 2 | `acs-` | Cisco ACS | `hda.qcow2` |
| 3 | `alteon-` | Radware Alteon | `virtioa.qcow2` |
| 4 | `ampcloud-` | Ampcloud Private | `hda.qcow2`, `hdb.qcow2`, `hdc.qcow2` |
| 5 | `asa-` | Cisco ASA (ported) | `hda.qcow2` |
| 6 | `asav-` | Cisco ASAv | `virtioa.qcow2` |
| 7 | `aruba-` | Aruba Virtual Mobility Controller | `hda.qcow2`, `hdb.qcow2` |
| 8 | `arubacx-` | Aruba CX Switch | `virtioa.qcow2` |
| 9 | `barracuda-` | Barracuda FW | `hda.qcow2` |
| 10 | `bigip-` | F5 BIG-IP | `virtioa.qcow2`, `virtiob.qcow2` |
| 11 | `brocadevadx-` | Brocade vADX | `virtioa.qcow2` |
| 12 | `cda-` | Cisco CDA | `hda.qcow2` |
| 13 | `cips-` | Cisco IPS | `hda.qcow2`, `hdb.qcow2` |
| 14 | `clearpass-` | Aruba ClearPass | `hda.qcow2`, `hdb.qcow2` |
| 15 | `coeus-` | Cisco WSA (coeus) | `virtioa.qcow2` |
| 16 | `cpsg-` | Check Point | `hda.qcow2` |
| 17 | `csr1000v-` | Cisco CSR v1000 3.x | `virtioa.qcow2` |
| 18 | `csr1000vng-` | Cisco CSR v1000 16.x / 17.x | `virtioa.qcow2` |
| 19 | `csr1000vng-` | Cisco CSR v1000 16.x SD-WAN | `virtioa.qcow2` |
| 20 | `cucm-` | Cisco CUCM | `virtioa.qcow2` |
| 21 | `cumulus-` | Cumulus Linux | `virtioa.qcow2` |
| 22 | `esxi-` | VMware ESXi | `hda.qcow2`, `hdb.qcow2`, `hdc.qcow2` … |
| 23 | `extremexos-` | ExtremeOS | `sataa.qcow2` |
| 24 | `firepower-` | Cisco FirePower 5.4 NGIPS | `scsia.qcow2` |
| 25 | `firepower-` | Cisco FirePower 5.4 FMC | `scsia.qcow2` |
| 26 | `firepower6-` | Cisco FirePower 6.x NGIPS | `sataa.qcow2` |
| 27 | `firepower6-` | Cisco FirePower 6.x FMC | `virtioa.qcow2` |
| 28 | `firepower6-` | Cisco FirePower 6.x FTD | `virtioa.qcow2` |
| 29 | `fortinet-` | Fortinet FW | `virtioa.qcow2` |
| 30 | `fortinet-` | Fortinet SGT | `virtioa.qcow2` |
| 31 | `fortinet-` | Fortinet Mail | `virtioa.qcow2`, `virtiob.qcow2` |
| 32 | `fortinet-` | Fortinet Manager | `virtioa.qcow2` |
| 33 | `hpvsr-` | HP Virtual Router | `hda.qcow2` |
| 34 | `huaweiar1k-` | Huawei AR1000v | `virtioa.qcow2` |
| 35 | `huaweiusg6kv-` | Huawei USG6000v | `hda.qcow2` |
| 36 | `infoblox-` | Infoblox | `virtioa.qcow2` |
| 37 | `ise-` | Cisco ISE 1.x | `hda.qcow2` |
| 38 | `ise-` | Cisco ISE 2.x | `virtioa.qcow2` |
| 39 | `jspace-` | Junos Space | `virtioa.qcow2` |
| 40 | `junipervrr-` | Juniper vRR | `virtioa.qcow2` |
| 41 | `kerio-` | Kerio Control Firewall | `sataa.qcow2` |
| 42 | `linux-` | Any Linux | `virtioa.qcow2` |
| 43 | `mikrotik-` | Mikrotik Router | `hda.qcow2` |
| 44 | `nsvpx-` | Citrix Netscaler | `virtioa.qcow2` |
| 45 | `nsx-` | VMware NSX | `hda.qcow2` |
| 46 | `nxosv9k-` | Cisco NX9K Nexus (SATA best perf.) | `sataa.qcow2` |
| 47 | `olive-` | Juniper Olive | `hda.qcow2` |
| 48 | `ostinato-` | Ostinato Traffic Generator | `hda.qcow2` |
| 49 | `osx-` | Apple macOS | `hda.qcow2` + `kernel.img` |
| 50 | `paloalto-` | Palo Alto FW | `virtioa.qcow2` |
| 51 | `panorama-` | Palo Alto Panorama | `virtioa.qcow2`, `virtiob.qcow2` |
| 52 | `pfsense-` | pfSense FW | `virtioa.qcow2` |
| 53 | `phoebe-` | Cisco ESA (phoebe) | `virtioa.qcow2` |
| 54 | `prime-` | Cisco Prime Infra | `virtioa.qcow2` |
| 55 | `pulse-` | Pulse Secure | `virtioa.qcow2` |
| 56 | `riverbed-` | vRiverbed | `virtioa.qcow2`, `virtiob.qcow2` |
| 57 | `scrutinizer-` | Plixer Scrutinizer Netflow | `virtioa.qcow2` |
| 58 | `silveredge-` | Silver Peak Edge | `hda.qcow2` |
| 59 | `silverorch-` | Silver Peak Orchestrator | `hda.qcow2` |
| 60 | `sonicwall-` | Dell SonicWall FW | `sataa.qcow2` |
| 61 | `sourcefire-` | Sourcefire NGIPS | `scsia.qcow2` |
| 62 | `stealth-` | Cisco StealthWatch | `hda.qcow2` |
| 63 | `sterra-` | S-terra VPN | `hda.qcow2` |
| 64 | `sterra-` | S-terra Gate | `virtioa.qcow2` |
| 65 | `timos-` | Alcatel-Lucent Timos | `hda.qcow2` |
| 66 | `timoscpm-` | Nokia Timos 19 CPM | `virtidea.qcow2` |
| 67 | `timosiom-` | Nokia Timos 19 IOM | `virtidea.qcow2` |
| 68 | `titanium-` | Cisco NXOS Titanium | `virtioa.qcow2` |
| 69 | `vcenter-` | VMware vCenter | `sataa.qcow2` (12 GB), `satab.qcow2` (1.8 GB), `satac.qcow2` (15 GB), `satad.qcow2` (25 GB), `satae.qcow2` (25 GB), `sataf.qcow2` (10 GB), `satag.qcow2` (10 GB), `satah.qcow2` (15 GB), `satai.qcow2` (10 GB), `sataj.qcow2` (1.0 GB), `satak.qcow2` (10 GB), `satal.qcow2` (10 GB), `satam.qcow2` (100 GB) |
| 70 | `veos-` | Arista Switch | `hda.qcow2`, `cdrom.iso` |
| 71 | `veloedge-` | Velocloud Edge | `virtioa.qcow2` |
| 72 | `velogw-` | Velocloud Gateway | `virtioa.qcow2` |
| 73 | `veloorch-` | Velocloud Orchestrator | `virtioa.qcow2`, `virtiob.qcow2`, `virtioc.qcow2` |
| 74 | `versaana-` | Versa Networks Analyzer | `virtioa.qcow2` |
| 75 | `versadir-` | Versa Networks Director | `virtioa.qcow2` |
| 76 | `versavnf-` | Versa Networks FlexVNF Edge | `virtioa.qcow2` |
| 77 | `vios-` | Cisco L3 vIOS Router | `virtioa.qcow2` |
| 78 | `viosl2-` | Cisco L2 vIOS Switch | `virtioa.qcow2` |
| 79 | `vmx-` | Juniper vMX Router | `hda.qcow2` |
| 80 | `vmxvcp-` | Juniper vMX-VCP | `virtioa.qcow2`, `virtiob.qcow2`, `virtioc.qcow2` |
| 81 | `vmxvfp-` | Juniper vMX-VFP | `virtioa.qcow2` |
| 82 | `vnam-` | Cisco VNAM | `hda.qcow2` |
| 83 | `vqfxpfe-` | Juniper vQFX-PFE | `hda.qcow2` |
| 84 | `vqfxre-` | Juniper vQFX-RE | `hda.qcow2` |
| 85 | `vsrx-` | Juniper vSRX 12.1 FW/Router | `virtioa.qcow2` |
| 86 | `vsrxng-` | Juniper vSRX v15.x FW/Router | `virtioa.qcow2` |
| 87 | `vtbond-` | Cisco Viptela vBond | `virtioa.qcow2` |
| 88 | `vtedge-` | Cisco Viptela vEdge | `virtioa.qcow2` |
| 89 | `vtmgmt-` | Cisco Viptela vManage | `virtioa.qcow2`, `virtiob.qcow2` |
| 90 | `vtsmart-` | Cisco Viptela vSmart | `virtioa.qcow2` |
| 91 | `vwaas-` | Cisco WAAS | `virtioa.qcow2`, `virtiob.qcow2`, `virtioc.qcow2` |
| 92 | `vwlc-` | Cisco vWLC WiFi Controller | `megasasa.qcow2` |
| 93 | `vyos-` | VyOS Router | `virtioa.qcow2` |
| 94 | `win-` | Windows (non-server editions) | `hda.qcow2` or `virtioa.qcow2` |
| 95 | `winserver-` | Windows Server Editions | `hda.qcow2` or `virtioa.qcow2` |
| 96 | `xrv-` | Cisco XRv Router | `hda.qcow2` |
| 97 | `xrv9k-` | Cisco XRv 9000 Router | `virtioa.qcow2` |

---

## Acknowledgments

Naming conventions sourced from the official EVE-NG documentation and publicly available community resources, including:

- <a href="https://github.com/hegdepavankumar/Cisco-Images-for-GNS3-and-EVE-NG" target="_blank"><strong>hegdepavankumar/Cisco-Images-for-GNS3-and-EVE-NG</strong></a>
- <a href="https://www.eve-ng.net/index.php/documentation/" target="_blank">EVE-NG Official Documentation</a>

> **Disclaimer:** This reference is provided for educational and lab purposes only.  
> All vendor software and trademarks belong to their respective owners.

---

<div align="center">
  <a href="README.md">← Back to Main README</a>
  &nbsp;|&nbsp;
  <a href="ALL-PASSWORDS.md">🔑 All Images Passwords</a>
  &nbsp;|&nbsp;
  <a href="QEMU-PASSWORDS.md">🖥️ EVE-NG Qemu Passwords</a>
</div>
