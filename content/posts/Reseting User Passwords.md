---
date: 2024-11-11
# description: ""
# image: ""
lastmod: 2024-11-11
showTableOfContents: false
# tags: ["",]
title: "Reseting User Passwords"
type: "post"
---

## Connect to the Domain Controller

- Launch Remote Desktop Connection
- Go to 10.160.200.22
- Login with your credentials that you have set in B126B

## Go to Users and Computers

- Launch Server Manager
- Click Tools in the top right hand corner
- Go to Active Directory Users and Computers
- Click the arrow next to B126B.local then click the arrow next to the group
- Click on the groups name
You will now see a list of Users
- Right Click the user you want to reset the password for
- Click Reset Password...
- Enter the following password - ```B126B-D```
- Make sure to select User must change password at next logon 
- If it says the Account Lockout Status is Locked then select Unlock the user's account
- Click Ok

## Close the server
- Drag your mouse to the top centre of the screen
- Click the x icon