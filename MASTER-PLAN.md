# Virtue CRE — Website Master Rebuild Plan

**Property:** ai.virtue.cre · **Owner:** Zach · **Build:** static HTML/CSS, handed to Johnny to host on the Virtue site
**Last updated:** 2026-06-02 · **Target:** working rebuild over the next 2–3 days

---

## 1. The vision

Zach owns the **commercial real estate** vertical of Virtue. Johnny and Liam keep the parent `virtue.company` brand generalized and unbranded. `ai.virtue.cre` is the CRE-only property: an easy-to-understand, high-converting landing site that **every channel routes into** — LinkedIn, cold email, a CRE-only Meta ads campaign, and the in-person "Using Claude in CRE" events.

North-star references (Zach's picks): **Costanera** (favorite — the "operations on autopilot" five-box section), **Pacific Software Ventures**, **AR Consulting**. The bar: looks professional and product-grade, not "vibe-coded."

## 2. Locked decisions (from the positioning session)

- **Positioning:** "The AI build partner for commercial real estate." (hero line, Option B)
- **Identity:** embedded build partner, not rented AI. You own it, we stay.
- **ICP:** all of CRE — brokers, debt & equity fund managers, acquisitions/operators.
- **On-ramp offer:** **The First Build** — bring one workflow, fixed price, 2–3 weeks, you keep it. **Money-back if it misses the scoped hours.**
- **Domain:** `ai.virtue.cre`. Handoff: Zach builds, Johnny hosts/updates.
- **Distribution:** outreach + Meta ads + events all point here.

### Locked in build session (2026-06-02)

- **Landing scroll order:** Hero/CTA → integrations marquee → What we build → Testimonials → How we work (3 steps) → price + Get started → Events → Fit → footer.
- **Price:** the dashboard/build is **$20,000–$40,000 depending on scope** (shown on page).
- **Testimonials slider:** Julia Heriford (CBRE) and Don Fosseen (Head of Acquisitions, Goodman Real Estate). Quotes drafted, pending their approval.
- **Integrations marquee:** grayscale logo bar — Outlook, Excel, SharePoint, OneDrive, Mailchimp, Instantly, HeyReach (real logo SVGs to be swapped in; wordmarks for now).
- **3-step process:** Discovery → Demo → Full integrated build.
- **Booking:** replace Calendly with a Google Calendar **appointment-schedule** link that writes directly to Zach's calendar (Zach generates the public URL in Google Calendar; a static site cannot write to a calendar on its own).
- **Intake automation:** the primary CTA captures an email, then auto-sends the brand-tool discovery questionnaire (the BG/Sansome format) so answers arrive before the first call. Needs a small backend endpoint (Johnny) — UI is mocked now.
- **Events tab:** upcoming in-person events + a Luma join link + proof of past event success.

## 3. Open decisions (need Zach)

- [x] **Design direction** — LOCKED: **hybrid** (Virtue cream/ink palette + Costanera five-box layout, in-card UI mockups, conversion structure). On the Virtue kit, no sign-off needed. See §4.
- [ ] **The five CRE capability cards** — confirm the final five and their names. See §6.
- [x] **Scope** — LOCKED: **multi-page** (Landing / Solutions / Process / About / Blog). Build the landing centerpiece first, then replicate the approved shell across pages.
- [ ] **Price** for The First Build (pending Johnny) — page can launch with "scoped on the call" until set.
- [ ] **Naming permission** — can we name Goodman and Sansome (logo / quote)? Biggest credibility unlock.
- [ ] **Real metrics** — confirm the 60% / 30–40% / 2–3 week stats are defensible to publish.
- [ ] **Brand-kit divergence** — if we go dark/serif, confirm Johnny is OK diverging from the Helvetica-only Virtue kit for the CRE sub-brand.
- [ ] **Rady fork** — compete head-on vs coexist with Maxwell Rady / AR Consulting.

## 4. Design direction

Costanera is the north star for **structure and polish**, not necessarily palette. The "vibe-coded" feeling we are fixing comes from flat color blocks and no product imagery. Costanera beats that with: a confident display headline, **mini UI mockups inside each capability card**, generous spacing, and restrained motion.

**Recommended: hybrid.** Keep the Virtue cream/ink palette (continuity with the deliverables prospects receive), but steal Costanera's five-box layout, the in-card UI mockups, and the conversion structure. If we decide the CRE site should feel more like a product company than a consultancy, we move to a darker, higher-energy treatment (this diverges from the parent brand kit and needs Johnny's sign-off).

## 5. Homepage spec (section by section)

1. **Nav** — Virtue·CRE mark, links (Approach / The First Build / Proof / Events), primary CTA "Start with one workflow."
2. **Hero** — "The AI build partner for commercial real estate." + outcome subhead + dual CTA + ex-CBRE trust line.
3. **The five-box capability grid** (centerpiece, Costanera-style, with mini UI mockups). See §6.
4. **Why us** — three pillars: operators not agency · you own it, we stay · we teach CRE to use AI.
5. **The First Build** — the offer card, 3 steps, money-back guarantee.
6. **Proof** — stat band + named/anonymized builds (Goodman, Sansome) + event traction.
7. **Fit** — "a fit if / not a fit if."
8. **Events** — Using Claude in CRE as the community funnel.
9. **CTA band + footer.**

## 6. The five CRE capability cards (proposed — confirm/adjust)

Costanera's five were generic (AI Agents, AI Workflows, Dashboards, Operations Software, Process Automations). Ours are CRE-specific, each with a mini UI mockup:

1. **AI Email Agent** — drafts, triages, and routes deal and tenant email in your voice, with checkpoints where they matter.
2. **LP & Investor Reporting Agent** — investor updates and committee memos generated from your live numbers, in your format.
3. **Underwriting & Lease Abstraction** — proposals, OMs, and leases read and run through your model, so a deal arrives already analyzed.
4. **Acquisitions Dashboard** — every deal, its stage, and what needs you today, pulled into one screen.
5. **Property Management Dashboard** — portfolio health, occupancy, and key dates unified for the people who decide.

*(Alternates to swap in: Deal Sourcing Agent · Comp & Market Intelligence · Process Automations.)*

## 7. Distribution & growth

- **LinkedIn cadence** — the repeatable post: "new Claude model shipped → here is what changed for CRE → here is what we built with it → comment to get it." Route to ai.virtue.cre.
- **Meta ads (CRE-only)** — mirror Costanera's channel that drove 17 clients in 3 months. Dedicated CRE creative → the landing page.
- **In-person events** — "Using Claude in CRE" as the trust-and-community funnel; capture and route to the site.
- **The Rady list** — 3,470 enriched commenters as a first warm audience.

## 8. Handoff to Johnny

- Deliver as clean, self-contained static HTML/CSS (no build step), plus an `/assets` folder.
- Asset list to hand over: logos (CBRE + named clients if permitted), founder headshot/bio, event photos, any real product screenshots for the card mockups.
- Note canonical URL and any redirects from existing CRE traffic.

## 9. Phased plan (2–3 days)

**Day 1 — Direction + centerpiece**
- [ ] Lock design direction (§4) and the five cards (§6)
- [ ] Build the five-box capability grid with mini UI mockups
- [ ] Refine hero to remove the "vibe-coded" feel (type scale, spacing, real trust signal)

**Day 2 — Conversion spine**
- [ ] The First Build offer section (final copy, guarantee, price or placeholder)
- [ ] Proof section (stats + builds + event), Fit, Events, CTA band
- [ ] Full responsive pass + restrained motion

**Day 3 — Real content + handoff**
- [ ] Swap placeholder copy/stats for confirmed, defensible content
- [ ] Drop in real assets (logos, headshot, screenshots)
- [ ] Final QA (brand rules, links, mobile) + package for Johnny

## 10. Inputs needed from Zach (checklist)

**Zach to do (reminders):**
- [ ] Create the Google Calendar **appointment schedule** and send the public booking URL (replaces the placeholder in the intake section)
- [ ] Send the **Luma event URL** (replaces placeholder in Events)
- [ ] **Headshots** for Julia Heriford and Don Fosseen
- [ ] Get **Julia and Don to approve** their drafted testimonial quotes

**Emailed to Johnny (2026-06-02):**
- [ ] Intake auto-send backend: `/api/cre-intake` → auto-send questionnaire + calendar hold
- [ ] Virtue codebase/assets: founder bios + headshots, data-volcano image, brand fonts/colors/logo lockups

**Done this session:** monochrome tool logos (Outlook/Excel/SharePoint/OneDrive/Mailchimp/HubSpot + Instantly/HeyReach wordmarks), Goodman acquisitions hero mock, stats ($2B+ / 60% / 2–6 wks / 57+), $20–40k average-engagement price + redesigned guarantee card, intake UI cleanup, removed the T-12s line.
