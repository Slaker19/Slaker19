<h1 align="center">Alvin Perez</h1>

<p align="center">
  <a href="https://github.com/Slaker19">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=0EA5E9&center=true&vCenter=true&random=false&width=620&lines=T%C3%A9cnico+IT;Entusiasta+del+hardware;Homelab+sobre+Proxmox+VE;Backend+Go+%C2%B7+KVM+%2F+Incus;Creador+de+WebKVM" alt="typing" />
  </a>
</p>

<h3 align="center">Técnico IT · Backend Go · Virtualización (KVM + Incus/LXC) · Homelab sobre Proxmox VE</h3>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e3a8a,100:0ea5e9&height=120&section=footer" width="100%" />

---

### Sobre mí

- **Técnico IT** — me dedico a la infraestructura y la administración de sistemas tanto a nivel profesional como por pasión personal.
- Entusiasta del hardware: montaje, arquitectura, benchmarks y optimización al milímetro.
- Mi entorno diario corre sobre **Proxmox VE**: hipervisor de producción para virtualización, contenedores LXC, passthrough IOMMU y almacenamiento ZFS/Btrfs.
- Creador y mantenedor de **[WebKVM](https://github.com/Slaker19/webkvm)**: panel web autoalojado de alto rendimiento para gestionar un host de virtualización Linux, distribuido como un único binario Go con el frontend Svelte embebido.
- Soporte híbrido nativo: **KVM/QEMU** para máquinas virtuales y **Incus** (el fork comunitario de LXD) para contenedores ligeros con paquetes nativos y cero dependencias de snap.
- Obsesión por la reproducibilidad: probado en Ubuntu, Fedora y Arch con instalador *one-liner* multidistro, soporte de paquetes deb/rpm, imagen Docker y CLI nativa.
- Enfoque riguroso en seguridad: HTTPS nativo con certificados autofirmados automáticos (SAN IP/DNS), RBAC granular, autenticación 2FA/TOTP, cortafuegos nftables por VM y suite de CI 100% verificada.

---

### Proyecto estrella

**[WebKVM](https://github.com/Slaker19/webkvm)** — Gestor web híbrido y autoalojado: VMs KVM + contenedores Incus/LXC

[![CI](https://github.com/Slaker19/webkvm/actions/workflows/ci.yml/badge.svg)](https://github.com/Slaker19/webkvm/actions/workflows/ci.yml)
[![Go](https://img.shields.io/badge/Go-1.26-00ADD8?logo=go&logoColor=white)](https://golang.org)
[![Svelte](https://img.shields.io/badge/Svelte_5-FF3E00?logo=svelte&logoColor=white)](https://svelte.dev)
[![License](https://img.shields.io/badge/License-AGPLv3-blue.svg)](https://github.com/Slaker19/webkvm/blob/main/LICENSE)
[![i18n](https://img.shields.io/badge/i18n-es%20%7C%20en%20%7C%20ca-informational)](https://github.com/Slaker19/webkvm)

```bash
curl -fsSL https://raw.githubusercontent.com/Slaker19/webkvm/main/scripts/install-webkvm.sh | sudo bash
```

- **Arquitectura de binario único**: Backend Go compilado con frontend Svelte 5 incrustado (~14 MB de binario, ~7 MB de RAM en reposo), sin bases de datos externas ni reverse proxy obligatorio.
- **Gestión híbrida KVM + Incus/LXC**: Ciclo de vida completo de VMs y contenedores, consolas VNC (noVNC) y terminal serie interactiva en el navegador, métricas en tiempo real y cloud-init studio.
- **Almacenamiento avanzado**: Pools locales y remotos (NFS, SMB) con propósitos dedicados, migración de discos en caliente, importación/exportación de OVA y vzdump.
- **Passthrough de hardware**: Asignación de GPUs, tarjetas de red y dispositivos USB con validación previa de aislamiento IOMMU/VFIO.
- **Redes y seguridad**: Puentes Linux unificados, redes NAT/aisladas, firewall nftables por VM, control de accesos RBAC con ACL por recurso, 2FA/TOTP, tokens de API y auditoría estructurada.
- **Distribución multidistro**: Instalador idempotente con rollback automático para Debian/Ubuntu, Fedora/RHEL y Arch, contenedor Docker oficial, paquetes `.deb`/`.rpm` y cliente de línea de comandos (`webkvm-cli`).

---

### Stack técnico

<div>

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Svelte](https://img.shields.io/badge/Svelte_5-FF3E00?style=for-the-badge&logo=svelte&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![QEMU/KVM](https://img.shields.io/badge/QEMU%2FKVM-FF6600?style=for-the-badge&logo=qemu&logoColor=white)
![Incus/LXC](https://img.shields.io/badge/Incus%2FLXC-0EA5E9?style=for-the-badge&logo=linux&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox_VE-E57000?style=for-the-badge&logo=proxmox&logoColor=white)

</div>

---

### Estadísticas

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Slaker19&show_icons=true&theme=tokyonight&hide_border=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Slaker19&layout=compact&theme=tokyonight&hide_border=true" />
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com?user=Slaker19&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Slaker19/Slaker19/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Slaker19/Slaker19/output/github-contribution-grid-snake.svg" />
    <img alt="snake" src="https://raw.githubusercontent.com/Slaker19/Slaker19/output/github-contribution-grid-snake.svg" />
  </picture>
</p>

---

### Contacto

<a href="mailto:alvinpp1908@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://slaker19.github.io"><img src="https://img.shields.io/badge/Portfolio-slaker19.github.io-0ea5e9?style=for-the-badge&logo=githubpages&logoColor=white" /></a>
<a href="https://github.com/Slaker19/webkvm"><img src="https://img.shields.io/badge/WebKVM-repo-181717?style=for-the-badge&logo=github&logoColor=white" /></a>

---
*Si WebKVM te resulta útil, apoya el proyecto dejando una ⭐ en el [repositorio](https://github.com/Slaker19/webkvm).*
