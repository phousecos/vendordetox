# Vendor Detox™ — Landing Page

A single-page marketing site for **Vendor Detox™**, a fixed-fee vendor-spend
diagnostic from J. Lynne &amp; Co., delivered by senior technology advisors.
The page is written for the mid-market C-suite — **CEO, COO, CFO, and CIO** —
and leads with the offer, the benefit, and transparent pricing.

## Contents

- `index.html` — the complete landing page. Self-contained: all CSS and
  JavaScript are inline, no build step and no external dependencies.

## Sections

1. **Hero** — headline, offer, and a sample "reconciled vendor registry" card
2. **C-suite value row** — what the Detox means for CEO / CFO / COO / CIO
3. **The blind spot** — the problem (shelfware, redundancy, autopilot renewals)
4. **How it works** — the four-step engagement
5. **What you receive** — the five deliverables
6. **Pricing** — the three fixed-fee tiers (Clarity / Standard / Enterprise)
7. **Savings Capture** — the optional, contingency-based second step
8. **When it pays off most** — fit criteria
9. **About** — the senior technology advisors who deliver the Detox
10. **Final CTA** — book a 30-minute call

## Editing

Before going live, replace these placeholders:

- **Scheduling link** — the "Book a call" buttons use `data-cta="schedule"`
  / `href="#"`. Point them at your real scheduling URL (e.g. Calendly).
- **Email** — the mailto link uses `hello@jlynne.co`; update if needed.
- **Portrait** — the About section uses a monogram placeholder (`JL`). Swap
  in a team photo or firm mark if desired.

## Preview

Open `index.html` in any browser, or serve locally:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```
