# Shubham & Gopika — Wedding Website

A single-page wedding invitation site. No build step, no dependencies — just open `index.html` in a browser.

## Files

- `index.html` — the full site (HTML + CSS inline)
- `rsvp-qr.png` — QR code linking to the RSVP Google Form

## Edit details

Everything is in `index.html`. Search for these strings to update content:

- `Shubham` / `Gopika` — names
- `Sixth of December` — headline date
- `15th November 2026` — RSVP deadline
- `Shree Krishna Inn` / `Gokulam Park` / `Kannur` / `Bhubaneswar` — venues
- `#ShubhamWedsGopika` — hashtag
- The RSVP and Zola registry URLs live in the footer links

## Host on GitHub Pages (free)

1. Create a new repository on GitHub (e.g. `shubhamandgopika`).
2. Push these files to it:
   ```bash
   git init
   git add .
   git commit -m "Wedding website"
   git branch -M main
   git remote add origin https://github.com/<your-username>/shubhamandgopika.git
   git push -u origin main
   ```
3. In the repo on GitHub: **Settings → Pages → Build and deployment → Source = Deploy from a branch → Branch = `main` / `(root)` → Save**.
4. The site will be live at `https://<your-username>.github.io/shubhamandgopika/`.

To serve it directly from your account root (so the URL is just `https://<your-username>.github.io/`), name the repository `<your-username>.github.io` instead.
