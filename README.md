https://monxcode.github.io/Cyber-Shield/

# CyberShield | Tech4Impact

**CyberShield** ek **frontend-only, browser-based cybersecurity awareness tool** hai jo **HTML, Tailwind CSS aur Vanilla JavaScript** se bana hai.  
Ye users ko suspicious links ya messages analyze karne me help karta hai aur simple language me batata hai **kyon** koi link risky ho sakta hai.

Project **Gen Z–style UI**, glassmorphism, neon gradients aur explainable logic ke saath banaya gaya hai — perfect for **hackathons & demos**.

---

## What CyberShield Does

Paste karo koi bhi **URL ya message** → **Scan** button dabao →  
CyberShield turant browser ke andar analysis karta hai aur dikhata hai:

- Risk Level (Safe / Suspicious / Dangerous)
- Animated risk meter
- Clear reasons (human-readable)
- Safety tips (what to do next)

---

## Key Features

- Pure frontend only (No backend, no database)
- Instant in-browser analysis
- Deterministic Rule Engine (Explainable, no black box AI)
- Modern Gen Z UI (Glass + Neon)
- Fully responsive (mobile friendly)
- GitHub Pages compatible
- Hackathon-ready

---

## Detection Logic (How it Works)

CyberShield heuristic-based rules use karta hai, jo phishing patterns detect karte hain  
(inspired by Google Safe Browsing principles).

### Checks Performed
- HTTP (no HTTPS)
- IP address based URLs
- `@` symbol trick
- URL shorteners (bit.ly, tinyurl, etc.)
- Phishing keywords (login, verify, win, urgent)
- Too many subdomains
- Risky TLDs (.xyz, .top, .site, etc.)
- Brand impersonation (fake Google / PayPal / Amazon)

Har rule ek risk score add karta hai, jisse final level decide hota hai.

---

## Risk Levels Explained

- Safe – Link normal lag raha hai, phir bhi alert raho  
- Suspicious – Kuch red flags mile hain  
- Dangerous – High risk, bilkul interact mat karo  

---

## Technologies Used

- HTML5  
- Tailwind CSS (CDN)  
- Vanilla JavaScript  
- SVG Icons  
- Google Font: Plus Jakarta Sans  

---

## Sample Links (Demo)

Safe example  
`https://www.google.com`

Dangerous example (demo purpose)  
`http://verify-google-account.xyz/login`

---

## Ideal For

- Google / College Hackathons  
- Cybersecurity awareness tools  
- Frontend-only challenges  
- Student demo projects  

---

## Disclaimer

CyberShield ek educational & awareness tool hai.  
Ye real-time antivirus ya threat-intelligence systems ka replacement nahi hai.

---

## Team

Project: CyberShield  
Team: Tech4Impact  

---

Think before you click. Stay cyber-safe.