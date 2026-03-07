# Rythu Mitra – Deployment Guide

## Files
| File | Description |
|------|-------------|
| `index.html` | Full landing page & website |
| `app.html` | Mobile app preview (24 screens) |
| `suraksha.html` | Rythu Mitra Suraksha system page |
| `vercel.json` | Vercel routing config |

## Deploy to Vercel

### Option A – Vercel CLI
```bash
npm install -g vercel
cd rythu-mitra
vercel
```

### Option B – Vercel Dashboard
1. Go to https://vercel.com and sign in.
2. Click **Add New Project**.
3. Select **Upload** and drag the entire `rythu-mitra` folder.
4. Click **Deploy**.

### Option C – GitHub
1. Create a new GitHub repo.
2. Upload all project files.
3. Connect the repo on https://vercel.com/new.
4. Vercel will auto-deploy on every push.

## Routes after deployment
- `yourdomain.vercel.app/` → Website
- `yourdomain.vercel.app/suraksha` → Rythu Mitra Suraksha
- `yourdomain.vercel.app/app` → App preview

## Local preview
Open `index.html` in a browser. No local server is required.
