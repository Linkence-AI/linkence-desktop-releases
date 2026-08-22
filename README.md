# Linkence Desktop

Official Windows downloads for Linkence Desktop.

[Download Linkence Desktop 0.1.0 Beta](https://github.com/Linkence-AI/linkence-desktop-releases/releases/download/desktop-v0.1.0/Linkence_0.1.0_x64-setup.exe)

Linkence Desktop gives an existing Linkence workspace a dedicated Windows app. It uses the same account, workspace, permissions, conversations, AI coworkers and agents available in the web application.

## Current release

**Linkence Desktop 0.1.0 Beta**

- Platform: Windows x64
- Installer: `Linkence_0.1.0_x64-setup.exe`
- Size: 3.8 MB
- [Release notes](https://github.com/Linkence-AI/linkence-desktop-releases/releases/tag/desktop-v0.1.0)
- [SHA-256 checksum](https://github.com/Linkence-AI/linkence-desktop-releases/blob/main/checksums/desktop-v0.1.0.txt)

Beta releases provide early access to the desktop experience. Review the release notes before installation and use the latest published Beta package.

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
(Get-FileHash .\Linkence_0.1.0_x64-setup.exe -Algorithm SHA256).Hash.ToLower()
```

Expected SHA-256:

```text
f1c5236605502bc886100a867b2cf2be90a0a14505975dfd020ddd7f7eb7ddb8
```

## Releases

- [Latest published release](https://github.com/Linkence-AI/linkence-desktop-releases/releases)
- [Linkence Desktop 0.1.0 Beta](https://github.com/Linkence-AI/linkence-desktop-releases/releases/tag/desktop-v0.1.0)

## Help and security

- [Product support](https://linkence.ai/support)
- [Security at Linkence](https://linkence.ai/security)
- [Linkence website](https://linkence.ai)

Copyright 2026 Linkence Private Limited. All rights reserved.
