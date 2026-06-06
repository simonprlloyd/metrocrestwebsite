# Metrocrest — Page Expansion Guide & AI Prompts

The site build-out is **structurally complete**: 54 interlinked pages, schema, NAP, clean URLs, and a sitemap. Every service and area page is fully indexable right now.

This guide is for the optional next step from the workflow doc: bringing the core pages up to the **1,500–2,500 word** depth that wins competitive local rankings. Each core page has a marked slot where long-form copy drops in — no HTML knowledge needed.

---

## How to expand a page (2 minutes each)

1. Open the page file, e.g. `site/services/wedding-dress-cleaning/index.html`
2. Find this marker (use Ctrl/Cmd-F):
   ```
   <!-- ===== EXPANDABLE CONTENT: paste AI long-form copy below ===== -->
   ```
3. Run the matching prompt below in your AI of choice (Grok/Claude/etc.), with the bracketed parts filled in.
4. Paste the generated HTML between the two markers. Wrap paragraphs in `<p>` and use `<h3 class="h3">` for subheads — or ask the AI to output that formatting directly (prompt already requests it).
5. Save. Done.

**Business facts to feed every prompt (NAP):**
- Name: Metrocrest
- Address: 3709 Spring Valley Rd, Addison, TX 75001
- Phone: (972) 243-1982
- Since: 1999 · Rating: 4.7★ (309+ reviews)
- Differentiators: family-run since 1999, drive-thru, same-day (drop by 9 AM M–F), 24-hr after-hours drop box, full-time in-house tailor, hand-finished work, bridal specialty
- Hours: Mon–Fri 7–6, Sat 8–5, closed Sun

---

## PROMPT A — Core Service Pages (use for the 13 service pages)

> You are an experienced local SEO copywriter specializing in dry cleaning and bridal garment-care businesses. You write engaging, trustworthy content that ranks well and gets read by real people.
>
> Task: Write a high-value service page (1,800–2,500 words) for **Metrocrest**, a family-run dry cleaner and bridal house in Addison, TX (since 1999), to build topical authority around: **[SERVICE NAME — e.g. Wedding Dress Cleaning]**.
>
> Primary keyword: **[PRIMARY KEYWORD — e.g. "wedding dress cleaning Addison TX"]**
> Secondary keywords to use naturally: [list 4–6 related terms]
>
> Business facts to weave in: 3709 Spring Valley Rd, Addison TX 75001 · (972) 243-1982 · since 1999 · 4.7★ 309+ reviews · drive-thru · same-day option · 24-hr drop box · in-house tailor · hand-finished.
>
> Search intent: commercial + informational — people want to understand the service, trust the provider, and book.
>
> Instructions:
> 1. Open with the searcher's real concern and why Metrocrest answers it.
> 2. Scannable outline (H3 subheads): what the service involves → the Metrocrest process step by step → fabrics/items handled → pricing factors (no fixed prices, explain what drives cost) → why local clients choose us → FAQs → CTA.
> 3. Show E-E-A-T: concrete craft detail, real process, Addison/DFW references.
> 4. Use short paragraphs, occasional bullet lists, 1–2 small tables.
> 5. Tone: warm, expert, conversational. No fluff, no repetition.
> 6. Output as clean HTML: `<p>...</p>` for paragraphs and `<h3 class="h3">...</h3>` for subheads. No `<html>`/`<head>` wrapper, no inline styles.

## PROMPT B — Area Pages (use for the 8 area pages)

> You are a senior local SEO specialist who ranks single-location businesses by writing hyperlocal landing pages that dominate neighborhood searches.
>
> Task: Write an SEO-optimized neighborhood page (1,200–2,200 words) for **Metrocrest** (dry cleaner & bridal house, Addison TX, since 1999) serving **[AREA — e.g. Plano, TX]**.
>
> Rank for: "[service] [area]", "best dry cleaners [area]", "wedding dress cleaning near [area]".
> Primary keyword: **"dry cleaners [AREA]"**
>
> Business facts: 3709 Spring Valley Rd, Addison TX 75001 · (972) 243-1982 · just off the Dallas North Tollway · drive-thru · same-day · 24-hr drop box · pickup & delivery.
> Local tie-ins for this area: [landmarks/neighborhoods — e.g. Legacy West, Downtown Plano, Willow Bend].
>
> Instructions:
> 1. Analyze what [AREA] searchers want; prove relevance honestly without claiming a fake address there.
> 2. Outline (H3): neighborhood intro → why we're great for locals here → services tailored to them → directions/proximity proof → local FAQs → CTA.
> 3. Use real [AREA] references (streets, landmarks, commute patterns).
> 4. 8–10 local-flavored FAQs.
> 5. Tone: warm, community-oriented, neighborly. Human voice.
> 6. Output clean HTML: `<p>` and `<h3 class="h3">` only. No wrapper tags, no inline styles.

## PROMPT C — Service-in-City Combo Pages (optional, 30 pages)

The combo pages (e.g. `/services/dry-cleaning/plano/`) are intentionally lighter (~300 words) and serve longtail capture. Expand only the highest-value ones if you want. Use Prompt B's structure but keep to 600–900 words and focus tightly on the one service + one area pairing to avoid cannibalizing the parent pages.

---

## Interlinking rules already applied (don't break them)
- Service pages link to 2–4 area pages; area pages link to 3–6 service pages.
- Max 8–10 SEO links per sub-page. When you add long-form copy, you can add 1–3 more *contextual* links but stay under the cap.
- Vary anchor text — don't repeat the same phrase.

## After expanding
- Re-run nothing required; pages are static.
- Resubmit `sitemap.xml` in Google Search Console.
- The doc's reminder: keep a steady stream of reviews + fresh photos coming in.
