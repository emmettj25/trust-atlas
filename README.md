# Trust Atlas

**The world's directory of vendor trust and security pages.**

Trust Atlas is a searchable, community-contributed database of trust centers — the security and compliance portals companies use to demonstrate their security posture to customers (e.g. `trust.vanta.com`, `trust.stripe.com`).

🌐 **Live site:** [trust-atlas.vercel.app](https://trust-atlas.vercel.app)

---

## What It Does

- **Search** any company's trust center by name or URL
- **Favorite** trust centers you reference frequently — persists across sessions
- **Contribute** by submitting a missing trust center via the "Add Your Trust Center" modal
- **Explore** a curated, growing database of real trust centers across the industry

---

## Why It Exists

Trust centers are scattered across the web with no central index. Security professionals, procurement teams, and compliance reviewers often spend time hunting for a vendor's trust page. Trust Atlas fixes that with a single, fast, searchable directory.

---

## Tech Stack

| Layer | Choice |
|---|---|
| Frontend | Vanilla HTML/CSS/JS (single file) |
| Fonts | Geist + Geist Mono (Google Fonts) |
| Hosting | Vercel (auto-deploys from GitHub) |
| Storage | localStorage (favorites, client-side) |

No framework, no build step, no database — intentionally simple for v1.

---

## Running Locally

No install needed. Just open the file:

```bash
git clone https://github.com/YOUR_USERNAME/trust-atlas.git
cd trust-atlas
open index.html   # or just drag into a browser
```

---

## Deploying

The repo is connected to Vercel. Every push to `main` auto-deploys. No Vercel dashboard interaction needed after initial setup.

```bash
git add .
git commit -m "your message"
git push
# → live in ~30 seconds
```

---

## Roadmap

- [ ] Company favicons/logos next to each entry
- [ ] Mobile-optimized layout
- [ ] Persistent backend (submissions saved server-side)
- [ ] Custom domain + public launch
- [ ] Next.js migration for scale

---

## Contributing a Trust Center

Know a trust center that's missing? Use the **"Add Your Trust Center"** button in the app sidebar, or open a PR adding an entry to the `entries` array in `index.html`.

---

## License

MIT
