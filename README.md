# The WhatsApp Add-on Gallery

A browsable pattern library of **100 WhatsApp Business use cases** for CleverTap, across 12 APAC verticals. Not a deck. A tool you can open mid-conversation and filter to the right prototype in seconds.

**Live:** https://shijunneo-bot.github.io/whatsapp-addon-gallery/

---

## What this is

Most WhatsApp conversations stall on one question: what do we actually send? This answers it visually. Every card is a message pattern tied to a real business moment, with a live WhatsApp preview, the Meta template category, the cost logic, and the timing signal that makes it relevant now.

## What's inside

Six sections:

- **Use-Case Library** — the 100 cards. Filter by vertical, Meta category, cadence, or deliverability, then open any card for the full pattern.
- **Why WhatsApp · Evidence** — sourced benchmarks on reach, lifecycle outcomes, marketing and utility performance, and ads that click to WhatsApp. Every figure is attributed, including where the research was vendor-commissioned.
- **Direct vs Connect** — the two ways to run WhatsApp on CleverTap, and what each one covers.
- **Categories & Economics** — Meta's four categories and the free-window logic that drives cost.
- **Setup, Templates & WABA** — how templates get created, submitted, and approved.
- **How to Use This** — a short reading guide for the tags and stamps.

## What each card gives you

The goal, the roadblock it solves, the mechanics, the trigger that makes it relevant now, and a live WhatsApp mockup with sample copy. Two things take it from pattern to build:

- **Copy message / Copy template** — the body text alone, or the full structured block as an approval-ready draft.
- **Set it up in CleverTap** — a closest-match config that reads down like the campaign builder: Qualification, Message type, Template category, Header specs, Body variables mapped to `{{1}}` `{{2}}`, Buttons, and When. Plus the reminder that the template has to be approved in Meta first.

## Reading the tags honestly

- **Deliverability stamp** comes first on every card: CleverTap-ready, Caveat, or Via auth provider.
- **`suggested`** marks a best-fit starting point on judgement-call fields such as Qualification, where the right answer depends on your own project setup. Structural facts carry no tag because they are certain.
- **Authentication** one-time passcodes are routed through a dedicated auth provider or SMS rather than CleverTap Direct. Those cards are flagged so the full channel picture is visible.
- **Placeholder tokens** like `{{name}}` are readable drafts. Map real values in the template builder before sending.
- **Rates and benchmarks** are current to the dates cited. Confirm the live rate card before any cost model.

## Files in this repo

| File | Purpose |
|---|---|
| `index.html` | The entire gallery, self-contained |
| `og.png` | Open Graph share image, 1200x630 |
| `robots.txt` | Crawler directives, including AI answer engines |
| `sitemap.xml` | Search engine sitemap |
| `llms.txt` | Structured summary for AI engines |
| `README.md` | This file |

All six belong at the repo root. `og.png`, `robots.txt`, `sitemap.xml`, and `llms.txt` must sit at the root or their URLs will not resolve.

## Updating it

One self-contained `index.html`, everything inline, no asset folder.

1. In the repo, **Add file → Upload files**, drag the new file in (same name replaces the old one), **Commit changes**.
2. Pages redeploys in about a minute. Same URL.
3. If the browser still shows the old version, hard refresh (Cmd+Shift+R, or Ctrl+Shift+R on Windows). That is cache, not a failed deploy.

## Build standards

- Single self-contained HTML file, all CSS and JS inline, no external assets or libraries.
- Light and dark themes, both tested against WCAG AA contrast.
- Reduced-motion honoured, keyboard operable, skip link, visible focus states.
- Structured data (WebSite, CollectionPage, FAQPage, ItemList, BreadcrumbList) plus a no-JavaScript crawlable fallback listing all 100 use cases.
- Card content and setup sections are engine-driven, so new cards inherit them automatically.

---

Part of a seventeen-gallery CleverTap channel suite. Built and maintained by SJ Neo.
