# IntelliWheels - Capstone Project

## AI-Powered Automotive Marketplace

IntelliWheels is a full-stack AI-powered automotive marketplace designed for the Jordanian and GCC market. It transforms traditional car buying and selling by leveraging Generative AI to provide a conversational, contextual, and personalized car discovery experience.

> **Note:** This project documentation is provided for portfolio demonstration only. Source code is proprietary and not included in this repository.

---

## Project Overview

IntelliWheels addresses key challenges in the used car market:

- **Information Overload** — Buyers struggle to navigate thousands of listings without expert guidance
- **Lack of Price Transparency** — No reliable way to assess fair market value
- **Language Barriers** — Full bilingual support (Arabic + English) with RTL layout
- **Cold-Start Problem** — Traditional recommendation systems fail without user history; IntelliWheels uses conversational AI instead

---

## Core Features

| Feature | Description |
|---------|-------------|
| **AI Chatbot** | Conversational car assistant powered by Google Gemini 2.5 Flash (bilingual) |
| **Vision AI** | Upload a car photo → AI identifies make, model, year, and estimated price |
| **Price Estimation** | Rule-based expert system for fair market value assessment |
| **Semantic Search** | Natural language queries (e.g., "family SUV under 20,000 JOD with good mileage") |
| **Car Listings** | Users list and browse cars with images, videos, and specs |
| **Dealer Network** | Admin-verified dealers with dedicated Dealer Hub for inventory management |
| **Messaging** | Direct buyer-seller communication |
| **Reviews & Favorites** | Car ratings and personal wishlist system |

---

## Technology Stack

| Layer | Technologies |
|-------|-------------|
| **Frontend** | Next.js 16, React 19, TypeScript 5, Tailwind CSS 3.4, Leaflet (maps) |
| **Backend** | Python, Flask 3.0, Gunicorn, SQLAlchemy |
| **AI/ML** | Google Gemini 2.5 Flash (Chatbot + Vision), Rule-Based Expert System (Pricing), Keyword Scoring (Search) |
| **Database** | SQLite (dev) / PostgreSQL (prod) |
| **Cloud** | Vercel (frontend), Render (backend), Cloudinary (media CDN) |
| **Auth** | Google OAuth, session-based authentication with PBKDF2 hashing |

---

## Project Documents

| Document | Description |
|----------|-------------|
| `IntelliWheels-Banner.pdf` | Visual project overview and key highlights |

> Additional project documents (report, test plan, presentation) are available upon request.

---

## Team

| Name | Role |
|------|------|
| **Hamza Ja'bari** | Co-Founder / Developer |
| **Amro Freihat** | Co-Founder / Developer |
| **Muhannad Al Melhim** | Co-Founder / Developer |

**Supervised by:** Dr. Aya Karajeh  
**Degree:** B.Sc., Fall 2025–2026  
**Domain:** [intelliwheels.co](https://intelliwheels.co)

---

*This capstone project was completed as part of my B.Sc. program.*
