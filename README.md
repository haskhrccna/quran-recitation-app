# quran-recitation-app
AI-powered Quran recitation analysis with Tajweed evaluation
# 📿 Quran Recitation Analysis App

AI-powered application for analyzing Quran recitation with advanced Tajweed evaluation.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.104.1-009688.svg)](https://fastapi.tiangolo.com)

## ✨ Features

- 🎙️ **Audio Recording** - High-quality browser-based recording
- 🤖 **AI Analysis** - Whisper model specialized for Quran
- 📊 **Tajweed Evaluation** - Advanced rules checking (Madd, Ghunnah, Qalqala)
- 📈 **Progress Tracking** - Comprehensive statistics and history
- 🔐 **Secure** - JWT authentication

## 🚀 Quick Start

### Using Docker (Recommended)

\`\`\`bash
# Clone repository
git clone https://github.com/YOUR_USERNAME/quran-recitation-app.git
cd quran-recitation-app

# Setup environment
cp .env.example .env
# Edit .env with your settings

# Start services
docker-compose up -d

# Access
# API: http://localhost:8000
# Docs: http://localhost:8000/docs
\`\`\`

### Manual Setup

See [DEPLOYMENT.md](docs/DEPLOYMENT.md) for detailed instructions.

## 📖 Documentation

- [Deployment Guide](docs/DEPLOYMENT.md)
- [API Reference](docs/API.md)
- [Integration Guide](docs/INTEGRATION.md)

## 🛠️ Tech Stack

**Backend:**
- FastAPI
- PostgreSQL
- Whisper AI (Tarteel)
- PyTorch

**Frontend:**
- React
- Tailwind CSS
- Web Audio API

## 📝 License

MIT License - see [LICENSE](LICENSE) file

## 🤝 Contributing

Contributions welcome! Please read our contributing guidelines first.

## 📧 Contact

- Email: your-email@example.com
- Website: https://your-website.com
