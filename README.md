<div align="center">

# James Rio Abaquita

**Full Stack Developer** — building production SaaS on Laravel, Next.js, and React.

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://jamesrio.tech)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/james-rio-abaquita-40992a331/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jamesabaquitar@gmail.com)

</div>

---

## About

A Graduate B.S. IT student who ships real software. I've contributed to an enterprise SaaS suite at Infinity Hub and built my own multi-tenant SaaS platform — Sursur and Gradoo — from architecture to deployment. I work across the full stack: database schema, API design, frontend UX, and real-time systems. Occasionally extends into IoT and ML when the project calls for it. CCNA-certified.

---

## Work Experience

**Full Stack Developer — Internship** · Infinity Hub Digital Marketing *(Feb 2026 – May 2026)*

Contributed across ManPro: a 3-platform enterprise SaaS suite (HRMS, Manual, LMS) serving HR, payroll, and learning for multiple enterprise clients.

- Architected cross-app SSO unifying 3 platforms with tokenized POST login, role-aware routing, and identity context enrichment
- Built a RAG-style AI assistant with embedding-based retrieval.
- Delivered an ESP32 + AS608 fingerprint attendance prototype with offline-first NVS buffering and UUID idempotency, fully integrated with payroll
- Led full RBAC migration across backend and frontend, removing all legacy permission paths from production in LMS

---

## Projects

### [Laravel Headless API](https://api.sursur.tech/docs/api) — Multi-Tenant SaaS Backend
> The backbone powering Sursur, Gradoo, and the broader platform.

`Laravel 13` `PHP 8.4` `stancl/tenancy` `Sanctum` `Stripe` `Reverb` `Horizon` `Pest`

- Isolated MySQL database per tenant with token-ability-based tenancy resolution
- Full Stripe checkout → webhook → tenant provisioning pipeline with signature verification
- 6 custom middleware layers across 80+ endpoints: tenant init, quota, module guards, subscription checks, dynamic CORS

---

### [Sursur](https://sursur.tech) — SaaS Platform Frontend
> Super-admin control plane for managing tenants, apps, and the platform.

`Next.js 16` `React 19` `TypeScript` `TanStack Query` `Shadcn UI` `Laravel Echo`

- Tenant approval, rejection, and admin impersonation flows with Sanctum token swapping
- Cookie-based proxy auth via Next.js API routes — tokens never exposed to the browser
- Edge middleware route protection + real-time updates via Reverb

---

### [Gradoo](https://beta.gradoo.sursur.tech) — Classroom & Grading SaaS
> A proper grading system for educators, not just a CRUD app.

`Next.js 16` `React 19` `TypeScript` `TanStack Query & Table` `Zod` `SheetJS`

- Subdomain-based multi-tenant routing via Next.js edge middleware (tenant slug extracted from hostname)
- Weighted grading engine: configurable Prelim / Midterm / Finals components + grade finalization workflows
- Batch enrollment via spreadsheet import (SheetJS), attendance session management, group task tracking

---

### [Project Imago](https://demo.imago.jamesrio.tech) — E-Commerce Platform
> Editorial streetwear store with a real operations backend.

`Laravel 12` `Livewire 4` `Filament v5` `Reverb` `Tailwind CSS 4`

- 5-stage Kanban order board with inventory deduction on ship, stock restoration on cancel, and transition guards
- GCash payment verification + guest checkout via persistent UUID tokens (no accounts required)
- Role-based admin panel (5 roles), ledger view with `.xlsx` / `.csv` export, real-time WebSocket sync

---

### [AgriGuard](https://github.com/JamesRioA/AgriGuard) — IoT Bird Deterrence System *(Capstone)*
> Hardware-software hybrid protecting rice fields from bird predation.

`C++` `ESP32` `YOLOv8` `Laravel` `Vue` `MQTT` `RTSP`

- Custom YOLOv8 model trained on a proprietary Chestnut Munia bird dataset
- ESP32 + Raspberry Pi 4 mesh via MQTT and RTSP, sub-second actuator response
- Offline-first Vue.js dashboard for field monitoring without internet connectivity

---

## Tech Stack

| | |
|:---|:---|
| **Backend** | Laravel · Livewire · Filament · PHP 8.4 · Node.js · Express |
| **Frontend** | Next.js · React · Vue · TypeScript · Tailwind CSS · TanStack Query · Shadcn UI |
| **Databases** | MySQL · PostgreSQL · MongoDB |
| **Real-time** | Laravel Reverb · Echo · WebSockets · MQTT |
| **AI / ML** | YOLOv8 · RAG · Embedding-based Retrieval |
| **IoT** | ESP32 · Raspberry Pi · C++ · PlatformIO · UART |
| **Infra** | Linux · Docker · Git · CI/CD · Vercel · OpenAPI/Scramble |

---

## Education & Certifications

**B.S. Information Technology** — Bukidnon State University *(Aug 2022 – Jun 2026)* · **Magna Cum Laude**

- 🏆 **Web Developer of the Year** & **Network Expert of the Year** — BukSU IT Department
- 🏅 Cisco Certified Network Associate (CCNA) 1–3 — Network Fundamentals, Switching & Routing
- 🛡️ Introduction to Cybersecurity — Cisco Networking Academy
- ASEAN Green Entrepreneurship Hackathon — Participant *(May–Jul 2025)*
- DICT HackForGov4 — Regional Hackathon *(Nov 2025)*
- Cisco AJPC NetAcad Riders — APJC Region Recognition *(Mar 2025)*

---

<p align="center">
  <img src="https://github-readme-stats-eight-theta.vercel.app/api?username=JamesRioA&show_icons=true&theme=transparent&hide_border=true&title_color=3B82F6&text_color=555&count_private=true" alt="GitHub Stats" />
  &nbsp;
  <img src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=JamesRioA&layout=compact&theme=transparent&hide_border=true&title_color=3B82F6&text_color=555&hide=html,css&langs_count=6" alt="Top Languages" />
</p>
