# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Mid-career professionals exploring a move into franchise brokering, usually early and still undecided:

- **CXOs** who have run teams, budgets and P&Ls and want work they own.
- **Sales professionals** who can build relationships and work a pipeline, and want to point those skills at something they believe in.
- **Consultants** who already guide people through big decisions.

They arrive curious, often before they have signed with any broker network. Their job is to find out, without pressure, whether this work fits them and what it really involves.

## Product Purpose

A single landing page for **The Franchise OG**, a franchising veteran who offers a free 30-minute intro call (phone or video). The call covers whether brokering fits the visitor, how brokers get clients, how brokers get paid, and which broker network suits them.

Success is a booked call. There is no paid offer behind the call: it is free advice only, and future work must not imply a coaching program, a network referral, or any other sale.

## Positioning

Advice from someone who helped start the franchise broker industry: over 25 years in franchising, and one of the first franchise brokerages in the nation. Because nothing is being sold, the advice can be straight, including "not yet" or "this isn't for you."

## Operating Context

- Visitors book through an external scheduling link. Every booking button carries `data-booking` and gets its URL from `BOOKING_URL` in `index.html`. It is still a placeholder (`https://calendly.com/REPLACE-ME/intro-call`).
- The flow is three steps: book (share background and interest), talk (30 minutes, visitor asks the questions), and leave with next steps.
- It is franchise-adjacent marketing, so the footer carries the disclaimer: "This is not an offer to sell a franchise. Franchise offerings are made only by Franchise Disclosure Document."

## Capabilities and Constraints

- Static site: `index.html`, `styles.css`, and a small inline script. There is no build step or framework.
- `/privacy` and `/terms` are linked but do not exist in this repo yet.
- **Confirmed figures:** 25+ years in franchising, 500+ successful placements, 1000+ brokers mentored. The current copy disagrees with these ("20+ years" in the hero and stats; "hundreds" and "thousands" in About). Bring it into line when the page is next edited.

## Brand Commitments

- **Name:** The Franchise OG. A persona for now; no real name is shown.
- **Assets:** `images/og-wordmark-light.svg`, `images/og-wordmark-dark.svg`, `images/og-headshot.jpg`.
- **Voice:** first person, plain and direct, no hype. Short sentences. It is candid about fit ("Most people who ask me about brokering should not start yet") and explicitly no-pressure.

## Evidence on Hand

- The three confirmed figures above, and the founding-era brokerage claim.
- The headshot photo.
- **Absent:** the person's real name, the name of the original brokerage, testimonials, case studies, press, logos, and named clients or networks. Future work must not invent any of these.

## Product Principles

1. **Honesty is the offer.** Nothing is being sold, so never write copy that sells harder than the call does.
2. **One action.** Every section serves booking the free call.
3. **Meet people early.** Talk to visitors as curious, not committed, and lower the stakes of reaching out.
4. **Claims stay provable.** Use only the confirmed figures. Mark anything unverified, and never fabricate proof.

## Accessibility & Inclusion

The page already includes a skip link, real values in the HTML for screen readers behind the animated stats, and a `prefers-reduced-motion` check. Keep these in place. No formal standard has been specified beyond that.
