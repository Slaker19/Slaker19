<h1 align="center">Alvin Perez</h1>

<p align="center">
  <a href="https://github.com/Slaker19">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=0EA5E9&center=true&vCenter=true&random=false&width=620&lines=T%C3%A9cnico+IT;Entusiasta+del+hardware;Homelab+sobre+Proxmox+VE;Backend+Go+%C2%B7+KVM+%2F+Incus;Creador+de+WebKVM" alt="typing" />
  </a>
</p>

<h3 align="center">Técnico IT · Backend Go · Virtualización (KVM + Incus/LXC) · Homelab sobre Proxmox VE</h3>

<p align="center">
  <a href="https://slaker19.github.io"><img src="https://img.shields.io/badge/Portfolio-slaker19.github.io-0ea5e9?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio" /></a>
  <a href="https://github.com/Slaker19/webkvm"><img src="https://img.shields.io/badge/WebKVM-v0.1.6-10b981?style=for-the-badge&logo=go&logoColor=white" alt="WebKVM" /></a>
  <a href="mailto:alvinpp1908@gmail.com"><img src="https://img.shields.io/badge/Gmail-alvinpp1908%40gmail.com-ea4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" /></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e3a8a,100:0ea5e9&height=120&section=footer" width="100%" />

---

### Sobre mí

- **Técnico IT**: Dedicado profesional y vocacionalmente a la infraestructura, diagnosis de hardware y administración de sistemas Linux en entornos de producción.
- **Entusiasta del hardware & bajo nivel**: Montaje, telemetría térmica, tuning de latencia, topología de memoria y passthrough IOMMU/VFIO optimizado al milímetro.
- **Homelab en producción**: Mi laboratorio y servicios diarios corren 24/7 sobre un nodo **Proxmox VE (Ryzen 7 5700U 8C/16T, 32 GB RAM, almacenamiento híbrido NVMe/SSD/HDD)**, con microsegmentación de red, passthrough PCIe y almacenamiento resiliente.
- **Creador de [WebKVM](https://github.com/Slaker19/webkvm)**: Plataforma autoalojada y ligera que unifica la gestión de máquinas virtuales (**KVM/QEMU via libvirt**) y contenedores de sistema (**Incus/LXC**) bajo un único binario Go con frontend Svelte 5 embebido.

---

### 🚀 Proyecto Principal: WebKVM

> **Gestor web híbrido autoalojado: VMs KVM/QEMU + Contenedores Incus/LXC**

<p align="left">
  <a href="https://github.com/Slaker19/webkvm/releases/tag/v0.1.6"><img src="https://img.shields.io/github/v/release/Slaker19/webkvm?style=flat-square&color=10b981&label=Release" alt="Release" /></a>
  <a href="https://github.com/Slaker19/webkvm/actions/workflows/ci.yml"><img src="https://img.shields.io/github/actions/workflow/status/Slaker19/webkvm/ci.yml?branch=main&style=flat-square&logo=githubactions&logoColor=white&label=CI" alt="CI Status" /></a>
  <a href="https://github.com/Slaker19/webkvm/actions/workflows/codeql.yml"><img src="https://img.shields.io/badge/CodeQL-passing-brightgreen?style=flat-square&logo=github&logoColor=white" alt="CodeQL" /></a>
  <img src="https://img.shields.io/badge/Go-1.24+-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/Svelte-5-FF3E00?style=flat-square&logo=svelte&logoColor=white" alt="Svelte 5" />
  <img src="https://img.shields.io/badge/License-AGPLv3-blue.svg?style=flat-square" alt="License" />
</p>

```bash
# Instalador directo multi-distro (Debian, Ubuntu, Fedora, Arch)
curl -fsSL https://raw.githubusercontent.com/Slaker19/webkvm/main/scripts/install-webkvm.sh | sudo bash
```

- **Binario único de alto rendimiento**: Backend Go compilado con frontend Svelte 5 incrustado (~14 MB binario, ~7-10 MB RAM en reposo), sin dependencias de bases de datos externas ni proxy inverso obligatorio.
- **Gestión híbrida KVM + Incus/LXC**: Ciclo de vida completo para VMs (libvirt) y contenedores del sistema (Incus, sin snaps), terminal serie interactiva y consolas VNC web (noVNC).
- **Redes del Host & Bonding L2**: Creación y gestión segura de bonds (`active-backup`, `802.3ad LACP`, `balance-rr`, `balance-xor`, etc.), persistencia atómica en Netplan (`/etc/netplan/`) y protección contra aislamiento del uplink primario.
- **Almacenamiento unificado**: Soporte para pools locales, ZFS, Software RAID (mdadm), NFS y SMB, migración de discos en caliente, importación OVA y backups en streaming.
- **Seguridad robusta**: Autenticación WebAuthn/Passkeys, 2FA TOTP, RBAC granular con ACL, Security Jail (monitor activo de brute-force SSH con bloqueo automático de IP) y notificaciones multi-canal (SMTP con RFC 2047, Discord, Telegram, Webhooks).
- **Distribución lista para producción**: Paquetes nativos `.deb`/`.rpm`, imagen Docker oficial con `webkvm-cli` integrada e instalador idempotente.

---

### 🛠️ Stack Técnico & Herramientas

<table>
  <tr>
    <td width="20%"><strong>Lenguajes & Backend</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
      <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Bash" />
      <img src="https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white" alt="PowerShell" />
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
    </td>
  </tr>
  <tr>
    <td><strong>Virtualización & Contenedores</strong></td>
    <td>
      <img src="https://img.shields.io/badge/KVM%2FQEMU-FF6600?style=flat-square&logo=qemu&logoColor=white" alt="QEMU/KVM" />
      <img src="https://img.shields.io/badge/libvirt-005C8A?style=flat-square&logo=linux&logoColor=white" alt="libvirt" />
      <img src="https://img.shields.io/badge/Incus%2FLXC-0EA5E9?style=flat-square&logo=linux&logoColor=white" alt="Incus" />
      <img src="https://img.shields.io/badge/Proxmox_VE-E57000?style=flat-square&logo=proxmox&logoColor=white" alt="Proxmox VE" />
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
    </td>
  </tr>
  <tr>
    <td><strong>Sistemas Operativos</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
      <img src="https://img.shields.io/badge/Debian-A81D33?style=flat-square&logo=debian&logoColor=white" alt="Debian" />
      <img src="https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white" alt="Ubuntu" />
      <img src="https://img.shields.io/badge/Fedora-51A2DA?style=flat-square&logo=fedora&logoColor=white" alt="Fedora" />
      <img src="https://img.shields.io/badge/Arch_Linux-1793D1?style=flat-square&logo=archlinux&logoColor=white" alt="Arch Linux" />
      <img src="https://img.shields.io/badge/Windows_Server-0078D6?style=flat-square&logo=windows&logoColor=white" alt="Windows Server" />
    </td>
  </tr>
  <tr>
    <td><strong>Redes, Seguridad & Storage</strong></td>
    <td>
      <img src="https://img.shields.io/badge/nftables-E95420?style=flat-square&logo=linux&logoColor=white" alt="nftables" />
      <img src="https://img.shields.io/badge/Netplan-77216F?style=flat-square&logo=canonical&logoColor=white" alt="Netplan" />
      <img src="https://img.shields.io/badge/WireGuard-88171A?style=flat-square&logo=wireguard&logoColor=white" alt="WireGuard" />
      <img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare" />
      <img src="https://img.shields.io/badge/ZFS-5A6B7C?style=flat-square&logo=linux&logoColor=white" alt="ZFS" />
      <img src="https://img.shields.io/badge/NFS%2FSMB-333333?style=flat-square&logo=linux&logoColor=white" alt="NFS/SMB" />
    </td>
  </tr>
  <tr>
    <td><strong>Frontend & Web</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Svelte_5-FF3E00?style=flat-square&logo=svelte&logoColor=white" alt="Svelte 5" />
      <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite" />
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" />
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3" />
      <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" alt="Nginx" />
    </td>
  </tr>
  <tr>
    <td><strong>Observabilidad & SysAdmin</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" alt="Prometheus" />
      <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" alt="Grafana" />
      <img src="https://img.shields.io/badge/TrueNAS-0095D5?style=flat-square&logo=truenas&logoColor=white" alt="TrueNAS" />
      <img src="https://img.shields.io/badge/Zabbix-D40000?style=flat-square&logo=zabbix&logoColor=white" alt="Zabbix" />
      <img src="https://img.shields.io/badge/Cockpit-008080?style=flat-square&logo=redhat&logoColor=white" alt="Cockpit" />
    </td>
  </tr>
</table>

---

### 🖥️ Entorno de Laboratorio (Homelab PVE 9)

```text
┌────────────────────────────────────────────────────────────────────────┐
│                        HOMELAB PROD NODE (PVE 9)                       │
│      AMD Ryzen 7 5700U (8C/16T @ 15W TDP) · 32 GB DDR4 · NVMe + SSDs   │
├──────────────────────────────────┬─────────────────────────────────────┤
│   MÁQUINAS VIRTUALES (KVM)       │   SERVICIOS AUTOALOJADOS (LXC)      │
│  • ubuntu-server (apt CI / apps) │  • AdGuard / Pi-hole (DNS recursivo)│
│  • fedora-webkvm (dnf CI testbed)│  • Nginx Proxy Manager + Cloudflare │
│  • arch-webkvm (pacman testbed)  │  • Vaultwarden, Immich, Jellyfin    │
│  • Redes: vmbr0, bridges L2, NAT │  • Beszel, Glances, Prometheus node │
└──────────────────────────────────┴─────────────────────────────────────┘
```

---

### 📊 Actividad en GitHub

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Slaker19&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Slaker19 Stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Slaker19&layout=compact&theme=tokyonight&hide_border=true" alt="Top Langs" />
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com?user=Slaker19&theme=tokyonight&hide_border=true" alt="Slaker19 Streak" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Slaker19/Slaker19/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Slaker19/Slaker19/output/github-contribution-grid-snake.svg" />
    <img alt="Snake contribution animation" src="https://raw.githubusercontent.com/Slaker19/Slaker19/output/github-contribution-grid-snake.svg" />
  </picture>
</p>

---

### 📬 Conecta conmigo

<p align="center">
  <a href="mailto:alvinpp1908@gmail.com"><img src="https://img.shields.io/badge/Gmail-alvinpp1908%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://slaker19.github.io"><img src="https://img.shields.io/badge/Portfolio-slaker19.github.io-0ea5e9?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio" /></a>
  <a href="https://github.com/Slaker19/webkvm"><img src="https://img.shields.io/badge/WebKVM-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="WebKVM Repo" /></a>
</p>

<p align="center">
  <sub>⭐ Si te interesa la virtualización ligera y el software de sistemas, no dudes en revisar o apoyar <a href="https://github.com/Slaker19/webkvm"><b>WebKVM</b></a>.</sub>
</p>
