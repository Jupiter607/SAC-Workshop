# Vibe Coding the Future of SAC — Workshop Site

## What's in this folder

```
sac-workshop/
├── index.html      ← The entire participant site (single file)
└── README.md       ← You are here
```

---

## How to open in Cursor

1. Open **Cursor**
2. File → Open Folder → select `sac-workshop/`
3. Click `index.html` in the sidebar
4. Right-click → **Open with Live Preview** (or install the Live Server extension)

The site will open in your browser at `localhost:5500`

---

## How to deploy with Vercel (recommended)

1. Go to **[vercel.com](https://vercel.com)** and sign in (or create a free account)
2. Click **Add New → Project**
3. If your files are in a GitHub repo: import the repo and Vercel auto-deploys
4. If you just have the folder locally: install the Vercel CLI and run `vercel` from the project folder, or drag the folder into the Vercel dashboard
5. Vercel gives you a live URL instantly (e.g. `https://sac-workshop.vercel.app`)
6. Optionally add a custom domain in Project Settings → Domains

Every push to `main` auto-deploys. No build step needed — it's a single static HTML file.

---

## How to generate the QR code for your presentation

Once you have your Vercel URL, go to any of these free QR generators:
- **qr-code-generator.com**
- **qrcode-monkey.com** (lets you add SAC colors)
- **Google's built-in**: type `qr code [your URL]` directly into Google Search

**QR code slide tips:**
- Make the QR code at least 4 inches square on the slide
- Put the URL in text below it (for people who'd rather type)
- Add: "Scan to follow along on your phone or laptop"
- Display this slide for the first 5 minutes while people are getting settled

---

## Customizing the site in Cursor

All content is in `index.html`. Key spots to edit:

| What | Where to find it |
|------|-----------------|
| Workshop date | Search for `Spring 2026` |
| SAC colors (red/gold) | Search for `--red` and `--gold` in the `<style>` block |
| Agenda timing | Search for `0 – 15 min`, `15 – 45 min`, etc. |
| Project descriptions | Search for `Project 01`, `Project 02`, etc. |
| Checklist items | Search for `check-row` |

**To ask Cursor's AI to make changes**, just press `Cmd+K` (Mac) or `Ctrl+K` (Windows) and describe what you want:
- "Change the red color to match SAC's exact brand red #C8102E"
- "Add a 7th project card about grading automation"
- "Make the hero section shorter"
