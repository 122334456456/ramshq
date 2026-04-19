# 🦺 RAMS HQ

**AI-Powered Health & Safety Intelligence Platform**

Generate, analyse and score Risk Assessment & Method Statements aligned to IOSH, NEBOSH and UK HSE standards — in under 60 seconds.

🌐 Live: [myramshq.com](https://myramshq.com)

---

## Features

- ⚡ Plain English → Full RAMS generation
- 🔍 AI gap analysis against IOSH & NEBOSH frameworks  
- 🦺 PPE with exact EN ISO standards
- 📊 RAMS Quality Score dashboard (0–100)
- 🌍 Multi-jurisdiction mode (UK / EU / UAE / US)
- 📸 Photo-to-hazard AI
- 🔔 Live regulation alerts
- 🎓 Toolbox Talk generator + interactive 10-question knowledge test
- 🧠 Organisational learning
- ⚖️ Liability Confidence Score

---

## Routes

| URL | App |
|-----|-----|
| `myramshq.com/` | Web App (desktop) |
| `myramshq.com/mobile` | Mobile App (phone simulator) |

---

## Getting Started

### Prerequisites
- Node.js 18+
- npm or yarn

### Install & Run Locally

```bash
# Install dependencies
npm install

# Start dev server (http://localhost:3000)
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

---

## Deploy to Vercel

### Option 1 — GitHub (recommended)

1. Push this folder to a GitHub repository
2. Go to [vercel.com](https://vercel.com) → **Add New Project**
3. Import your GitHub repository
4. Vercel auto-detects Vite — just click **Deploy**
5. Add your custom domain `myramshq.com` in **Settings → Domains**

### Option 2 — Vercel CLI

```bash
npm install -g vercel
vercel
```

---

## DNS Configuration (myramshq.com)

In your domain registrar, add these DNS records:

| Type  | Host | Value |
|-------|------|-------|
| A     | @    | `76.76.21.21` |
| CNAME | www  | `cname.vercel-dns.com` |

---

## Project Structure

```
ramshq/
├── public/
│   └── favicon.svg
├── src/
│   ├── App.jsx          ← Web app (desktop)
│   ├── Mobile.jsx       ← Mobile app (phone simulator)
│   ├── main.jsx         ← Entry point + routing
│   └── index.css        ← Global styles
├── index.html
├── package.json
├── vite.config.js
├── vercel.json
└── .gitignore
```

---

## Tech Stack

- **Frontend:** React 18 + Vite
- **AI:** Anthropic Claude API (claude-sonnet-4)
- **Hosting:** Vercel
- **Domain:** myramshq.com

---

## Legal

⚠️ All AI-generated RAMS documents are drafts only. They must be reviewed and approved by a competent Health & Safety professional before use on site. RAMS HQ accepts no liability for documents used without professional review.

---

© 2025 RAMS HQ Ltd
