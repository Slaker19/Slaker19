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

- **Técnico IT** — me dedico a esto y también lo vivo como afición.
- Entusiasta del hardware: montaje, benchmarks y exprimir cada componente al máximo.
- Mi laboratorio completo corre sobre **Proxmox VE** (el host donde trabajo a diario): VMs, LXC, passthrough y ZFS.
- Desarrollo **[WebKVM](https://github.com/Slaker19/webkvm)**: gestor híbrido nativo de **VMs (KVM)** y **contenedores (Incus/LXC)** con interfaz web — un solo binario Go con el frontend embebido.
- **Incus** (fork comunitario de LXD) como backend de contenedores: paquetes nativos en todas las distros, cero snap, y compatible con los LXD ya instalados.
- Docker soportado como alternativa al instalador nativo (imagen publicada, socket del host).
- Obsesionado con que funcione en todas partes: probado en Ubuntu, Fedora y Arch con instalador one-liner multi-distro.
- Con ojo en la seguridad: HTTPS nativo con cert autofirmado, RBAC, firewall nftables por VM, CodeQL limpio, CI en verde.

---

### Proyecto estrella

**[WebKVM](https://github.com/Slaker19/webkvm)** — Gestor híbrido nativo: VMs KVM + contenedores Incus/LXC con UI web

![Go](https://img.shields.io/badge/Go-1.26-00ADD8?logo=go&logoColor=white)
![Svelte](https://img.shields.io/badge/Svelte_5-FF3E00?logo=svelte&logoColor=white)
![CI](https://img.shields.io/badge/CI-passing-brightgreen)
![CodeQL](https://img.shields.io/badge/CodeQL-clean-success)
![License](https://img.shields.io/badge/License-AGPLv3%20%2F%20Commercial-blue)

```bash
curl -fsSL https://raw.githubusercontent.com/Slaker19/webkvm/main/scripts/install-webkvm.sh | sudo bash
```

- Instalador one-liner para Debian/Ubuntu, Fedora/RHEL y Arch (paquetes nativos, cero snap)
- HTTPS directo del backend (cert autofirmado, SAN IP + dominio) — sin reverse proxy obligatorio
- **Híbrido KVM + Incus/LXC**: vista unificada con badge de tipo, filtro por instancia, creación desde imágenes oficiales con cloud-init, redimensionar disco raíz, interfaces y métricas en vivo
- Redes NAT + bridge macvlan (los mismos bridges de libvirt para VMs y contenedores), snapshots, backups en streaming, RBAC y auditoría
- ~14 MB de binario, ~7 MB de RAM en reposo

---

### Stack

<div>

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Svelte](https://img.shields.io/badge/Svelte_5-FF3E00?style=for-the-badge&logo=svelte&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![QEMU/KVM](https://img.shields.io/badge/QEMU%2FKVM-FF6600?style=for-the-badge&logo=qemu&logoColor=white)
![Incus/LXC](https://img.shields.io/badge/Incus%2FLXC-0EA5E9?style=for-the-badge&logo=linux&logoColor=white)
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
Si WebKVM te resulta útil, deja una estrella en el repo.
