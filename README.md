# Summer 2026 Internship Tracker & Resume Matcher

A comprehensive internship tracking tool with integrated AI-powered resume matching, built for Summer 2026 recruiting season.

**Live Site:** [https://evolvedtroglodyte.github.io/Vishnu-Anapalli-Internship-Tracker/](https://evolvedtroglodyte.github.io/Vishnu-Anapalli-Internship-Tracker/)

## Features

### Internship Tracker
- **402 verified Summer 2026 internship roles** across 4 categories:
  - **Texas** (36 roles) - Local opportunities in TX
  - **Remote / Hybrid** (28 roles) - Work from anywhere positions
  - **Business Tech / Analytics** (65 roles) - Data Analyst, Business Analyst, Data Science, BI roles
  - **Software Engineering / Tech** (273 roles) - Pure SWE/CS positions
- **Prestige-based ordering** - Roles sorted by company tier:
  1. Elite Quant/Finance (Citadel, HRT, Jump)
  2. FAANG+ (Google, Amazon, Apple, Meta, Netflix)
  3. Top Tech/AI (NVIDIA, OpenAI, Anthropic)
  4. Unicorns/High-Growth (Stripe, Databricks)
  5. Defense/Aerospace (Lockheed, SpaceX)
  6. Enterprise Tech (Oracle, IBM, SAP)
  7. Finance Tech (Capital One, Goldman)
  8. Mid-Size Tech
  9. Startups & Other
- **Application status tracking** - Track Applied, Interview, Offer, Rejected statuses
- **Persistent state** - Your progress saves to localStorage
- **Fullscreen mode** - Expand any section for focused browsing

### Resume Matcher (Powered by GPT-4o)
- **AI-powered analysis** - Compares your resume against any job description
- **Match scoring** - Get a percentage match with detailed breakdown
- **Keyword extraction** - See matched vs missing skills by category
- **Actionable suggestions** - Prioritized improvements with copy-paste examples
- **Quick job selection** - Select any tracked internship to auto-fill job details
- **All 402 jobs searchable** - Search by company, role, location, or description

## Usage

1. **Browse Internships**: Click section headers to expand/collapse
2. **Track Applications**: Use dropdown to update status (Applied → Interview → Offer)
3. **Match Resume**: 
   - Click "Resume Matcher" button
   - Enter your OpenAI API key (stored locally only)
   - Upload resume (PDF/TXT) or paste text
   - Paste job description or select from tracker
   - Click "Analyze Match"

## Tech Stack

- Pure HTML/CSS/JavaScript (no frameworks)
- OpenAI GPT-4o API for resume analysis
- localStorage for state persistence
- GitHub Pages for hosting

## Data Sources

- [SimplifyJobs/Summer2026-Internships](https://github.com/SimplifyJobs/Summer2026-Internships)
- [speedyapply/2026-SWE-College-Jobs](https://github.com/speedyapply/2026-SWE-College-Jobs)
- [vanshb03/Summer2026-Internships](https://github.com/vanshb03/Summer2026-Internships)
- [intern-list.com](https://www.intern-list.com)
- [Indeed](https://www.indeed.com)
- [Glassdoor](https://www.glassdoor.com)
- Direct company career pages

## Filtering Criteria

All roles are filtered to ensure eligibility:
- ✅ **US locations only** (no Canada, UK, or international)
- ✅ **Undergraduate eligible** (no PhD or Masters required roles)
- ✅ **Open to all** (removed US citizenship required roles)
- ✅ **Verified open** (links checked for active applications)

## Local Development

Simply open `internship_tracker_v5.html` in a browser. No build step required.

## Changelog

### v5 (December 28, 2025)
- Added 70+ new roles from expanded research
- Removed 39 ineligible roles (Canada, UK, PhD/Masters required)
- Renamed sections for clarity:
  - "Remote Opportunities" → "Remote / Hybrid"
  - "Business Technology / Hybrid" → "Business Tech / Analytics"
- Changed Offers section to light green color
- Added new data sources: intern-list.com, Indeed, Glassdoor
- All jobs now searchable in Resume Matcher
- Total: 402 verified US undergraduate-eligible roles

### v4 (December 27, 2025)
- Prestige-based ordering implementation
- Resume Matcher v2 integration
- 369 verified roles

## Built By

[Vishnu Anapalli](https://vishnuanapalli.netlify.app)

---

*Last updated: December 28, 2025*
