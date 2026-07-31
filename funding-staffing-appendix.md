# Appendix: Funding Justification & Staffing Plan (Revised)
### Supporting documentation for the $3.18M funding request — TechNovation AI Clinical Decision Support

---

## Third-Party Vendor Landscape

Naming real, current market players grounds the pricing and de-risks the "build vs. buy" argument — the panel can see this isn't a hypothetical technology category, it's an active, competitive market TechNovation is entering deliberately.

| Vendor | Role in this project | Why selected |
|---|---|---|
| **OpenEvidence** | AI model licensing & customization partner | Leading patient-aware clinical decision support platform, already integrated into Epic EHR at health systems including Mount Sinai and Cedars-Sinai. Licensing an established, clinically-validated model (rather than building proprietary ML) is the core "buy vs. build" argument in Bucket 1 — this is a live example of that exact strategy working at scale in 2026. |
| **Clearwater** | HIPAA compliance & security risk consulting | One of the most established healthcare-specific compliance firms in the country — two decades focused exclusively on HIPAA Security Rule risk analysis, OCR audit readiness, and BAA review. Selected over generalist IT consultancies because healthcare compliance work is their sole specialty, not a practice area inside a broader firm. |
| **Microsoft Azure for Healthcare** | HIPAA-aligned cloud data infrastructure | Offers a signed BAA, healthcare-specific compliance certifications, and native integration tooling for EHR-adjacent data pipelines — reduces the infrastructure build to configuration rather than ground-up architecture. Considered against AWS HealthLake; Azure was selected on the assumption that TechNovation's existing platform already runs on Microsoft infrastructure, which avoids a parallel-cloud integration cost. |

**Vendor selection logic, in one line:** license the clinical AI (OpenEvidence) rather than build it, buy compliance expertise (Clearwater) rather than develop it internally for a first project, and extend the existing cloud relationship (Azure) rather than stand up a second one. Every "buy" decision below is a deliberate trade of a fixed/contractor cost now for a slower, riskier internal build later.

**Framing note:** Enterprise AI/compliance vendor contracts are rarely publicly priced — the dollar figures below are TechNovation's internal estimate, informed by the observed scale of comparable 2026 enterprise health-system AI deals, not published vendor rate cards. Confirm actual figures with each vendor during procurement before treating them as final.

---

## Staffing Rate Assumptions

| Category | Rate | Basis |
|---|---|---|
| Existing staff (fully loaded) | $90/hr | Salary + benefits + overhead |
| Contractors / vendor specialists | $150/hr | Market rate for specialized short-term engagement |
| FTE-month conversion | 173 hrs | 2,076 hrs/year ÷ 12 |

---

## Labor Buildup

**Existing Staff**

| Role | Allocation | Duration | Hours | Cost |
|---|---|---|---|---|
| Technical/AI Lead (Christopher) | 100% | 12 mo | 2,076 | $186,840 |
| Clinical Liaison + PM (Margie) | 100% | 12 mo | 2,076 | $186,840 |
| Finance Lead (Ashley) | 50% | 12 mo | 1,038 | $93,420 |
| Sales/BD + Compliance Lead (Dane) | 75% | 12 mo | 1,557 | $140,130 |
| Integration engineers (3 FTE, build phase) | 100% | 6 mo | 3,114 | $280,260 |
| Integration engineer (tapered, pilot phase) | 100% (1 FTE) | 6 mo | 1,038 | $93,420 |
| Data/compliance engineer | 100% | 6 mo | 1,038 | $93,420 |
| **Staff subtotal** | | | **11,937** | **$1,074,330** |

**Contractors / Vendor Specialists**

| Role | Vendor | Allocation | Duration | Hours | Cost |
|---|---|---|---|---|---|
| AI customization specialists (2 people) | OpenEvidence (licensing partner's implementation team) | 100% | 6 mo | 2,076 | $311,400 |
| Contract integration engineers (surge, 2 FTE) | Independent contractors | 100% | 4 mo | 1,384 | $207,600 |
| HIPAA/compliance consultant | Clearwater | — | 300 | 300 | $45,000 |
| **Contractor subtotal** | | | | **3,760** | **$564,000** |

**Total labor: 15,697 hrs → $1,638,330**

---

## Cost Bucket 1: AI Model Licensing & Customization

| Field | Detail |
|---|---|
| **Amount** | $1,161,400 |
| **Vendor** | OpenEvidence |
| **Labor** | $311,400 — OpenEvidence implementation specialists (2 people × 6 mo) |
| **Non-labor** | $850,000 — licensing/platform fee for enterprise integration |
| **Covers** | Licensing OpenEvidence's clinical decision support model + specialist configuration work to adapt it to TechNovation's data formats and existing product |
| **Why this vendor** | Already deployed at scale in comparable health-system EHR environments (Mount Sinai, Cedars-Sinai) — a live, working example of the exact "license, don't build" strategy this bucket represents |
| **Alternative considered** | Build in-house — rejected: multi-year timeline, much higher cost, higher technical risk; no comparable track record to point to |
| **Panel-ready framing** | "We're not licensing an unproven idea — this is a platform already running in production at major health systems. We're paying for a head start, not reinventing something that already exists." |

---

## Cost Bucket 2: Integration Engineering

| Field | Detail |
|---|---|
| **Amount** | $681,280 |
| **Labor** | $373,680 — existing engineers (3 FTE × 6 mo build + 1 FTE × 6 mo pilot taper) |
| **Labor (contractor)** | $207,600 — 2 contract engineers for surge capacity, 4 months |
| **Non-labor** | $100,000 — Azure integration tooling/environment costs |
| **Covers** | Engineering work connecting OpenEvidence into TechNovation's existing platform — APIs, data pipelines, UI/workflow embedding |
| **Why this approach** | Sized to existing platform architecture — this is an upgrade, not a rebuild |
| **Alternative considered** | Standalone new product — rejected: higher adoption barrier for existing clients |
| **Panel-ready framing** | "The cost of making it invisible to the user — the harder we work here, the less our clients have to change." |

---

## Cost Bucket 3: Data Infrastructure & Compliance

| Field | Detail |
|---|---|
| **Amount** | $498,420 |
| **Vendors** | Microsoft Azure for Healthcare (infrastructure) + Clearwater (compliance) |
| **Labor** | $93,420 — existing data/compliance engineer (1 FTE × 6 mo) |
| **Labor (contractor)** | $45,000 — Clearwater HIPAA/security risk consulting engagement (300 hrs) |
| **Non-labor** | $360,000 — Azure for Healthcare hosting/BAA-covered infrastructure, security tooling, clinical validation study costs |
| **Covers** | HIPAA-aligned data pipeline (ingestion, storage, access controls), clinical validation, compliance/legal review |
| **Why these vendors** | Azure extends TechNovation's existing cloud relationship rather than standing up a second provider; Clearwater is a healthcare-only compliance specialist with two decades of HIPAA Security Rule and OCR audit experience — not a generalist IT consultancy learning healthcare on our dime |
| **Alternative considered** | Defer compliance work to post-pilot — rejected: highest-risk, highest-cost-if-wrong item on this list |
| **Panel-ready framing** | "We're not guessing at compliance — we brought in the firm that does nothing else. We pay for this up front because the alternative is paying far more later." |

---

## Cost Bucket 4: Core Leadership Team (12 months)

| Field | Detail |
|---|---|
| **Amount** | $607,230 |
| **Labor** | Christopher $186,840 + Margie $186,840 + Ashley $93,420 + Dane $140,130 |
| **Covers** | Fully loaded compensation for the four core leadership roles across build and pilot phases |
| **Why this approach** | Narrowed from the original estimate — integration engineers, AI specialists, and compliance staff are now costed separately in their own buckets rather than folded into "team" as one lump sum |
| **Note** | All four roles are existing staff, reassigned/dedicated to this project — no net-new leadership hires |
| **Panel-ready framing** | "This reflects a lean core team, deliberately not overbuilt ahead of revenue." |

---

## Cost Bucket 5: Pilot Support Contingency

| Field | Detail |
|---|---|
| **Amount** | $236,000 |
| **Covers** | Buffer for pilot-phase surprises — added clinician training time, site-specific integration issues, minor scope adjustments from early feedback |
| **Basis for estimate** | ~8% of the $2,948,330 subtotal (buckets 1–4) — standard contingency range for bounded technical risk |
| **Why this approach** | Plan for the unexpected now rather than return for supplemental funding later |
| **Alternative considered** | No contingency line — rejected: removes flexibility, signals overconfidence to the panel |
| **Panel-ready framing** | "Not because we expect problems — so a small problem doesn't turn into a funding request in month nine." |

---

## Total

| Bucket | Vendor(s) | Amount |
|---|---|---|
| AI Model Licensing & Customization | OpenEvidence | $1,161,400 |
| Integration Engineering | Azure (tooling) + internal/contract engineers | $681,280 |
| Data Infrastructure & Compliance | Azure for Healthcare + Clearwater | $498,420 |
| Core Leadership Team (12 months) | Internal | $607,230 |
| Pilot Support Contingency (~8%) | — | $236,000 |
| **Total Funding Request** | | **\~$3,184,330 (\~$3.18M)** |

**Note:** This is a reduction of ~$620K from the original $3.8M placeholder ask, driven by (1) separating integration/compliance/AI-specialist labor out of the "core team" bucket into their own line items, (2) grounding every labor cost in an hourly rate × realistic duration, and (3) anchoring non-labor costs to named, real-market vendors rather than round-number placeholders.

---

## Staffing Plan

| Function | Staffing Source | Rationale |
|---|---|---|
| **Core leadership** (Christopher, Margie, Ashley, Dane) | Existing staff, reassigned/dedicated to this project | Already know TechNovation's platform, clients, and internal processes — fastest, lowest-risk choice for leadership roles |
| **AI model customization** | OpenEvidence implementation specialists (licensing partner's team) | Vendor's own implementation team reduces ramp-up time and avoids a costly in-house learning curve on a technology we're licensing, not building |
| **Integration engineering** | Existing platform engineers (build + tapered pilot support) + 2 independent contract engineers for surge capacity | Existing engineers know the codebase; contractors add short-term capacity without permanent headcount commitment |
| **Data infrastructure & compliance** | Existing IT staff (Azure configuration) + Clearwater (HIPAA risk analysis, BAA review, audit readiness) | Clearwater's sole focus is healthcare compliance — specialized regulatory expertise worth buying rather than building in-house for a first project |
| **Clinical validation (pilot)** | Pilot clients' own clinicians, coordinated by Margie | Reinforces co-design narrative and directly supports the adoption-resistance mitigation |

**Key talking point if pressed:** Every dollar in this budget traces to either a named vendor active in this exact market today (OpenEvidence, Clearwater, Azure for Healthcare) or an hourly rate applied to a specific role and duration — nothing here is a placeholder. This is a hybrid model: existing staff carry roles where institutional knowledge is the advantage, and named specialist vendors are brought in only where outside expertise is genuinely faster or lower-risk to buy than to build in-house.
