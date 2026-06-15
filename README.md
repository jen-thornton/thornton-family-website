# thethorntons.ca
 
Personal family website for the Thornton family — Orleans, Ontario.
 
Live at **[thethorntons.ca](https://thethorntons.ca)**
 
---
 
## About
 
A static multi-page site introducing the Thornton family: Rob, Jennifer, Natalie, and Kaitlyn. Each family member has their own profile page. Jennifer's section also includes a dedicated portfolio showcasing her work in fraud operations and compliance.
 
The site is designed to serve as both a personal hub and a professional-facing resource — useful for hiring managers, collaborators, geocaching friends, or anyone curious about who we are.
 
---
 
## Pages
 
| Path | Description |
|------|-------------|
| `/` | Family homepage — hero, member grid, our story |
| `/rob/` | Rob Thornton — Senior Software Engineer |
| `/jennifer/` | Jennifer Thornton — Senior Fraud & Compliance Operations Analyst |
| `/jennifer/portfolio/` | Jennifer's portfolio — case studies and frameworks |
| `/natalie/` | Natalie Thornton — Mathematics student, uOttawa '29 |
| `/kaitlyn/` | Kaitlyn Thornton — Artist & Animator |
 
---
 
## Tech stack
 
- **Pure HTML & CSS** — no frameworks, no build step, no JavaScript dependencies
- **Google Fonts** — EB Garamond (serif) + Inter (sans-serif)
- **Fully static** — deployable to any static host
---
 
## Project structure
 
```
/
├── index.html              # Family homepage
├── images/                 # Shared image assets
│   ├── family-hero.jpg
│   ├── rob.jpg
│   ├── jennifer.jpg
│   ├── natalie.jpg
│   ├── kaitlyn.jpg
│   └── couple.jpg
├── rob/
│   └── index.html
├── jennifer/
│   ├── index.html
│   ├── jennifer-thornton-resume.pdf
│   └── portfolio/
│       └── index.html
├── natalie/
│   └── index.html
└── kaitlyn/
    └── index.html
```
 
---
 
## Design
 
- Warm stone palette (`#F8F6F1` through `#1C1C1E`)
- Serif headings (EB Garamond), light-weight sans body (Inter 300)
- Responsive — mobile breakpoints at 768px and 480px
- Sticky navigation, CSS Grid layouts, subtle hover transitions
---
 
## Running locally
 
No build tools required. Just open any `index.html` in a browser, or serve the root directory with any static file server:
 
```bash
# Python
python3 -m http.server 8000
 
# Node (if you have npx)
npx serve .
```
 
Then visit `http://localhost:8000`.
 
---
 
## Deployment
 
The site is static HTML and deploys to any host that serves flat files. Current live deployment is at [thethorntons.ca](https://thethorntons.ca).
 
---
 
## Family
 
| Member | Role |
|--------|------|
| Rob Thornton | Senior Software Engineer |
| Jennifer Thornton | Senior Fraud & Compliance Operations Analyst |
| Natalie Thornton | Mathematics student, uOttawa '29 |
| Kaitlyn Thornton | Artist & Animator |
 
*Supervised by Khaleesi & Luna.*
 
---
 
© 2026 The Thorntons · thethorntons.ca
