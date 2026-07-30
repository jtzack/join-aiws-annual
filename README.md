# AIWS Annual Premium Upgrade Landing Page

Landing page promoting the upgrade offer to an AI Writing Skool (AIWS) Annual Premium Membership.

## What's here

- `index.html` — the complete landing page. Fully self-contained (single file): all styles are inline, fonts load from Google Fonts, and the SamCart checkout (`aiws-annual` on the `ship` subdomain) is embedded at the bottom of the page.

## Page structure

1. **Hero** — headline, sub-headline, and CTA button that anchors down to the checkout
2. **The Upgrade** — 3 benefit cards (save $388/year, priority Hot Seats, unlock 9 mini-courses) plus a monthly-vs-annual price comparison
3. **Inside Each Course** — checklist of what every mini-course includes
4. **Here's What's Inside** — grid of all 9 Digital Writing Fundamentals mini-courses
5. **AIWS Standard** — everything included in the standard membership
6. **Checkout** — embedded SamCart checkout

## Swapping in real assets

The 9 course cards currently use CSS gradients styled after the official course covers. To use the real cover images instead, add them to an `images/` folder and replace each card's `.course-art` background (the `--art` custom properties `c1`–`c9` in the `<style>` block) with the corresponding image. Same goes for the AIWS logo in the header/footer — the text-based logo can be replaced with an `<img>` tag once a logo file is added.
