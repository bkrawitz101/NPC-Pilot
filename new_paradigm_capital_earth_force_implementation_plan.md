# New Paradigm Capital (NPC) & Earth Force by NPC — Implementation Plan

**Date:** November 25, 2026  
**Objective:** Upgrade the existing New Paradigm Capital website from a static informational site into a dual-sided, functional **Web Portal** connecting capital and asset-class designers (**NPC**) with skilled regenerative stewards and apprentices (**Earth Force by NPC**)—with zero placeholders or "coming soon" dead links.

---

## 1. Strategic Architecture & 2-Way Gateway

The front door acts as an active routing portal rather than a static brochure. Visitors are greeted with a unified macro-narrative before choosing one of two live operational portals:

* **The Shared Macro-Thesis:** Roughly 2% of the population currently farms, while economic transitions and automation will drive a massive wave back toward localized, land-based production. America uniquely enables fee-simple land ownership paired with common-law trusts and localized production—creating an unprecedented opportunity to turn underutilized land and skilled labor into multi-generational, resilient wealth.
* **Door 1: New Paradigm Capital (Capital & Asset Class)**  
  *Target Audience:* Capital allocators, peer asset-class designers, normative accounting specialists, and local investors backing land and labor.
* **Door 2: Earth Force by NPC (Stewards & Apprentices)**  
  *Target Audience:* The skilled "5%" who know how to work with nature (soil, solar, water, agroforestry, carpentry, legal) and the next generation ready to learn on a 6-month tour of duty.

---

## 2. Dual-Portal Feature Breakdown & Controlled "Bleed-Over"

Both portals run on a single shared backend directory of **People, Projects, and Places** (modeled on the clean profile architecture of LightTribe), using controlled cross-visibility ("bleed-over") so each side sees concrete proof of the other without drowning in irrelevant clutter.

| Portal Layer | Portal 1: New Paradigm Capital (NPC) | Portal 2: Earth Force by NPC |
| :--- | :--- | :--- |
| **Access & Gating** | **Mandatory Digital NDA Gate** before viewing financial instruments, promissory note structures, and private property assessments (no non-competes required). | **Open Enrollment Funnel**—zero financial or investor jargon upfront; simple permission waivers only when viewing private partner properties. |
| **Core Narrative** | The "pennies-to-dollars" financial vehicle: promissory notes backing skilled labor, normative accounting for ecological intangibles, and county-scale turnaround math (Nevada County pilot scaling to Reno, Sacramento, and the Bay Area). | "Ground-side Space Force" mobilization: trading fragile urban overhead for real skills, room and board, cash/1099 pathways, and earned land stewardship. |
| **Primary Action** | Review the asset-class thesis, stress-test the financial framework, and inspect vetted deals and talent pools. | Complete the **Skills & Passion Intake** (identifying core competencies, "1-in-10,000" rare skills, and preferred locations) to get matched with land and capital. |
| **Shared Directory ("Bleed-Over")** | Viewable profiles of vetted Earth Force leads, active apprentices, and assessed properties ready for funding. | Simplified, readable *8 Forms of Capital* primer plus active property listings showing where recruits can deploy. |

---

## 3. Core Functional Modules

### A. NPC Investor & Asset Class Portal (`/investors`)
1. **Digital NDA Onboarding:** Captures investor/peer credentials and logs a timestamped NDA signature before unlocking the data room.
2. **Asset Class & Normative Accounting Data Room:**
   * Promissory note structure backing Earth Force labor and land acquisition.
   * Normative accounting methodology quantifying ecological and intangible capital gains.
   * County-scale turnaround thesis (establishing the 2.5-hour urban-to-rural buffer model linking Nevada County with Reno, Sacramento, and the Bay Area).
3. **Vetted Talent & Land Directory:** Live view of Earth Force lead stewards, apprentice cohorts, and assessed properties ready for capital deployment.
4. **Property & Accountability Ledger:** Transparent public/investor reporting on active managed properties—documenting assessments, stewardship status, and accountability ("the good, the bad, and the ugly").

### B. Earth Force by NPC Portal (`/earth-force`)
1. **Mission Briefing & Value Proposition:**
   * Contrasts fragile urban living expenses against the basecamp stewardship model (room, board, cash/1099 income, and long-term equity/parcel pathways).
   * Presents a simplified, jargon-free explanation of the **8 Forms of Capital**.
2. **Two-Tier Recruitment Intake:**
   * **Tier 1 — Faculty / Lead Stewards (The 5%):** Individuals with proven hands-on expertise (regenerative soil, off-grid solar, water systems, agroforestry, ranching, natural building, or legal/structuring). Matched directly with funded land and freed from routine maintenance bottlenecks so they can teach and build.
   * **Tier 2 — Apprentices (6-Month Tour of Duty):** Gen Z, Millennials, and Gen X career-shifters seeking hands-on training in pods of 5–10 students under a Lead Steward, with room and board provided while earning their place in Earth Force.
3. **Structured Profile Generator:** Intake submissions automatically populate standardized **People, Projects, and Places** profile cards (capturing core skills, passions, rare talents, and target regions).

---

## 4. Phased Execution Timeline

### Phase 1: Immediate Sprint (Target: December 2026 Launch)
* **Visual & Design Continuity:** Maintain the established NPC design system (`#30210F` Dark Espresso, `#423321` Warm Charcoal, `#ECEAE6` Soft Sand, `#8D8173` Warm Taupe) across the gateway and both portals, giving Earth Force a bold, mobilized sub-identity.
* **2-Way Gateway Deployment:** Build the front-door landing experience routing cleanly into `/investors` and `/earth-force` with zero dead links.
* **NDA Gate & Investor Polish:** Wrap existing NPC financial documents and articles behind the NDA workflow and refine copy for peer review.
* **Earth Force Intake Launch:** Ship the recruitment intake form and connect submissions to the shared **People, Projects, and Places** database.
* **Accountability Ledger Launch:** Publish the initial property assessments and stewardship status module for December accountability milestones.

### Phase 2: Case Studies, Permissions & Cohort Matching (Q1 2027)
* **Permissioned 8 Forms of Capital Case Studies:** Upon receiving formal owner sign-offs, publish simplified *8 Forms of Capital* executive reports for **Scott Ladd**, **Michael Rash**, and the **Nail Factory** project across both portals as live proof-of-concept demonstrations.
* **Initial Pod Deployment:** Match the first cohort of Lead Stewards (with 1099/cash stipends and faculty housing) with 5–10 apprentices per site and underutilized partner acreage (including Bay Area landowners holding rural acreage within a 200-mile radius of Nevada County).

### Phase 3: Regional Hub Expansion (Q2–Q3 2027)
* **Urban-Rural Corridor Scaling:** Replicate the Nevada County pilot model across Northern California hubs—connecting rural production zones directly with **Reno**, **Sacramento**, and the **San Francisco Bay Area**—and introduce fractional equity/stewardship tracking inside member profiles.

---

## 5. Technical Architecture & Data Schema

* **Frontend:** Modular single-page application (HTML5 / Vite / React) with clean client-side routing (`/`, `/investors`, `/earth-force`, `/directory`) sharing UI components and authentication state.
* **Backend & Security:** PostgreSQL / Supabase (or structured API backend) enforcing role-based access levels:
  * `public` (Gateway, Earth Force mission, open recruitment intake, public property accountability highlights)
  * `earth_force_member` (Full Earth Force directory, simplified 8 Forms of Capital reports, property waivers)
  * `nda_investor` (Full NPC financial instruments, promissory note structures, full property assessments, and vetted talent pool)
* **Core Database Tables:**
  * `users_profiles` (`id`, `role`, `nda_signed_at`, `tier`, `hard_skills[]`, `rare_talents`, `passions`, `preferred_regions[]`, `bio`)
  * `properties_places` (`id`, `name`, `region`, `acreage`, `status`, `eight_forms_summary`, `permission_level`, `stewardship_notes`)
  * `projects_cohorts` (`id`, `property_id`, `lead_steward_id`, `apprentice_slots`, `focus_disciplines[]`, `funding_status`)