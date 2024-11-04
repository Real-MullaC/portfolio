---
date: 2024-11-04
lastmod: 2024-11-04
title: "Updating Computers Group Policy"
type: "post"
---

## Connect to the Domain Controller

- Launch Remote Desktop Connection
- Go to 10.160.200.22
- Login with your credentials that you have set in B126B

## Configuring Group Policy

- Launch Server Manager
- Click Tools in the top right hand corner
- Go to Group Policy Management
- Click the arrow next to B126B.local
- Right-Click Default Group Policy and click Edit
- Make your changes in here.

## Setting Group Policy

- On each Client PC launch cmd (Command Prompt)
- Run command '''gpupdate /force'''
- After command ran restart PC