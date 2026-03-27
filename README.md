# ChaseWorksLab Homelab

3x Mac Mini cluster running Proxmox VE, self-hosted services, and ongoing automation experiments.

> Goal: if the house burned down and new hardware showed up, these repos are everything needed to get back to a running state.

---

## Repos

| Repo | Description | Status |
|---|---|---|
| [chaseworkslab-proxmox](https://github.com/chaserbot/chaseworkslab-proxmox) | Proxmox VE post-install, cluster setup, NFS storage | 🔧 Active |

---

## Hardware

| Device | Role |
|---|---|
| Mac Mini x3 (A1347) | Proxmox cluster — pve1, pve2, pve3 |
| Mac Mini x1 (A1347) | NAS / Pegasus DAS host (macOS) |
| Ace Magician CK10 | Jellyfin media server |
| Pegasus DAS | Shared storage via Thunderbolt |
| Luxul ABR-5000 | Router |
| Ubiquiti USW PoE 8 Lite | Switch |

---

## Planned

- `chaseworkslab-network` — DNS, VLANs, Tailscale
- `chaseworkslab-media` — Jellyfin, arr-stack, qBittorrent
- `chaseworkslab-services` — Paperless, Uptime Kuma, n8n, AdGuard
