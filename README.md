# post-extraction-site-use

A Claude skill for determining the highest-value successor use for a depleted extraction site — quarry, mine, gravel pit, landfill, or industrial void.

---

## The problem it solves

Research on post-extraction land use follows a predictable failure pattern: generate a scenario, source it well, build a compelling case — and only discover in the final round of research that the mechanism you proposed already exists in statute, or that the operator is a sophisticated commercial party who already has every incentive to solve this, or that the void's current use depends on it remaining a void.

The failure isn't analytical. The reasoning on the available material is usually sound. The failure is *sequencing* — verification runs last, after the analyst is invested in the answer. Pass 03 arrives as a surprise rather than a confirmation.

This skill reorganizes the work so that doesn't happen.

---

## How it works

Research organizes into three passes, each narrowing the question so the next can be asked more sharply:

| Pass | Question | Output |
|---|---|---|
| **01 — Solution Space** | What could this site become? | A ranked candidate set; one carried forward |
| **02 — Scenario Definition** | If that use, then who, how much, when? | A coherent, sourced scenario |
| **03 — Governing Language & Feasibility** | Does the mechanism already exist? | A proposal, or a narrowed real finding |

**All four verification gates run at the start of Pass 01** — not as a final review step. This is the single most important structural rule in the skill:

- **Gate 1 — Source Hierarchy:** operator's own documentation and the filed regulatory document are required rows, searched explicitly before any analysis begins
- **Gate 2 — Assumption Register:** every claim tagged SOURCED / DERIVED / ASSUMED before any prose is written, including a check for assumptions that would strengthen the argument if true
- **Gate 3 — Negative Claim Protocol:** any "no X exists" assertion requires the search that established it, or downgrades to "I have not found evidence of X"
- **Gate 4 — Red Team:** "What would have to be true for this entire analysis to be worthless?" — asked while the analysis is going well

If Pass 03 surprises you, the gates were skipped.

---

## Installation

Requires [Claude Code](https://docs.claude.ai/en/docs/claude-code/getting-started) or Claude Desktop with Projects.

```bash
# Clone into your Claude skills directory
git clone https://github.com/matteoc19/post-extraction-site-use

# Or add to an existing Claude project
cp -r post-extraction-site-use /path/to/your/project/skills/
```

Claude will load the skill automatically when `SKILL.md` is present in the project context. Reference it explicitly with:

> *Use the post-extraction-site-use skill to analyze [site name].*

---

## What's in this repo

```
SKILL.md                        The skill — three passes, four gates, eleven steps
reference/
  permanente-case.md            Worked example: Permanente Quarry, Santa Clara County, CA
  spoil-matching.md             Sub-procedure for the fill/reclamation branch (invoke only
                                if fill survives Pass 01 gates and is carried forward)
```

**`SKILL.md`** is the primary file. It contains the full three-pass framework with all gates, steps, the locked-sequence enforcement, and the terminal null-finding branch.

**`reference/permanente-case.md`** traces the framework against a real site — including what each gate would have caught if it had been run first, and the Pass 03 finding that dissolved the coordination proposal into something narrower and more useful.

**`reference/spoil-matching.md`** is a sub-procedure invoked only when the fill/reclamation branch survives all Pass 01 gates. It covers volume derivation (with shown arithmetic), staged supply-vs-demand reconciliation, and the institutional matching step.

---

## Where it came from

This skill was extracted from independent research on the Permanente Quarry in Santa Clara County — a 198-acre, 1,200-foot-deep limestone quarry that closed in 2023 and faces a 42-million-cubic-yard backfill obligation over forty years.

The research ran three passes. The third pass dissolved the coordination proposal it had built in the second by finding a statutory pathway that already existed, an operator who already had the information assumed to be missing, and a permitting-timeline risk that turned out to be the real finding. The skill packages the questions Pass 03 asked so they run first, not last.

Full research artifact: [permanente-quarry-proposal.vercel.app](https://permanente-quarry-proposal.vercel.app/)

---

## Tested against

| Site | Outcome | Key finding |
|---|---|---|
| Permanente Quarry, CA *(from zero)* | Narrowed finding | Coordination mechanism already codified in IDEFO (14 CCR 17388.3); real constraint is permitting-timeline risk |
| Thornton Quarry, IL | Null finding | Void is a 7.9-billion-gallon Deep Tunnel stormwater reservoir; filling it destroys flood infrastructure |
| Brazil, IN clay pits | Null finding | Clay impermeability makes the void the asset; fill market already exists by statute (CCDD) |

Two nulls and one narrowed finding out of three adversarial tests. A framework that never green-lights anything is as useless as one that always does — if a candidate genuinely has no occupied pathway and a live decision exists, the skill is designed to say so and proceed.

---

## License

MIT — use, adapt, and redistribute freely.

---

*Built with Claude (Anthropic). Judgment, site selection, and editorial direction by Matteo Calafiura-Soleri.*
