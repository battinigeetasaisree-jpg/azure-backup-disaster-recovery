# Azure Backup & Disaster Recovery Project

This project demonstrates implementation of Azure VM backup, recovery validation, and disaster recovery testing using Recovery Services Vault.

---

## Project Overview

In this project, I implemented:

- Recovery Services Vault creation
- Enhanced Backup Policy configuration
- VM backup enablement
- On-demand backup execution
- Recovery point validation
- Restore VM from backup
- Application validation after restore

---

## Architecture Components

- Resource Group: rg-prod-infra
- Virtual Machine: vm-web-02
- Recovery Services Vault: rsv-prod-backup
- Backup Policy: Enhanced (Multiple daily backups)
- Retention: 30 days

---

## Disaster Recovery Validation

The VM was successfully restored using the latest recovery point, and application services (NGINX) were verified post-restore.

---

## Skills Demonstrated

- Azure Backup
- Recovery Services Vault
- Backup Policy Design
- Disaster Recovery Testing
- RPO & RTO Understanding
- Business Continuity Planning
- Azure Infrastructure Protection


