# VintageTimes.mk

Website for **VintageTimes.mk** — vintage original watches. Omega, Longines, Zenith, Seiko & more.

## Live link (after setup)

**https://altinald.github.io/vitangetimes/**

---

## GitHub Pages — enable once (required)

The site will show **404** until you do this **one time**:

### Step 1 — Open Pages settings

Go to: **https://github.com/AltinALD/vitangetimes/settings/pages**

### Step 2 — Choose source

Under **Build and deployment**:

| Setting | Value |
|---------|-------|
| **Source** | `Deploy from a branch` |
| **Branch** | `main` |
| **Folder** | `/ (root)` |

Click **Save**.

### Step 3 — Wait

Wait **1–3 minutes**, then open: **https://altinald.github.io/vitangetimes/**

---

## If you see a failed "Deploy GitHub Pages" workflow

That old workflow expected **GitHub Actions** as the Pages source. This repo now uses **branch deploy** instead (simpler for a static site).

1. Ignore or delete any failed workflow runs under the **Actions** tab.
2. Follow the steps above — use **Deploy from a branch**, not GitHub Actions.

---

## Push to GitHub

Make sure you push to the correct remote:

```bash
git push vitangetimes main
```

(`origin` points to a different repo — use `vitangetimes` for this project.)

---

## Still 404?

- Repo must be **Public**
- Use exact URL: `https://altinald.github.io/vitangetimes/`
- Hard refresh: `Ctrl + Shift + R`
