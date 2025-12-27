# Vish's Internship Tracker v3

A comprehensive Summer 2026 internship tracker with integrated AI-powered resume matching.

## Features

### 📊 Internship Tracker
- **314 curated internship roles** across 4 categories:
  - Texas (24 roles)
  - Remote (22 roles)
  - Business Technology (66 roles)
  - Software Engineering (202 roles)
- Track application status (Applied, Interview, Offer, Rejected)
- Direct apply links to job postings
- Persistent state saved in browser

### 📄 Resume Matcher (AI-Powered)
- Upload your resume (PDF)
- Search and select from 314 tracked roles
- Paste any job description for analysis
- Get ATS optimization score with breakdown:
  - Hard Skills (40%)
  - Tools & Technologies (25%)
  - Job Title Match (15%)
  - Soft Skills (10%)
  - Other Keywords (10%)
- Categorized keyword matching with frequency analysis
- Actionable improvement suggestions with copy-paste examples

## Usage

1. Visit the [live site](https://evolvedtroglodyte.github.io/Vishnus-Internship-Tracker/)
2. **Tracker Mode**: Browse internships, track your applications
3. **Resume Matcher**: Click "Resume Matcher" button → Upload resume → Search for a role or paste job description → Analyze

### API Key Setup
The Resume Matcher uses OpenAI's GPT-4o-mini for analysis. On first use:
1. You'll be prompted for your OpenAI API key
2. The key is stored **only in your browser's localStorage**
3. Never transmitted anywhere except directly to OpenAI

## Tech Stack
- Pure HTML/CSS/JavaScript (no build tools required)
- PDF.js for resume parsing
- OpenAI API for AI analysis
- localStorage for data persistence

## Local Development
```bash
# Clone the repo
git clone https://github.com/evolvedtroglodyte/Vishnus-Internship-Tracker.git

# Serve locally (required for API calls)
python3 -m http.server 8000

# Open http://localhost:8000
```

## Last Updated
December 27, 2025

---
Built by Vish for Summer 2026 internship applications
