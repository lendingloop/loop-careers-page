# Loop Careers Page — Prototype

Clickable HTML prototype of a new **Careers** page for the Loop marketing site
(bankonloop.com), for stakeholder review. **The final build happens in Webflow** —
this file never ships as-is.

- **Open it:** double-click `index.html` (self-contained; fonts/images load locally from `assets/`).
- **Built with:** the `generate-marketing-page` skill
  (`~/loop/projects/Project #3 - AI Design Agent/SKILLS/generate-marketing-page/`).
- **Structure source:** Rebecca's mockup `Loop Careers — Flat@1080p (1).png` (guiding
  principles → leadership → FAQ → roles → Stay in the Loop). Nav + footer cloned from
  the live site (real link slugs, real palette `#033d2b` / `#c4f6c6` / `#f9f8f4`,
  ArticulatCF).
- **Interactive:** nav dropdowns, leadership tile selector, FAQ accordion, role
  search + department/location filters with live count and empty state, smooth-scroll
  hero CTAs.

## ⚠️ Placeholders / verify before sharing externally

| Item | Status |
|---|---|
| Vision & Mission graphics | CSS-gradient placeholders, labeled on-page — Rebecca is making original graphics |
| Leadership | **Real names/titles from public sources** (theorg.com, press) — verify titles are current. Quotes are **draft copy**, not real quotes. Photos are placeholder tiles |
| 9 open roles | Placeholder listings from the mockup — not real postings |
| FAQ answers | "What we look for" is from the mockup; the other six are **draft copy** from about-page themes |
| `careers@bankonloop.com` | Unverified — mockup said `career@`; the live site's careers form is unlabeled (homepage has a `jobs@trueteams.co` mailto). Confirm the right inbox |

Per request: no "Life at Loop" section, and no salary-range mentions anywhere
(the mockup's roles intro was reworded to drop "salary range").

## Hero (suggested, per brief)

The mockup's abstract-panel hero was replaced with the real site's dark-green hero
treatment (`assets/loop-hero-background.png`, the #035239→#011710 recipe), a
two-weight "Careers at **Loop**" headline, the live careers page's real subcopy, and
a roles-count chip that reads from the roles data.
