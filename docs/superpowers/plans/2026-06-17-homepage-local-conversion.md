# Homepage Local Conversion Layout Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Refactor the homepage into a shorter, conversion-focused layout that still preserves local SEO signals for Bern and supports Google Ads traffic.

**Architecture:** Keep the site as a single static HTML file, but reorganize the page into a concise hero and top-services flow above the fold, then move trust, reviews, map, lashes, FAQ, and SEO support content lower on the page. Reuse the existing multilingual switching approach and simplify dense sections rather than adding new dependencies.

**Tech Stack:** Static HTML, inline CSS, existing vanilla JavaScript language toggles and tracking hooks.

---

### Task 1: Restructure the above-the-fold homepage

**Files:**
- Modify: `index.html`

- [x] Replace the current hero and CTA flow with a shorter local-conversion structure centered on Bern nail services, Treatwell booking, and the first-booking discount.
- [x] Reduce introductory copy in German, English, and Vietnamese to 1-2 short lines each.
- [x] Keep two primary actions only: online booking and calling.

### Task 2: Compress service discovery and pricing

**Files:**
- Modify: `index.html`

- [x] Replace the dense price section with a more scannable presentation that highlights top nail services first.
- [x] Keep Treatwell-aligned pricing data, but reduce cognitive load on first view.
- [x] Update featured service cards to match the new top-of-page service priorities.

### Task 3: Reorder lower-page trust and SEO sections

**Files:**
- Modify: `index.html`

- [x] Move trust, reviews, map/contact, lashes, and FAQ into a clearer sequence for local SEO and decision support.
- [x] Keep explicit Bern location signals, multilingual support, and booking details visible without long paragraphs.
- [x] Ensure keywords for Nagelstudio Bern, Manicure, Pedicure, Acryl/Gel, and Wimpern remain naturally present.

### Task 4: Refresh styling for readability and mobile scanning

**Files:**
- Modify: `index.html`

- [x] Reduce repeated glass-card density and create stronger visual hierarchy between hero, service cards, trust items, and lower SEO sections.
- [x] Make pricing and content blocks easier to scan on mobile.
- [x] Preserve the current brand feel while making the page look lighter and less text-heavy.

### Task 5: Verify content consistency

**Files:**
- Modify: `index.html`

- [x] Recheck that the 10 percent message only refers to the first online Treatwell booking.
- [x] Recheck that Treatwell-linked services and homepage messaging stay consistent.
- [x] Review final copy for German-first quality and remove wording that feels translated or repetitive.
