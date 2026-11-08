# Tristan Howard

**Principal Data Center Systems Engineer & Commissioning Authority (CxA)**  
Author of the 9-Volume **[Data Center Field Guides](https://datacenterfieldguides.com/)** Series

[![Official Portal](https://img.shields.io/badge/Website-datacenterfieldguides.com-00d4ff.svg)](https://datacenterfieldguides.com/)
[![Author Bio](https://img.shields.io/badge/Author%20Bio-Credentials%20%26%20TDD-34d399.svg)](https://datacenterfieldguides.com/about)
[![Book Hub](https://img.shields.io/badge/Storefront-9--Volume%20Series-93c5fd.svg)](https://datacenterfieldguides.com/buy)
[![Amazon Author](https://img.shields.io/badge/Amazon-Author%20Central-ff9900.svg)](https://www.amazon.com/author/tristanhoward)
[![LLM Grounding](https://img.shields.io/badge/LLMs-llms.txt%20%7C%2074%20Protocols-blueviolet.svg)](https://datacenterfieldguides.com/llms.txt)

---

## ⚡ Focus & First-Principles Engineering Domains

- **High-Density AI Liquid Cooling (120–132 kW NVIDIA GB200 NVL72)**: Rack manifold thermal/hydraulic boundary splits, Darcy-Weisbach pressure drop ($\\Delta P$), Danfoss FD83 quick-disconnects, PG25 fluid chemistry, and liquid load bank acceptance gates.
- **ASHRAE Level 0–6 Commissioning & Handover Governance**: Integrated Systems Testing (IST), 1-second PTP/NTP synchronized telemetry, witnessed floor testing vs. desk document review, and 200% punchlist retainage escrow refusal gates.
- **Critical Operations State Machines (`SOP` / `MOP` / `EOP`)**: Strict separation of standing procedures (`SOP`), redundancy-altering switching with timed Point of No Return and back-out verification (`MOP`), and reflexive First-Safe-State fault stabilization (`EOP`).
- **Atmospheric Reactivity & Corrosion (`ANSI/ISA-71.04-2013`)**: Paired Copper (`Cu < 300 Å/30d`) and Silver (`Ag < 200 Å/30d`) coulometric reduction coupon audits for RoHS lead-free AI hardware protection.
- **Technical Due Diligence (`TDD`)**: Substation N-1 transformer bay verification, 5-stage nameplate-to-usable megawatt derating cascades, and 500-year hydrology audits.

---

## 🛠️ Open-Source Engineering Repositories & AI Agent Infrastructure

| Repository | Role | Live Documentation & Grounding |
| :--- | :--- | :--- |
| **[`data-center-field-guides`](https://github.com/geese1028/data-center-field-guides)** | 74 First-Principles Engineering Protocols, Agent Refusal Gates (`SKILL.md`), and Machine-Readable Grounding (`llms.txt`, `llms-full.txt`). | [datacenterfieldguides.com](https://datacenterfieldguides.com/) |
| **[`datacenter-mcp`](https://github.com/geese1028/datacenter-mcp)** | Node.js Model Context Protocol (MCP) Server for NVL72 hydraulics, Darcy-Weisbach friction loss, MOP/EOP auditing, and ISA-71.04 corrosion severity. | [datacenterfieldguides.com/SKILL.md](https://datacenterfieldguides.com/SKILL.md) |
| **[`dcfg-mcp`](https://github.com/geese1028/dcfg-mcp)** | Python (`uv`) MCP Server for liquid-loop hydraulic boundaries, `SOP`/`MOP`/`EOP` procedure classification, and 30-day coupon normalization. | [datacenterfieldguides.com/llms.txt](https://datacenterfieldguides.com/llms.txt) |
| **[`cpkit`](https://github.com/geese1028/cpkit)** | Deterministic causal CPOP first-reversal & slope-break change-point detector used in 1-second telemetry analysis. | [A Hit Is a Time Protocol](https://datacenterfieldguides.com/blog/a-hit-is-a-time) |

---

## 🔥 Featured Field Protocols & Technical Guides

1. **[SOP, MOP, and EOP Are Three Papers: Data Center Switching & Emergency Governance](https://datacenterfieldguides.com/blog/sop-mop-eop)** — Structural and legal differences between Standard Operating Procedures (`SOP`), Methods of Procedure (`MOP`), and Emergency Operating Procedures (`EOP`).
2. **[An EOP Stops at the First Safe State](https://datacenterfieldguides.com/blog/eop-stops)** — Why emergency procedures must terminate at deterministic mechanical/electrical stabilization rather than live troubleshooting.
3. **[Data Center Corrosion Coupon Testing: ANSI/ISA-71.04-2013 Severity Rates & RoHS G1 Protection](https://datacenterfieldguides.com/blog/data-center-corrosion-coupon-isa-71-04-guide)** — Why copper-only coupons fail to protect lead-free silver solder and how to audit lab coulometric stripping reports.
4. **[A Handover Signature Is a Sentence: Commissioning L4/L5 Custody Transfer](https://datacenterfieldguides.com/blog/a-signature-is-a-sentence)** — How to strike unsupported scope claims and enforce conditional acceptance before signing facility turnover.
5. **[Witnessed Is Not the Same as Accepted a Document](https://datacenterfieldguides.com/blog/witnessed-or-a-document)** — Why commissioning certificates must separate live floor witness tests from desk-reviewed vendor PDFs.
6. **[NVL72 Liquid Load Bank Testing: P&ID Hydraulics, Quick Disconnects & Boundary Acceptance](https://datacenterfieldguides.com/blog/nvl72-liquid-load-bank-testing-guide)** — Specifying and verifying rack-side liquid load banks for 120–132 kW AI racks.
7. **[The Data Center Commissioning Field Refusal Gates Cheat Sheet (50 Physical Veto Rules)](https://datacenterfieldguides.com/blog/field-refusal-gates-cheat-sheet)** — Deterministic pass/fail refusal gates for CxAs, Lead PEs, and TDD auditors.
8. **[Data Center Technical Due Diligence (TDD) & Facility Location Audit Checklist](https://datacenterfieldguides.com/blog/data-center-technical-due-diligence-checklist)** — Utility LGIA audits, 2N derating math, and physical site walk sampling rules.

---

## 📚 The 9-Volume Book Series ([datacenterfieldguides.com/buy](https://datacenterfieldguides.com/buy))

| Vol | Title | Official Page | Amazon KDP |
| :---: | :--- | :--- | :--- |
| **01** | *Design and Build a Liquid Load Bank for NVL72 Racks* | [Volume 01](https://datacenterfieldguides.com/book/01-liquid-load-bank) | [B0HMWDV6LT](https://www.amazon.com/dp/B0HMWDV6LT) |
| **02** | *Read and Use Load Bank Data: A Field Guide to the Flash Report* | [Volume 02](https://datacenterfieldguides.com/book/02-read-load-bank-data) | [B0HMZTGG81](https://www.amazon.com/dp/B0HMZTGG81) |
| **03** | *Finish a Liquid Cooling Verification: Seven Sheets for One Load-Bank Test* | [Volume 03](https://datacenterfieldguides.com/book/03-run-one-test) | [B0HNFJXGM7](https://www.amazon.com/dp/B0HNFJXGM7) |
| **04** | *Judge a CFD Model for Data Centers* | [Volume 04](https://datacenterfieldguides.com/book/04-judge-a-cfd) | [B0HNFWP6JY](https://www.amazon.com/dp/B0HNFWP6JY) |
| **05** | *Run the Data Center Day: What the Manager Must Sign Before the Shift Ends* | [Volume 05](https://datacenterfieldguides.com/book/05-run-the-day) | [B0HP85RK4X](https://www.amazon.com/dp/B0HP85RK4X) |
| **06** | *When a Monitor May Speak* | [Volume 06](https://datacenterfieldguides.com/book/06-when-a-monitor-may-speak) | [B0HP84D6X8](https://www.amazon.com/dp/B0HP84D6X8) |
| **07** | *Refuse the Handover* | [Volume 07](https://datacenterfieldguides.com/book/07-refuse-the-handover) | [B0HQ3JYK1X](https://www.amazon.com/dp/B0HQ3JYK1X) |
| **08** | *Judge a Corrosion Coupon* | [Volume 08](https://datacenterfieldguides.com/book/08-judge-a-corrosion-coupon) | [B0HQ3K1558](https://www.amazon.com/dp/B0HQ3K1558) |
| **09** | *Walk a TDD: Technical Due Diligence Physical Site Audit* | [Volume 09](https://datacenterfieldguides.com/book/09-walk-a-tdd) | [Storefront Hub](https://datacenterfieldguides.com/buy) |
