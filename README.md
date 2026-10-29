# Cześć, tu Andrzej Kowalczyk 👋
### AI Citizen Developer & Systems Architect | Python • FastAPI • React • Agentic Automations • Zero-Trust Security

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Andrzej_Kowalczyk-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/andrzej-kowalczyk)
[![Security](https://img.shields.io/badge/Protocol-AGOS_4.1_Zero--Trust-success?style=flat&logo=shield)](https://github.com/kowalenko486-tech/agos-audit-)
[![Python](https://img.shields.io/badge/Python-3.12-blue?style=flat&logo=python)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-Production_Ready-009688?style=flat&logo=fastapi)](https://fastapi.tiangolo.com/)
[![React](https://img.shields.io/badge/React-19_&_Next.js-61DAFB?style=flat&logo=react)](https://react.dev/)

Łączę ponad 20 lat praktycznego doświadczenia operacyjno-wdrożeniowego (koncern WAGO Elwag) z nowoczesnym programowaniem (**FastAPI, React 19, TypeScript, Docker**) i inżynierią agentów AI. 

Zamiast wykonywać powtarzalną pracę ręcznie, buduję bezpieczne, deterministyczne systemy cyfrowe, które eliminują wąskie gardła, przetwarzają dokumenty i oszczędzają ludziom setki godzin żmudnej pracy.

---

## 🛠️ Filozofia Inżynierska: Deterministyczne AI (Zero-Hallucination)
W aplikacjach biznesowych, księgowych i operacyjnych nie ma miejsca na halucynacje modeli LLM. Moje rozwiązania opierają się na architekturze **Pydantic Gate**:
1. **AI Intake:** Modele językowe (OpenAI Structured Outputs, Gemini, Claude) odpowiadają za parsowanie, zrozumienie kontekstu i ekstrakcję danych z niestrukturyzowanych dokumentów.
2. **Deterministyczna Bramka Walidacji:** Rygorystyczny schemat Pydantic weryfikuje poprawność arytmetyczną (np. $\sum netto + VAT = brutto$), sumy kontrolne (NIP mod-11, IBAN mod-97) i formaty danych.
3. **Bezpieczny Rdzeń Transakcyjny:** Wyłącznie w 100% zwalidowane dane trafiają do bazy (PostgreSQL / SQLite) lub zewnętrznych systemów ERP / API księgowych.

---

## 🚀 Wyróżnione Projekty & Repozytoria

### 1. [LogjiParse](https://github.com/kowalenko486-tech/LogjiParse) — AI Document & Invoice Parsing Microservice
*Mikrousługa w FastAPI do automatycznej ekstrakcji i strukturyzacji danych z dokumentów biznesowych (faktury, zlecenia, CMR).*
* **Tech:** Python 3.12, FastAPI, OpenAI API Structured Outputs, Pydantic v2, ReportLab PDF, Stripe & Webhooks, Supabase.
* **Kluczowe cechy:** Zamiana niestrukturyzowanego tekstu/dokumentu w ścisły schemat JSON, automatyczne generowanie czytelnych raportów PDF oraz integracja płatności.

### 2. [AGOS 4.1 Security & DLP Audit](https://github.com/kowalenko486-tech/agos-audit-) — Standalone External Security Validator
*W pełni niezależna paczka walidacji bezpieczeństwa aplikacji zintegrowanych z AI i systemami zewnętrznymi.*
* **Tech:** Python, Pytest, Docker, GitHub Actions CI, AST Static Analyzer.
* **Kluczowe cechy:** 
  * Egress DLP & TokenVault: matematyczna walidacja sum kontrolnych **NIP (modulo-11)**, **IBAN (ISO mod-97)**, **PESEL (modulo-10)**, kart płatniczych (**algorytm Luhna**) oraz maskowanie danych wrażliwych (PII).
  * AST-SAST & Anti-Slopsquatting (ochrona przed podatnościami `eval`, `shell=True` oraz halucynowanymi bibliotekami).
  * Odporność na Prompt Injection (benchmark 122 scenariuszy InjecAgent).

### 3. InstallerCRM — Dedykowany System CRM / ERP dla Branży OZE & HVAC
*Kompleksowy system operacyjny (Single-Tenant / On-Premise) łączący frontend React 19 z backendem FastAPI.*
* **Tech:** FastAPI, SQLAlchemy 2.0, React 19, TailwindCSS, Gemini 2.5 Flash, ReportLab, Docker Compose, Caddy.
* **Kluczowe cechy:** Hybrydowy intake zapytań (AI + Regex) $\rightarrow$ Pydantic Gate $\rightarrow$ silnik wycen ROI i automatyczne generowanie 10-stronicowych ofert PDF. Szyfrowanie wrażliwych danych at-rest (**Fernet AES-128**).

### 4. BlindCV SaaS — Platforma Rekrutacyjna z Płatnościami
*Narzędzie SaaS do automatycznej anonimizacji danych osobowych (PII/RODO) w dokumentach aplikacyjnych.*
* **Tech:** Next.js 15, TypeScript, Tailwind CSS, Supabase (PostgreSQL RLS, triggery), Lemon Squeezy (webhooki HMAC SHA-256).

### 5. DockTime — Yard Management & Ramp Slot Booking System
*System rezerwacji okien czasowych na rampach i zarządzania placem manewrowym.*
* **Tech:** React, Vite, Node.js, Express, MongoDB, autorski Geofencing GPS (formuła Haversine'a), CI/CD na Railway.

---

## 💻 Stos Technologiczny

```text
Backend:           Python 3.12 (FastAPI, SQLAlchemy 2.0, Pydantic v2, Celery/AsyncIO), Node.js, Express
Frontend:          React 19, Next.js (App Router), TypeScript, JavaScript (ES6+), Tailwind CSS, Vite
Bazy Danych:       PostgreSQL (Row Level Security - RLS), Supabase, SQLite, MongoDB
Agentic AI / LLM:  OpenAI API, Google Gemini, Claude, RAG, n8n, Prompt Engineering
Bezpieczeństwo:    Data Loss Prevention (DLP), TokenVault, Szyfrowanie AES-128 Fernet, OWASP Top 10 LLM
DevOps & Cloud:    Docker, Docker Compose, Caddy, Cloudflare Tunnel, GitHub Actions, Vercel, Railway
Enterprise / RPA:  SAP EWM, Microsoft Power Automate Desktop & Cloud, Power Apps, SharePoint
```

---

## 📬 Kontakt

* **E-mail:** [Kowalenko486@gmail.com](mailto:Kowalenko486@gmail.com)
* **Telefon:** +48 793 584 371
* **Lokalizacja:** Wrocław / Dobrzykowice, Polska
* **LinkedIn:** [linkedin.com/in/andrzej-kowalczyk](https://linkedin.com/in/andrzej-kowalczyk)
