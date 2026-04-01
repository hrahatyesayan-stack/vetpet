# 🐾 VetPet — Pet Health & Telemedicine App

> **AI-powered health tracking + video vet consultations for dogs and cats**

VetPet is a mobile app focused on **4 core features** for pet owners:

🤖 **AI Symptom Checker** — Describe symptoms → get urgency level (green/yellow/red). Species-specific: cat not eating 24h = EMERGENCY, dog = observation. 25 hardcoded clinical rules + OpenAI GPT-4o.

📹 **Vet Video Calls** — Book and video-call a licensed veterinarian. Species-specific pre-visit forms. Cat Friendly certified vets. Diagnosis + prescriptions in-app.

🗺 **Care Roadmap** — Breed-specific health timeline: vaccinations, checkups, dental, neutering, senior screenings. Auto-generated from 400+ dog and 70+ cat breed profiles.

💯 **Wellness Score** — Daily tracking (food, water, walks/play, sleep) → score 0-100. Cat-specific: water intake alerts for CKD prevention.

-----

## 🛠 Tech Stack

|Layer      |Technology                 |
|-----------|---------------------------|
|Mobile     |React Native + Expo SDK 52 |
|Backend    |NestJS 10 + TypeScript     |
|Database   |PostgreSQL 16              |
|Cache      |Redis 7                    |
|Video Calls|Daily.co SDK               |
|AI         |OpenAI GPT-4o              |
|Push       |Firebase Cloud Messaging   |
|Payments   |Payment gateway integration|
|Monorepo   |Turborepo                  |
|CI/CD      |GitHub Actions + Expo EAS  |

## 📊 Database: ~17 Tables

- **Core:** User, Pet, Breed, PetPhoto
- **Health:** HealthRecord, Vaccination, Medication, WellnessLog, ActivityLog, CareTemplate, CareRoadmapItem
- **Vet:** VetProfile, Consultation, AiTriageSession, TriageRule
- **Payments:** Subscription, Payment

**Key principle:** `species` (dog/cat) is the primary dimension across all tables.

-----

## 🎯 Roadmap: 16 Steps, 8 Weeks

### Phase 0: Infrastructure (Week 1)

- [x] Monorepo (Turborepo + apps + packages) ✅
- [ ] Docker (PostgreSQL + Redis)
- [ ] Database schema (~17 tables)
- [ ] Auth (Phone + OTP + JWT)
- [ ] CI/CD

### Phase 1: Core Screens (Weeks 2-4)

- [ ] Mobile navigation (4 tabs) + UI Kit
- [ ] Onboarding + pet profiles (400 dog breeds + 70 cat breeds)
- [ ] Dashboard + Wellness Score (species-adaptive)
- [ ] AI Symptom Checker (25 hardcoded rules + OpenAI)
- [ ] Care Roadmap (breed-specific milestones)

### Phase 2: Telemedicine + Payments (Weeks 5-7)

- [ ] Vet video consultations (Daily.co)
- [ ] AI Chatbot “Buddy”
- [ ] Subscriptions + payment integration

### Phase 3: Polish + Launch (Week 8)

- [ ] Multi-language support
- [ ] Push notifications (FCM)
- [ ] Launch prep + deploy

-----

## 🤝 Hiring: Full-Stack Developer

**This is a paid project** with complete documentation ready.

### We Need

- React Native + Expo (2+ years)
- NestJS + TypeScript (2+ years)
- PostgreSQL + TypeORM
- REST API design

### We Provide

- Complete Technical Specification (screen-by-screen walkthrough)
- 16-step development plan with exact implementation details
- Database schema (17 tables, ready to implement)
- 400+ dog breeds + 70+ cat breeds with health data
- 25 species-specific clinical triage rules
- Initialized Turborepo monorepo

### Timeline & Budget

- **8 weeks** total
- **$3,000 — $7,000** (milestone-based payments)
- Remote OK

### How to Apply

Open an Issue: `[Application] Your Name — Full-Stack Developer`

Include: GitHub profile, 2-3 relevant projects, availability, rate.

See `docs/DEVELOPER_BRIEF.md` for full details.

-----

## 📄 Documentation

|Document                 |Description                |
|-------------------------|---------------------------|
|`docs/MASTER_PLAN.md`    |16-step development plan   |
|`docs/DEVELOPER_BRIEF.md`|Full job posting with scope|

-----

**Built with ❤️ for pets**
