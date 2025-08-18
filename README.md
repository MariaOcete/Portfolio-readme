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

## Tech Stack

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/tailwindcss/tailwindcss-original.svg" alt="Tailwind CSS" title="Tailwind CSS" height="28" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg" alt="React" title="React" height="28" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vitejs/vitejs-original.svg" alt="Vite" title="Vite" height="28" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/django/django-plain.svg" alt="Django" title="Django" height="28" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" alt="Python" title="Python" height="28" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vercel/vercel-original.svg" alt="Vercel" title="Vercel" height="28" />
</p>
    
          
          


**Frontend:** React, Vite, Tailwind CSS, react-i18next, react-toastify, react-icons  
**Backend (contact endpoint):** Django, SMTP email, IP rate‑limiting, CORS  
**Infra:** Vercel (hosting/SSL), Render (API), Porkbun (DNS)


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
