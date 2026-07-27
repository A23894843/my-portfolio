<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=timeAuto&height=200&section=header&text=my-portfolio-abhinandan&fontSize=36&fontColor=ffffff&animation=twinkling&fontAlignY=38&desc=Cybersecurity%20%26%20Software%20Engineering%20Portfolio&descAlignY=58&descSize=16&descColor=ffffff" width="100%"/>

[![Live Site](https://img.shields.io/badge/🌐_Live_Site-my--portfolio--abhinandan.vercel.app-0D1117?style=for-the-badge)](https://my-portfolio-abhinandan.vercel.app)
[![Deployed on Vercel](https://img.shields.io/badge/Deployed_on-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://my-portfolio-abhinandan.vercel.app)
[![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://my-portfolio-abhinandan.vercel.app)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://my-portfolio-abhinandan.vercel.app)

</div>

---

## 📸 Preview

> A dark-themed, cybersecurity-aesthetic single-page portfolio with live GitHub activity, real-time LeetCode stats, animated matrix background, and smooth scroll-reveal sections.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🌧️ **Matrix Rain Background** | Falling binary/hex characters with cursor-driven scan highlight |
| 🔌 **Circuit Board Parallax** | SVG circuit traces that shift with mouse movement |
| ⌨️ **Terminal Typing Effect** | Typewriter animation on hero subtitle |
| 📊 **Live GitHub Activity** | Real-time streak stats + contribution heatmap via demolab & activity-graph |
| 🧩 **Live LeetCode Stats** | Fetches Easy / Medium / Hard solve counts on every page load |
| 🌗 **Light / Dark Toggle** | Persistent theme saved to `localStorage` |
| 📱 **Fully Responsive** | Mobile-first layout, works on all screen sizes |
| ♿ **Reduced Motion** | Respects `prefers-reduced-motion` — all animations disabled gracefully |
| 🔍 **Scroll Reveal** | Sections fade in as you scroll via `IntersectionObserver` |

---

## 🗂️ Structure

```
portfolio/
│
├── index.html          # Single-file portfolio (HTML + CSS + JS all-in-one)
└── README.md           # This file
```

> The entire site is a **single self-contained HTML file** — no build tools, no frameworks, no dependencies. Just open in a browser.

---

## 🚀 Running Locally

```bash
# Clone the repo
git clone https://github.com/A23894843/my-portfolio-abhinandan.git

# Navigate into it
cd my-portfolio-abhinandan

# Open in browser (any of these work)
open index.html           # macOS
start index.html          # Windows
xdg-open index.html       # Linux

# Or serve with Python for live-reload
python3 -m http.server 3000
# → visit http://localhost:3000
```

---

## 🧰 Tech Stack

**No frameworks. No build step. Pure web.**

| Layer | Tech |
|-------|------|
| Structure | HTML5 semantic markup |
| Styling | CSS3 — custom properties, grid, flexbox, keyframe animations |
| Logic | Vanilla JavaScript (ES5/ES6) |
| Fonts | Google Fonts — Inter, JetBrains Mono, Space Grotesk |
| Hosting | Vercel (auto-deploy from `main` branch) |

---

## 🔗 Live Data Integrations

| Widget | API | Updates |
|--------|-----|---------|
| GitHub Streak | `streak-stats.demolab.com` | Daily |
| Contribution Graph | `github-readme-activity-graph.vercel.app` | Per push |
| LeetCode Stats | `alfa-leetcode-api.onrender.com` | Per page load |

---

## 📑 Sections

- **`// whoami`** — Hero with name, typed subtitle, bio, and location
- **`// tech_stack`** — Language and tool tags
- **`// security_domains`** — Cybersecurity knowledge areas
- **`// experience`** — CodSoft Python Internship
- **`// projects`** — Cyber Defensive Engine & Dr. Vaccine Antivirus
- **`// github_activity`** — Live streak + contribution graph
- **`// leetcode_stats`** — Live problem-solving stats with progress bars
- **`// academic_history`** — Education & Certifications

---

## 🛠️ Customising

All personal data is in `index.html`. Key things to update:

```html
<!-- LeetCode username (line ~671) -->
var username = 'a23894843';

<!-- GitHub username (throughout) -->
A23894843

<!-- Resume Drive link -->
https://drive.google.com/file/d/YOUR_FILE_ID/view
```

---

## 📄 License

This project is open source. Feel free to use it as inspiration for your own portfolio — just swap out the content with your own!

---

<div align="center">

**Built by [Abhinandan](https://my-portfolio-abhinandan.vercel.app) · Deployed on Vercel**

<img src="https://capsule-render.vercel.app/api?type=waving&color=timeAuto&height=120&section=footer&reversal=true" width="100%"/>

</div>
