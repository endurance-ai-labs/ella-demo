# Ella — A.I. Voice Agent (marketing demo)

A single-page marketing demo for **Ella**, the A.I. voice agent that remembers every
conversation. Content is rebranded from the Endurance A.I. landing page; the visual
system (warm near-white canvas, electric-cobalt accent, hairline borders, Inter) is
borrowed from the RJS / Payline Commissions design tokens for cross-product consistency.

## Stack
Plain static HTML + CSS — no build step. Just open `index.html` or serve the folder.

```
index.html     # marketing landing page (cobalt/blue brand) + embedded demo video
styles.css     # landing design tokens + page styles
console.html   # product console dashboard ("This week with Ella")
console.css    # console design tokens (blue/slate SaaS palette)
```

## Surfaces
- **Landing** (`index.html`) — long-scroll marketing page positioning Ella as an
  AI-native system that captures every customer conversation (phone, Zoom/Teams/
  Google Meet, in-person). Includes the original "after hours" demo video.
- **Console** (`console.html`) — the product dashboard a customer logs into,
  recreated from the `Ella Console` design handoff in the blue/slate SaaS palette
  (Newsreader + Hanken Grotesk + Space Mono; `#2f6df0` accent). Weekly overview with
  KPI cards, a "Needs a look" worklist (tab-filterable), "Coming up", a
  "Recent conversations" memory feed, and an "Ask Ella" popover. All sample data.

## Local preview
```bash
npx serve .
# or
python -m http.server 8000
```

## Deploy
Static site — drops onto Vercel, Cloudflare Pages, or GitHub Pages with no config.

---
© 2026 Ella · An Endurance Labs product
