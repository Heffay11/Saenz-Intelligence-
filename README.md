# Saenz Intelligence — Landing Page

Flat-fee AI operations audits for business owners and professional practices.
One self-contained `index.html` — no build step, no dependencies, no framework.

---

## What it is

A single-page marketing site. The whole thing (HTML, CSS, JS) lives in `index.html`,
so it runs anywhere a browser can open a file and deploys with a single upload.

**Core message:** *"You don't have time to figure out AI. That's my job."*
You bring the pain points → I observe (virtual or on-site) → I hand you a one-page plan.
Flat fee, no retainer, you own everything.

---

## Preview it locally

**Easiest:** double-click `index.html` — it opens in your browser.

**With live-reload** (auto-refreshes when the file is saved):
```bash
npx browser-sync start --server --files "*.html" --port 3000
```
Then open <http://localhost:3000>

---

## Share it with Steve (get a live link)

The fastest way to a public URL is **GitHub Pages**:

1. Create a new GitHub repo (e.g. `saenz-intelligence`).
2. Upload **`index.html`** (and this `README.md`).
3. In the repo: **Settings → Pages → Build from branch → `main` / root → Save**.
4. Wait ~1 minute. Your link will be:
   `https://<your-username>.github.io/saenz-intelligence/`
5. Send that link to Steve.

> Only upload `index.html` and `README.md`. You can skip `files.zip` (original assets, not needed to run the site).

---

## Before it goes live — TODO

- [x] **Real email** — the "Book a Discovery Call" button is wired to `jeff.saenz@gmail.com`.
      Swap to a branded business email later if you set one up (search for `mailto:` in `index.html`).
- [ ] **Headshot** — the About section shows a "JS" placeholder block. Drop in a photo when ready.
- [ ] **Confirm location** — footer says "San Diego, California." Update if wrong.
- [ ] **Service names** — "The AI Operations Audit™ / Build Sprint™ / Tune-Up™" use ™.
      Fine as unregistered marks; drop the ™ if you'd rather keep it low-key.

---

## Notes

- **Stats and calculator are illustrative**, not claimed results — deliberately kept
  honest for a soft-launch with no track record yet to point to.
- **Positioning stays generic about the day job** (Fortune 500, no employer named) on purpose —
  keeps the side business cleanly separate from work-owned IP.
