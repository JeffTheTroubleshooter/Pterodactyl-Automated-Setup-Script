Pterodactyl Automated Setup Script
Description

This repository contains a Bash script that automates the installation and basic setup of Pterodactyl, an open-source game server management platform.

The script was created using my own notes with the help of AI and is designed to make deploying Pterodactyl on Ubuntu faster and easier by automating most of the required setup steps.


Supported OS

Ubuntu only

You will be prompted for:

Domain or server IP

Database password

Admin email address


Enable Wings:

sudo systemctl enable --now wings


Warning

This script makes system-level changes.
It is recommended to run it on a fresh Ubuntu server.

License

MIT License

Author

JeffTheTroubleshooter
