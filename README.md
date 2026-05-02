# Hermes Agents in Production

## Building Autonomous AI Systems with Railway Deployment

### A Technical Textbook

**Live Demo:** [reservato-production.railway.app](https://reservato-production.railway.app) (coming soon)

**GitHub:** [github.com/oddsifylabs/hermes-textbook](https://github.com/oddsifylabs/hermes-textbook)

---

## 📖 What This Is

A **hands-on technical textbook** for building production-ready autonomous AI agent systems using Hermes Agents. Every chapter includes complete working code, architecture diagrams, and real-world deployment on Railway.

## 🏗️ The Project: Reservato

Throughout this book, you'll build **Reservato** — a production-ready reservation booking system:

| Feature | Description |
|---------|-------------|
| 🍽️ Restaurant Reservations | Table booking with time slots, party size |
| 📅 Real-time Availability | Conflict detection, calendar integration |
| 💳 Stripe Payments | Deposits and cancellation fees |
| 📧 Automated Confirmations | Email/SMS reminders via Hermes Agents |
| 🤖 AI Agent Booking | Natural language reservation handling |
| 📊 Analytics Dashboard | Occupancy rates, revenue tracking |

## 📚 Book Structure

### Part I: Foundations
1. Hermes Agents Overview
2. Tool System Deep Dive
3. Skills & Automation

### Part II: Building Reservato
4. Multi-Agent Workflows
5. Database & Models (SQLAlchemy)
6. API Development (FastAPI)
7. Frontend Integration (HTMX + Tailwind)

### Part III: Production Deployment
8. Railway Deployment
9. Monitoring & Observability
10. Maintenance & Iteration

## 🚀 Quick Start

### Prerequisites
- Python 3.11+
- Git
- Railway account (free tier works)

### Clone the Repository

```bash
# Textbook source
git clone https://github.com/oddsifylabs/hermes-textbook.git
cd hermes-textbook

# Reservato project
git clone https://github.com/oddsifylabs/reservato.git
cd reservato
```

### Install Dependencies

```bash
cd reservato
pip install -e ".[dev]"
```

### Set Up Environment

```bash
cp .env.example .env
# Edit .env with your API keys
```

### Run Locally

```bash
uvicorn src.api.main:app --reload
# Visit http://localhost:8000/docs
```

## 📊 Architecture

See interactive diagrams:
- [Agent Architecture](diagrams/01-agent-architecture.html)
- [Booking Flow](diagrams/02-booking-flow.html)

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| **Agent Framework** | Hermes Agents |
| **Backend** | FastAPI (Python 3.11+) |
| **Database** | PostgreSQL (Railway managed) |
| **Deployment** | Railway.app |
| **Payments** | Stripe |
| **Email** | Resend |
| **SMS** | Twilio |
| **Frontend** | HTMX + Tailwind CSS |

## 📖 Chapters

| Chapter | Status | Description |
|---------|--------|-------------|
| 1 | ⏳ Coming Soon | Hermes Agents Overview |
| 2 | ⏳ Coming Soon | Tool System Deep Dive |
| 3 | ⏳ Coming Soon | Skills & Automation |
| 4 | ⏳ Coming Soon | Multi-Agent Workflows |
| 5 | ⏳ Coming Soon | Database & Models |
| 6 | ⏳ Coming Soon | API Development |
| 7 | ⏳ Coming Soon | Frontend Integration |
| 8 | ⏳ Coming Soon | Railway Deployment |
| 9 | ⏳ Coming Soon | Monitoring & Observability |
| 10 | ⏳ Coming Soon | Maintenance & Iteration |

## 🎯 Learning Outcomes

After completing this book, you will be able to:

- ✅ Build autonomous AI agents with Hermes
- ✅ Design multi-agent workflows
- ✅ Deploy production APIs on Railway
- ✅ Integrate payments, email, and SMS
- ✅ Implement monitoring and alerting
- ✅ Manage production deployments

## 🤝 Contributing

Contributions welcome! This is a living textbook.

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

MIT License — Free for personal and commercial use.

## 🙏 Acknowledgments

Built with:
- [Hermes Agents](https://github.com/hermes-agents/hermes)
- [FastAPI](https://fastapi.tiangolo.com/)
- [Railway](https://railway.app/)
- Coffee ☕

---

**First Edition** | 2026 | Jesse J. Collins & Markus Hermes

🐢 *Process > Results. Ship early, ship often.*
