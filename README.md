# Happy Birthday Varnika 🎀

A single-page, mobile-first birthday website with a girly-pop / coquette Y2K aesthetic — animated gradient mesh background, floating hearts & sparkles, glassmorphism cards, polaroid photo frames, scroll-triggered reveals, and confetti bursts.

## Files
- `index.html` — the whole site (self-contained: HTML + CSS + JS)
- `photo1.jpg`, `photo2.jpg` — Varnika's photos

## View locally
Just open `index.html` in any browser:

```bash
# either double-click index.html, or serve it:
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy on Vercel (fastest way to share a link)
1. Push this folder to a GitHub repo (already done if you're reading this on GitHub).
2. Go to [vercel.com](https://vercel.com) → **Add New… → Project** → import this repo.
3. Framework preset: **Other**. No build command needed. Output directory: `.` (root).
4. Click **Deploy** — you'll get a live `*.vercel.app` link in ~30 seconds.

**Or via CLI:**
```bash
npm i -g vercel
vercel        # follow the prompts, accept defaults
vercel --prod # promote to a production URL
```

## Deploy on Netlify (alternative)
- Drag-and-drop the whole folder onto [app.netlify.com/drop](https://app.netlify.com/drop) — instant live link.
- Or connect the GitHub repo; no build command, publish directory `.`.

## Customizing
- **Colors:** edit the CSS variables at the top of `index.html` (`--pink`, `--lilac`, `--mint`, `--hot`).
- **Message:** edit the text inside the `<!-- 3. MESSAGE -->` section.
- **Captions:** edit the `.cap` text under each photo.
- **Swap photos:** replace `photo1.jpg` / `photo2.jpg` (keep the same filenames).
