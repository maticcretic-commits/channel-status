# channel-status

All of Nitesh's channels in one place: status, latest post and links.
A single static page (`index.html`) — no build step, no trackers, no sign-in.

Live site: https://maticcretic-commits.github.io/channel-status/

## What it improves on the original

The original page (niteshlhsnda-droid.github.io/channel-status) listed 10 channels
from one account with follower counts and latest posts. This version keeps all of
that data and adds:

- A second group: the brands on the MaticCretic account (Daily Current Affairs and
  the meme brand — Meme Adda, ratified 1 Nov 2026 — on YouTube / Facebook /
  Instagram, plus Automate with Nitesh),
  with statuses from Jarvis's verified records — including the permanently
  disabled Instagram account, the selfie-gated Kal Se Pakka account, and the
  refused Facebook Page, so nothing looks live when it is not.
- Filters (platform + status), search, and a totals bar that counts live,
  needs-attention, and unknown/pending channels.
- Honest labelling: the page is a hand-updated snapshot, not a live feed. No
  figure is guessed — where a count or a URL is not verified, none is shown.
- Per-card platform marks drawn as inline SVG (no copied logo files).

## How to update

1. Edit the card data in `index.html` (status pill, facts, latest post, date).
2. Update the "Snapshot updated" line in the header and the group notes.
3. Commit and push to `main`. GitHub Pages serves the new version within
   a few minutes (CDN can lag — check with a hard refresh).

Rules for updates: never invent a follower/subscriber count, a post date, or a
URL. If it is not verified, write "not verified" / "not on file" and leave the
link off. Never mark the disabled Instagram account as recoverable, and never
mark the gated @kalsepakkamemes account as live or as the meme brand handle —
it stays parked untouched, and the meme brand is Meme Adda (ratified 1 Nov 2026).
