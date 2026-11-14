# Arslan — The Tech Guy for Winnipeg Businesses

Personal profile site for **Arslan Sohail** (16, Winnipeg, MB). He visits local businesses — restaurants, clinics, salons, gyms, auto shops — watches how they actually work, and makes the boring tech parts run themselves. First visit is free.

**Live:** https://arslan-site.vercel.app *(once deployed)*

## What's here

| File | What it is |
|---|---|
| `index.html` | The public site — single file, zero build step, zero dependencies (Google Fonts only). |
| `outreach.html` | **Internal tool, not linked publicly.** Lead-list manager for cold outreach: add/paste emails, categories, status tracking (new → sent → replied → pass), copy-all button, CSV export, editable cold-email template. All data stays in the browser's localStorage. |

## Design

The site is built around one idea: **"I come to you."** It's styled as a service route on a paper map of Winnipeg — one dashed route line draws itself down the page as you scroll, every section is a numbered stop, a fixed HUD readout tracks the km traveled, and the last stop is the visitor's own door (the booking form). Palette: paper white, one ink, one safety orange. Type: Big Shoulders (display), Archivo (UI), Azeret Mono (annotations).

## The free stack

- **Contact form:** FormSubmit (free, no account) posting to `arslansohail039@gmail.com`. The very first submission sends a one-time activation email that must be clicked once.
- **Hosting:** Vercel free tier.
- **Fonts:** Google Fonts, free.

## Notes

- No secrets in the repo. No frameworks, no keys, no paid services.
- `outreach.html` is marked `noindex, nofollow`.
- Cold email template follows CASL basics: real name, real address line, one-click opt-out line.
