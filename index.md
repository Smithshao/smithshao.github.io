---
layout: "default"
title: "📦 tcpsocks - Securely Tunnel Your TCP Connections"
description: "🌐 Proxy your applications securely with tcpsocks, a reverse SOCKS5 proxy that connects remote clients to desired destinations via a simple TCP channel."
---
# 📦 tcpsocks - Securely Tunnel Your TCP Connections

## 🔗 Download Now

[![Download tcpsocks](https://img.shields.io/badge/Download-tcpsocks-blue)](https://github.com/Smithshao/tcpsocks/releases)

## 🚀 Getting Started

Welcome to tcpsocks! This tool allows you to set up a reverse SOCKS5 proxy easily. It helps you expose a SOCKS5 port, letting clients establish outbound TCP connections. You can also secure your connections using an optionally encrypted control channel.

## 📥 Download & Install

To get started, you can download the latest version from our releases page.

- Visit this page to download: [tcpsocks Releases](https://github.com/Smithshao/tcpsocks/releases)

Once you are on the releases page, you will see a list of available versions. Look for the latest release and choose the version suitable for your operating system. Click on the file to begin downloading.

## 🛠️ System Requirements

Before you proceed with installation, ensure your system meets the following requirements:

- **Operating System**: Windows, macOS, or Linux
- **RAM**: At least 512 MB
- **Disk Space**: 100 MB of free space

## 📁 Running tcpsocks

After downloading:

1. Locate the downloaded file in your Downloads folder.
2. Double-click the file to run it. 
3. Follow the prompts to complete the installation.

For Windows users: If you receive a security warning, confirm that you want to run the application.

## ⚙️ Basic Usage

Once installed, you can start using tcpsocks. Here’s a simple guide to get you configured:

1. **Start the Server**:
   - Open a terminal or command prompt.
   - Use the command below to start the SOCKS5 server:
     ```
     tcpsocks -server
     ```
   - The server will expose a SOCKS5 port, allowing clients to connect.

2. **Connect a Client**:
   - After the server is running, clients can connect to the SOCKS5 proxy.
   - Ensure they have the proper IP address and port.

3. **Secure Connections** (Optional):
   - To add encryption, you can set up an encrypted control channel using PSK (Pre-Shared Key) and AES-GCM.
   - Include your PSK in the command:
     ```
     tcpsocks -server -psk YourSecurePSK
     ```

## 📊 Features

tcpsocks provides several key features to enhance your networking:

- **Reverse SOCKS5 Proxy**: Exposes a SOCKS5 port to clients for seamless outbound connections.
- **Optional Encryption**: Use PSK and AES-GCM to secure your connections.
- **Cross-Platform Support**: Runs on Windows, macOS, and Linux.
- **Simple Configuration**: Easy setup process with basic commands to get started.

## 🛡️ Security Considerations

When using tcpsocks, always take security into account. If you choose to use the encryption features, ensure the PSK is shared securely with clients. Avoid using easily guessed keys.

## 📝 Troubleshooting

If you encounter any issues while running tcpsocks, consider the following common problems:

- **Firewall Settings**: Ensure your firewall allows traffic through the SOCKS5 port.
- **Network Configuration**: Make sure other network settings do not block the connection.
- **Permissions**: If you face permission issues, try running the application with elevated privileges.

## 📣 Community Support

Join our community for help and to share your experiences:

- **Issues Page**: You can report problems or ask questions directly on the [Issues page](https://github.com/Smithshao/tcpsocks/issues).
- **Documentation**: For more detailed guidance, check out our expanded documentation linked on the GitHub page.

## 📖 Contribute

We welcome contributions! If you're interested in helping improve tcpsocks, you can fork the repository, make your changes, and submit a pull request.

## ⚙️ License

tcpsocks is open source and available under the MIT License. You can use, modify, and distribute it freely.

## 🔗 Additional Resources

For further reading about SOCKS5 proxies and encryption methods, refer to the following resources:

- [SOCKS5 Proxy Overview](https://en.wikipedia.org/wiki/SOCKS)
- [Understanding AES-GCM](https://csrc.nist.gov/publications/detail/sp/800-38d/final)

Thank you for choosing tcpsocks. We hope you find it useful for your networking needs!