# Linode CLI - Snap Package

[![Snap Store](https://snapcraft.io/linode-cli/badge.svg)](https://snapcraft.io/linode-cli)

A Snap package for the **Linode CLI**, providing an easy way to manage your Akamai Cloud resources from the terminal.

> **Scope:** This repository maintains the **Snap packaging** only. The Linode CLI itself is developed and maintained by the Akamai Cloud engineering team.

---

## 📦 Installation

Install from the Snap Store:

```bash
snap install linode-cli
```
---

## 🚀 Quick Start

Configure your preferences and connect your Akamai Cloud account:

```bash
linode-cli configure
```

View available commands:

```bash
linode-cli --help
```

---

## 🔄 Update

The Snap tracks upstream Linode CLI releases. To update:

```bash
snap refresh linode-cli
```

---

## ✨ Features

- **Compute** - Create, update, and delete Linodes. Manage instance types, images, backups, and power states.
- **Networking** - Manage ip addressed, VLANs, VPCs, and Cloud Firewalls.
- **Domains** – Create and manage DNS zones and records. 
- **Storage** - Provision and manage Block Storage volumes and Object Storage buckets.
- **Load Balancing** - Configure and monitor NodeBalancers and backend nodes for high availability.
- **Databases** - Deploy and maintain Managed Databases for MySQL and PostgreSQL.
- **Kubernetes** - Create, update, and manage Linode Kubernetes Engine (LKE) clusters.
- **Events** - List and inspect system and account events for auditing and automation.
- **Account** - View billing info, manage users, SSH keys, API tokens, and account settings.
- **Support** - Open and track support tickets.
- **Automation** - Execute StackScripts, upload custom images, and integrate with CI/CD workflows.

---

## 🧩 Architectures & Requirements

- Supported Architectures: **amd64** and **arm64** (Snap **core24** base).
- Confinement: **strict** (standard store sandbox).

---

## 🌍 Availability

The Linode CLI can be used across [all Akamai Cloud regions](https://www.linode.com/global-infrastructure/).

---

## 🔗 Links

- **CLI Documentation:** https://techdocs.akamai.com/cloud-computing/docs/cli
- **Upstream Source:** https://github.com/linode/linode-cli
- **Snap Store Page:** https://snapcraft.io/linode-cli
- **Report Linode CLI Issues (Upstream):** https://github.com/linode/linode-cli/issues
- **Report Snap Packaging Issues:** https://github.com/adamovera/linode-cli-snap/issues

---

## 📄 License

- Upstream Linode CLI: [BSD-3-Clause License](https://github.com/linode/linode-cli/blob/main/LICENSE)
- Snap Package: MIT
