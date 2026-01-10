**Live Here:** https://monxcode.github.io/Cyber-Shield/

# CyberShield | Tech4Impact

**CyberShield** is a **frontend-only, browser-based cybersecurity awareness tool** built using **HTML, Tailwind CSS, and Vanilla JavaScript**.  
It helps users analyze suspicious links or messages and clearly explains **why** a link may be unsafe.

The project features a **Gen Z–inspired animated UI**, glassmorphism effects, neon gradients, and fully explainable logic — making it ideal for **hackathons, demos, and learning projects**.

---

## What CyberShield Does

Paste any **URL or message** → Click **Scan** →  
CyberShield instantly runs an **in-browser security analysis** and shows:

- Risk Level (Safe / Suspicious / Dangerous)
- Animated risk progress bar
- Smooth loading and result transitions
- Clear, human-readable reasons
- Context-aware safety tips

---

## Key Features

- Frontend-only (No backend, no server, no database)
- Instant client-side analysis
- Deterministic Rule Engine (Explainable, no black-box AI)
- Animated UI (shimmer effects, floating icons, smooth transitions)
- Glassmorphism + neon gradient design
- Fully responsive (mobile-first)
- Deployable on GitHub Pages
- Hackathon-ready architecture

---

## Animations & UI Enhancements

CyberShield uses lightweight CSS animations to improve user experience:

- Floating shield icon in header
- Shimmer effect on cards
- Animated loader during scanning
- Smooth slide-up animation for results
- Animated risk meter fill based on threat score
- Hover and focus micro-interactions

All animations are **CSS-based**, keeping performance fast and bundle size minimal.

---

## Detection Logic (How It Works)

CyberShield uses **heuristic-based phishing detection**, inspired by **Google Safe Browsing principles**.

### Checks Performed
- HTTP links (no HTTPS)
- IP address–based URLs
- `@` symbol deception
- URL shorteners (bit.ly, tinyurl, etc.)
- Phishing keywords (login, verify, win, urgent)
- Excessive subdomains
- Risky TLDs (.xyz, .top, .site, etc.)
- Brand impersonation patterns

Each rule adds a **risk score**, which determines the final risk level.

---

## Risk Levels Explained

- **Safe** – No common phishing patterns detected  
- **Suspicious** – Some warning signs present  
- **Dangerous** – High risk, avoid interaction  

---

## Technologies Used

- HTML5  
- Tailwind CSS (CDN)  
- Vanilla JavaScript  
- SVG Icons  
- Google Font: Plus Jakarta Sans  

---

## Sample Links (For Demo)

Safe example  
`https://www.google.com`

Dangerous example (demo purpose only)  
`http://verify-google-account.xyz/login`

---

## Ideal For

- Google or college hackathons  
- Cybersecurity awareness tools  
- Frontend-only challenges  
- Student portfolio projects  

---

## Disclaimer

CyberShield is an **educational and awareness tool**.  
It does not replace real-time antivirus software or professional threat-intelligence systems.

---

## Team

Project: CyberShield  
Team: Tech4Impact  

---

Think before you click. Stay cyber-safe.