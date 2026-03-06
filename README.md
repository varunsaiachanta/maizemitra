# KisanDirect – Deployment Guide

## Files
| File | Description |
|------|-------------|
| `index.html` | Full landing page & website |
| `app.html` | Mobile app preview (19 screens) |
| `vercel.json` | Vercel routing config |

## Deploy to Vercel (3 steps)

### Option A – Vercel CLI (Fastest)
```bash
npm install -g vercel
cd kisandirect
vercel
```
Follow the prompts. Your site will be live in ~30 seconds.

### Option B – Vercel Dashboard (No code needed)
1. Go to https://vercel.com and sign in (free account)
2. Click **"Add New Project"**
3. Select **"Upload"** and drag the entire `kisandirect` folder
4. Click **Deploy**

### Option C – GitHub (Best for future updates)
1. Create a new GitHub repo
2. Upload all files to it
3. Connect the repo on https://vercel.com/new
4. Vercel auto-deploys on every git push

## URLs after deployment
- `yourdomain.vercel.app/` → Landing page
- `yourdomain.vercel.app/app` → App preview

## Local preview
Just open `index.html` in your browser — no server needed.
