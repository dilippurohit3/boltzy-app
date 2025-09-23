# ⚡ Boltzy

<div align="center">
  <img src="public/boltzy-logo.svg" alt="Boltzy Logo" width="120" height="120">
  
  **Watch videos together with friends anywhere.**
  
  [![Netflix Sync](https://img.shields.io/badge/Netflix-Sync-red?style=for-the-badge&logo=netflix)](https://github.com/dilippurohit3/boltzy)
  [![React](https://img.shields.io/badge/React-18+-blue?style=for-the-badge&logo=react)](https://reactjs.org/)
  [![TypeScript](https://img.shields.io/badge/TypeScript-5+-blue?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
  [![Node.js](https://img.shields.io/badge/Node.js-18+-green?style=for-the-badge&logo=node.js)](https://nodejs.org/)
</div>

## 🎬 What is Boltzy?

Boltzy is a modern, Netflix-inspired video synchronization platform that allows friends to watch videos together in real-time. Built with cutting-edge technology and featuring a sleek, dark UI that rivals the best streaming platforms.

### ✨ Key Features

- **🎥 Netflix Sync** - Rave-style Netflix synchronization (everyone uses their own Netflix account)
- **📺 YouTube Integration** - Watch YouTube videos together with perfect sync
- **🖥️ Screen Sharing** - Share your screen, browser tabs, or applications
- **💬 Real-time Chat** - Chat with emojis, GIFs, and reactions
- **📹 Video Chat** - Face-to-face conversations while watching
- **☁️ Virtual Browser** - Cloud-based browser for content requiring login
- **📱 Mobile Responsive** - Works perfectly on all devices
- **🔒 Secure** - No data collection, privacy-first approach

## 🚀 Quick Start

### Prerequisites

- Node.js 18+ 
- npm or yarn
- PostgreSQL (for production)
- Redis (for caching)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/dilippurohit3/boltzy.git
   cd boltzy
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env
   # Edit .env with your configuration
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   ```
   http://localhost:3000
   ```

## 🎯 How Netflix Sync Works

Boltzy uses a revolutionary "Rave-style" synchronization approach:

1. **Everyone uses their own Netflix account** - No sharing credentials
2. **Perfect synchronization** - Play, pause, and seek commands are synced
3. **Respects DRM** - Works within Netflix's terms of service
4. **Real-time chat** - React to moments together
5. **Cross-platform** - Works on any device with Netflix

### Netflix Sync Process

1. **Start a Netflix session** - Host creates a room and shares Netflix URL
2. **Everyone joins** - Participants open the same Netflix content
3. **Mark ready** - Each person confirms they're at the right video
4. **Sync controls** - Host controls playback for everyone
5. **Enjoy together** - Perfect synchronization with real-time chat

## 🛠️ Technology Stack

### Frontend
- **React 18** - Modern React with hooks and concurrent features
- **TypeScript** - Type-safe development
- **Semantic UI React** - Modern component library
- **Socket.IO Client** - Real-time communication
- **WebRTC** - Peer-to-peer video/audio chat

### Backend
- **Node.js** - Server runtime
- **TypeScript** - Type-safe server code
- **Socket.IO** - Real-time bidirectional communication
- **MediaSoup** - Advanced WebRTC SFU for high-quality streaming
- **PostgreSQL** - Relational database
- **Redis** - Caching and session management

### Infrastructure
- **Docker** - Containerization
- **Firebase** - Authentication and user management
- **Stripe** - Payment processing
- **DigitalOcean/Hetzner** - Cloud hosting

## 📱 Features in Detail

### 🎥 Netflix Synchronization
- **Rave-style sync** - Everyone uses their own Netflix account
- **Perfect timing** - Play, pause, seek commands synchronized
- **Real-time indicators** - See who's ready and synced
- **Cross-platform** - Works on any device with Netflix

### 📺 Multi-Platform Support
- **YouTube** - Direct YouTube video synchronization
- **Screen Sharing** - Share your entire screen or specific applications
- **File Sharing** - Upload and watch your own videos
- **Virtual Browser** - Cloud browser for content requiring login
- **HTTP Streams** - Support for HLS, DASH, and other streaming protocols

### 💬 Social Features
- **Real-time Chat** - Text chat with emoji reactions
- **Video Chat** - Face-to-face conversations
- **Voice Chat** - Audio-only communication
- **Reactions** - Quick emoji reactions during playback
- **User Profiles** - Customizable user profiles

### 🔧 Advanced Features
- **Playlists** - Queue multiple videos
- **Room Management** - Private rooms with passwords
- **User Permissions** - Host controls and moderation
- **Mobile App** - Progressive Web App (PWA) support
- **Offline Support** - Works without internet (local videos)

## 🎨 UI/UX Design

Boltzy features a modern, Netflix-inspired interface:

- **Dark Mode** - Easy on the eyes for long viewing sessions
- **Netflix Red** - Familiar color scheme for instant recognition
- **Responsive Design** - Works perfectly on desktop, tablet, and mobile
- **Smooth Animations** - Polished interactions and transitions
- **Accessibility** - WCAG compliant for all users

## 🚀 Deployment

### Production Setup

1. **Database Setup**
   ```bash
   # PostgreSQL
   createdb boltzy
   psql boltzy < sql/schema.sql
   ```

2. **Environment Configuration**
   ```bash
   # Set production environment variables
   NODE_ENV=production
   DATABASE_URL=postgresql://...
   REDIS_URL=redis://...
   ```

3. **Build and Deploy**
   ```bash
   npm run build
   npm start
   ```

### Docker Deployment

```bash
# Build Docker image
docker build -t boltzy .

# Run with Docker Compose
docker-compose up -d
```

## 🤝 Contributing

We welcome contributions to Boltzy! Please read our [Contributing Guidelines](CONTRIBUTING.md) before submitting pull requests.

### Development Setup

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests if applicable
5. Submit a pull request

## 📄 License

**All Rights Reserved** - This software is proprietary and confidential.

Copyright (c) 2024 Dilippurohit3. All rights reserved.

This software and associated documentation files (the "Software") are the exclusive property of Dilippurohit3. The Software is protected by copyright laws and international treaties.

**No part of this Software may be:**
- Copied, modified, or distributed without explicit written permission
- Used for commercial purposes without a valid license
- Reverse engineered, decompiled, or disassembled
- Incorporated into other software without authorization

**For licensing inquiries, please contact:** [dilippurohit3@gmail.com](mailto:dilippurohit3@gmail.com)

## 🆘 Support

- **Documentation** - [Wiki](https://github.com/dilippurohit3/boltzy/wiki)
- **Issues** - [GitHub Issues](https://github.com/dilippurohit3/boltzy/issues)
- **Discussions** - [GitHub Discussions](https://github.com/dilippurohit3/boltzy/discussions)
- **Email** - [admin@boltzy.me](mailto:admin@boltzy.me)

## 🙏 Acknowledgments

- **Netflix** - For the inspiration and UI/UX patterns
- **Rave** - For the innovative Netflix sync approach
- **React Team** - For the amazing framework
- **Socket.IO** - For real-time communication
- **Open Source Community** - For the incredible tools and libraries

---

<div align="center">
  <strong>Made with ⚡ by Dilippurohit3</strong>
  
  [![GitHub](https://img.shields.io/badge/GitHub-dilippurohit3-black?style=for-the-badge&logo=github)](https://github.com/dilippurohit3)
  [![Email](https://img.shields.io/badge/Email-admin@boltzy.me-red?style=for-the-badge&logo=gmail)](mailto:admin@boltzy.me)
</div>