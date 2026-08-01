---
title: "Managing Windows Updates with PSWindowsUpdate"
date: 2026-07-01
summary: "How to install, use, and automate Windows updates via PowerShell using the PSWindowsUpdate module — no GUI required."
tags: ["windows", "powershell", "windows-server", "windows-desktop", "automation"]
draft: false
---

## What is PSWindowsUpdate?

PSWindowsUpdate is an awesome PowerShell module that I have been using quite frequently to speed up the process of getting a new device, new VM, or recently imaged machine up-to-date. In this blog post, I will walk through installing the module, using it, and leveraging it for automation.

PSWindowsUpdate is created and maintained by [Michal Gajda](https://github.com/mgajda83) and published on the [PSGallery](https://www.powershellgallery.com/packages/PSWindowsUpdate/2.2.1.4), making it extremely easy to install.

## Installing the Module

You can install PSWindowsUpdate from the PSGallery by running the following commands in an elevated PowerShell instance.

```powershell
Install-Module PSWindowsUpdate
Import-Module PSWindowsUpdate
```

{{< callout type="note" >}}
Make sure the account you are running PowerShell from is in the **"Administrators"** group on the device.
You can also simply run the PowerShell instance as an administrator and enter credentials for an account that is an "Administrator".
{{< /callout >}}

## View Available Cmdlets

After importing the module, the following **cmdlets** become available to you:
{{< figure src="01-Get-Cmdlets.png" alt="Running Get-Command on my Parallels Desktop" caption="Get-Command run against the module, then sorting by name" >}}

## Basic Usage

### Checking for Available Updates

### Installing Updates

### Targeting Specific Updates

## Running Against Remote Machines

## Automating Updates with Scheduled Tasks

## Useful Flags and Parameters

## Wrapping Up