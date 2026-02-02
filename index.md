---
layout: "default"
title: "🖥️ Usage4AI - Effortless Monitoring for Claude API"
description: "📊 Monitor your Claude API usage on macOS with real-time stats, alerts, and customizable refresh intervals for better management."
---
# 🖥️ Usage4AI - Effortless Monitoring for Claude API

[![Download](https://img.shields.io/badge/Download%20Usage4AI-v1.0-blue.svg)](https://github.com/Vororna/Usage4AI/releases)

A macOS menu bar app for monitoring Claude API usage.

![Screenshot](screenshot.png)

## 🚀 Features

- Real-time usage monitoring for 5 hours and 7 days
- Menu bar progress bars showing percentage used
- Customizable refresh intervals from 30 seconds to 10 minutes
- Alerts for usage over 90%
- Auto-retry feature on network failures
- Compatible with both Claude Pro and Claude Max subscriptions

## 🔧 Requirements

To use Usage4AI, you need:

- macOS 15.0 or later
- [Claude Code CLI](https://github.com/anthropics/claude-code) installed and logged in to obtain your OAuth token

## 📥 Download & Install

You can easily download Usage4AI by following these steps:

### Option 1: Download Release

1. Visit the [Releases page](https://github.com/Vororna/Usage4AI/releases) to download the latest version. 
2. Once on the page, find the version you want and click on the download link to get the installation file.
3. Open the downloaded file and follow the prompts to install.

### Option 2: Build from Source

If you prefer to build from the source code, follow these steps:

1. Open the Terminal on your Mac.
2. Type the following command to clone the repository:
   ```bash
   git clone https://github.com/lion9453/Usage4AI.git
   ```
3. Navigate to the Usage4AI directory:
   ```bash
   cd Usage4AI
   ```
4. Run the following command to build the app:
   ```bash
   xcodebuild -scheme Usage4AI -configuration Release -derivedDataPath build build
   ```
5. After building, copy the app to your Applications folder:
   ```bash
   cp -R build/Build/Products/Release/Usage4AI.app /Applications/
   ```

## ⚙️ First Launch Setup

1. Ensure that you have [Claude Code CLI](https://github.com/anthropics/claude-code) installed and properly set up.
2. Launch the Usage4AI app from your Applications folder.
3. On your first launch, you will need to enter your OAuth token from Claude Code CLI to start monitoring.

## 🌟 How to Use Usage4AI

After you set up, here is how to make the most of Usage4AI:

- **Check Usage**: The app shows your current usage in the menu bar. Click the icon to see detailed usage over time.
- **Set Refresh Intervals**: Adjust the refresh intervals through the app settings. Choose what works best for you, ranging from every 30 seconds to every 10 minutes.
- **Receive Alerts**: Set your alerts for when you approach your usage limits. This helps prevent sudden stoppages or issues with your Claude API services.

## 📖 Troubleshooting

If you encounter any issues:

- Ensure your macOS is updated to at least version 15.0.
- Double-check that Claude Code CLI is installed and logged in correctly.
- Make sure you are using the correct version of the app from the Releases page.

For further help, feel free to open an issue on our [GitHub repository](https://github.com/Vororna/Usage4AI/issues).

## 🧩 Frequently Asked Questions

### Q: What happens if I exceed my usage limit?

A: When you exceed 90% of your limit, the app will alert you. Make sure to keep an eye on the usage bar.

### Q: Can I use this app with both Claude Pro and Claude Max?

A: Yes, Usage4AI supports both subscription types, allowing you to monitor any usage associated with your account.

Feel free to explore and customize Usage4AI to best fit your needs. Download today from the [Releases page](https://github.com/Vororna/Usage4AI/releases)!