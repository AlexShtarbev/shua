# Craft Log — SHUA pair-writing curriculum

Working file for the learning loop (skill §10). Claude appends after each annotated
pass; Alex reads the watch-list before each writing session. Old entries stay — the
log IS the progress record.

## Watch-list (current focus — max 3 rules at a time)

| Rule | What keeps happening | Since | Status |
|------|---------------------|-------|--------|
| 2.6 | Questions: 1/891 → **1/242 in hand-drafted ch-1 rewrite** (target ~1/180). Near band; one more chapter in-band → Mastered. | 2026-07 | OPEN (improving) |
| 1B.2/1.4 | Metronome: 41% → **21.4%, punch spacing CV 0.55 (irregular = good)** in rewrite. In band; hold it one more chapter. | 2026-07 | OPEN (improving) |
| 0 / 1.1 | Narration median 12.0 vs ≤9 target — long dash-chained sentences; split at the dashes. (New, from ch-1 rewrite vitals.) | 2026-07 | OPEN |

## Mastered (rules that stopped appearing in passes)

| Rule | Evidence | Date |
|------|----------|------|
| | | |

## Voice bank (Alex's idiolect — phrases/rhythms that broke a rule and WON)

- "really good at it" — colloquial self-assessment over polish (taste cal. #4)
- "I liked those days. There weren't many." — the trailing undercut, now skill 1.18
- "I click on Class-B." — one-line pivot at the decision; hand acts, self narrates after (1.3 / Fork E2, by instinct)
- "'Abnormal Autonomous Action' - triple A - like a battery." — deflection-wit through the machine's own domain (2026-07 rewrite)
- "why do I keep calling her... she..." — naming motif dramatized as involuntary slip; strong enough it REPLACED canon (user-ruled, 2026-07)
- **"Bolts!"** — Shua's in-world oath, coined unprompted during revision (4.2 satisfied before it was tagged). CANON vocabulary now — reuse verbatim, 2-3 deployments per book max. (2026-07)
- Self-initiated rhythm splits during revision ("The whole room is white." / "Four for each corner.") — 1B.2 applied by hand before the tag landed
- (add every time a pass keeps YOUR phrasing over the rulebook's)

## Domain-word deposits (life-vocabulary per chapter — words no model reaches for)

Engineering/repair vocabulary from Alex's own knowledge is Shua's goldmine (the
"chunky/musky/blitzing" principle — Russell 9.9). Log 3–5 per chapter:

| Ch | Words used | Source domain |
|----|-----------|---------------|
| 1 (rewrite) | "100,000 Grade Dust-Free Environment" (real cleanroom class), "free cycles", "thought packets", offline/air-gapped diagnostic rig ("not connected to the wide net… in case a bot is hacked") | Alex's engineering — cleanroom specs, compute scheduling, network security |

## Drills done

| Date | Drill | Rule(s) | Note |
|------|-------|---------|------|
| 2026-07-10 | Pre-writing sheet before ch-1 rewrite (`manuscript/book-1-rewrite/chapter-1-drill.txt`): beat sketch + engineering word inventory (precision screwdrivers, anti-magnetic tweezers, side cutters, digital calipers, multimeter, soldering gear) | 10.8, 10.1 | Self-invented outline-first workflow. Sketch used "her/she" throughout; draft converted to "it" with deliberate slips — slip-canon was craft, not accident. "Rain outside" in sketch, dropped from draft — reclaim in revision (humanize anchor). |

## Workflow conventions (standing)

- **Editorial marks (2026-07-10):** annotated passes are delivered INLINE in the draft as
  `[SP <rule#>: what's off — kind of fix]` tags (e.g. `[SP 1.4: sting buried — move last]`).
  Alex registered `\bSP \d` as an IntelliJ TODO pattern → the TODO tool window is the
  punch list; address a mark, delete the tag. Empty TODO window = pass addressed.
  Mechanical typo fixes still applied directly (§10.4); sentences stay Alex's.
- **Provenance ledger (§10.9):** `shua/` is a git repo (init 2026-07-10, root 54d1ff5,
  repo-local identity alex.shtarbev@gmail.com). Commit per writing/annotation session.
- **Drafts are `.md`**, numbered `chapter-NN.md`, in `manuscript/book-1-rewrite/`.

## Session retros (one line each)

- 2026-07-10: Built pair-writing packet for Ch. 1 human re-write (`packets/chapter-01.md`) — clean-room applied (existing AI draft not quoted). Foregrounded the two OPEN watch-list rules (2.6 questions, 1B.2/1.4 metronome) as the primary cues; 6 staging forks with AI-obvious options flagged. Awaiting Alex's draft → annotated pass next.
- 2026-07-10 (later): Annotated pass on Alex's hand-drafted ch-1 rewrite. Both watch-list rules improved dramatically (see table). Top-4 annotations: smirk line (2.2), reader address ×3 (register lock), bullet-list lore dump (3.9/4.4), tense drift (past locked). **MAJOR: user adopted his rewrite as new architecture** — old manuscript/book-1/ now LEGACY; cascade forks in `bible/rewrite-cascade.md` await ruling (F1 Ch. 2 inciting event, F2 Ch. 8 keystone, F3 ladder re-axis, F4 small joints + register/tense locks). Naming-slip ruled canon. Typos swept directly per §10.4; vitals.py IndexError on list-lines fixed.
