# LearnVest — Vercel Deployment Guide
## "Learn Money. Play Smart. Build Wealth." 🦊

---

## FILES IN THIS ZIP

learnvest_vercel/
├── api/
│   └── index.py          ← Flask backend (all API routes)
├── templates/
│   └── index.html        ← Full frontend app
├── static/               ← Static assets folder
├── vercel.json           ← Vercel configuration (REQUIRED)
└── requirements.txt      ← Python dependencies (REQUIRED)

---

## STEP-BY-STEP: DEPLOY TO VERCEL (Free, No Expiry)

### STEP 1 — Create a GitHub Account
Go to https://github.com and sign up for free if you don't have one.

### STEP 2 — Create a New GitHub Repository
1. Click the "+" icon (top right) → "New repository"
2. Name it: learnvest-mvp
3. Set to Public
4. Click "Create repository"

### STEP 3 — Upload Your Files to GitHub
1. On the new repo page, click "uploading an existing file"
2. Drag and drop ALL files from inside this zip:
   - api/ folder (with index.py inside)
   - templates/ folder (with index.html inside)
   - static/ folder
   - vercel.json
   - requirements.txt
3. Scroll down → click "Commit changes"

   IMPORTANT: Keep the folder structure exactly as shown.
   vercel.json must be at the ROOT level, not inside any subfolder.

### STEP 4 — Create a Vercel Account
1. Go to https://vercel.com
2. Click "Sign Up" → choose "Continue with GitHub"
3. Authorize Vercel to access your GitHub

### STEP 5 — Deploy Your App
1. On Vercel dashboard, click "Add New Project"
2. Find and select your "learnvest-mvp" repository
3. Click "Import"
4. On the configuration page:
   - Framework Preset: leave as "Other"
   - Root Directory: leave as "./" (default)
   - DO NOT change anything else
5. Click "Deploy"

### STEP 6 — Wait ~60 Seconds
Vercel will build and deploy automatically.
When done, you'll see a green "Congratulations!" screen.

### STEP 7 — Get Your Live Link
Your app is now live at:
   https://learnvest-mvp.vercel.app
   (or similar — Vercel shows the exact URL)

Click "Visit" to see your live app!

---

## YOUR LIVE LINK (share this in Google Form)

https://learnvest-mvp.vercel.app

Paste this link in your Google Form description:
"Try our LearnVest MVP before filling the form: [your link]"

---

## IMPORTANT NOTES

- FREE FOREVER: Vercel's Hobby plan is free with no expiry
- NO CREDIT CARD required
- Link never expires unless you manually delete the project
- Supports unlimited visits for an MVP/demo
- Each user gets their own session (progress saved per browser)

---

## IF DEPLOYMENT FAILS

Most common fix: Make sure vercel.json is at the ROOT of your
repository, not inside any subfolder.

Your GitHub repo structure must look like this:
  learnvest-mvp/
  ├── api/index.py
  ├── templates/index.html
  ├── static/
  ├── vercel.json         ← MUST be here at root
  └── requirements.txt    ← MUST be here at root

---

## TEAM — Group B, TAPMI 2026
Himanshi Dubey (CEO) · Deevij Rawul (CTO) · Saumil Garg (CMO)
Shivangi Goel (CPO) · Simran Pachori (CFO) · Drishti Patrikar (CCO)

contact@learnvest.in | learnvest.in
