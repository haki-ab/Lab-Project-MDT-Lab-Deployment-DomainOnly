# Lab-Project-MDT-Lab-Deployment-DomainOnly
# MDT Deployment Lab – Domain Only Access

This lab demonstrates how to deploy Windows 10/11 using **Microsoft Deployment Toolkit (MDT)** with the following customizations:

- **Bootstrap.ini**: Preconfigured Deployment Share path
- **CustomSettings.ini**: Skip rules (control which wizard pages appear)
- **Unattend.xml**: Domain join, bypass local account setup, enforce domain-only login

## Scenario
Simulates an **enterprise environment** (e.g. school or office) where all endpoints:
- Automatically join the domain `haki.lab`
- Do not allow standalone local accounts
- Require users to log in with Active Directory credentials

## Value
This lab is a bridge between **Lite Touch Deployment (MDT)** and **Zero Touch / Cloud Deployment** using SCCM or Intune.

## Files
- `Bootstrap.ini` → Deployment share connection
- `CustomSettings.ini` → Wizard control
- `Unattend.xml` → OS deployment configuration

## Next Steps
- Extend to SCCM lab for Zero Touch
- Integrate with Intune/Autopilot for Cloud deployment
