# Sources — Provenance

**Profile compiled:** September 2026  
**Workspace root:** `/workspace/mchu-1-superpower/`

## Provenance table

| Output / fact domain | Agent / label | Source file (absolute) | Date | Notes |
| --- | --- | --- | --- | --- |
| Full official-site company brief | **superpower (out)** / site pack | `/workspace/superpower-health-company-brief.md` | Sep 2026 | → `sources/web/company-brief.md` (legacy mirror: `sources/website-brief.md`). Attachment: agent `70df4b9e-…` |
| Inbound sitemap / nav notes | **superpower (in)** | inbound scrape (def501c6) | Sep 2026 | → `sources/web/inbound-tree.md` (full) + `sources/web/inbound-notes.md` (~7.4k URLs; Explore / Compare / Company / Legal) |
| Multi-source diligence brief | (workspace pack) | `/workspace/superpower/SUPERPOWER_HEALTH_COMPANY_BRIEF.md` | Sep 2026 | Includes off-site press, lawsuit docket, Sacra; used only where labelled **[off-site]** |
| Official Series A notes | first-party page extract | `/workspace/superpower/OFFICIAL_Series_A.md` | Sep 2026 | From https://superpower.com/series-a → `sources/series-a.md` |
| X/Twitter brief + status IDs + screenshots | **superpower (X)** | `/workspace/superpower-x/BRIEF.md` + deep OrganAge/Giannis/Series A + PNGs | Sep 2026 | → `sources/x/` (incl. `series-a.md` + `assets/`) + root `assets/` (legacy: `sources/x-brief.md`). Attachment: agent `5b6cff69-…` |
| Company overview / pricing / labs / legal / contact | consolidated | derived from above | Sep 2026 | Prefer official-site; flag conflicts |
| Leadership (Kevin full name, X status) | site + X | website briefs + x-brief | Sep 2026 | Site often says “Kevin” only; X names Kevin Unkrich |
| Investors | Series A page + X | `sources/series-a.md`, `sources/x/series-a.md` | Sep 2026 | Canonical $30M Forerunner-led list; X status `1914701970830713224` frames Forerunner+Day One |

## Agent attachment paths (if useful)

- `/home/box/agent-data/agents/70df4b9e-b773-4ef1-bd7b-9b9397df5d5f/attachments/` — long website brief
- `/home/box/agent-data/agents/def501c6-6579-4d4b-a903-a6f83e76b861/attachments/` — shorter site brief
- `/home/box/agent-data/agents/5b6cff69-0954-40db-8505-009d2a8fa133/attachments/` — X PNGs

## Evidence labels used in company docs

| Label | Meaning |
| --- | --- |
| *(unmarked / official-site)* | From superpower.com pages |
| **[inferred from checkout catalog JSON]** | Embedded checkout SKU amounts |
| **[off-site]** | Press, Sacra, LinkedIn, dockets, third-party estimates |
| **[X]** | Public X.com profile notes |
| **Conflict** | Same-site or cross-source disagreement — both sides kept |

## Source packs (preferred paths)

- Web: `sources/web/README.md`, `sources/web/company-brief.md`, `sources/web/inbound-tree.md`, `sources/web/inbound-notes.md`
- X: `sources/x/README.md`, `sources/x/BRIEF.md`, `sources/x/series-a.md` (+ `sources/x/assets/` screenshots)
