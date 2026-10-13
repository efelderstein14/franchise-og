# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

People who are considering becoming a franchise broker: CXOs who have run teams, budgets and P&Ls; sales professionals who can build relationships and work a pipeline; and consultants who already guide people through big decisions. They want work they own. Most arrive from social media or referrals, are early in their research, have not spoken to anyone yet, and need to trust the person before they book time with him. Prospective franchise owners are not the audience of this site.

## Product Purpose

The Franchise OG offers a free 30-minute intro call, by phone only (no video), with no obligation. The site exists to get aspiring franchise brokers to book that call. Success is a booked call. There is no paid offer behind the call: it is free advice only, and the site must not imply a coaching program, a network referral or any other sale.

## Positioning

The Franchise OG helped build the franchise brokerage space: over 25 years ago he launched one of the first franchise brokerages in the nation. A newer broker network or coach can teach the job; it cannot truthfully claim to have been there when the job was invented. The call is honest guidance, including telling people when brokering is not for them yet.

## Operating Context

Visitors land on a single page, usually on a phone, from a social post or a referral link. Visitors do not pick a time on a scheduler: every `data-booking` button opens a pop-up request form (name, phone, email), and the OG calls them back. Submissions are posted to a GoHighLevel workflow's Inbound Webhook trigger (`REQUEST_WEBHOOK_URL` in the inline script) as form fields: full_name, first_name, last_name, phone, email, interest (from the button's `data-interest`), source, page_url, utm_* and submitted_at.

## Capabilities and Constraints

- Static single page: `index.html` + `styles.css`, no build step.
- Keep the `data-booking` / `data-interest` wiring and the `REQUEST_WEBHOOK_URL` constant in the inline script; the form's consent line must stay under the submit button.
- The footer must carry the FDD disclaimer: "This is not an offer to sell a franchise. Franchise offerings are made only by Franchise Disclosure Document."
- Privacy policy and Terms live in `privacy.html` and `terms.html` (operator MFO Inc., Maryland law, contact topfranchises@gmail.com).

## Brand Commitments

- Name: The Franchise OG. He stays anonymous: no personal name, location or affiliations.
- Voice: first person, plain, direct, no hype, no pressure. "Straight answers, no pitch."

## Evidence on Hand

Facts that must stay consistent everywhere they appear:

- 25+ years in franchising.
- Launched one of the first franchise brokerages in the nation, over 25 years ago.
- 500+ candidates placed.
- 1,000+ brokers mentored.
- Free 30-minute intro call, by phone, no obligation. Not a video call, and not self-scheduled.

Assets: `images/og-headshot.jpg`, a faceless photo of a man buttoning a navy suit jacket, gold watch on his wrist; `images/og-wordmark-light.svg` and `images/og-wordmark-dark.svg` (not used by the current page).

There are no testimonials, case studies, press mentions, earnings figures or client names. Do not invent any; ask before adding new claims.

## Product Principles

1. Trust before the ask: earn belief with real, consistent facts before asking for time.
2. Honesty is the offer: "not yet" is a legitimate outcome of the call and should be said out loud.
3. One action: every path on the page ends at booking the call.
4. Respect the early researcher: no jargon walls, no pressure, no gatekeeping.
