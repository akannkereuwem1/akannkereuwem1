<div align="center">

# Akan Nkereuwem
### Software Engineer| Backend Systems · Mobile Development · AI Integration

[![Portfolio](https://img.shields.io/badge/Portfolio-akan--nkereuwem.dev-000000?style=flat&logo=safari&logoColor=white)](https://akan-nkereuwem.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/akan-nkereuwem)
[![Email](https://img.shields.io/badge/Email-akannkereuwem@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:akannkereuwem@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-akannkereuwem1-181717?style=flat&logo=github&logoColor=white)](https://github.com/akannkereuwem1)

**Nigeria 🇳🇬 · Open to Remote · Available for Work**

</div>

---

## About

Software engineer with a focus on **backend systems**, **cross-platform mobile development**, and **AI-integrated products**. I build things that are reliable under pressure and designed to last: not just to ship.

My work spans layered REST APIs with strict architectural separation, Flutter applications engineered for offline-first UX, and multi-agent AI pipelines with compliance guardrails. Currently studying Computer Science (B.Sc., expected 2027) and deepening my understanding of event-driven architecture and serverless design patterns.

> *"As AI reshapes what's possible in software, I'm focused on being the kind of engineer who understands systems deeply enough to direct it well."*

---

## Engineering Philosophy

| Principle | Implementation |
|-----------|----------------|
| **Observability as a Prerequisite** | Logs, metrics, and distributed tracing before anything goes to production |
| **Operational Maturity over Novelty** | Battle-tested stacks chosen over trend-chasing |
| **Iterative Delivery & Rapid Feedback** | Ship functional versions early, iterate on real-world data |
| **Architecture First** | Business logic in service layers — views stay thin, tests stay fast |
| **Compliance by Design** | Security, rate limits, and legal guardrails enforced at the architecture layer |

---

## Technical Toolkit

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

### Backend & APIs
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=flat&logo=express&logoColor=white)

REST API design · JWT & OAuth 2.0 · Role-Based Access Control · Async programming · API versioning · Third-party service integration · WebSockets

### Mobile Development
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)
![React Native](https://img.shields.io/badge/React%20Native-61DAFB?style=flat&logo=react&logoColor=black)

Cross-platform iOS & Android · Offline-first architecture · Riverpod state management · GoRouter navigation · Hive local storage · Stripe payment integration · FCM push notifications

### Databases
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)

Query optimization · Indexing strategies · Schema design · SQLAlchemy · Prisma · Migration management

### AI & Automation
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI%20API-412991?style=flat&logo=openai&logoColor=white)

Machine learning fundamentals · AI API integration (OpenAI, Google Vision) · Multi-agent pipeline design · Prompt engineering · Data processing & automation · AI-enhanced application architecture

### DevOps & Infrastructure
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=github-actions&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)

CI/CD pipelines · Heroku · Railway · DigitalOcean · Gunicorn · Linux

### Testing
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)

TDD · Unit & integration testing · Property-based testing (Hypothesis) · 85–90%+ coverage standards

---

## Featured Projects

### AgroNet — Agricultural Marketplace API `● in-progress`

> Mobile backend REST API connecting Nigerian smallholder farmers directly to buyers, removing middlemen from the agricultural supply chain.

Built on a strict **Views → Services → Models** layered architecture with Django REST Framework. Business logic is isolated in service modules — views stay thin and deterministic. External integrations (Interswitch payments, Google Vision image classification, TensorFlow price prediction) are decoupled into dedicated service modules so they fail gracefully without breaking core order flow.

**Key Technical Decisions:**
- Custom DRF permission classes enforce `farmer/buyer` RBAC at the permission layer
- Order lifecycle managed as a state machine preventing illegal state transitions (`pending → confirmed → paid → completed`)
- Property-based tests via Hypothesis validate correctness properties across randomised inputs
- AI price prediction and image classification services isolated to fail independently of core business logic

**Stack:** `Python 3.11` · `Django 6` · `Django REST Framework` · `PostgreSQL` · `SimpleJWT` · `TensorFlow` · `Google Vision API` · `Interswitch` · `Cloudinary` · `Docker` · `Gunicorn` · `drf-spectacular`

[GitHub →](https://github.com/akannkereuwem1/agro-net/) · [Live API Docs →](https://agronet-backend-02382983bf13.herokuapp.com/api/docs/)

---

### Signature Scent — Flutter E-Commerce Mobile App `● live`

> Full-stack premium e-commerce mobile app (iOS & Android) for a local perfume boutique, engineered for offline-first UX and a premium Belle Époque visual identity.

Implemented a strict **Presentation → Domain ← Data** Flutter architecture so the UI is completely decoupled from backend concerns. All remote calls route through repository abstractions backed by Dio, with Hive caching enabling full offline browsing. The Node.js/Express backend is stateless and swappable without touching any Flutter layers.

**Key Technical Decisions:**
- Stripe payment sheet with server-side `PaymentIntent` creation — amount calculated from DB, never trusted from the client
- Webhook-confirmed order status polling to handle async payment confirmation
- Cache invalidation strategy for wishlist/cart state sync between offline Hive store and server
- 90%+ domain layer test coverage with 26 correctness properties validated via property-based tests

**Stack:** `Flutter` · `Dart` · `Riverpod` · `GoRouter` · `Hive` · `Node.js` · `Express` · `TypeScript` · `PostgreSQL` · `Stripe` · `Firebase Cloud Messaging` · `Docker` · `JWT`

[GitHub →](https://github.com/akannkereuwem1/signature-scent-mobile-application)

---

### Compliant Internship Outreach Automation `● live`

> Compliance-first, multi-agent Python pipeline that discovers Nigerian tech companies, extracts public HR contacts, and sends personalised outreach — controlled via a Telegram bot.

Built on a **Directive-Orchestration-Execution (DOE)** architecture: Directives are markdown SOPs defining agent behavior; the Orchestrator sequences the pipeline and validates output contracts; deterministic Python Execution scripts carry out each step. Compliance is enforced structurally — `robots.txt` is always respected, rate limits are hard-coded (15 emails/day, 5 emails/hour, 120s minimum delay between sends), and a do-not-contact list is checked before every send.

**Key Technical Decisions:**
- DOE architecture separates agent behavior definitions from orchestration logic from execution — each layer is independently testable
- Async Telegram bot event loop kept non-blocking despite multi-tier rate limiting on the send pipeline
- Zero compliance violations logged across all sends; 100% delivery rate, 0% bounce rate on initial run

**Stack:** `Python` · `SQLite` · `Gmail SMTP` · `Google Sheets API` · `Telegram Bot API` · `BeautifulSoup4` · `DuckDuckGo Search` · `gspread`

---

### WriteFlow API — Production-Grade Blogging Platform

> Scalable REST API powering modern content platforms with social features, personalised feeds, and real-time pagination.

**Metrics:** 5,000+ concurrent users · sub-200ms response times · 65% feed query time reduction via PostgreSQL indexing · 85% test coverage

**Stack:** `Flask` · `SQLAlchemy` · `Marshmallow` · `PostgreSQL` · `Docker` · `Redis` · `pytest`

[GitHub →](https://github.com/akannkereuwem1/writeflow-api)

---

### AFE E-Commerce (Blockchain) — 1st Place Hackathon Winner

> Decentralised marketplace with on-chain product verification via STORY Protocol, solving counterfeiting in e-commerce.

Built a full-stack decentralised marketplace in 48 hours. Deployed to production with 99% uptime.

**Stack:** `STORY Protocol` · `Smart Contracts` · `Web3.js` · `React.js`

[Live Demo →](https://afe-ecommerce-onchain.vercel.app/) · [GitHub →](https://github.com/akannkereuwem1/afe-ecommerce-onchain)

---

## Career Highlights

```python
profile = {
    "name": "Akan Nkereuwem",
    "focus": ["Backend Systems", "Mobile Development", "AI Integration"],
    "currently_building": "AgroNet — mobile backend API for Nigerian agricultural supply chain",
    "currently_learning": ["Event-driven architecture", "Serverless design patterns"],
    "currently_reading": "Fundamentals of Software Architecture — Mark Richards",
    "experience": {
        "orpion_tech": {
            "role": "Backend Developer",
            "apis_served": "50K+ monthly active users",
            "performance_gain": "60% latency reduction via DB optimization",
            "test_coverage": "85%+ across all production codebases",
        }
    },
    "achievements": {
        "hackathon": "1st Place — STORY Protocol Blockchain Hackathon 2025",
        "certifications": [
            "Data Structures & Algorithms Specialization — Coursera (2024)",
            "Software Development Professional Certificate — Digital for All (2023)",
        ],
    },
    "education": "B.Sc. Computer Science (Expected 2027) · GPA: 4.5/5.0",
}
```

---

## Professional Experience

### Backend Developer — Orpion Tech `2022 – Present`

Architected and shipped RESTful APIs serving 50K+ monthly active users across Fintech, SaaS, and E-commerce platforms.

- Optimised database performance through indexing strategies and query restructuring, reducing response latency by 60%
- Led containerisation initiative migrating legacy applications to Docker, cutting deployment time from hours to minutes
- Implemented JWT authentication, RBAC, and input validation across all microservices
- Established test culture achieving 85%+ code coverage and reducing production bugs by 40%
- Collaborated with cross-functional teams translating business requirements into scalable backend architecture

**Stack:** Python · Django · FastAPI · PostgreSQL · Redis · Docker · AWS S3 · GitHub Actions

---

## Education

**B.Sc. Computer Science** (Expected 2027) · GPA: 4.5/5.0  
Focus: Software Engineering · Data Structures · Database Systems

**Certifications:**
- Data Structures & Algorithms Specialization — Coursera (2024)
- Software Development Professional Certificate — Digital for All (2023)
- Currently studying: System Design · Microservices Architecture · AWS · Serverless Patterns

---

## Upcoming Technical Writing `Q2 2026`

- *Building Scalable REST APIs: A Production Engineer's Guide*
- *Database Optimization: From 5 Seconds to 50ms*
- *System Design Fundamentals for Backend Engineers*

Topics: Microservices · API security · Performance optimization · Test-Driven Development · Distributed systems

---

## Let's Connect

I'm open to engineering roles, freelance projects, and technical collaborations. If you have something worth building, let's talk.

<div align="center">

📧 [akannkereuwem@gmail.com](mailto:akannkereuwem@gmail.com) · 🔗 [linkedin.com/in/akan-nkereuwem](https://linkedin.com/in/akan-nkereuwem) · 🌐 [akan-nkereuwem.dev](https://akan-nkereuwem.dev)

**Nigeria 🇳🇬 · Open to Remote Work Worldwide**

[![GitHub followers](https://img.shields.io/github/followers/akannkereuwem1?label=Follow&style=social)](https://github.com/akannkereuwem1)

</div>