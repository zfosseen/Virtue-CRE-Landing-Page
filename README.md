# Virtue CRE — Landing Page

The landing page for Virtue's commercial real estate vertical, intended to live at **ai.virtue.cre**. Static and self-contained: plain HTML, CSS, and a little JS. No build step, no dependencies.

## View it
Open `index.html` in any browser.

## Structure
- `index.html` — the entire site (all sections + styles + scripts inline)
- `assets/virtue-logo.png` — the Virtue wordmark used in the header and footer
- `assets/logos/` — monochrome tool logos (currently unused; the integrations bar is wordmarks)
- `MASTER-PLAN.md` — the build plan and handoff notes

## Hosting
Deploy `index.html` plus the `assets/` folder to any static host (or the Virtue site under the `ai.virtue.cre` path). Fonts load from Google Fonts at runtime.

## Before it goes live
- **Booking link:** the intake "Book a time" button points at a placeholder. Replace `REPLACE-WITH-GOOGLE-BOOKING` with the real Google Calendar appointment-schedule URL.
- **Intake backend:** the email form posts to `/api/cre-intake` (placeholder). Wire an endpoint that captures the email, auto-sends the discovery questionnaire, and optionally drops a calendar hold.
- **Headshots:** testimonial avatars use initials; swap in real photos when available.

## Notes
No API keys, tokens, or secrets are included in this repository.
