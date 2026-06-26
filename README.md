# Nexus AI — Landing Page

A premium SaaS landing page for an AI automation platform, built with pure HTML, CSS, and vanilla JavaScript. No frameworks, no dependencies, no build step.

**Created by:** Shudhanshu Kumar  
**Email:** shudhanshukumar973@gmail.com

---

## 🚀 Live Demo

Deploy instantly via GitHub Pages — see [Deployment](#deployment) below.

---

## ✨ Features

### 1. Matrix-Driven Pricing & Currency Switcher
- Toggle between **Monthly** and **Annual** billing (20% discount applied dynamically)
- Switch between **USD ($)**, **INR (₹)**, and **EUR (€)** in real time
- All prices computed from a multi-dimensional config matrix with regional tariff multipliers
- Animated price transitions on every change

### 2. Bento-to-Accordion with Context Lock
- **Desktop (≥900px):** Features display as an asymmetric **Bento Grid** with hover states
- **Mobile (<900px):** Automatically reflows into a touch-optimized **Accordion** list
- **Context Lock Constraint:** If you hover a bento card on desktop and resize past the mobile breakpoint, the exact active card index is transferred to the accordion — the corresponding panel opens automatically with a toast confirmation

### 3. Full Landing Page Sections
- Fixed navigation with scroll effect
- Hero with live dashboard mockup
- Logo trust bar
- Feature showcase (Bento / Accordion)
- Pricing tier matrix
- Customer testimonials
- CTA banner
- Footer with creator credit

---

## 📁 Project Structure

```
nexus-ai-landing/
├── index.html          # Entire site (HTML + CSS + JS, self-contained)
├── README.md           # This file
├── .gitignore          # Standard web gitignore
└── .github/
    └── workflows/
        └── deploy.yml  # GitHub Actions — auto-deploy to GitHub Pages
```

---

## 🛠️ Local Development

No build step required. Just open the file:

```bash
# Option 1: Open directly in browser
open index.html

# Option 2: Use a local server (recommended)
npx serve .
# or
python3 -m http.server 8080
```

---

## 🌐 Deployment

### GitHub Pages (Recommended — Free)

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set **Source** to `Deploy from a branch`
4. Select branch: `main`, folder: `/ (root)`
5. Click **Save** — your site will be live at:
   ```
   https://<your-username>.github.io/<repo-name>/
   ```

### Auto-Deploy via GitHub Actions

The included `.github/workflows/deploy.yml` automatically deploys to GitHub Pages on every push to `main`. No manual steps needed after setup.

### Netlify (One-click)

1. Go to [netlify.com](https://netlify.com)
2. Drag and drop the project folder onto the Netlify dashboard
3. Done — live in seconds

### Vercel

```bash
npx vercel
```

---

## 🎨 Tech Stack

| Layer | Choice |
|-------|--------|
| Markup | Semantic HTML5 |
| Styling | Pure CSS (custom properties, grid, flexbox) |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | Google Fonts — Syne + Inter |
| Icons | Inline SVG |
| Deploy | GitHub Pages / Netlify / Vercel |

---

## 📄 License

MIT — free to use, modify, and deploy.
