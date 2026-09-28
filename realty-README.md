# Lone Star Realty Group — AI Chatbot Demo

A single-file, self-contained demo website for a fictional Dallas real-estate brokerage,
showcasing an embedded AI chat assistant ("Dusty"). No build step, no external
dependencies — just open `index.html` in a browser.

## What it does

- **Fictional business homepage** — Lone Star Realty Group, Dallas, TX:
  hero, 3 featured listings (price / beds / baths / neighborhood),
  buyer & seller services, testimonials, contact info, office hours.
- **Embedded chatbot widget ("Dusty")** — friendly Texas-realtor personality,
  rule-based keyword/intent engine written in vanilla JS:
  - **FAQs** — areas served, buying process steps, commission structure,
    financing / pre-approval guidance
  - **Listing search** — understands natural queries like *"3 bed under 500k"*,
    *"condo under 350k"*, *"5 bedroom"* and matches against the sample listings
  - **Viewing booking** — multi-step flow: pick a property → name → phone →
    email → preferred date/time → confirmation summary with reference number
  - **Seller lead capture** — property address → selling timeline → name → phone,
    promises a free 24-hour market analysis
  - **Callback capture** — name + phone for anything the bot can't answer
- **Page ↔ chat integration** — each listing card has an "Ask Dusty about this
  home" link that opens the widget and asks about that property directly.
- **Mobile-responsive**, typing indicator, quick-reply chips, input validation
  (phone digits, email format), graceful fallbacks.

## Files

- `index.html` — the entire demo (inline CSS + JS, works offline)

## Notes

- "Lone Star Realty Group", the listings, phone number, and reviews are all
  fictional — this is a portfolio piece demonstrating chatbot capabilities for
  real-estate businesses.
- The bot is a compact rule-based demo engine, not a live LLM integration.
