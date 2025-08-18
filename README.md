# María Ocete — [Portfolio](https://mariaocete.com)

 
**Email:** mariaocete93@gmail.com  
**GitHub:** https://github.com/MariaOcete  
**LinkedIn:** https://www.linkedin.com/in/maria-ocete-martin/  

A bilingual (EN/ES) portfolio showcasing my work as a **Full‑Stack Web Developer**.  
Frontend built with **React + Vite + Tailwind**, talking to a minimal **Django** API (secure contact form).

---

## Highlights
- ⚡ **Fast, clean UI** (React + Vite + Tailwind)
- 🌍 **English/Spanish** via `react-i18next` (language preference persists)
- 🔒 **Secure contact form** — reCAPTCHA v2, server verification, IP rate‑limit
- ☁️ **Production deploys** — Vercel (frontend) + Render (API) on custom domain with SSL
- 🔗 **SPA rewrites** — deep links like `/about`, `/projects`, `/contact` don’t 404

---

## Tech Stack <p>
  <img alt="React" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="32" />
  <img alt="Vite" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vite/vite-original.svg" height="32" />
  <img alt="Tailwind" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-plain.svg" height="32" />
  <img alt="Django" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/django/django-plain.svg" height="32" />
  <img alt="Vercel" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vercel/vercel-original.svg" height="32" />
</p>

**Frontend:** React, Vite, Tailwind CSS, react-i18next, react-toastify, react-icons  
**Backend (contact endpoint):** Django, SMTP email, IP rate‑limiting, CORS  
**Infra:** Vercel (hosting/SSL), Render (API), Porkbun (DNS)

**Frontend:** React, Vite, Tailwind CSS, react-i18next, react-toastify, react-icons  
  
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=ffffff)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=ffffff)
![i18next](https://img.shields.io/badge/i18next-26A69A?style=flat-square&logo=i18next&logoColor=ffffff)
![React Toastify](https://img.shields.io/badge/React_Toastify-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![React Icons](https://img.shields.io/badge/React_Icons-20232A?style=flat-square&logo=react&logoColor=61DAFB)

**Backend (contact endpoint):** Django, SMTP email, IP rate‑limiting, CORS  
  
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=ffffff)
![SMTP](https://img.shields.io/badge/SMTP-3B82F6?style=flat-square&logo=minutemailer&logoColor=ffffff)
![IP rate-limiting](https://img.shields.io/badge/IP_rate%E2%80%91limiting-555555?style=flat-square)
![CORS](https://img.shields.io/badge/CORS-555555?style=flat-square)

**Infra:** Vercel (hosting/SSL), Render (API), Porkbun (DNS)  
  
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=ffffff)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=111111)
![Porkbun (DNS/SSL)](https://img.shields.io/badge/Porkbun_(DNS%2FSSL)-FF6A8A?style=flat-square)

---

## Architecture Snapshot
```
Browser
  └── React SPA (Vite + Tailwind)
        ├─ i18n (EN/ES)
        ├─ Routes: /, /about, /projects, /contact
        └─ Form → POST /api/contact/submit
                         │
                         ▼
                 Django API (Render)
                   ├─ Verify reCAPTCHA v2
                   ├─ Rate‑limit by IP
                   └─ Send email via SMTP
```

---

## Project Structure (short)
```
/
├─ src/                # routes, pages, components, i18n
├─ public/             # static assets
├─ vercel.json         # SPA rewrites
└─ .nvmrc              # Node 20 for consistent builds
```

**Good places to review**
- `src/i18n/*` — i18next setup (EN/ES), persistent language
- `src/pages/Contact.jsx` — reCAPTCHA, validation, toasts, API call
- `src/components/*` — reusable UI, accessibility (labels, keyboard handling)

---

## Screenshots
> A few views from the live site.

![Home](https://github.com/user-attachments/assets/5149eadc-5998-4619-beeb-2025972807c5)
![About](https://github.com/user-attachments/assets/50022591-4ea1-48e6-ba2d-5761e4c951e1)
![Projects](https://github.com/user-attachments/assets/d9781f8b-86c0-4799-915d-225a64f73d96)
![Contact](https://github.com/user-attachments/assets/9c180cbc-a921-4054-8afe-e44450f4e377)

---

## Why this project?
- Demonstrates **end‑to‑end ownership**: clean UI, secure API, production deploy, domain/DNS/SSL.  
- Focus on **reliability & clarity**: reCAPTCHA, error toasts, accessible components, readable code & comments.

---

## Contact
Questions or feedback? I’m happy to share more details (including API code).  
**mariaocete93@gmail.com**
