# ASM Tool Architecture - Attack Surface Management Platform

> A comprehensive visual guide to a full-stack Attack Surface Management platform architecture.

## 🚀 Live Demo

[Deploy on Vercel](https://vercel.com/new/import?repository-url=https://github.com/Niranjan-js/ASM-detail.pro)

## 📋 Features

- **Interactive Layer Explorer**: Click to expand 15+ architecture layers
- **Data Flow Visualization**: See how scans travel through the entire platform
- **Complete Architecture Summary**: Stats, principles, tech stack and security details
- **Responsive Design**: Works seamlessly on desktop, tablet and mobile
- **Dark Mode**: Eye-friendly dark theme throughout

## 🛠️ Tech Stack

- **Frontend**: Pure HTML5 + Vanilla JavaScript
- **Styling**: CSS3 with gradients and animations
- **Deployment**: Vercel (zero-config static hosting)

## 📂 Project Structure

```
ASM-detail.pro/
├── index.html          # Main page (optimized for Vercel)
├── vercel.json         # Vercel configuration
├── package.json        # Project metadata
├── .gitignore          # Git ignore rules
└── README.md           # This file
```

## 🔧 Local Development

```bash
# Simple HTTP server (no build required)
python -m http.server 8000

# Or with Node.js
npx http-server
```

Then open `http://localhost:8000` in your browser.

## 📤 Deploy to Vercel

### Option 1: One-Click Deploy
1. Click the "Deploy on Vercel" button above
2. Authorize GitHub access
3. Done! Your site is live

### Option 2: Manual Deploy
```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel --prod
```

### Option 3: Via GitHub
1. Push code to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Import your repository
4. Vercel auto-deploys on every push

## 🎨 Architecture Overview

### 15+ Layers Covered:
- 👥 **Users** - Security analysts & SOC teams
- 🖥️ **Next.js Frontend** - Dashboard & UI
- ⚙️ **FastAPI Backend** - REST API & core services
- 🎯 **Scan Orchestrator** - Pipeline manager
- ⚡ **Redis + Celery** - Distributed task queue
- 🔍 **Discovery Layer** - Subdomain enumeration
- 📡 **Enumeration Layer** - Live host detection
- 🛡️ **Vulnerability Layer** - Scan execution
- 🗄️ **PostgreSQL** - Data persistence
- 🧠 **AI & Risk Engine** - Scoring & prioritization
- 🔗 **External Integrations** - Threat intelligence
- ⏱️ **Monitoring & Scheduling** - Continuous scans
- 🔔 **Alerting System** - Multi-channel notifications
- 📄 **Reporting** - PDF/CSV/JSON export
- 🚀 **Infrastructure** - Docker & deployment

## 📊 What You'll Learn

- ✅ Full-stack ASM platform design
- ✅ Async job orchestration patterns
- ✅ Horizontal scaling strategies
- ✅ Security best practices (JWT, RBAC, audit logs)
- ✅ Integration patterns with external APIs
- ✅ Modern DevOps practices

## 🔒 Security Features

- JWT authentication with refresh tokens
- Role-based access control (Admin/Analyst/Viewer)
- Immutable audit logs with timestamps
- API rate limiting and input sanitization
- CORS and CSP headers
- Secure error handling

## 📈 Scalability

- **Async-first architecture**: Celery workers handle all heavy lifting
- **Horizontal scaling**: Spin up workers as Docker containers
- **Load balancing**: Nginx reverse proxy with TLS
- **Database optimization**: PostgreSQL with async ORM
- **Monitoring**: Prometheus + Grafana for visibility

## 🤝 Contributing

Found a bug or want to improve the docs? Please submit an issue or PR!

## 📝 License

MIT License - feel free to use this for your own projects

## 🔗 Related Resources

- [Next.js Documentation](https://nextjs.org/docs)
- [FastAPI Guide](https://fastapi.tiangolo.com/)
- [Celery & Redis](https://docs.celeryproject.io/)
- [Nuclei Templates](https://github.com/projectdiscovery/nuclei-templates)
- [Vercel Docs](https://vercel.com/docs)

---

**Made with ❤️ by Niranjan-js**
