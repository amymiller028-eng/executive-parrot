[README.md](https://github.com/user-attachments/files/28603042/README.md)
# 90-Day Ramp Dashboard

A personal, clickable dashboard for tracking my transition into a People Analytics role — daily habits, case studies, assessment-trends work, dates, and notes — plus a portfolio page that lives right alongside it.

**Live site:** _add your GitHub Pages link here once it's published (see below)._

---

## What's in here

- `index.html` — the dashboard (habits, phases, case studies, trends, with dates + notes)
- `portfolio.html` — an editable portfolio page; click any text to edit it
- Everything saves automatically in your browser, with Export/Import buttons to back up or move between devices

No installation, no build step, no dependencies. It's plain HTML/CSS/JavaScript.

---

## How to put this on GitHub (beginner-friendly, no command line)

You said you've made a GitHub account but barely used it. This whole thing can be done in the browser.

### 1. Create the repository
1. Go to https://github.com and sign in.
2. Click the **+** in the top-right → **New repository**.
3. Name it something like `career-dashboard`.
4. Set it to **Public** (you said you don't mind it being public).
5. Leave everything else as-is and click **Create repository**.

### 2. Upload these files
1. On the new repo's page, click **uploading an existing file** (it's in the "Quick setup" text), or go to **Add file → Upload files**.
2. Drag in `index.html`, `portfolio.html`, and this `README.md`.
3. Scroll down and click **Commit changes**.

### 3. Turn on GitHub Pages (this makes it a live website)
1. In the repo, click **Settings** (top tab).
2. In the left sidebar, click **Pages**.
3. Under **Branch**, pick **main** and the **/ (root)** folder, then click **Save**.
4. Wait about a minute, then refresh. GitHub will show a link like:
   `https://YOUR-USERNAME.github.io/career-dashboard/`
5. That link is your live dashboard. Bookmark it. The "View my portfolio" button will work automatically.

That's it — you now have a public, clickable dashboard you can open from any device.

---

## Editing it later

- **Quick text/notes:** just use the live site — your dates and notes save in the browser automatically.
- **Changing the actual habits, case studies, or trends:** edit `index.html` (the list near the top of the `<script>`, in the `DATA` object) and re-upload via **Add file → Upload files** (it'll overwrite the old one).
- **Backing up your progress:** click **Export progress** on the dashboard. Because progress is saved per-browser, exporting is how you move it to a new computer (then **Import** there).

---

## Note on how progress is saved

Progress, dates, and notes are stored in your browser's `localStorage`. That means:
- It persists between visits **on the same browser/device**.
- It does **not** sync across devices automatically — use Export/Import for that.
- Clearing your browser data will clear it, so export a backup now and then.

If you later want true cross-device sync, that's a natural next project once you're comfortable with GitHub.
