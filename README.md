# Trip Planner — DakJen Creative
### Parallel group trip planner with cash + points cost calculator

---

## Deploy to Vercel (free, ~5 min)

1. Go to [vercel.com](https://vercel.com) and sign up / log in
2. Click **Add New → Project**
3. Choose **"Deploy from a folder"** or drag this whole folder into the Vercel dashboard
4. Set **Root Directory** to `public`
5. Click **Deploy**

Vercel gives you a URL like `your-project.vercel.app` — that's your live app.

---

## Install on Desktop (after deploying)

**Mac / Windows (Chrome or Edge):**
1. Open your Vercel URL in Chrome or Edge
2. Look for the install icon (⊕) in the address bar, or go to Menu → "Install Trip Planner"
3. Click Install — it appears in your dock / taskbar like a native app

**iPhone (Safari):**
1. Open the URL in Safari
2. Tap the Share button → "Add to Home Screen"
3. Tap Add

**Android (Chrome):**
1. Open the URL in Chrome
2. Tap the three-dot menu → "Add to Home screen" or "Install app"

---

## Files

```
public/
  index.html     ← Full app, self-contained
  manifest.json  ← PWA install config
  sw.js          ← Service worker (offline support)
vercel.json      ← Routing config for Vercel
```

---

## Data / Storage

Each user's trips are saved **locally in their browser** (localStorage).
Trips do not sync across devices or users — each device has its own data.

If you want shared/cloud trips in the future, that would require a backend (Supabase, Firebase, etc.).

---

Built by DakJen Creative
