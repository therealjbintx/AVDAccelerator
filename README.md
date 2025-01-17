# Azure Virtual Desktop (AVD) Accelerator

- [Azure Virtual Desktop (AVD) Accelerator](#azure-virtual-desktop-avd-accelerator)
  - [Overview](#overview)
  - [Features](#features)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
      - [On-Prem VM Domain Join](#on-prem-vm-domain-join)
      - [Azure Active Directory VM Domain Join](#azure-active-directory-vm-domain-join)
  - [Additional Guides](#additional-guides)
  - [Estimated Deployment Times](#estimated-deployment-times)

## Overview

Azure Virtual Desktop (AVD) Accelerator is an Azure Marketplace offering that allows you to use your existing subscription to deploy a customized AVD environment. An easy-to-follow setup wizard will guide you through the process to deploy AVD according to your needs.

## Features

- Azure Active Directory (AAD) Virtual Machine (VM) Join
- On-Prem VM Join
- Apply DoD Security Technical Implementation Guides (STIGs) to deployed VMs using [PowerStig](https://github.com/Microsoft/PowerStig)
- Simplified VM sizing based on [Microsoft documentation](https://docs.microsoft.com/en-us/windows-server/remote/remote-desktop-services/virtual-machine-recs)
- AAD Account creation

## Getting Started

Prerequisites vary based on whether the VMs are going to be On-Prem or AAD joined.

### Prerequisites

#### On-Prem VM Domain Join

- Accounts that will log into the VMs must be synced to Azure Active Directory (AAD).
- Connectivity to an On-Prem Domain Controller (could be a Domain Controller as IAAS).
  - A Virtual Network can be created during deployment or an existing one be specified if it has connectivity to the On-Prem domain.

#### Azure Active Directory VM Domain Join

For a full AAD deployment, there are no prerequisites at this time.

## Additional Guides

- [Management and Logon Rights to VMs](articles/ManagementAndLogonRights.md)
- [Enable CAC Auth to AVD Accelerator Offering](articles/EnableCacAuth.md)
- [Using a custom VHD from Hyper-V for VM Image](articles/CustomVhd.md)
- [Creating Accounts During Deployment](articles/AccountCreation.md)
- [Resource Naming Convention](articles/NamingConvention.md)
- [Resources Deployed](articles/DeployedResources.md)

## Estimated Deployment Times
