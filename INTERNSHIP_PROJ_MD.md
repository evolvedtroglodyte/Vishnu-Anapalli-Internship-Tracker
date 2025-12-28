# INTERNSHIP TRACKER PROJECT

## Project Overview

| | |
|---|---|
| **Live URL** | https://evolvedtroglodyte.github.io/Vishnu-Anapalli-Internship-Tracker/ |
| **GitHub Repo** | https://github.com/evolvedtroglodyte/Vishnu-Anapalli-Internship-Tracker.git |
| **Local Path** | `~/Desktop/VISH'S PROJECTS/internship-tracker-v3` |
| **Built By** | [Vishnu Anapalli](https://vishnuanapalli.netlify.app) |

---

## Current State (v6 - December 28, 2025)

### Role Statistics
| Section | Count |
|---------|-------|
| Texas | 34 |
| Business Tech / Analytics | 62 |
| Software Engineering / Tech | 250 |
| Quant / Trading | 8 |
| Remote / Hybrid | 26 |
| **Total** | **380** |

### Tab Order
1. **Texas** - All TX locations
2. **Business Tech / Analytics** - Data Analyst, Business Analyst, Data Science, BI
3. **Software Engineering / Tech** - SWE/CS roles
4. **Quant / Trading** - Elite trading firms only
5. **Remote / Hybrid** - Work from anywhere positions

### Prestige Ordering (applied to all sections)
1. Elite Finance (Goldman Sachs, Bank of America)
2. FAANG (Amazon, Apple, Microsoft)
3. Top Tech/AI (NVIDIA, OpenAI, Anthropic, Databricks, Stripe)
4. Finance Tier 2 (Capital One, Barclays, Wells Fargo, Nasdaq)
5. Unicorns (Cloudflare, Coinbase, Datadog, Figma)
6. Enterprise Tech (Oracle, IBM, Dell, Intuit)
7. Healthcare (Genentech, AstraZeneca, CVS Health)
8. Defense (Lockheed, BAE Systems, Shield AI, CACI, Leidos)
9. Industrial (Honeywell, Texas Instruments)
10. Other (alphabetical)

### Quant Firms (all 8 in prestige order)
1. Citadel
2. Citadel Securities
3. Hudson River Trading
4. Jump Trading
5. Optiver
6. Tower Research Capital
7. Virtu Financial (2 roles)

### Features
- **Internship Tracker**: Browse 380 verified roles across 5 categories
- **Resume Matcher**: AI-powered (GPT-4o) resume-to-job matching
- **Prestige Ordering**: Roles sorted by company tier within each section
- **Application Tracking**: Track Applied, Interview, Offer, Rejected statuses
- **Persistent State**: Progress saves to localStorage

### Data Sources
- SimplifyJobs, speedyapply, vanshb03 (GitHub)
- intern-list.com, Indeed, Glassdoor

### Filtering Criteria
- ✅ US locations only (no Canada, UK, international)
- ✅ Undergraduate eligible (no PhD/Masters required)
- ✅ No true duplicates (same URL removed)

---

## Tech Stack

- **Frontend**: Pure HTML/CSS/JavaScript (single file, ~230KB)
- **AI**: OpenAI GPT-4o API (user provides key)
- **Storage**: localStorage
- **Hosting**: GitHub Pages

---

## Git Commands

### Standard Push
```bash
cd ~/Desktop/VISH\'S\ PROJECTS/internship-tracker-v3
git add .
git commit -m "Your commit message"
git push origin main
```

### After Downloading from Claude
```bash
cd ~/Desktop/VISH\'S\ PROJECTS/internship-tracker-v3
# 1. Download files, rename HTML to index.html
# 2. Then:
git add .
git commit -m "vX: description"
git push origin main
```

---

## How to Add New Roles

### Role Object Format
```javascript
{ 
  id: "section-###",
  section: "texas|biztech|swe|quant|remote", 
  company: "Company Name", 
  role: "Job Title", 
  desc: "Brief description.", 
  location: "City, State", 
  deadline: "Rolling", 
  url: "https://unique-application-link.com" 
}
```

### Counts to Update When Adding Roles
- Header stats: `totalCount`, `texasCount`, `bizTechCount`, `sweCount`, `quantCount`, `remoteCount`
- Resume Matcher: "Search from X roles"
- Footer: "X verified roles"

### Deduplication Rule
Only remove roles if they have the **exact same URL**. Different roles at the same company with different URLs should both stay.

---

## Session History

### Session 36 (December 28, 2025)
- Added **Quant / Trading** section (8 roles)
- Fixed prestige ordering in ALL sections
- Properly removed 19 true duplicates (same URL only)
- Major finance companies (Bank of America, Goldman, NVIDIA) now at top of BizTech
- FAANG companies at top of SWE
- v6: 380 verified roles

### Session 34-35 (December 27-28, 2025)
- Added 70+ new roles, removed 39 ineligible
- Renamed sections, green Offers header
- v5: 402 roles

### Sessions 1-33
- Built initial tracker with Resume Matcher v2
- Prestige ordering, GitHub Pages deployment
- v4: 369 roles

---

## Changelog

### v6 (December 28, 2025)
- New Quant / Trading section (8 roles)
- Fixed prestige ordering in all sections
- Removed 19 true duplicates (same URL)
- 380 verified roles

### v5 (December 28, 2025)
- Added 70+ new roles
- Removed 39 ineligible (Canada, UK, PhD)
- 402 roles

### v4 (December 27, 2025)
- Prestige-based ordering
- Resume Matcher v2
- 369 roles

---

## Future Ideas

- [ ] Deadline sorting/filtering
- [ ] Export to CSV
- [ ] Notes field per application
- [ ] Dark mode
- [ ] Salary filter

---

*Last Updated: December 28, 2025*
