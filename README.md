# VPN Admin App

**A web-based administration panel for managing VPN servers, users, and configurations with real-time monitoring and analytics.**

## ✨ Features
- **User Management**: Create, edit, and manage VPN user accounts
- **Server Monitoring**: Real-time status tracking for multiple VPN servers
- **Connection Analytics**: View active sessions, bandwidth usage, and connection history
- **Configuration Management**: Generate and distribute client configs automatically
- **Multi-Protocol Support**: Compatible with OpenVPN, WireGuard, and other VPN protocols
- **Security Dashboard**: Monitor security events and access patterns

## 🚀 Quick Start

### Prerequisites
- Node.js 16+ and npm
- VPN server(s) running OpenVPN or WireGuard

### Installation
```bash
# Clone the repository
git clone https://github.com/ultimate-m-tech-ltd/vpn-admin-app.git

# Install dependencies
cd vpn-admin-app
npm install

# Configure environment
cp .env.example .env
# Edit .env with your settings

# Start the application
npm start