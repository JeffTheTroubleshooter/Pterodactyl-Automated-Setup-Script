# Pterodactyl Automated Setup Script

## Description

This repository contains a Bash script that automates the installation and basic setup of **Pterodactyl**, an open-source game server management platform.

The script was created using my own notes with the help of AI and is designed to make deploying Pterodactyl on **Ubuntu** faster and easier by automating most of the required setup steps.

---

## Supported OS

* Ubuntu only

---

## During Installation

You will be prompted for:

1. Domain or server IP
2. Database password
3. Admin email address (optional)

---

## After Installation

Enable Wings **after creating a node** in the panel:

```bash
sudo systemctl enable --now wings
```

---

## Video Guide

A full walkthrough and demonstration of this script is available on YouTube:

▶️ https://youtu.be/ngzIf1GsHWo

---

## License

MIT License

---

## Author

**JeffTheTroubleshooter**
