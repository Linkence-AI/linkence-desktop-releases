# Linkence Desktop

Official Windows downloads for Linkence Desktop.

[Download Linkence Desktop 0.2.0 Beta](https://github.com/Linkence-AI/linkence-desktop-releases/releases/download/desktop-v0.2.0-qa.1/Linkence_Desktop_Computer-Use_QA_0.2.0_x64-setup.exe)

Linkence Desktop gives an existing Linkence workspace a dedicated Windows app. It uses the same account, workspace, permissions, conversations, AI coworkers and agents available in the web application.

## Current release

**Linkence Desktop 0.2.0 Beta**

- Platform: Windows x64
- Installer: `Linkence_Desktop_Computer-Use_QA_0.2.0_x64-setup.exe`
- Size: 4.5 MB
- [Release notes](https://github.com/Linkence-AI/linkence-desktop-releases/releases/tag/desktop-v0.2.0-qa.1)
- [SHA-256 checksum](https://github.com/Linkence-AI/linkence-desktop-releases/blob/main/checksums/desktop-v0.2.0-qa.1.txt)

This Beta adds reliable automatic reconnection and early read-only Local Files and Windows Computer capabilities for approved pilot workspaces. Review the release notes before installation and use the latest published Beta package.

## Get started

1. Download the Windows installer.
2. Run the installer and open Linkence.
3. Enter the full URL for an existing Linkence workspace.
4. Select **Save & Connect**.
5. Sign in with the account already used for that workspace.

A workspace URL normally follows this format:

```text
https://your-company.linkence.ai
```

## Requirements

- Windows x64
- An active Linkence workspace
- A Linkence account with access to that workspace
- An internet connection

## Verify the download

Run this command in PowerShell from the folder containing the installer:

```powershell
(Get-FileHash .\Linkence_Desktop_Computer-Use_QA_0.2.0_x64-setup.exe -Algorithm SHA256).Hash.ToLower()
```

Expected SHA-256:

```text
5088f6ffbabfafdba17d23ae6747c85225bcf0c0e0cf311be6c4e6ffb9a266b1
```

## Releases

- [Latest published release](https://github.com/Linkence-AI/linkence-desktop-releases/releases)
- [Linkence Desktop 0.2.0 Beta](https://github.com/Linkence-AI/linkence-desktop-releases/releases/tag/desktop-v0.2.0-qa.1)
- [Linkence Desktop 0.1.0 Beta](https://github.com/Linkence-AI/linkence-desktop-releases/releases/tag/desktop-v0.1.0)

## Help and security

- [Product support](https://linkence.ai/support)
- [Security at Linkence](https://linkence.ai/security)
- [Linkence website](https://linkence.ai)

Copyright 2026 Linkence Private Limited. All rights reserved.
