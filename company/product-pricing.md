# Product & pricing

**Conflict-heavy section.** Prefer live homepage + checkout SKUs for “current”; keep older official pages as historical/alternate.

## Current primary offer (homepage + checkout)

- **Annual Superpower Membership** marketed as: **150+ lab tests across 2 blood draws**, dashboard, protocol, AI + care team, marketplace access.
- **Stated price (homepage / HSA landing / marketplace CTA):** **$349 per year**  
  Sources: https://superpower.com/ , https://superpower.com/hsa-fsa-eligible , https://superpower.com/marketplace/collections/panels
- **Checkout catalog SKUs [inferred from checkout catalog JSON], Sep 2026:**
  - `baseline-membership-sep-2026` → **$349.00/year** (`amount: 34900`)
  - `baseline-membership-sep-2026-ny-nj` → **$599.00/year** (`amount: 59900`)
  - Source: https://superpower.com/checkout
- Membership is **recurring annual**, auto-renews; cancel anytime for future renewals.
- Satisfaction refund window in Membership Agreement (through earlier of 7 days after initial results delivery or 45 days after start) — https://superpower.com/legal/membership (effective **9.01.2026**).  
  **Conflict:** some FAQ copy says **no refunds** (secondary site brief / FAQ framing).

## Older / alternate official pricing (still live or historical)

| Claim | URL / source | Notes |
| --- | --- | --- |
| **$199/yr**, **100+ biomarkers**, one panel/year framing | https://superpower.com/blog/superpower-is-now-199 (updated **March 26, 2026**) | Blog promo; conflicts with current $349 / 150+ / two-draw |
| Comparison table **$349/yr** vs clinics **$365/yr** | `/blood-test`, `/baseline-membership` | Aligns with current $349 |
| Base acquisition landing: **$399** or **$499**; at-home **+$99**; Galleri **+$1,092**; gut **+$239** | https://superpower.com/s/base | Legacy; “100+ labs”; “24 US states” language |
| CTA math **$0.82/day** (≈ $299/yr) vs marketplace **$0.96/day** (≈ $349/yr) | Homepage / marketplace | Day-rate inconsistency |
| Advanced Blood Panel add-ons | Quest **$388**; BioRef **$598**; Advanced upgrade **$189** / NY-NJ **$199** | **[inferred from checkout catalog JSON]** |
| Launch **$499**/yr **[off-site]** | TechCrunch Apr 2025 | Historical launch price |
| Employer ~**$179**/yr via Thatch **[off-site]** | Sacra | B2B channel |

### Must-read price conflicts

1. Current consumer baseline: **$349/yr**
2. Checkout NY/NJ: **$599/yr**
3. Blog (Mar 2026): **$199/yr**
4. Base landing legacy: **$399 / $499**
5. Press history: **$499** launch → later **$199** class messaging

## What’s included (current marketing consensus)

- **150+ biomarkers** across baseline + retest (two draws/year) — homepage, how-it-works, marketplace
- Results dashboard / Data Vault; upload past labs; wearable sync (Apple Health, Whoop, Oura, etc.)
- Personalized protocol (lifestyle, diet, supplements); **Superpower AI** chat with clinical guardrails
- **24/7 / on-demand care team** (Terms: non-clinical = CS, RDNs, coaches, advisors; clinical care via affiliated Medical Groups)
- Marketplace: add-on diagnostics (gut, toxins, **Grail Galleri**), supplements, peptides, prescriptions
- Cancel anytime (marketing); **HSA/FSA eligible**; **does not bill insurance**

### Biomarker / draw conflicts

| Topic | Claim A | Claim B |
| --- | --- | --- |
| Biomarker count | **150+** (homepage) | **100+** / “over 100” (Series A page, older FAQ/blog); blood-test FAQ sometimes mixes both |
| Draws per year | **Two** (homepage, how-it-works FAQ) | **One annual test** still on some blood-test / baseline FAQ and $199 blog |
| Panel framing | Baseline + **60+** retest | Older “single panel” packaging |

## Insurance / HSA–FSA

- Does **not** bill insurance (FAQ; Membership Agreement §6)
- Membership is **not** health insurance; Medicare claims for membership fees prohibited
- **HSA/FSA eligible** (marketed). Checkout marks `eligibleFundingPolicies: FLEX / HSA_FSA` **[inferred from checkout catalog JSON]**
- Terms: HSA/FSA may cover eligible non-prescription purchases; **cannot** be used for prescription medications on the platform

## Partnerships & acquisitions (official site)

| Item | Evidence | Label |
| --- | --- | --- |
| Quest Diagnostics | Lab network partner | Official |
| SoulCycle | Press feature linked from site | Official outbound |
| **Base** acquired | “Base has been acquired by Superpower” | https://superpower.com/s/base |
| **Feminade** | No dedicated public acquisition page (`/s/feminade` → 404); referral JS only on Base landing | Official site incomplete; full acquisition narrative **[off-site]** |
| B2B / orgs | Employers, health plans, consultants | https://superpower.com/organizations |
| LegitScript | Footer “LegitScript Certified” | Official |
