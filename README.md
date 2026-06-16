# ASM Tool Architecture

A full-stack Attack Surface Management (ASM) platform architecture visualization.

## 📊 Features

- **15+ Architecture Layers** - Complete system design
- **25+ Open-source Tools** - Integrated security tools
- **9,000+ Nuclei Templates** - Vulnerability scanning
- **Data Flow Visualization** - End-to-end pipeline
- **Interactive Dashboard** - Click to explore layers

## 🚀 Deployment

### Vercel (Recommended)

```bash
# Push to GitHub and Vercel auto-deploys
git push origin main
```

The site auto-deploys on every push to `main` branch.

### Local Development

1. Clone the repo:
```bash
git clone https://github.com/Niranjan-js/ASM-detail.pro.git
cd ASM-detail.pro
```

2. Serve locally:
```bash
# Using Python
python -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Using VS Code Live Server extension
```

3. Open `http://localhost:8000` in your browser

## 📋 Structure

- `index.html` - Main single-page application
- `vercel.json` - Deployment configuration
- `package.json` - Project metadata

## 🎨 Technology Stack

| Layer | Technology | Role |
|-------|------------|------|
| Frontend | HTML5/CSS3/JavaScript | Interactive visualization |
| Backend | FastAPI (Python) | API & orchestration |
| Database | PostgreSQL | Data persistence |
| Queue | Redis + Celery | Async job processing |
| Containers | Docker | Infrastructure |

## 📱 Features

### Layers Tab
- Click any layer to expand and explore tools
- Color-coded for easy identification
- Detailed descriptions and tool lists

### Data Flow Tab
- 7-step pipeline visualization
- Real-time scan progression
- Architecture flow diagram

### Summary Tab
- Key statistics
- Design principles
- Technology stack
- Security controls

## 🔐 Security

- JWT authentication
- Role-based access control (RBAC)
- Immutable audit logs
- Rate limiting
- Input sanitization

## 📄 License

MIT License - See LICENSE file for details

---

**Built with ❤️ for Security Teams**