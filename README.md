# Self Hosted Gaming

Self Hosted Gaming is a developing web-based management application for dedicated game servers running on user-owned Windows computers. Its initial focus is ARK: Survival Ascended (ASA).

**This is a public project-information repository. The application implementation is currently private; this repository does not contain its source code or an installer.**

Website: https://selfhostedgaming.duckdns.org/

## Project scope

The application provides server status and lifecycle controls, reviewed settings and mod configuration, backups, and same-computer ASA cluster management. The website uses authenticated accounts and permissions, with a connector on the hosting computer. Wider distribution and multi-computer clusters remain development goals.

## Intended CurseForge API use

We are applying for third-party API access to the ARK: Survival Ascended catalogue. The planned catalogue workflow is to:

- Search ASA mods using the official API.
- Display project names, descriptions, project IDs and links to official CurseForge project pages.
- Let an authorized user add a project ID to a draft server mod list and review changes before saving.

The current catalogue integration requests metadata only. It does not mirror, rehost or redistribute mod files, or bypass premium ownership and platform restrictions. Game-managed mod installation is separate from catalogue search. API access has not yet been approved or verified with a live key.

Initially the project serves a small private group. Wider availability and paid features may be considered later; no billing plans are currently implemented.

## Private information

This repository contains project information only. It does not include API keys, passwords, account records, game saves, backups or private deployment configuration.
