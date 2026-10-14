<!-- jr-brand:start -->
<p align="center">
  <a href="https://jannikreinhard.com/">
    <img src="https://raw.githubusercontent.com/JayRHa/.github/main/assets/readme/brand-header.png" alt="Jannik Reinhard — I help enterprises ship secure AI agents" width="100%">
  </a>
</p>
<p align="center">
  <a href="https://jannikreinhard.com/">Website</a> ·
  <a href="https://www.linkedin.com/in/jannik-r/">LinkedIn</a> ·
  <a href="https://x.com/jannik_reinhard">X</a> ·
  <a href="https://www.youtube.com/@jannikreinhard">YouTube</a>
</p>
<!-- jr-brand:end -->

# Intune custom compliance scripts

**Type:** Collection · **Status:** Community project

## Overview

PowerShell scripts for Microsoft Intune Custom Compliance policies and device configuration checks.

This repository contains Microsoft Intune custom compliance discovery scripts and their matching JSON definitions. Each folder covers one practical Windows compliance check.

## Quickstart

1. Open the folder for the check you want to use.
2. Review and test the PowerShell discovery script on a test device.
3. In the Microsoft Intune admin center, create a custom compliance policy.
4. Upload the `.ps1` discovery script and import the matching `.json` definition.
5. Assign the policy to a test group before a wider rollout.

> **Note:** Always review the expected values in the JSON file. Adjust them to match your own compliance requirements.

## Available Checks

| Check | Purpose |
| --- | --- |
| `Check-AvEnabled` | Confirm that antivirus protection is enabled |
| `Check-FirewallEnabled` | Confirm that Windows Firewall is enabled |
| `Check-FreeStorage` | Check available storage |
| `Check-IfAppIsInstalled` | Detect whether a required application is installed |
| `Check-IfDeviceIsEncrypted` | Check device encryption |
| `Check-IfDeviceIsUpToDate` | Check the Windows update state |
| `Check-IfUnathorizedLocalAdmins` | Detect unexpected local administrators |

## License

This project is available under the terms in [LICENSE](LICENSE).

<!-- jr-brand-footer:start -->
---

[Articles and guides](https://jannikreinhard.com/) · [Repository index](https://github.com/JayRHa/.github/blob/main/REPOSITORIES.md)
<!-- jr-brand-footer:end -->
