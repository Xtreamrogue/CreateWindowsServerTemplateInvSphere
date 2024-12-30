
# Windows Server 2022 Template for vSphere

## Overview
This repository helps you create a Windows Server 2022 template on vSphere with the following features enabled by default:
- Automatic login
- WinRM
- Remote Desktop

> **Note:** This project is a collection of code samples from various GitHub users, whose original contributions are unfortunately unknown.

## Default Credentials
- **Username:** Administrator  
- **Password:** P@ssw0rd  

Feel free to modify these credentials to suit your needs.

## Before You Build
1. Review and edit **autounattend.xml** as necessary.  
2. Remove or update any comments in **credentials.json**.

## How to Build
Run the following command to build the template:

```bash
packer build -var-file=credentials.json windows2022.json
