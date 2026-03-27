# Hey, I'm Chase 👋

Event production by day. Homelab, self-hosting, and automation by night.

I document my homelab build publicly so others can use the scripts and
learn from what works (and what doesn't).

---

## 🖥 The Lab

3-node Proxmox cluster on Mac Mini A1347s, a macOS NAS brain with a Pegasus DAS,
Pi-hole for DNS, and a growing stack of self-hosted services.

Long-term goals: reproducible infrastructure, everything in Git,
wipe-and-restore any machine in under an hour.

---

## 📦 Public Repos

| Repo | What it is |
|------|------------|
| [chaseworkslab-proxmox](https://github.com/chaserbot/chaseworkslab-proxmox) | Proxmox VE install scripts for Mac Mini A1347 hardware |
| chaseworkslab-docker *(coming soon)* | Docker Compose stacks for self-hosted services |
| chaseworkslab-dns *(coming soon)* | Pi-hole / LXC DNS configs |

---

## 🔧 Current Stack

- **Hypervisor:** Proxmox VE
- **Storage:** Pegasus DAS via macOS SMB/NFS
- **DNS:** Pi-hole
- **Remote access:** Tailscale *(in progress)*
- **Automation:** n8n *(in progress)*
- **Media:** Jellyfin, Audiobookshelf
- **Arr stack:** Sonarr, Radarr, qBittorrent, Overseerr
- **Monitoring:** Uptime Kuma
- **Docs:** Paperless-ngx

---

*Scripts are written to be curl-friendly and reusable on identical hardware.
Use at your own risk, PRs welcome.*
