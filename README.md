# Active-Directory.PowerShell

This started in 2024 as a placeholder for an Active Directory bulk-user exercise ([the tutorial I followed](https://www.youtube.com/watch?v=MHsI8hJmggI)).

The full, current version lives in my Projects repo: **[Windows Server and Active Directory lab](https://github.com/ConvictSarge/Projects/blob/main/windows-ad-lab/README.md)**. It covers:

- an unattended Windows Server 2025 install on Proxmox (VirtIO drivers, QEMU guest agent, no console clicking)
- domain controller promotion and a scripted, idempotent directory build: OUs per department, groups, admin tiering, a fine-grained password policy and two GPOs
- PowerShell for bulk onboarding from CSV, safe offboarding (nothing deleted, group memberships saved first) and an account hygiene report
- real outputs from runs against the live lab domain, and the bugs that testing found and fixed
