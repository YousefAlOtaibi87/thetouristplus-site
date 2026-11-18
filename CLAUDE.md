# CLAUDE.md — thetouristplus-site

## What this is
The public website for TheTouristPlus (thetouristplus.com): Arabic home page, English page (`en.html`), terms, privacy, and payment pages. Hosted on GitHub Pages.

## Stack
- Static HTML/CSS/JS, no build step.
- If any page talks to Supabase, use only the publishable key. Never put secret or service_role keys in this repo.

## Rules when changing content or code
- Brand name: "TheTouristPlus" in English; Arabic spelling "ذا تورست بلس". Slogan: "اطلب رحلتك وشركاؤنا يوفرون أفضل الأسعار". Never say agencies "compete" (تتنافس) — agencies are partners.
- Never publish agency commission rates, app user/download numbers, or partner names.
- Arabic pages RTL first; keep the English page in sync with the Arabic one.
- Terms and privacy text are approved by the owner — don't change wording without being asked.
- Keep changes small. Never commit straight to `main`: use a branch and a PR.

## Reviews
Follow REVIEW.md for every code review.

## Talking to the owner
Reply in Arabic, short and clear.
