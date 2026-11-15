# NextAgent — The Tech Team for Winnipeg Businesses

**NextAgent** is Arslan Sohail's Winnipeg AI agency. The site sells one offer: we visit local businesses — restaurants, clinics, salons, gyms, auto shops — watch how they actually work, and make the boring tech parts run themselves. First visit is free. Run by **Arslan** (founder) with the NextAgent AI bench behind him.

**Live:** https://arslan-site.vercel.app *(once deployed)*

## What's here

| File | What it is |
|---|---|
| `index.html` | The public site — single file, zero build step, zero dependencies (Google Fonts only). |
| `outreach.html` | **Internal tool, not linked publicly.** Lead-list manager for cold outreach: add/paste emails, categories, status tracking (new → sent → replied → pass), copy-all button, CSV export, editable cold-email template. All data stays in the browser's localStorage. |

## Design

The site is built around one idea: **"We come to you."** It's styled as a service route on a paper map of Winnipeg — one dashed route line draws itself down the page as you scroll, every section is a numbered stop, a fixed HUD readout tracks the km traveled, and the last stop is the visitor's own door (the booking form). Palette: paper white, one ink, one safety orange. Type: Big Shoulders (display), Archivo (UI), Azeret Mono (annotations).

## The free stack

- **Contact form:** FormSubmit (free, no account) posting to `arslansohail039@gmail.com`. The very first submission sends a one-time activation email that must be clicked once.
- **Hosting:** Vercel free tier.
- **Fonts:** Google Fonts, free.

## Notes

- No secrets in the repo. No frameworks, no keys, no paid services.
- `outreach.html` is marked `noindex, nofollow`.
- Cold email template follows CASL basics: real name, real address line, one-click opt-out line.
