---
date: 2024-11-04
lastmod: 2024-11-04
title: "Connecting to Domain Controller"
type: "post"
---

## Change DNS settings on client
- Launch Control Panel
- Click Network and Internet
- Click Network and Sharing Centre
- Click Change adapter settings
- Right-Click Ethernet and click Properties
- Select Internet Protocol Version 4 (TCP/IPv4)
- Click Properties
- Select Use the following DNS server addresses and enter the following:
    - 10.160.200.22
- Click Ok
- Click Close

## Joining a domain
- Head to Settings and go to System
- Go to About
- Click Domain or Workgroup
- Click Change
- Click Domain then enter the following:
    - B126B.local
    - Login with your admin credentials on the pop up that shows.
- Close everything
- Restart the system