# Progressive Mind — Landing Page

A single-page marketing site for a one-stop software shop offering full-stack MERN,
Python, DevOps, and AI / agentic AI engineering services.

## Stack

None. It's one self-contained `index.html` — all CSS and JS inline, no build step,
no dependencies. The only external request is a Google Fonts stylesheet
(Inter + JetBrains Mono).

## Run locally

```bash
python3 -m http.server 8765
# → http://localhost:8765
```

Or just open `index.html` in a browser.

## Deploy

Any static host works. Build command: *none*. Output directory: `/`.

Cloudflare Pages is the recommended target — unlimited bandwidth on the free tier
and no commercial-use restriction.

## Notes

- The contact form is **front-end only**. It validates, shows a success state, and
  submits nowhere. Wire it to Formspree, Netlify Forms, or a Worker before going live.
- Stats and testimonials are placeholder copy. Replace with real figures.
