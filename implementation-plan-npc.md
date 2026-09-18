# ANTIGRAVITY IMPLEMENTATION SHEET (VERSION 2.0)
## Project: New Paradigm Capital (NPC) & Light Portal Web Platform
**Document Version:** 2.0 (Updated with 2026-13-09 Sunday Mastermind Brief)  
**Target Output:** Single-File Static HTML5 Web Portal (`index.html`)  
**Strategic Lead:** Kiril Ravensong (Strategic Director)  
**Strategic Contact:** KirilRavensong@protonmail.com | 530-859-3888  
**Geographic Scope:** Nevada County, California (Nevada City)  

---

### 1. PROJECT OVERVIEW & GOVERNANCE PHILOSOPHY

* **Primary Purpose:** An invitation-only, gated web dashboard and landing page for an executive-level think tank, angel investors, and mastermind collaborators.
* **Core Philosophy ("WHY First"):** Lead strictly with the systemic purpose and vision before introducing products or financial mechanics: *"At Rethinking Capital, we believe there is more than enough wealth to solve all of society's core resilience, housing, and capital challenges."*
* **Design-Build Notice:** Clearly state that the initiative is in its pre-phase / design-build phase seeking a $500,000 seed raise to prove the land-labor backed asset class instrument across two properties in Nevada County.
* **Target Audience ("The New Medici"):** Visionaries, financial architects, legal experts, landowners, and cultural leaders with the skills, connections, resources, consciousness, and will to design and build new paradigm solutions at the county level.

---

### 2. ETHAN'S 4 QUALIFYING QUESTIONS FRAMEWORK
*(Integrated directly from the 2026-13-09 Sunday Mastermind session to anchor all messaging and UX flows)*

1. **Who is the audience?**  
   * **The New Medici:** Multidisciplinary leaders, angel investors, land stewards, and conscious creators who recognize that a county-level mastermind must be deployed *now* to create a replicable template for civilizational resilience.
2. **What is the message?**  
   * **Living Villages as the Core Solution:** Living villages solve nearly all current crises—providing multigenerational affordable housing, local food security, and an optimal environment to raise children and honor elders, independent of broader economic fragility.
   * **The Nevada County Opportunity:** 10,000+ acres of former marijuana cultivation land sit unused with intact water rights. While worthless to conventional cash buyers due to lack of infrastructure, they are ideal for land-labor backed agroforestry settlements.
3. **How do we deliver it?**  
   * **Need-to-Know Invite-Only Outreach:** Direct engagement backed by a private, gated web portal that holds high-level data and non-public briefs required for informed decision-making.
4. **What action are we asking them to take?**  
   * **Sign an NDA -> Log in -> Complete a simple bio -> Review interest-matching briefs -> Participate in the Mastermind or refer exceptional peers.**

---

### 3. DESIGN TOKENS & VISUAL STYLEGUIDE

* **Color Palette (CSS Variables):**
  * `--color-bg-primary` (Pure White / Main Backdrop): `#FFFFFF`
  * `--color-bg-card` (Taupe / Containers): `#b6a690`
  * `--color-text-primary` (Pure Black / Body Text): `#000000`
  * `--color-text-heading` (Metallic Gold / Titles): `#D4AF37`
  * `--color-accent` (Flat Gold / Titles): `#bf8b2d`
  * `--color-accent-blue` (Sky Blue / CTAs & Badges): `#9eb0d1`
* **Typography Specification:**
  * **Font Family:** `'Adobe Caslon Pro', serif, Arial, sans-serif`
  * **Section Labels:** `text-transform: uppercase; font-size: 0.7rem; font-weight: 700; letter-spacing: 0.18em; color: var(--color-accent)`
  * **Main Headlines:** `font-weight: 700; letter-spacing: -0.02em; line-height: 1.2; color: var(--color-text-heading);`
  * **Body Copy:** `Helvetica Light, Helvetica Medium (All Caps); font-size: 1rem; line-height: 1.6; color: var(--color-text-primary);`
* **Buttons & Interactivity:**
  * **Primary CTA:** Background `#30210F`, Border `1px solid #D4A359`, Color `#FFFFFF`, Padding `0.85rem 2rem`, Tracking `0.12em uppercase`.
  * **Hover Effects:** Subtle gold glow, clean opacity transitions (200ms ease).
* **Asset & Imagery Guidelines:**
  * **Strict Constraint:** Real, tangible local photography of Nevada County parcels, water infrastructure, and regional sites — strictly NO generic AI artwork.

---

### 4. COMPLETE SITE ARCHITECTURE & CONTENT SPECIFICATION

#### LEVEL 1: PUBLIC GATEWAY & HERO LANDING (Pre-NDA)

1. **Top Navigation Bar:**
   * Logo / Brand: **NEW PARADIGM CAPITAL**
   * Tagline Badge: *Nevada County Pilot Foundation*
   * CTA Button: `Member Access / NDA Request`

2. **Hero Section:**
   * **Category Label:** SYSTEMIC RESILIENCE & CAPITAL ARCHITECTURE
   * **Main Headline:** "Redefining Wealth, Reimagining Progress"
   * **Subheadline:** "A land- and labor-backed asset class structured via a targeted capital pool to deploy our flagship countywide pilot program in Nevada County, California."
   * **Vision Callout Box:** *"At Rethinking Capital, we believe that there is more than enough wealth to solve all of society's core resilience, settlement, and capital challenges."*
   * **Action CTAs:**
     * `Request Executive NDA & Access` (Triggers Gate Modal)
     * `Explore Strategic Vision` (Smooth scroll to Overview)

3. **Public Gateway Modal (NDA & Password Gate):**
   * Form Fields: Full Name, Email Address, Phone Number, Entity / Organization, Strategic Interest (Investor / Advisor / Landowner / Participant).
   * Checkbox: *"I agree to review non-public Pilot Foundation briefs under confidential executive think tank protocol."*
   * Password Input (Client-side trigger to unlock Dashboard Level 2).

---

#### LEVEL 2: EXECUTIVE THINK TANK DASHBOARD (Post-NDA Unlocked)

1. **Executive Status Banner:**
   * **Status:** Pre-Phase Design-Build Pilot Foundation ($500,000 Seed Raise)
   * **Location Target:** Nevada County, CA (2 Properties within a 15–30 minute driving radius)

2. **The $500k Dual-Asset Architecture Breakdown:**
   * **Position A — Village Land Acquisition (~$250,000):**
     * Asset: 160 Acres Sebastopol Raw Land Parcel (former cultivation site with intact water rights).
     * Mechanism: Skilled labor settles against land equity at **1,560 hours per 5 sovereign acres** (up to ~32 gross parcels).
   * **Position B — Commercial Asset Buyout (~$250,000):**
     * Asset: Castile on the Ridge (9-acre operating hospitality site).
     * Mechanism: Generates liquid cash flow via Lighthouse retreats; pays cash wages to workers.
   * **Position Zero — The Land Option:**
     * Low five-figure option securing the village parcel baseline prior to full raise completion.
   * **The Ring-Fence Protocol:**
     * Investor risk is strictly bounded to Castile on the Ridge.
     * Worker land equity is strictly bounded to Sebastopol land.
     * **No Cross-Collateralization:** Protects worker land equity from investor downside in all scenarios.
   * **The Labor Crossing Mechanism:**
     * Workers earn cash wages at Castile while settling land equity at Sebastopol. Avoiding commercial payroll cash expenses covers annual debt service on Castile.

3. **Document & Intelligence Repository (Interactive File Cluster):**
   * **Cluster A: Normative Accounting & Intangibles Framework:**
     * *Nevada County 8 Forms of Capital Assessment Index* (Financial, Social, Intellectual, Natural, Cultural, Spiritual, Experiential, Material).
     * *Rethinking Capital Normative Accounting Briefing Note* (Double-entry bookkeeping capitalizing natural/human assets onto balance sheets).
     * *Mastermind Core Thesis:* The 4 Questions Framework & Civilizational Resilience Brief.
   * **Cluster B: Land & Stranded Asset Recovery:**
     * *10,000+ Acre Agroforestry Opportunity:* Rehabilitating former cultivation sites valued at zero by cash buyers due to intact water rights.
     * *Stranded Assets & Fire Remediation Whitepaper:* Fire insurance challenges, underwater debt, and site remediation R&D.
     * *Historic Sample Audits:* Nail Factory Assessment & Redacted Ranch Reports.
   * **Cluster C: Legal & County Viability Briefs:**
     * *Full Spec Deeds & Conveyance Vehicle Options:* Fee title, tenancy-in-common, cooperative membership, ground leases.
     * *County Viability & 0.5% Buy-In Evaluation:* Transparent documentation tracking county support vs. alternative location deployment.

---

#### LEVEL 3: FAMILY OF BUSINESSES (Light Portal Ecosystem)

A responsive 4-card interactive grid representing the interconnected businesses:

1. **Earth Force:**
   * *Focus:* Cultivating resilient food forest villages, living university guilds, and self-sufficient settlements.
   * *Features:* Living University permaculture training; deployment of a 200-strong Permaculture Ranger Force across Nevada County.
2. **LIGHT:**
   * **LighTribe:**
     * *Focus:* Creative gig-economy network connecting cultural talent, artists, landowners, and active land projects.
   * **Light Creative:**
     * *Focus:* Full-spectrum creative agency providing brand strategy, spatial design, and messaging architecture for conscious enterprises.
   * **LightHouse:**
     * *Focus:* Transformative membership-driven retreat spaces and nature sanctuaries generating hospitality revenue.
3. **Natural Intelligence (NI):**
   * *Focus:* Open-source AI ecosystem mapping, real-time bio-metric processing, environmental digital twins, and alignment to living human values.
4. **Strategic Partners:**
   * *Ecosystem Alignment:* **ReThinking Capital** (fiscal sponsor & accounting frameworks), **Future Is Now** (art/music/technology convergence).

---

#### LEVEL 4: DYNAMIC APPLICANT INTAKE & DISCOVERY SORTING

An interactive step-by-step form that sorts respondents into four distinct discovery lanes for mastermind and investment onboarding:

* **Lane Selection:**
  * `Lane 1: Executive / Think Tank ("The New Medici")` (Asset class designers, legal, & financial architects)
  * `Lane 2: Investor Class` (Position A $250k Land, Position B $250k Commercial, or $50M Regional Pool)
  * `Lane 3: Strategic Referrers` (Connecting key political, land, or capital leaders)
  * `Lane 4: Local Participants / Workers` (Skilled labor, land donors, & regional rangers)
* **Form Inputs:** Contact Info, Area of Expertise / Intangible Assets Contributed, Mastermind Availability.
* **Footer Details:**
  * Direct Contact: **Kiril Ravensong** (`KirilRavensong@protonmail.com` | 530-859-3888)
  * Copyright & Disclaimer: *New Paradigm Capital LLC · Nevada County Pilot Foundation · Version 2.0 · Confidential Executive Think Tank Briefing · Not an offer to sell securities.*

---

### 5. TECHNICAL IMPLEMENTATION SPECIFICATIONS

* **Single File Structure:** Embed CSS in `<style>` block and JS in `<script>` block inside `index.html`.
* **State Management:** Simple JS state toggling between `#state-public` and `#state-dashboard` upon NDA password submission.
* **Modal Overlay Engine:** Reusable pure JS modal controller for the NDA Gate and Document Viewers.
* **Responsive Breakpoints:**
  * Desktop: `1200px+` (Multi-column grids)
  * Tablet: `768px - 1199px` (2-column grids)
  * Mobile: `<767px` (Single column stacked layout)
