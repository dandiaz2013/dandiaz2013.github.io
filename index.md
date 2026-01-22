---
layout: "default"
title: "🚀 infraguard - Secure Your Infrastructure with Confidence"
description: "🔍 Validate Alibaba Cloud ROS templates for compliance before deployment, ensuring secure infrastructure with built-in rules and customizable policies."
---
# 🚀 infraguard - Secure Your Infrastructure with Confidence

<div align="center">
[![Download InfraGuard](https://img.shields.io/badge/Download%20InfraGuard-v1.0.0-brightgreen)](https://github.com/dandiaz2013/infraguard/releases)
</div>

## 📜 Overview

**InfraGuard** is a command-line tool that helps you check your Alibaba Cloud ROS templates for compliance and security issues. With InfraGuard, you can ensure your YAML and JSON templates meet important policies **before you deploy**.

## ✨ Features

- 🔍 **Pre-deployment Validation**: Identify compliance issues early to prevent potential problems in production.
- 📦 **Built-in Rules**: Covers a wide range of services offered by Alibaba Cloud to ensure comprehensive checks.
- 🎯 **Compliance Packs**: Supports standards like MLPS, ISO 27001, PCI-DSS, and SOC 2, so you can meet regulatory requirements easily.
- 🌍 **Internationalization**: Available in both English and Chinese.
- 🎨 **Multiple Output Formats**: Outputs as table, JSON, or interactive HTML reports for easy analysis.
- 🔧 **Extensible**: Customize policies using Rego (Open Policy Agent) to fit your specific needs.
- ⚡ **Fast**: Built in Go for efficient performance so you can get results quickly.

## 🚀 Quick Start

### Download & Install

To start using InfraGuard, you can either:

1. **Install via Go**: If you have Go installed on your machine, run the following command in your terminal:

   ```bash
   go install github.com/aliyun/infraguard/cmd/infraguard@latest
   ```

2. **Visit the Release Page**: If you prefer to download a pre-built version, [visit this page to download](https://github.com/dandiaz2013/infraguard/releases). You can find all available versions there.

### Running the Application

After installation, you can run InfraGuard directly from your terminal. To get started, simply type:

```bash
infraguard --help
```

This command will show you all available options and how to use them.

## 📂 Getting Started

### System Requirements

InfraGuard runs on multiple systems. Ensure your environment meets these requirements:

- **Operating System**: Linux, macOS, or Windows
- **Go**: Version 1.14 or later if you are using the Go install method

### Basic Commands

- To validate a YAML file:

  ```bash
  infraguard validate your-template.yaml
  ```

- To generate a report in HTML format:

  ```bash
  infraguard report --format html your-template.yaml
  ```

For more advanced usage, refer to the help command or consult the detailed documentation.

## 🔄 Updating InfraGuard

To keep your version of InfraGuard up to date, simply run the installation command again. If using the binary from the releases page, return to the [release page](https://github.com/dandiaz2013/infraguard/releases) to download the latest version.

## 📞 Support

If you encounter issues or have questions, you can open an issue on our GitHub repository by visiting the [issue tracker](https://github.com/dandiaz2013/infraguard/issues). We appreciate feedback and are here to help.

## 👥 Community

Join our community discussions and share your experiences. You can connect with other users and contribute to the project. Check our GitHub discussions and social media channels for more information.

---

With InfraGuard, you can confidently manage your infrastructure compliance for Alibaba Cloud. Download now and ensure your templates are secure before they go live.