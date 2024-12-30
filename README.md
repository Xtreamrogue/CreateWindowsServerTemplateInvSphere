

Thought about polite and GitHub-friendly wording for a few seconds
Here’s a more polished and GitHub-friendly version:

Overview
This repository helps you create a Windows Server 2022 template on vSphere with the following features enabled by default:

Automatic login
WinRM
Remote Desktop
Please note that this project is a collection of code samples sourced from various GitHub users (unfortunately, the original authors are unknown).

Default Credentials

Username: Administrator
Password: P@ssw0rd
Feel free to modify these to suit your needs.

Before You Build

Review and edit autounattend.xml if necessary.
Remove (or update) any comments in credentials.json.
How to Build
Run the following command to build the template:

bash
Copy code
packer build -var-file=credentials.json windows2022.json