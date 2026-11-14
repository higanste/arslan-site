# PRODUCT.md

## Product

**Arslan** — personal profile / personal-brand site for Arslan Sohail (16), Winnipeg, Canada.

Positioning: **"the tech guy" for local Winnipeg businesses.** He comes to your business, looks at how you work, and shows you how AI + automation + a better web presence can make it slick. Not a faceless agency — one sharp young person who shows up, speaks human, and fixes your tech friction.

Assumption (labeled): nextagent.site is his agency domain; this profile is personal and may later live under a subpage or personal domain. No physical phone number shared yet — contact is email-first.

## Audience

Owners/managers of small local Winnipeg businesses — restaurants, clinics, salons, gyms, auto shops, retail. Usually 35–65, not techy, on their phone, skeptical of anything that smells like a scam or an expensive upsell. They found the site from a cold email, a QR code, a business card, or word of mouth.

## Visitor's job

Understand in ~5 seconds: "oh, a local kid who makes tech/AI work for businesses like mine." Then believe it enough to act.

## Primary action

**Book a free tech checkup** — a short form (name, business, what's annoying them) that sends to arslansohail039@gmail.com. Free, no commitment, framed like a free estimate, not a sales call.

## Proof

Real built projects (verified by the user): NextAgent (agency, nextagent.site), OnlyYes (onlyyes.life), ArslanAI, Arslan portfolio (arslanpro), arslanagnet, VizoraAI, linguaboss (Urdu translator), horror game builds, improveyou. Framed honestly: 10+ projects built by a 16-year-old — the count and the age ARE the story.

## Constraints

- **Free everything** — no paid APIs, no paid services. Contact form must be a free tier (FormSubmit or equivalent).
- **Mobile-first** — the audience lands on phones.
- **Slick + white base** with full-crazy motion (user confirmed: Awwwards-style kinetic type, scroll madness, white/slick ground but unhinged motion).
- Honest age: 16 is the selling point, never hidden, never lied about elsewhere.
- Language: human, confident, zero corporate jargon. He talks like a person who fixes things.

## Brand commitments

- White/light ground (user-pinned), motion as the loud layer.
- The "tech guy who shows up" narrative: visit → look → diagnose → automate → make it slick.
- Free tech checkup as the standing offer.

## Security posture (from user's pasted checklist)

Static site: no auth, no JWT, no GraphQL, no XML parsing — most attack classes n/a. Real items: no hardcoded API keys/credentials in the repo or client bundle (Vercel already flagged hardcoded Firebase creds in nextagent-v3), contact endpoint must not expose secrets, and the Vercel token shared in chat must be rotated. X-Forwarded-For/cache/CSRF items: n/a for a static page with no cookies/sessions; form posts to a third-party free service over HTTPS.
