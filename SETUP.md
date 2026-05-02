# MOHAMEDFAIZN — GitHub Profile Repository

This is the special profile repository for **Mohamed Faiz N**.
The `README.md` in this repo is automatically displayed on your GitHub profile page.

---

## Folder Structure

```
MOHAMEDFAIZN/
├── README.md                        ← Your profile page (auto-displayed by GitHub)
├── .gitignore
├── SETUP.md                         ← This file
└── .github/
    └── workflows/
        └── snake.yml                ← Auto-generates contribution snake animation
```

---

## Upload Steps (First Time)

### Option A — GitHub Web UI (easiest)

1. Go to [github.com/new](https://github.com/new)
2. Set repository name exactly as: `MOHAMEDFAIZN`
3. Set visibility to **Public**
4. Do NOT initialize with README (you already have one)
5. Click **Create repository**
6. On the next screen, click **"uploading an existing file"**
7. Drag and drop everything inside this folder (including the `.github` folder)
8. Commit with message: `feat: initialize profile README`

### Option B — Git CLI

```bash
cd MOHAMEDFAIZN

git init
git add .
git commit -m "feat: initialize profile README"
git branch -M main
git remote add origin https://github.com/MOHAMEDFAIZN/MOHAMEDFAIZN.git
git push -u origin main
```

---

## Activating the Snake Animation

After pushing your files:

1. Go to your repo on GitHub
2. Click the **Actions** tab
3. You'll see **"Generate Snake Animation"** workflow
4. Click it → click **"Run workflow"** → click the green **"Run workflow"** button
5. Wait ~1 minute for it to complete
6. The snake SVG will be generated and pushed to the `output` branch automatically
7. After that, it will auto-run every day at midnight UTC

> If the workflow fails with a permissions error:
> Go to **Settings → Actions → General → Workflow permissions**
> Select **"Read and write permissions"** → Save

---

## Stats Cards

The GitHub Stats, Top Languages, and Streak cards work automatically.
If your stats appear empty or incorrect:

- Make sure your repos are **Public**
- Go to GitHub **Settings → Contributions** and ensure activity is visible publicly

---

## Pinned Repositories (Recommended Order)

Pin these 4–6 repos on your profile for maximum recruiter impact:

| # | Repository | Why |
|---|---|---|
| 1 | `UnivMeta` | Live production system — strongest signal |
| 2 | Steganography System | Shows CS fundamentals + security depth |
| 3 | Digital Divide 2.0 | AI + offline-first innovation |
| 4 | IoT project (from internship if public) | Embedded systems breadth |
| 5 | DSA / algorithms repo | Shows current growth mindset |
| 6 | Any other strong project | Fills the 6-pin limit |

To pin: Go to your GitHub profile → click **"Customize your pins"** → select repos.

---

*Profile built for Mohamed Faiz N — KARE BCA 2026*
