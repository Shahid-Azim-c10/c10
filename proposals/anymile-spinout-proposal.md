# AnyMile — Spin-Out Deal Memo

**Format:** Sequoia Capital investment memo structure
**From:** Shahid Azim, C10 Labs
**To:** Zafer Sahinoglu, Mitsubishi Electric US
**For:** Mitsubishi Electric US CEO + Sponsor Executive Satoshi Takeda
**Review date:** June 4, 2026 (Boston)
**Status:** Draft v4 — Sequoia-format rewrite for Zafer's review prior to internal circulation

---

## 1. Company purpose

**AnyMile is the orchestration layer for cargo air mobility — the middleware
that connects drone operators, airframe OEMs, and state airspace authorities into a
single, FAA-auditable network.**

---

## 2. Problem

Cargo air mobility is being funded ahead of the infrastructure that makes it
operable at scale.

- **State DoTs are stuck.** Both Louisiana DoT and Texas DoT have FAA-funded cargo
  delivery programs in flight and have independently told us, this week, that
  orchestration is the missing piece. Without it, every operator integrates
  point-to-point with every other operator, OEM, and airspace authority — and
  nothing produces the consolidated, FAA-visible reporting the grants require.
- **Operators can't scale BVLOS.** The FAA's BVLOS expansion creates demand the
  operators are not architected to serve: each new corridor, vehicle, or counterpart
  is a bespoke integration.
- **OEMs ship vehicles without a network.** Airframe OEMs land cargo platforms into
  customers with no shared orchestration plane, leaving the customer to glue it
  together.
- **No incumbent owns the layer.** Aviation software is dominated by either
  passenger-side ATM systems or vehicle-side OEM stacks. The horizontal
  multi-operator/multi-OEM/multi-jurisdiction orchestration layer is unclaimed.

---

## 3. Solution

A neutral, third-party orchestration platform — operated as an independent
venture-backed company — that:

- Provides a single API and operational console for drone operators, OEMs, and
  airspace authorities to share schedules, telemetry, and compliance data.
- Generates the FAA-grade reporting state DoTs need to defend and renew their
  grants.
- Onboards new operators and corridors as a reusable SOW rather than as a custom
  integration each time.
- Stays neutral by being structurally independent of any single OEM, operator, or
  geography — including its strategic anchor, Mitsubishi Electric US.

---

## 4. Why now

A 12–18 month window is open and will not stay open.

- **Regulatory.** The FAA's BVLOS rule expansion is converting research corridors
  into operational ones.
- **Funding.** Multiple state DoT grant cycles (TX and LA active; others queued)
  are spending against cargo air mobility *right now*.
- **Customer pull is live this week.** Both Louisiana DoT and Texas DoT have
  confirmed orchestration as the blocker. AnyMile has just been admitted to the
  Texas CAAT.
- **No category leader yet.** Whoever becomes the default integration point in the
  next 12–18 months sets the protocol, the reporting format, and the data
  gravity.
- **Spin-out unlock.** Inside ME, AnyMile competes for budget against a global
  P&L. Outside ME, it can contract, deploy, and iterate at venture speed while ME
  retains strategic upside.

---

## 5. Market size

- **Beachhead — state DoT cargo programs.** ~50 US state DoTs, with the leading 8–10
  running FAA-funded programs in the next 24 months. Annual platform spend per
  state DoT, fully deployed, is in the high six to low seven figures.
- **Adjacent — drone cargo operators.** Several hundred BVLOS-authorized US
  operators within 36 months; per-flight orchestration fees compound with usage.
- **Adjacent — airframe OEM integrations.** A double-digit set of cargo airframe
  OEMs globally; each integration is both a revenue line and a distribution
  channel.
- **Long-term — international airspace authorities and passenger AAM.** The same
  orchestration primitive extends to passenger air mobility and to non-US
  jurisdictions as their BVLOS frameworks mature.

The defensible bottom-up TAM is in the low billions annually within 5–7 years;
the strategic prize is owning the protocol.

---

## 6. Competition

- **Vehicle-side OEM stacks.** Built for their own airframes; structurally cannot
  be neutral, which is the buyer requirement at the state and federal level.
- **Passenger-side ATM incumbents.** Optimized for crewed aviation; slow,
  expensive, and not architected for high-frequency low-altitude cargo.
- **Point UTM startups.** Solve a slice (deconfliction, identification) but not
  the multi-operator commercial orchestration layer.
- **Internal ME program (status quo).** Slower decision cycles, harder to sign
  third-party operators who view ME as a competitor in adjacent categories.

**Why AnyMile wins:** neutrality + first regulator/customer relationships + a
build partner (C10 Labs) that can put a venture-grade team and capital structure
around it in 90 days.

---

## 7. Product

- **Orchestration core:** flight planning, deconfliction, telemetry ingest, and
  operator/OEM/authority APIs.
- **Compliance & reporting:** FAA-grade reporting packs generated automatically
  from operational data, sized to what state DoTs must hand to the FAA.
- **Operator console:** day-of-operations UI for dispatchers and airspace
  managers.
- **Integration kit:** reusable SOW + reference architecture that compresses new
  DoT or OEM onboarding from quarters to weeks.

IP is contributed by ME at spin-out close via an assignment-and-license
agreement; ME retains a perpetual royalty-free internal-use license with narrow,
time-boxed field-of-use carve-outs that do not depress seed valuation.

---

## 8. Business model

- **Per-flight orchestration fee** — variable, scales with operator usage.
- **Platform subscription** — annual, tiered by connected operators/vehicles;
  sold to state DoTs and enterprise operators.
- **Integration & professional services** — year-one revenue that funds the
  deployment team without burning seed capital on services headcount.
- **OEM revenue share** — when AnyMile ships as the default orchestration layer
  with a cargo airframe.

Gross margin profile is SaaS-like at steady state; year-one mix is services-heavy
by design, then inverts as the reusable SOW pattern takes hold.

---

## 9. Team & sponsors

**Founding team (formed within 90 days of close, C10 Labs-led search):**

- **CEO** — operator with FAA / DoT or regulated-infrastructure-software
  background. C10 Labs runs the search; ME has approval on the final candidate.
- **CTO / Head of Engineering** — preferred path is to retain the lead AnyMile
  engineer(s) from inside ME via a transition package (cash + meaningful ESOP).
- **Head of GTM / BD** — owns DoT and OEM pipeline; hired from C10 Labs' network
  of regulated-industry GTM operators.
- **Founding engineers (2–3)** — orchestration, integrations, airspace data.

**Strategic sponsors:**

- **Mitsubishi Electric US** — anchor strategic shareholder, IP contributor,
  first reference customer. Satoshi Takeda as ME-side executive sponsor and
  board member.
- **C10 Labs** — Cambridge-based AI-native venture studio; accountable for
  team formation, GTM, and capital formation. Shahid Azim on the board.

**Compensation framework:** below-market cash, top-quartile equity for the first
ten hires, benchmarked against Boston/Cambridge venture-backed seed-stage peers;
ESOP refresh pre-Series A so seed dilution doesn't under-incent the team.

---

## 10. Financials & capital plan

### 10.1 Founding cap table (fully diluted, pre-seed)

| Holder | Stake | Rationale |
|---|---|---|
| Mitsubishi Electric US | 40% | Core IP, brand, first-customer access, sponsor capital |
| Founding team ESOP | 40% | CEO, CTO, first ~10 hires; oversized to absorb seed dilution and remain venture-grade |
| C10 Labs (build partner) | 15% | Commercial scale-up, team formation, GTM, capital formation |
| Advisor / strategic partner pool | 5% | DoT advisors, airframe OEM partners, FAA SMEs |

Seed is intentionally **not** pre-reserved on the founding cap table — new
investors price the round and dilute all existing holders pro rata. ME and C10
Labs participate pro rata to defend ownership.

*Illustrative post-seed ($5M at $25M post → 20% dilution): ME ~32%, Team ~32%,
C10 Labs ~12%, Advisors ~4%, Seed investors 20%.*

All ME and C10 Labs shares vest over 36 months from spin-out close, 12-month
cliff, to align both sponsors with execution rather than transaction.

### 10.2 Capital plan

| Stage | Source | Amount | Use |
|---|---|---|---|
| Spin-out close | ME sponsor commitment | $1.0–1.5M | Founding team, legal, first pilots |
| Seed (month 3–6) | External lead + C10 Labs + ME pro rata | $4–6M | Engineering, GTM, 3–5 pilots |
| Series A (month 12–18) | Tier-1 venture | $15–25M | Scale GTM, OEM integrations, international |

ME sponsor commitment is structured as either (a) a SAFE that converts at the
seed with a 20% discount, or (b) primary equity at the founding valuation. The
seed is priced by an independent external lead, which protects ME from
internal-transfer-pricing scrutiny and gives the company a defensible market
valuation for downstream rounds.

### 10.3 Commercial milestones underwriting the plan

- **First 90 days:** Convert Texas DoT and Louisiana DoT relationships into two
  paid pilots under existing FAA grants; formalize Texas CAAT into a working
  group seat; stand up the reusable pilot SOW.
- **6–12 months:** 3–5 signed DoT or DoT-adjacent pilots, ≥1 multi-year
  enterprise contract; 2 airframe OEM integration partnerships; ARR run-rate
  sufficient to start the Series A conversation in month 12–15.

### 10.4 Governance

- **Board (5 seats at close):** 2 ME (incl. Satoshi Takeda), 1 C10 Labs (Shahid
  Azim), 1 CEO, 1 independent (jointly nominated).
- **ME protective provisions:** consent on (a) change of control, (b)
  transactions with a direct ME competitor, (c) material changes to the IP
  license, (d) issuance of senior preferred above an agreed cap.
- **Information rights:** monthly reporting + quarterly strategic review to ME
  and C10 Labs.
- **Anti-dilution:** ME and C10 Labs participate pro rata in seed and Series A;
  ME's strategic stake is otherwise non-anti-diluted to keep the structure
  investor-friendly.

---

## 11. Risks

| Risk | Mitigation |
|---|---|
| ME internal stakeholders block IP carve-out | Narrow, time-boxed field-of-use carve-outs; Satoshi Takeda pre-clears the path |
| CEO recruiting slips past 90 days | C10 Labs runs an interim operating GM from day one so customer momentum doesn't stall |
| DoT pilots slip past FAA reporting windows | Reusable pilot SOW + dedicated deployment lead; phased deliverables so partial results still report well |
| Seed market softens | ME sponsor commitment + C10 Labs syndicate provides a 12-month bridge regardless of external market |
| "Corporate spin-out = slow" perception | Independent board majority and external-led seed signal venture-grade governance from day one |

---

## 12. Vision & the ask

**Vision.** In five years, AnyMile is the default orchestration layer for cargo
air mobility in the United States and the reference protocol that international
airspace authorities adopt as their BVLOS regimes mature. ME holds a strategic
position in the category-defining platform without carrying it as a P&L line
item; C10 Labs has its flagship regulated-infrastructure spin-out; the operating
team has built a venture-grade independent company.

**The ask for the June 4 review:**

1. **Approve the spin-out in principle** on the structure above (ME 40 / Team 40
   / C10 Labs 15 / Advisors 5 founding cap table, ME sponsor capital, C10 Labs
   as build partner).
2. **Authorize term sheet negotiation** between ME and C10 Labs, with a target
   signed term sheet by end of July.
3. **Confirm Satoshi Takeda** as the ME-side board sponsor and executive
   air-cover for the spin-out.
4. **Green-light the Texas DoT and Louisiana DoT pilot conversations** to
   proceed under a "spin-out pending" posture so we don't lose the FAA reporting
   window.

---

*Prepared by Shahid Azim, C10 Labs. Draft v4 (Sequoia deal-memo format),
2026-05-16. Companion to Zafer Sahinoglu's internal ME spin-out memo.*
