# Geo Prospector Established Edition

Geo Prospector is a Windows desktop application for discovering, collecting, and exporting business prospect data by category and location.

> This repository distributes the official Windows installer and the application update manifest.

## Current Release

| Property | Value |
|---|---|
| Version | `6.7.23.1` |
| Release date | `2026-07-24` |
| Platform | Windows 10/11, 64-bit |
| Installer | `GeoProspectorSetup.exe` |
| File size | `264037836 bytes` |
| SHA-256 | `6785F71605AB56C9ACAD611AFF58FD598FABD23230A0AEF02420937C49F7840D` |

- [Download the latest installer](https://github.com/visi-digital-internasional/geo-prospector-update/releases/download/v6.7.23.1/GeoProspectorSetup.exe)
- [View the release notes](https://github.com/visi-digital-internasional/geo-prospector-update/releases/tag/v6.7.23.1)
- [Open the documentation](https://visi-digital-internasional.gitbook.io/geo-prospector)
- [Visit the official website](https://geoprospector.id)

## What Is New in 6.7.23.1

- Canonical category validation for B2B Finder.
- License-based B2B limits: Free 50, Starter 500, Business 1,000, Enterprise 5,000.
- Graceful Stop now preserves partial results, history, and correct credit usage.
- Email Finder supports up to 5,000 domains in both UI and backend.
- Live Email Finder ETA and corrected elapsed-time display.
- B2B ETA scales through 5,000 results and uses a stable warm-up phase.
- English and mojibake audit passed.
- Self-contained runtime and signed security anchor included.

## Main Features

- B2B prospect discovery by canonical category and location
- Single-category and multi-category searches
- Country, province, and city selection
- Saved Categories
- Persistent duplicate filtering
- Email Finder with manual and CSV website input
- CSV, Excel, TXT, and JSON export
- Device-bound license activation
- Remote membership, plan, and credit controls
- Automatic application updates
- Signed security anchor and build-integrity verification

## Installation

1. Download `GeoProspectorSetup.exe`.
2. Run the installer.
3. Complete the installation wizard.
4. Open Geo Prospector.
5. Activate the application with the license token supplied by Customer Support.

## Installer Verification

```powershell
Get-FileHash `
  -LiteralPath ".\GeoProspectorSetup.exe" `
  -Algorithm SHA256
```

Expected SHA-256:

```text
6785F71605AB56C9ACAD611AFF58FD598FABD23230A0AEF02420937C49F7840D
```

## Update Manifest

The application reads the public update manifest from:

`version.json`

Current download URL:

`https://github.com/visi-digital-internasional/geo-prospector-update/releases/download/v6.7.23.1/GeoProspectorSetup.exe`

## Build Security

Geo Prospector Established Edition uses:

- Ed25519 public-key verification
- Signed security anchor manifest
- Build-integrity verification
- Device-bound license activation
- Clock rollback protection

Private signing material is not included in the application or installer.

## Support

Use the **Send Activation Request** action inside the application to contact Customer Support.

## Publisher

Visi Digital Internasional

Copyright 2026 Visi Digital Internasional. All rights reserved.