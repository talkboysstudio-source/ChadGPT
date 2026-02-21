# ChadGPT 💪 — Groq Edition

> Powered by Groq's free API. No cost to users. No cap. 🔥

---

## Folder Structure
```
chadgpt-server/
├── server.js          ← Backend (hides your Groq API key)
├── package.json       ← Dependencies
└── public/
    └── index.html     ← Frontend (what users see)
```

---

## Step 1 — Get Your FREE Groq API Key

1. Go to https://console.groq.com
2. Sign up for free (no credit card needed!)
3. Click **"API Keys"** → **"Create API Key"**
4. Copy your key — it starts with `gsk_...`

Groq's free tier is very generous — thousands of messages per day at no cost. 🎉

---

## Step 2 — Deploy on Railway (Free)

### Push to GitHub
1. Go to https://github.com and create a new repo called `chadgpt`
2. Upload your files like this:
   ```
   server.js
   package.json
   public/
     index.html
   ```

### Deploy
1. Go to https://railway.app → sign up with GitHub
2. Click **"New Project" → "Deploy from GitHub repo"**
3. Select your `chadgpt` repo — Railway auto-detects Node.js!
4. Click **"Variables"** and add:
   - Name: `GROQ_API_KEY`
   - Value: your key (`gsk_...`)
5. Railway restarts and gives you a public URL like:
   `chadgpt-production.up.railway.app`

Share that link — anyone can use ChadGPT for FREE! 💪

---

## Alternative: Render.com (Also Free)

1. Go to https://render.com → New → Web Service
2. Connect your GitHub repo
3. Set environment variable: `GROQ_API_KEY` = your key
4. Done!

---

## Cost Breakdown

| Thing | Cost |
|---|---|
| Groq API | **FREE** (generous free tier) |
| Railway hosting | **FREE** (500 hrs/month) |
| Your Anthropic bill | **$0** |
| Total | **$0** 🔥 |

---

## Model Used
`llama-3.3-70b-versatile` — Groq's fastest, smartest free model. Blazing fast responses, no cap. ⚡

---

Stay hard. Ship the app. 💪👑
