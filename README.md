<!-- ═══════════════ HEADER ═══════════════ -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=220&section=header&text=Jonathan%20Della%20Santina&fontSize=44&fontColor=ffffff&fontAlignY=38&desc=Systems%20%26%20Network%20Engineer&descSize=20&descAlignY=60&animation=fadeIn" alt="Header" width="100%" />

<a href="https://github.com/JonathanDS30">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3500&pause=1000&color=2DD4BF&center=true&vCenter=true&width=640&lines=Network+segmentation+%26+perimeter+security;Multi-site+VPN+architectures+(IPsec);Infrastructure+reliability+(MCO);Monitoring%2C+backup+%26+automation" alt="Typing SVG" />
</a>

<br/>

![Role](https://img.shields.io/badge/Role-Systems_%26_Networks_Engineer-0f766e?style=for-the-badge)
![Company](https://img.shields.io/badge/@-E--MSN-1e293b?style=for-the-badge)
![Location](https://img.shields.io/badge/Based_in-Occitanie,_France-2563eb?style=for-the-badge)

</div>

---

## 👋 About me

I design, secure and keep **multi-site infrastructures** running.
My day-to-day sits at the crossroads of **networks**, **systems** and **security**: firewalls, VPNs, Active Directory, Microsoft 365, monitoring and backups.

> 💡 My approach: understand *why* it works before touching *how*. Evidence over assumptions, documentation over memory.

<table>
<tr>
<td width="50%" valign="top">

### 🎯 Focus areas
- 🔥 **Perimeter security** & firewalling
- 🌐 **Network segmentation** (VLAN, inter-VLAN policies)
- 🔐 **Site-to-site VPN** architectures (IPsec)
- ♻️ **Infrastructure reliability** (MCO)
- ☁️ **Microsoft 365 / Entra ID** environments

</td>
<td width="50%" valign="top">

### 🎓 Background
- 🏫 **MSc in Computer Science & Information Systems**
  EPSI Montpellier
- 💼 **Systems & Networks Engineer** @ E-MSN
- 🧭 Work-study track: field experience from day one

</td>
</tr>
</table>

---

## 🧰 Tech stack

<div align="center">

### 🌐 Network & Security
![Fortinet](https://img.shields.io/badge/Fortinet-EE3124?style=for-the-badge&logo=fortinet&logoColor=white)
![Stormshield](https://img.shields.io/badge/Stormshield-002D62?style=for-the-badge)
![Cisco](https://img.shields.io/badge/Cisco-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)
![pfSense](https://img.shields.io/badge/pfSense-212121?style=for-the-badge&logo=pfsense&logoColor=white)
![IPsec](https://img.shields.io/badge/VPN-IPsec-2563eb?style=for-the-badge)

### 🖥️ Systems & Cloud
![Active Directory](https://img.shields.io/badge/Active_Directory-0078D4?style=for-the-badge)
![Microsoft 365](https://img.shields.io/badge/Microsoft_365-D83B01?style=for-the-badge)
![Entra ID](https://img.shields.io/badge/Entra_ID-0078D4?style=for-the-badge)
![Intune](https://img.shields.io/badge/Intune-008AD7?style=for-the-badge)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Debian](https://img.shields.io/badge/Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white)

### ⚙️ Automation & IaC
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)

### 📈 Monitoring, Backup & Telecom
![Zabbix](https://img.shields.io/badge/Zabbix-CC0000?style=for-the-badge&logo=zabbix&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Veeam](https://img.shields.io/badge/Veeam-00B336?style=for-the-badge)
![Asterisk](https://img.shields.io/badge/Asterisk-F38020?style=for-the-badge)

</div>

---

## 🗺️ What I build: a multi-site reference design

```mermaid
flowchart LR
    subgraph A["🏢 Site A — Headquarters"]
        direction TB
        FWA["🔥 Firewall"]
        SRVA["🖥️ AD · DNS · Monitoring"]
        FWA --- SRVA
    end

    subgraph B["🏬 Site B — Branch"]
        direction TB
        FWB["🔥 Firewall"]
        SRVB["🖥️ AD · Backup repository"]
        FWB --- SRVB
    end

    FWA <==>|"🔐 IPsec site-to-site"| FWB
```

---

## 🚧 Currently exploring

<!-- Keep only what you are really working on. -->

| 🔬 Topic | 🎯 Goal |
| :-- | :-- |
| **FortiGate** | VLAN segmentation, policy design, `debug flow` troubleshooting |
| **IPsec & dynamic routing** | Site-to-site tunnels, OSPF over VPN |
| **Zabbix** | SNMP / agent monitoring with meaningful alerting |
| **Veeam Backup & Replication** | 3-2-1 strategy, off-site copy, *tested* restores |

> 🧪 Homelab: Proxmox + FortiGate + a fictional two-site company, built to break things, diagnose them and document the fix.

---

## 📊 GitHub stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=JonathanDS30&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=2dd4bf&icon_color=2dd4bf" alt="GitHub stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=JonathanDS30&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=2dd4bf&layout=compact" alt="Top languages" />

</div>

---

## 📫 Let's connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jonathan-della-santina/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jonathan.dellasantina433@gmail.com)

</div>

---

## 🌟 Beyond tech

<div align="center">

🎮 **Esport** — CS2 & Team Vitality &nbsp;|&nbsp; 🏋️ **Fitness** &nbsp;|&nbsp; 📘 **Continuous learning**

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=110&section=footer" alt="Footer" width="100%" />
