---
name: post-extraction-site-use
description: Determine the highest-value successor use for a depleted or closing extraction site — quarry, mine, gravel pit, landfill, or industrial void. Use whenever a user asks what should happen to a former or closing quarry/mine/pit, evaluates reclamation options, researches brownfield or post-industrial land reuse, wants to know if a site could host a specific use (fill, water storage, energy, open space, development), or is building a case to influence a site's reclamation or redevelopment outcome. Also use when a user has already assumed a successor use and wants it validated or stress-tested. Trigger on "what should happen to this quarry", "reclamation options", "post-mining land use", "can this pit be used for X", "quarry redevelopment", "mine closure planning", "brownfield reuse", or any request to analyze what a large industrial void should become.
---

# Post-Extraction Site Use

Research on a post-extraction site organizes into **three passes**, each narrowing the question so the next can be asked more sharply:

| | Pass | Question | Output |
|---|---|---|---|
| **01** | **Solution Space** | What could this site become? | A ranked candidate set; one carried forward |
| **02** | **Scenario Definition** | If that use, then who, how much, when? | A coherent, sourced scenario |
| **03** | **Governing Language & Feasibility** | Does the mechanism already exist? | A proposal, or a narrowed real finding |

The passes run in order. **All four verification gates run at the start of Pass 01** — not later, and not as a review step. This is the single most important structural rule in this skill, and the one most commonly violated.

**Why the gates belong in Pass 01:** the natural instinct is to build the scenario first and verify it once it looks good. That sequence reliably produces a well-sourced, internally coherent, entirely unnecessary proposal — because verification only arrives after the analyst is invested in the answer. Front-loading the gates means Pass 03 becomes *confirmation* rather than *surprise*. **If Pass 03 surprises you, the gates were skipped.**

---

# PASS 01 — Solution Space

**Purpose:** What could this site become? Generate candidate successor uses broadly, then evaluate each against physical, regulatory, institutional, and market conditions.

Pass 01 opens with the four gates. They are not preamble; they are the pass.

---

## GATE 1 — Source Hierarchy

Fill this table before any analysis. Do not proceed on news coverage or advocacy material when primary sources exist.

| Source class | Found? | Reference |
|---|---|---|
| Operator's own project site / public documentation | | |
| The actual filed regulatory document (reclamation plan, EIR, permit application) | | |
| Governing agency's public file (planning dept, state mining/EPA agency) | | |
| Independent physical measurement (satellite imagery, published survey) | | |
| Existing statutory/permit framework governing this use class in this jurisdiction | | |

Search explicitly for each. The operator's own site is the most commonly missed and often the richest — the party with the strongest incentive to publish is frequently the last one searched. Query patterns: `[site name] .com`, `[site name] reclamation plan`, `[operator] [site] project`.

**Any row marked "not found" must appear in the final output.** Every figure downstream of a missing row inherits reduced confidence. A missing primary source is a stated limitation, not an invisible gap.

---

## GATE 2 — Assumption Register

Build this table **before writing any prose**. Every quantitative or factual claim that will appear in output gets a row. No exceptions, including claims that feel obvious.

| Claim | Value | Status | Basis |
|---|---|---|---|
| *(example)* Pit footprint | 198 ac | SOURCED | Operator RPA §4.2 |
| *(example)* Tunnel spoil volume | 2.5M yd³ | DERIVED | π·24²·26,400÷27 × 1.25 swell |
| *(example)* Grade separation volume | ~200k yd³ ea | **ASSUMED** | typological range, unverified |

Exactly three statuses:

- **SOURCED** — traceable to a specific primary document, with section/table cited.
- **DERIVED** — calculated from sourced inputs, with the arithmetic shown in full.
- **ASSUMED** — everything else. Typological estimates, pattern-matched ranges, plausible interpolations.

**Rules:**
- Nothing untagged enters an artifact, diagram, or brief.
- An ASSUMED value must be visually distinguishable in any output (different line weight, "+" suffix, explicit hedge in prose). A reader must never mistake an assumption for a measurement.
- If a figure is needed and no source exists, mark it ASSUMED and *say so in the output* — do not produce a confident-sounding number to fill the hole. Interpolated numbers do not announce themselves; they get styled, cross-referenced, and built upon until they contaminate everything downstream.
- Re-check the register at the end of every pass. Any ASSUMED value still load-bearing is a debt to disclose.

**The convenient-assumption trap:**

After building the register, go back and mark every ASSUMED row that — *if true* — would **strengthen your argument**. Those are the dangerous ones.

Assumptions that cut against your thesis get scrutinized automatically; you go looking for reasons they're wrong. Assumptions that support it do not. They are tidy, evidence-shaped, narratively convenient, and they slide into the analysis unchallenged precisely because they make it better.

Any ASSUMED row flagged this way must either be **verified before use** or **explicitly excluded from the argument**. It may not be used as supporting evidence while still tagged ASSUMED.

---

## GATE 3 — Negative Claim Protocol

Any assertion of *absence* requires a documented search that established it.

Claims subject to this gate: "no mechanism exists," "nobody has proposed this," "there is no market for X," "the destination is unresolved," "no agency has authority over this," "this hasn't been done before."

For each, record the search that would have found the thing if it existed. If no such search was run, **downgrade the claim** from `"No X exists"` to `"I have not found evidence of X"`. These are different statements and only one of them is defensible.

Searching for absence is unnatural — it requires deliberately looking for the thing you already believe isn't there. Every other failure mode gets caught by normal research momentum. This one does not. It must be forced.

---

## GATE 4 — Red Team

Before generating candidates, answer in writing:

> **"What would have to be true for this entire analysis to be worthless?"**

Then go check whether it is true.

Typical worthless-making conditions:
- A functioning market or statutory pathway already routes this outcome (see Gate 3 — check, don't assume)
- The void's current or planned use is more valuable than any use being proposed
- The site owner has already decided, and the decision is not contestable
- The material/volume/timeline premise is off by an order of magnitude
- The proposed "gap" is already someone's job
- The operator is a sophisticated commercial party who already has every incentive and capability to solve this

Ask this gate **while the analysis is going well.** That is precisely when it feels like sabotage and precisely when it is most necessary.

---

## ⛔ Locked sequence — Steps 1 → 5

**These steps run in this order. The order is the method, not a formatting choice.**

- **Do not evaluate any candidate use before completing Step 3.**
- **Do not commit to any candidate before completing Step 5.**

**Why this is locked:** the dominant failure mode is *anchoring on the use you arrived expecting* — usually the one from the last site you studied, or the one implied by how the question was asked. You will evaluate that branch first, find supporting evidence (there is always some), and only discover the disqualifying fact late, as a rescue, if at all.

This is not hypothetical. In testing, running a fill-branch evaluation before Step 3 produced a fill-oriented analysis that only surfaced the disqualifying insight — *that the material being extracted was itself what made the void valuable* — at the very end, as a save. Re-run with Step 3 first, the same information killed the fill branch immediately and correctly. **Same facts, same analyst, different order, different answer.**

If you notice yourself building the case for a use before Step 3 is complete, stop and restart the sequence.

---

### Step 1 — What does the site physically permit?

Void geometry, depth, elevation range, water table, hydrology, geology, contamination profile, access, adjacency. Establish from primary sources (Gate 1); verify independently where possible.

Where independent measurement diverges from the official figure, **show the reconciliation** — a stated and explained discrepancy is more credible than a suspiciously clean match. If it cannot be reconciled with available data, say so.

### Step 2 — What is legally mandated or foreclosed?

Reclamation obligations, easements, zoning, contamination liability, water rights, existing permits and commitments.

This determines whether the void *must* be filled, *may* be filled, or *must not* be filled. A site under a mandated backfill obligation and a site serving as regional flood infrastructure look identical from above and have opposite correct answers.

### Step 3 — What is the void currently *for*?

Separate from Step 2. Ask directly: **does the void have a current or planned function that depends on it remaining a void?**

Flood/stormwater storage. Water supply reservoir. Groundwater recharge basin. Habitat. Scientific or geological value. Deep-tunnel system integration.

If yes, filling it destroys that function, and any fill-based proposal is not merely suboptimal but destructive. Cheap to ask, catastrophic to skip.

### Step 4 — Generate candidate successor uses broadly

Do not pre-commit. Generate across categories before evaluating any:

- Open space / recreation / trail connectivity
- Water: storage, groundwater recharge, flood control, supply
- Energy: pumped hydro, solar, geothermal, storage
- Fill / reclamation to grade (→ if this survives, see `reference/spoil-matching.md`)
- Research / education / scientific stewardship
- Development: residential, commercial, industrial
- Habitat restoration / conservation / mitigation banking
- Waste management: landfill, inert debris facility
- Continued extraction of a different resource

### Step 5 — For each candidate: does a pathway already exist?

**This is the check that Pass 03 will otherwise deliver as a surprise. Run it here, broadly, across every candidate.**

For each, search for: existing statutes, permit classes, agency programs, established markets, active brokers, trade associations, comparable permitted facilities in the same jurisdiction.

Pathways that already exist and are easy to miss:
- **Fill / inert debris:** most jurisdictions have a dedicated permit class with an established tipping-fee market (California's Inert Debris Engineered Fill Operation, 14 CCR 17388.3; Illinois's Clean Construction & Demolition Debris fill operations, 35 Ill. Adm. Code 1100). **Do not claim to be proposing a novel fill mechanism without searching the jurisdiction's fill-permit statute.**
- **Water storage:** the regional water or flood district may already have the site in a capital plan.
- **Conservation:** land trusts and mitigation banking have established acquisition pathways.

If a pathway exists, the question changes from *"propose a mechanism"* to *"why hasn't the existing mechanism been used here, and what would route this site into it?"* — a smaller, more honest, usually more actionable claim.

**Do not stop at the first workable mechanism found.** Ask whether a more canonical vehicle exists for this exact purpose in this exact jurisdiction.

---

## ✅ TERMINAL BRANCH — Null Finding Report

**If every viable candidate already has an occupied, functioning pathway, the research is complete at Pass 01. Stop here.**

This is a **successful and complete outcome**, not an aborted attempt. It is frequently the correct one. Most extraction sites do not have an unaddressed problem — they have an answer that arrived by physics, by statute, or by an institution quietly doing its job.

The framework is funnel-shaped and will exert pressure toward producing a proposal. Resist it. A well-cited proposal for a problem that is already solved is worse than no proposal: it wastes the reader's credibility budget, and if acted on may displace a working arrangement with a worse one.

**A Null Finding Report contains:**
1. The site and the question asked
2. The candidate uses generated (Step 4)
3. For each, the existing pathway that already occupies it — named, cited
4. **What would have to change for a proposal to become warranted** (a new owner, a lapsed permit, a funding window, a competing claim on the void)
5. The Gate 4 red-team answer that confirmed the null

Then stop. Do not proceed to Pass 02.

---

## Pass 01 Output

- The Gate 1 source table, including anything not found
- The Gate 2 assumption register, ASSUMED values flagged, convenient-assumption rows identified
- The Gate 4 red-team answer
- A **ranked candidate set**, each with: physical basis, existing pathway (if any), champion, blocker, and timeline
- **The distinction between *desirable* and *actionable*.** These are usually different. The most desirable end state may be a decades-long horizon with no funding and no committed actor; a less transformative option may be actionable now because it plugs into a process already underway. Rank on both axes, then ask: *does pursuing the actionable option foreclose the desirable one?* If not, the actionable option is usually the right one to carry forward — and saying so plainly, rather than pretending it is also the best possible end state, is both more honest and more persuasive.
- **One candidate carried into Pass 02**, with the reason stated.

---

# PASS 02 — Scenario Definition

**Purpose:** If that use, then who supplies or executes it, in what volume, and on what timeline? Take the surviving candidate to real parties, real numbers, real schedules.

Pass 02 does not re-litigate the candidate choice. It builds it out.

### Step 6 — Extract the governing figures from primary sources

From the site's own filed document, not coverage of it. Cite section and table. Tag every figure per Gate 2.

Distinguish carefully between numbers that look similar and are not: total obligation vs. the portion already satisfied on-site vs. the portion requiring outside input. These are routinely conflated, and the difference is usually the entire substance of the analysis.

Capture the *reason* behind any design constraint (a target elevation, a required surface, a phasing rule). The reason is frequently hydrological or structural, and stating it materially strengthens credibility.

### Step 7 — Derive what is not published; show the work

Most counterparties don't publish the figures you need. Derive them from public dimensions using basic geometry, and **show the arithmetic explicitly** rather than presenting a bare number.

State every conversion factor and its typical range. A **DERIVED** number and an **ASSUMED** typological guess must never look alike in an output.

### Step 8 — Identify the parties and the timeline

Who supplies, who receives, who permits, who blocks. Get real schedules — do not assume a project is underway because it has been announced. Verify construction start dates, contract letting dates, and approval timelines.

Place the site's demand phases and the counterparties' supply windows on the same timeline. Show where they overlap and where they gap. **State gaps honestly** — an identified supply that covers only a fraction of the need is often the most important finding.

## Pass 02 Output

A coherent, sourced scenario: the parties, the volumes, the timeline, the mechanism, and the visual artifacts (site section, regional plan) that make it legible.

**Coherent is not the same as necessary.** Pass 02 produces something that *works*. Pass 03 asks whether it is *needed*. Do not skip to advocacy here — the scenario is a hypothesis, not a conclusion.

---

# PASS 03 — Governing Language & Feasibility

**Purpose:** Does the mechanism already exist? Test the Pass 02 scenario against statute, permit classes, market practice, and the counterparties' actual commercial positions.

This is a *verification* pass. If Gate 3, Gate 4, and Step 5 were run properly in Pass 01, Pass 03 confirms what you already suspected. **If Pass 03 surprises you, the Pass 01 gates were skipped.**

### Step 9 — Test the mechanism against governing language

Read the actual statute or permit class governing this use in this jurisdiction. Not a summary of it. Determine whether the mechanism your scenario proposes is:
- already codified (it usually is)
- codified but unused at this site (the interesting case)
- genuinely absent (rare — and requires Gate 3 discipline to claim)

### Step 10 — Test the counterparties' actual position

The most common error is assuming a sophisticated commercial party lacks information or capability that they obviously possess.

Ask: *is this party already positioned to solve this?* A materials company that sells to the projects generating the material it needs is not a party lacking visibility. An operator whose own filing contains a commissioned regional supply study is not a party unaware of regional supply.

If the counterparty has the incentive, the capability, and the information, then the gap you believe you found is probably not a gap.

### Step 11 — Identify what actually survives

When the coordination premise dissolves, something narrower usually remains — and it is frequently *more* actionable because it is *more* specific.

Look for:
- **Timing risk** — an approval, permit, or contract with a hard external deadline, where slipping past it forecloses an option irreversibly
- **Sequencing risk** — a decision being made in the wrong order
- **A misidentified lever** — the right problem, the wrong institution

State what survives plainly, and state that it is not what Pass 02 proposed. A scenario that survives Pass 03 is a proposal. **One that dissolves has told you something equally useful: the system already works — and here, precisely, is where it doesn't.**

## Pass 03 Output

Either:

**A — Proposal.** The mechanism is genuinely absent or unused, a champion exists, and a live decision can be influenced. State it, with the Pass 01 gate outputs attached.

**B — Narrowed finding.** The coordination premise dissolves; a sharper, smaller, real constraint survives. This is not a failed run. It is frequently the more valuable output, and it is the more honest one.

In both cases, close with **what the analysis added versus what the source material already established.** Governing documents often already argue for the thing you think you discovered. The contribution is usually a cross-institutional translation, a routing, or a timing observation — rarely a novel fact.

---

# A note on base rates

In testing, this framework returned **two null findings out of two adversarial test sites**, and both were correct. That is a feature — but be alert to the opposite failure.

A framework that never green-lights anything is as useless as one that green-lights everything. If a candidate genuinely has no occupied pathway, an identifiable champion, and a live decision, say so plainly and proceed. **Do not manufacture a disqualification to appear rigorous.**

---

# Reference

- `reference/spoil-matching.md` — sub-procedure for the fill/reclamation branch: matching a site's fill demand to regional excavation supply. **Invoke only if fill survives Gate 3, Gate 4, and Step 5.**
- `reference/permanente-case.md` — worked example across all three passes: the candidates that lost, the scenario that cohered, and the governing-language research that dissolved it into something sharper.
