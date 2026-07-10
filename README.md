# WhatsApp Add-on Gallery

A browsable pattern library of 95 real-world use cases for the CleverTap WhatsApp add-on, across 12 APAC verticals. Not a deck. A tool you can open mid-conversation and filter to the right prototype in seconds.

**Live:** https://shijunneo-bot.github.io/whatsapp-addon-gallery/

> Swap the URL above if your repo name differs. Pages serves it from `index.html`, so the link stays clean.

---

## What this is

Most WhatsApp pitches stall at "what could we even send?" This answers that visually. Every card is a message pattern tied to a real business moment, with a live WhatsApp preview, the Meta category, the cost logic, and the timing signal that makes it relevant now. Built to explore what WhatsApp can do for a business, one industry at a time.

## What's inside

Five tabs:

- **Use-Case Library** — the 95 cards. Filter by vertical, Meta category, cadence, or deliverability. Search, group or flatten, then open any card for the full pattern.
- **Direct vs Connect** — the two ways to run WhatsApp on CleverTap, and what each one can and cannot do.
- **Categories & Economics** — Meta's template categories (Marketing, Utility, Authentication) and the free-window and per-message cost logic behind them.
- **Setup, Templates & WABA** — how templates get created, submitted, and approved, plus the WABA basics.
- **How to Use This** — a short reading guide for the tags and stamps.

## What each card gives you

Open any card for the goal, the roadblock it solves, the mechanics, the trigger that makes it relevant now, and a live WhatsApp mockup with sample copy. Two things take it from "nice pattern" to "I can build this":

- **Copy message / Copy template** — grab the body text alone, or the full structured block (category, header, body, buttons) as an approval-ready draft.
- **Set it up in CleverTap** — a closest-match config section that reads straight down like the campaign builder: Qualification, Message type, Template category, Header specs, Body variables mapped to `{{1}}` `{{2}}`, Buttons, and When. Plus a "before you build" note for the one wall nobody flags, that the template has to be approved in Meta first.

## Reading the tags honestly

- **Deliverability stamp** comes first on every card: CleverTap-ready, Caveat, or Not via CleverTap.
- **`suggested`** marks a best-fit starting point, not gospel. It shows up on judgement-call fields like Qualification, where the right answer depends on your own project setup. The structural facts (category, header specs, variables) carry no tag because they are certain.
- **Authentication and OTP are not deliverable via CleverTap Direct.** Those cards are shown for completeness and flagged. Route one-time codes through SMS or a dedicated auth provider.
- **Placeholder tokens** like `{{name}}` are readable drafts, not live variables. Map real values in the template builder before sending.
- **Meta rates are current to Jan 2026.** Confirm the live rate card before any cost model.

## Updating it

One self-contained `index.html`, everything inline, no asset folder. To ship a new version:

1. In the repo, **Add file → Upload files**, drag the new `index.html` in (same name replaces the old one), **Commit changes**.
2. Pages redeploys in about a minute. Same URL.
3. If the browser still shows the old version, hard refresh (Cmd+Shift+R, or Ctrl+Shift+R on Windows). That is cache, not a failed deploy.

## Build standards

- Single self-contained HTML file, all CSS and JS inline, no external assets.
- The card content and the config section are engine-driven. New cards inherit the copy actions and the CleverTap setup section with no extra work.
- Verified headless before shipping.

---

Built and maintained by SJ Neo for the CleverTap APAC CS team.
