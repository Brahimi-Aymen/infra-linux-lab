# Infra Linux Lab

## Objectif
Construire une infrastructure type PME pour démontrer des compétences SysAdmin / Réseaux / DevOps :
- Linux (Debian/Ubuntu)
- Réseau (NAT/VLAN/DMZ selon environnement)
- Docker / Docker Compose
- Sécurisation (SSH, firewall, durcissement)
- Observabilité (logs, monitoring basique)

## Architecture (high level)
Voir: `docs/architecture.md`  
Schéma: `diagrams/network-topology.png`

## Pré-requis
- VirtualBox / VMware / Proxmox (au choix)
- 2 à 4 VMs Linux (selon scope)
- Git, VS Code

## Quickstart
1. À venir : provision des VMs
2. À venir : configuration réseau
3. À venir : déploiement docker

## Documentation
- Architecture : `docs/architecture.md`
- Runbook (procédures) : `docs/runbook.md`
- Troubleshooting : `docs/troubleshooting.md`

## Roadmap
- [ ] Topologie + plan d’adressage
- [ ] SSH hardening + firewall
- [ ] Docker stack (nginx + app + db)
- [ ] Sauvegardes (cron + rsync)
- [ ] Logs / monitoring basique
