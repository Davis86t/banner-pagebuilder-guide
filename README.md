# Banner PageBuilder Guide

Practical, experience-driven documentation for maintaining and extending **Ellucian Banner PageBuilder** applications in higher-education environments.

This repository consolidates internal-quality reference material developed while supporting legacy Banner systems at a public university. It is intentionally pragmatic, opinionated, and written for developers who are already responsible for keeping PageBuilder apps alive in production.

---

## What This Is

This repo contains three complementary HTML documents:

- **PageBuilder Engineering Handbook**  
  A deep technical reference covering PageBuilder’s mental model, Virtual Domains, datasets, AngularJS scopes, and real execution flow.

- **PageBuilder Survival Guide**  
  A day-to-day working guide for developers touching existing PageBuilder pages, Virtual Domains, and resources.

- **PageBuilder Pitfalls Cheat Sheet**  
  A concise collection of the most common traps, failure modes, and proven fixes encountered in real Banner PageBuilder work.

All documents are provided as **self-contained HTML**, with dedicated dark (screen) and print versions and consistent layout across both. 

---

## Who This Is For

- Higher-ed software developers maintaining Banner / PageBuilder apps
- Developers inheriting legacy PageBuilder pages with little documentation
- Teams onboarding new devs into Banner Extensibility
- Developers who already know SQL, PL/SQL, and JavaScript and need PageBuilder-specific reality

---

## Who This Is Not For

- Beginners learning JavaScript or SQL
- “Hello World” PageBuilder tutorials
- Official Ellucian documentation
- Marketing or feature overviews of Banner

This material assumes you are already working in a **production, legacy, higher-ed environment**.

---

## How to Use This Repo

**Recommended order:**

1. Start with the **PageBuilder Survival Guide**  
   Use it while actively working on pages, domains, or debugging issues.

2. Reference the **PageBuilder Engineering Handbook**  
   When you need to understand *why* something behaves the way it does.

3. Keep the **PageBuilder Pitfalls Cheat Sheet** open  
   Especially when PageBuilder is “being weird” and not throwing helpful errors.

These documents are designed to be used together.

---

## Viewing the Docs

This repository is published as a browsable reference site via GitHub Pages.

- Use the **dark versions** for on-screen reading.
- Use the **print versions** for hard copies or PDFs.
- Links from the index page open in new tabs to preserve navigation.

The HTML files can also be downloaded and used locally with no build step.

---

## Philosophy

- Pragmatic over academic
- Maintainability over cleverness
- Assume legacy, production risk, and institutional constraints
- Treat PageBuilder as **AngularJS + PL/SQL under a DSL**, not a WYSIWYG tool

If you understand the real execution flow, PageBuilder becomes predictable — even when it’s unpleasant.

---

## Format & Maintenance

- HTML only (no PDFs)
- Print-friendly layouts included
- Actively maintained as real issues are encountered
- Built from internal notes, prior work, and production debugging

---

## Disclaimer

This repository is **not affiliated with or endorsed by Ellucian**.  
All product names are used for descriptive purposes only.

Content reflects real-world experience maintaining Banner systems and may not align with official documentation.

---

## Author

**Tanner Davis**  
Software Developer · Higher Education  
Focus: legacy systems, maintainability, and survivable enterprise stacks
