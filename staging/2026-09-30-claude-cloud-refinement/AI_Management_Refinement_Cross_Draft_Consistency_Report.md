# Cross-draft consistency report (Reconcile phase)

Status: RESEARCH / STAGING ONLY — reconciliation of five research drafts; nothing here ratifies, decides or changes any canonical file.
Prepared: 2026-10-01, Claude cloud research session (bounded worker), after the verifier/fixer passes on all five drafts.
Drafts checked (sizes at time of check): A Role Reference Corpus 162,009 chars; B Flowcharts 191,006; C Modularization Audit 175,074; D Prompt+Context Stage-1 213,643; E Efficiency Opportunities 128,101.
Method: `grep -n "^#"` outlines, `sed -n` of the sections named below, the closing sections of every draft, the digest `_workstream_summaries.md` (which predates the D and E fixes — the drafts were trusted where they differ), and source checks against the 44 mirrors and `_manifest.json` / `_folder_inventory.json`. Drive IDs were extracted with a 25+-character regex from all five drafts and checked against the manifest and inventory. Identifiers are the drafts' CURRENT ones (D: RAT-1..15, QD1-QD10, RT0-RT9, RM1-RM4; E: R-1..R-14, Q1-Q11, EFF-001..032 with EFF-019(a)/(b)).

Kinds used: **factual_numeric** (one draft is wrong, or two valid measurement methods must be labelled); **label_status** (RATIFIED / ACCEPTED_IN_PRINCIPLE / PROPOSED / CANDIDATE applied differently; decided from the sources); **terminology**; **judgement_disagreement** (preserve and cross-reference, never resolve).

Summary counts: factual_numeric 5 (T1, T3, T9, T13, T17) · label_status 2 (T8-c, T8-f) · terminology 3 (T7, T10, T14) · judgement_disagreement 5 (T6, T7-b, T11, T18, T19) · topics checked with no contradiction 13 (T2, T4, T5, T8-a/b/d/e/g, T12, T15, T16, T20-T26).

---

## T1. Always-read surface per role (chars / tokens) — A vs C vs E

What each draft says:
- A [Draft A § "0. How to read this document", size table]: Chief READ FIRST 1-7 + launch prompt **191,409** / 2,058 paragraphs; Chief + From-CEO 249,264; Architect READ FIRST 1-5 + launch + handoff 118,299; Architect + From-CEO 210,589; Delivery Assurance 150,449; Planner 147,556; CEO (Read 1-6 + bootstrap + CEO handoff) 119,925; four shared governance docs 103,351.
- C [Draft C § "2. Always-read surface per role …", table]: Chief READ FIRST + Project Instructions (PI) + launch prompt **193,734** (9 files); Chief + From-CEO 251,589; Chief + Full Work Sweep 610,327; Architect READ FIRST + PI + launch 117,201; Architect handoff RESTART 168,898; Architect union 212,914; Planner 149,881; Delivery 152,774; CEO Bootstrap list + PI + bootstrap 117,604; CEO RESTART RULE + PI 77,831; shared kernel PI+GB+MB 73,185; five-file kernel 105,676.
- E [Draft E § "3.1 Always-read surfaces per role"; § "3.2 The Chief 'rehydration tax'"]: shared core 103,351; Chief READ FIRST 1-7 + launch prompt **191,409**; Chief + two mailboxes 326,567; Architect READ FIRST 1-5 + handoff + From-CEO + launch 210,589; Planner 147,556; Delivery 150,449; CEO PI + Bootstrap 1-6 + CEO handoff 122,250; rehydration before launch prompt 184,188.

Agreement: every figure reconciles arithmetically against `_manifest.json` once the inclusion rules are stated. The only systematic difference is **AI_Management_Project_Instructions.txt (2,325 chars)**: C includes it in every row (and says so, flagging the inclusion for non-Chief roles as an inference); A excludes it everywhere; E excludes it except in its CEO row. Checks: 193,734 − 191,409 = 2,325; 149,881 − 147,556 = 2,325; 152,774 − 150,449 = 2,325; 122,250 − 119,925 = 2,325; 212,914 − 210,589 = 2,325; 105,676 − 103,351 = 2,325; 184,188 + 7,221 (Chief LP) = 191,409. The Architect headline figures differ only by what is included (A/E 210,589 includes From-CEO 92,290; C 117,201 is READ FIRST + PI + launch prompt only).
Kind: factual_numeric (two valid measurement methods; no number is wrong).
Resolution rule: label both methods. Add a one-line method note to A's and E's tables ("excludes Project Instructions, 2,325 chars, which Draft C includes; C's figures are therefore 2,325 higher per role") and to C's derivation paragraph (that A and E exclude it). Do not change any number.

## T2. Chief handoff size and threshold status

A § "0." and § "Source gaps"; B Diagram 5 gap 2 / Q12 / R9; C § "1.2", § "4.11", § "5"; D § "2.2" E5, § "Source gaps" G8; E § "3.2": all state **71,454 clean chars / 693 paragraphs** (manifest), above the ratified hard fail-visible threshold **>25,000 / >300** [Source: AI_Global_Brain.md § "Compact CURRENT / fail-visible stale state"; AI_Management_Brain.md § "Management Reliability Contract v1 — ratified 2026-09-29"]. Ratios are consistent: 2.86x (E) = "~2.9x" (C) = 71,454/25,000; 2.3x paragraphs (C) = 693/300; 5.95x the 12,000 target (E). The pre-compaction "~49k document characters" (Chief's own count) vs ~51,968 archive readback vs 71,454 current mirror is reported identically by A, D and E. Compaction history: C and E say two compactions in ~25 h (archives 2026-09-29 PreReliabilityCompact and 2026-09-30 PreChecklist5Compact, both in `_folder_inventory.json`); D cites only the 2026-09-30 one (E5) — not a contradiction.
Agreement: full. No edit.

## T3. Lane-state count (7 vs 8 with DELIVERED)

- A [§ "Unresolved questions" 10; § "Disagreements preserved" 6]: "seven in Brain/Global Brain; eight (adding DELIVERED) in the DA launch prompt"; transition token "DELIVERED / DELEGATED_IN_FLIGHT" (Brain, DA LP) vs "DELIVERED / IN_FLIGHT" (Global Brain).
- B [Diagram 3 gap 1; § "Disagreements preserved" 2; R4]: seven (Brain, Current Structure, Chief LP) vs eight (Delivery LP) vs "DELIVERED / IN_FLIGHT" (Global Brain); drawn as seven.
- C [§ "3" row 9; § "4.12"; § "4.13"; R2]: canonical home is the Management Brain (7); Global Brain § "One Owner-facing task is rendering only" lists six (omits OWNER_ACTION, legitimately); Delivery LP eight; MSA-CEO-015 "exactly these"; IN_FLIGHT token traced to COS-CEO-N-020 / MSA-CEO-016.
- D, E: do not count lane states (E § "3.3" counts vocabulary occurrences only).

Source check: AI_Management_Brain.md line 523 "Canonical live lane states:" lists seven including OWNER_ACTION; AI_Global_Brain.md line 618 lists the six non-Owner lanes and names OWNER_ACTION only inside the DONE_EVENT rule (line 624); the Delivery LP § "CANONICAL LIVE DELIVERY STATES" says "Use only these live states" and lists eight.
Agreement on the disagreement itself (7 vs 8): yes, preserved by A, B, C. One attribution imprecision: A's "seven in Brain/Global Brain" — the Global Brain never lists all seven in one place.
Kind: factual_numeric (minor attribution) plus a preserved judgement disagreement that is already consistent.
Resolution rule: correct A's attribution to "seven in the Management Brain (the Global Brain lists the six non-Owner lanes and names OWNER_ACTION separately)"; leave the 7-vs-8 question open in all drafts; cross-reference A item 11 / B R4 / C R2 (merged as RAT-038).

## T4. Precedence ladders

(a) Nine-step vs five-step: A § "2.2" ("the 1-9 list, by reference"); B § "Disagreements preserved" 4 and Diagram 5 gap 5; C § "4.2" and § "3" row 12; E does not address. All agree: Management Brain and Chief handoff carry nine steps; the Delivery LP carries five plus a collapsing sentence. Source confirmed (AI_Management_Brain.md lines 553-571).
(b) Instruction precedence sentence, Chief handoff vs Global Brain: only C analyses it [§ "4.1"]: Chief handoff "explicit current Owner instructions > AI Management Brain > Global Brain" (copied from Project Instructions) vs Global Brain § "Precedence" "Explicit current user instructions > specific Project Instructions > this global brain"; C's verdict "NOT CONFIRMED as a contradiction; three divergent wordings with an unstated tier" is consistent with the sources (verified at AI_Global_Brain.md line 295-297 and Chief handoff line 9). No other draft states a conflicting view; B Diagram 5 uses "precedence" only for the evidence ladder, which C notes is a second axis using the same word.
Agreement: full. No edit.

## T5. Staleness thresholds 4 h / 24 h / 24 h

A § "1.1" (Owner Brief stale after 4 hours) and § "4" matrix (24-hour READY/IN_FLIGHT); B Diagram 5 edge FR, 5(c) step 3, 5(d) row FR; C § "4.3"; D QD6/QD9 (reuse of the 24-hour Delivery age); E § "7.2" (Brief 4h; Chief 24h; Delivery READY 24h). All match AI_Management_Brain.md lines 579-583 (under § "Freshness and precedence are claim-specific") and the Delivery LP (24 h only). C's finding that the three windows are deliberately different and not a conflict is not contradicted anywhere.
Agreement: full. No edit.

## T6. Trigger Assurance detection-owner candidates

- A [§ "5.1"]: six candidates with pros/cons — Delivery Assurance; Chief; Architect; shared registry module with split ownership (a function); external clock (scheduled tasks / jobs); future Agent Relay durable workflows — "D plus E is the combination the sources' constraints point toward without naming it"; none chosen.
- B [R6 ownership options; § "Disagreements preserved" 9]: three ownership options — Chief/Delivery as today (CEO-COS-029 item 12 "no new role"); Efficiency function's wake-up path (Checklist #7 item 5); a dedicated Trigger Assurance function (P2) — plus "four placements in the sources"; drawn as the ratified placement only.
- C [§ "7.3" M-PHASE owner cell; Unresolved question 16]: owner UNRESOLVED; candidate writers Chief, Delivery Assurance, or the Efficiency function; Architect designs.
- D [RAT-3; § "11" Q2]: four detector options for the PCE triggers T1-T9 — EODA; Architect safety net; Chief proactive sweep; defer to the future Trigger Assurance model.
- E [§ "7.1" three hosts; § "7.5" three positions; R-5]: Architect audit; Delivery live checks; disposable cloud/Relay worker; and the three source positions (Owner demands proactive detection; ratified "no new Auditor"; Stage 0/Brain limit external clocks).
Agreement: all five say no owner is named and none chooses; the enumerations differ in granularity (A six, B three, D four, E three) because they slice the same source material differently (role vs function vs mechanism).
Kind: judgement_disagreement (different framings; no factual conflict).
Resolution rule: preserve and cross-reference — one line in A § 5.1, B R6, C Q16, D RAT-3 and E § 7.5 pointing to the others' enumerations; merged as RAT-017 with every option listed.

## T7. L0-L5 <-> ROLE CORE / KNOWLEDGE ROUTER / DOMAIN MODULE / DEEP SOURCE mapping

- A [§ "2.1"]: ROLE CORE = role profile of **L1**; KNOWLEDGE ROUTER = knowledge section of **L0**; DOMAIN MODULE = **L3**; DEEP SOURCE/EVIDENCE = **L4** (L5 for retired items); L2 is state, not corpus. CANDIDATE; "one scheme, not two".
- C [§ "7.1"]: "ROLE CORE = the role's slice of L1 plus its L0 router; KNOWLEDGE ROUTER = L0 (one per role …); DOMAIN MODULE = L3; DEEP SOURCE/EVIDENCE = L4 (and L5 when historical)"; L2 separate. CANDIDATE.
- B [Diagram 7 gap 4; R14]: four vocabularies (L0-L5; Design Brief § 5 four-step chain; Requirements six-item list; Checklist #3 chain) "are compatible, but a single vocabulary does not exist. NEEDS_RECONCILIATION at A3".
- D [§ "4.4"; § "11" Q8; D3; RAT-12]: at least four Owner-accepted vocabularies differing on where the router lives, whether the compact handoff is a layer and whether archive is a layer; the Architect would need to pick one.
(a) Terminology: A and C agree in substance (CORE<->L1, ROUTER<->L0, MODULE<->L3, DEEP<->L4/L5). C's phrase "ROLE CORE = the role's slice of L1 plus its L0 router" sits awkwardly beside its own "KNOWLEDGE ROUTER = L0" and beside A's placement of the router entirely in L0. Kind: terminology. Rule: cross-reference (no rewrite of C's CANDIDATE wording; add one line in C § 7.1 noting A's placement, and one in A § 2.1 noting C's).
(b) Judgement: A/C present the unification as a workable CANDIDATE; B/D present the vocabulary question as open for the Architect (NEEDS_RECONCILIATION). Kind: judgement_disagreement. Rule: preserve and cross-reference (A § 2.1 and C § 7.1 -> B Diagram 7 gap 4 / D § 4.4; D § 4.4 and B gap 4 -> A § 2.1 / C § 7.1). Merged as RAT-001.

## T8. Status labels

(a) **L0-L5 architecture**: ACCEPTED_IN_PRINCIPLE subject to Item #8 in A § 0 and § 2.3, B 7(d), C § 7.1, D § 4.4; B additionally marks the L2 size budget, restart fields and archive-before-compact RATIFIED (they are Contract v1 text) — A and C agree via their Contract citations. Consistent.
(b) **P0A-P6 plan**: PROPOSED everywhere it is labelled — A § 1.11 "proposed priority plan"; B R6 "a priority plan that is itself not ratified"; C § 6 row A1 "PROPOSED, feeds Item 8"; E § 7.4 and D cite it without a status label. Source: Chief handoff § "PROPOSED PRIORITY ORDER" (line 701); P0A/P0B carry a separate Owner approval (§ "P0A/P0B OWNER APPROVAL — TWO-STAGE CLAUDE HANDOFF", line 963), which D uses correctly. Consistent.
(c) **Canonical-intake gap**: B Diagram 1 rows INTAKE/TRIGREG "PROPOSED (Owner requirement for Item 8)"; E § 6 EFF-012 / Q9 / R-14 "PROPOSED … the section carries an 'Owner observation:' line but no explicit Owner disposition line"; A cites the requirements without a label; C R7 refers to it as "the canonical-intake requirement"; **D § 11 Q2 option C labels the proactive sweep "ACCEPTED_IN_PRINCIPLE under the intake gap"**. Source check (Chief handoff lines 609-673): the section contains "Owner observation:", "Requirement for Item #8 / final architecture:" (items 1-10), "Design implication:" and "Do not implement globally until Item #8 synthesis/prioritization is complete unless Owner explicitly overrides." No Owner disposition or state line; the "Owner direction:" line at 679 belongs to the following section (§ "POST-CHECKLIST PRIORITY / APPROVAL / IMPLEMENTATION PLAN — PROPOSED 2026-09-30"). Under the FRAME discipline (ACCEPTED_IN_PRINCIPLE = Owner checklist disposition recorded in the Chief handoff) the gap's requirement list is **PROPOSED** (Owner-observed gap; Chief-recorded requirement for Item #8; no disposition). Kind: label_status. Rule: correct D Q2 option C to PROPOSED with the evidence line; cross-reference B/E.
(d) **Identity gate**: RATIFIED 2026-09-30 (Brain) with enforcement surface OPEN (MSA-CEO-018) — A § 1.4/§ 4, B Diagram 2 / R3, C row 20 / § 4.21, D § 4.3 RT-table, E § 2.2/§ 5.3. Consistent.
(e) **Reliability Contract v1**: RATIFIED 2026-09-29 in all five; mailbox containment thresholds (>40,000 / >50 / >60%) "ratified by reference, unpublished" — B gap 1 / R8, C § 4.22 / row 11, E § 3.3 / R-1 agree (NEEDS_RECONCILIATION on whether they bind today). Consistent.
(f) **Stage 0 Prompt + Context Engineering documents**: A § 0 lists "Stage 0 Prompt + Context Engineering documents" as an example of **PROPOSED**, and writes "Stage 0 is PROPOSED" (§ 2.3) and "Stage 0 (PROPOSED)" (§ 4 observation 1); B Diagram 4 F-variant row: "PROPOSED (Chief-authored Stage 0 text under Owner EXECUTION HOLD; the companion Requirements file calls its content Owner-approved, so the field list's acceptance status is itself uncertain)"; D § 0 defines its own label **OWNER_APPROVED_REQUIREMENT** for the Requirements content and applies it in § 3, § 4.4 and § 5; E § 6 EFF-006 "Both are Owner-approved text under the Owner's Item #4 hold"; C § 4.20 records the status-line conflict without a label. Source check: Requirements header "Status: OWNER-APPROVED REQUIREMENTS / STAGE 1 READY FOR ARCHITECT DESIGN"; Design Brief header "REQUIREMENTS CAPTURED / EXECUTION HOLD" and closing "Owner disposition: HOLD STAGE 1 ROUTING …"; Chief To-CEO COS-CEO-N-023 (line 1540-1548) "Class: OWNER_APPROVED_ARCHITECTURE_STAGE … Owner disposition: APPROVED TO PROCEED with staged implementation", followed by § "COS-CEO-N-023 SEQUENCING HOLD — OWNER CORRECTION" (line 1582); Chief handoff item 4 "State: DESIGN ADVANCED / EXECUTION HOLD" (line 81) and § "PROMPT + CONTEXT ENGINEERING HOLD" "Stage 0 brief is captured input only" (line 225). Correct labelling under the FRAME discipline: the Stage 0 **requirements content** carries a recorded Owner disposition and is therefore ACCEPTED_IN_PRINCIPLE-class (D's OWNER_APPROVED_REQUIREMENT is the same thing under another name) with **execution/routing on HOLD** — approval of requirements is not authorization; the Stage 0 **design proposals** (placement, pilot form, writer allocations) remain PROPOSED. Kind: label_status. Rule: amend A § 0 example and A § 2.3 / § 4 wording; add the Chief-handoff item-4 state line to B's hedge; add an equivalence note to D § 0's label definition. No draft treats the HOLD as lifted.
(g) **HOLD**: an Owner disposition recorded in the Design Brief, the Chief handoff and the N-023 Owner correction, "not a ratified standard" (A item 7); every draft treats it as governing its own conduct. Consistent.

## T9. Manual-hop count of the 2026-09-30 chain — B Diagram 6 vs E § 2

- B [§ "6(c)" closing paragraph; § "6(f)" 1-2; § "Source gaps" 6]: **eight** Owner-carried chat switches for CEO-OPS-010 (four forward activations: CEO, Delivery, Claude, Claude repair; four returns to the Chief), six on the happy path, "7-8" allowing that the SENT-confirmation and DONE-report for COS-CEO-N-024 may have been one Owner turn; **~fourteen** for the two-stage plan (CEO-OPS-010 + CEO-OPS-011).
- E [§ "2.2" hops 1-22; § "2.3" counts]: Chain A (CEO-OPS-010) = 4 completed Owner activations plus 6 Owner report-back/confirmation turns marked [T] = **10** Owner transport turns (hops 3, 5, 6, 8, 9, 11, 12, 13); Chain B (CEO-OPS-011) = 3 activations + 3 report-backs = **6**; so **16** for the two stages; across all five chains 19 activations + ~20 report-back turns + 1 cloud launch (lower bounds).
Difference explained: B counts chat switches and merges adjacent "confirms sent" and "reports done" returns into one hop where the handoff does not time-stamp them separately; E counts every dated Owner report/confirmation block as a turn (its hop 3 and hop 9 each carry two [T] marks). Both are arithmetic over the same Chief-handoff entries and both say so; neither is wrong.
Kind: factual_numeric (two valid counting rules).
Resolution rule: label both methods — add one line to B § 6(c) and to E § 2.3 stating the other's figure and the counting difference. Merged into RAT-028 evidence.

## T10. Number of restatements of the Reliability Contract — C vs E

- C [§ "3" summary; rows 1, 9, 10, 12, 27]: "restated, wholly or in part, in nine files (both Brains, Current Structure, Architecture Current, both Chief and Delivery launch prompts, the Chief handoff, CEO-COS-029, CEO-OPS-009) plus its source in MSA-CEO-015"; every launch-prompt restatement diverges from the Brain in at least one token or field.
- E [§ "3.2"; § "3.3"]: read "at least four times" in the Chief startup set (Global Brain, Management Brain, Current Structure, Chief LP) and a fifth time in the Chief handoff; "only two of the four executive launch prompts restate the contract" (Chief, Delivery); Architecture Current "deliberately does not restate the CEO-owned sections".
Source check: Architecture Current § "RATIFIED RELIABILITY MODEL" is a pointer paragraph ("Architect does not duplicate those CEO-owned sections here"), but the same file restates the Architect-owned parts of Contract v1 (INV-CURRENT … INV-INDEPENDENT list, 7/30-day cadence with ACTIVE/DORMANT semantics, "No new Auditor role", "SENT_EVENT and DONE_EVENT are same-turn durable state transitions"). C's "in part" count therefore legitimately includes it; E's statement is about the CEO-owned core only.
Also consistent: "COS-CEO-N-023 remains HOLD" identical sentence 25 lines / 11 files (C row 25; E § 3.4); SENT_EVENT in 15 of 44 files (C row 1 raw count; E § 3.3). Different regexes give different "one-task-at-a-time" counts (C row 17 "15 normative / 86 raw lines in 21 files"; E "48-49 lines across 19 files"); both state their method.
Kind: terminology (scope of "restatement").
Resolution rule: cross-reference — one line in C § 3 summary ("Draft E counts only the CEO-owned core and notes Architecture Current points rather than restates it") and one in E § 3.3 ("Draft C's nine-file count includes Architecture Current's restatement of the Architect-owned INV/cadence parts").

## T11. Proposed sizes for CORE / ROUTER / MODULE — A vs C vs D

- A [§ "2.2"-"2.4"]: ROLE CORE <= 4,000 chars / 60 paragraphs; KNOWLEDGE ROUTER <= 3,000; DOMAIN MODULE <= 8,000 / 120 paragraphs; CORE + ROUTER + L2 CURRENT <= ~20,000 (below the 25,000 hard threshold). All CANDIDATE.
- C [§ "7.4"; R4 option B]: L0 router <= 2,000 each; Management L1 <= 8,000; L3 module <= 8,000; launch prompt <= 4,000. All CANDIDATE.
- D [§ "6.2" QD1-QD3]: for Claude lanes, launch packet soft <= 3,000 / hard <= 5,000; recovery handoff inherits the ratified 12k/15k/25k; startup read budget <= 40,000. All UNVERIFIED CANDIDATE; different objects (lane packets, not role corpora).
Agreement: CORE/launch prompt 4,000 and MODULE 8,000 coincide; **router 3,000 (A) vs 2,000 (C)** differs; D's figures are for a different artifact class and do not conflict.
Kind: judgement_disagreement (two CANDIDATE yardsticks).
Resolution rule: preserve and cross-reference (A § 2.3 <-> C § 7.4 row L0; both options in RAT-002; D's QD1-QD3 listed in RAT-045).

## T12. Recovery-handoff field list — B vs D

- D [§ "7.1"]: header fields STATUS / AS_OF / FRESHNESS_STATE / ROUTING_AUTHORITY (RATIFIED) + the ten CEO-OPS-010 fields (quoted from the packet) + four Stage 0 preservation items (CANDIDATE).
- B: does not enumerate recovery-handoff fields. B Diagram 7 row "L2 required restart fields" lists the Brain's RATIFIED restart list (STATUS, AS_OF, FRESHNESS_STATE, ROUTING_AUTHORITY, source pointers, live lanes, scoped blockers, unresolved IDs/triggers, exact Owner packet, next-transition condition, replay-prevention evidence); B Q8 / § "Disagreements preserved" 3 compares the **trigger-complete** field lists (six in the Chief handoff vs eight in the Design Brief). C row 27 compares the Brain's six resumption-packet fields with the Delivery LP superset.
Source check: Chief handoff § "GLOBAL TRIGGER-COMPLETE DESIGN PRINCIPLE" lists six elements; Design Brief § "6." lists eight (splits the trigger element into three and renames "exact executor" to "execution target") — B's 6-vs-8 is correct; E § 7.2 uses the six-element form, consistent with B.
Agreement: no contradiction — the drafts describe different field lists (lane recovery handoff; L2 restart contract; trigger-complete schema; resumption packet). No edit required beyond the register (RAT-017 schema options; RAT-042 manifest/packet schemas).

## T13. "Director of Efficiency" vs "function" wording — A vs E

- A [§ "5.2"; Unresolved question 5; § "Disagreements preserved" 4]: the Owner accepted the "function direction" (Checklist #7, ACCEPTED_IN_PRINCIPLE); the **CEO** recorded "Director of Efficiency idea remains PARKED FOR FUTURE REVIEW" (MSA-CEO-006 disposition); the **Chief** asked to "Revisit parked Director of Efficiency only after separating" four efficiencies (COS-CEO-N-021 Owner Evidence Addendum item 7); NEEDS_RECONCILIATION between "Director" and "function" preserved.
- E [§ "7.1"]: "the Owner's instruction to keep the parked 'Director of Efficiency' idea parked until … are separated [Chief To-CEO § 'COS-CEO-N-021 — OWNER EVIDENCE ADDENDUM', item 7]".
Source check: the addendum's numbered items 1-7 are the Chief's recommendations (item 1 "Clarify that Chief normally RENDERS …", item 6 "Determine whether …", item 7 "Revisit parked Director of Efficiency only after separating: …") inside a Chief-authored section that records Owner evidence; the parking itself is a CEO disposition recording the Owner's idea: "The Owner's separate Director of Efficiency idea remains PARKED FOR FUTURE REVIEW and is explicitly outside this ratification" [Source: AI_Management_Systems_Architect_From_CEO_Current.md § "MSA-CEO-006 — CEO DISPOSITION", "Director of Efficiency"]; also Chief From-CEO line 463 "remains parked for future review and is not part of this standard".
Agreement on substance (function first; role parked; Item #8 A2/A5 decides): yes (A item 6, E R-5). E's attribution of item 7 to "the Owner's instruction" is not supported.
Kind: factual_numeric (attribution).
Resolution rule: correct E § 7.1 to attribute item 7 to the Chief's recommendation and the parking to the CEO disposition of the Owner's idea; cross-reference A § 5.2.

## T14. Owner preference for platform + exact chat + model + effort on activation packets — D vs E vs B (and C)

- B [Diagram 6 row C7; gap 5; R11]: Owner preferences recorded only in the Chief handoff; reused by the CEO in CEO-OPS-012 item 7 so "operating de facto"; copy-block rule RATIFIED (Global Brain); platform/model/effort **PROPOSED** for the Destination Contract; decider CEO.
- C [§ "3" row 4; R3]: "Owner-stated preference, not yet RATIFIED into Brain text"; packets comply, contract does not; decider CEO.
- D [§ "7.2" template]: labels PASTE INTO as RATIFIED Destination Contract + "OWNER platform preference"; model/effort line sourced to CEO-OPS-012 item 7 and the Chief's model-choice note; QW2 proposes recording recommended vs actual model.
- E [§ "6" EFF-032; R-10]: promote four Owner preferences (platform naming; model+effort on coding-agent prompts; deliberate model selection; copyable prompt blocks) into the Brain; decider CEO as Brain owner, or Architect under an MSA-CEO-016-style delegation.
- A [§ "2.2"; quick win 4]: Owner-preference rules bind role outputs; Delivery packets already record them.
Agreement: label (Owner preference, practiced, not in Brain text) and the substance agree. Minor difference in decider options (B/C: CEO; E: CEO or Architect under delegation) — both appear in RAT-031.
Kind: terminology (decider phrasing). No edit beyond the register.

## T15. Drive IDs cited across drafts

All 25+-character IDs in A-E were extracted (A 52 distinct, B 36, C 76, D 36, E 48) and checked. Every ID resolves to `_manifest.json` or `_folder_inventory.json` (files, archives, folders), with three documented exceptions that are not errors: D cites `1f1xk9lDGlQRMeHxbBJtgKydh5d0scS0H` (AgentRelay_Claude_Recovery_Handoff_Current.md) and `17235XYIqJ7stVufYwWciohZQ-7QtfaEl-iaKAOLdrZo` (ULTUSB_Claude_Orchestrator_Activation_Current.md) "as quoted in CEO-OPS-011/012" — both appear verbatim in those packet mirrors and in the Executive Operations mailboxes; C cites `1iWiNCJ8nexIA5fsekBbLifbAco0DAfA5` (old Chief launch prompt) explicitly as a dead pointer from MSA-CEO-015, which the mirror confirms (Architect To-CEO line 2971) and the inventory lacks. ID-to-filename pairings were checked line by line; the current Chief launch prompt is `1PlPfeOvn1iFuuJvB1s9uoRufhOdbIU6D-1X8RQXF_xw` in all drafts; the research packet is `1hAAagOUtIDu_fYRxh2LRdZv9b8Z1Xg12i7T-YXRwcAw` in all drafts; the Design Brief `1J4uT…` and Requirements `1k_SD…` are never swapped.
Agreement: full. No edit.

## T16. Statements that read as decisions, directives or completed changes

Scan of all five drafts for "must / shall / should / implement / ratified / approved / decided / done / completed" in recommendation sections, excluding quoted source text. Every header and closing line states "Nothing in this document is ratified"; recommendation tables are labelled CANDIDATE / "draft default" / "proposal only"; no sentence asserts a completed canonical change or a made decision. Residual advisory phrasings judged case by case:
- D § "4.4": "The Architect should pick one layer vocabulary for the eventual Context Architecture Standard …" and D § "11" Q8: "The Architect should choose one before any artifact names a layer." — read as directives to the Architect; reword to conditional proposal language (RAT-001 / D RAT-12).
- E § "2.4": "the Architect should test it against more chains before drawing a conclusion" — a caution framed as "an observation about this one day"; left unchanged.
- E § "8.1": imperative quick-win phrasing ("archive-first …, then compact to target (Chief)") under the header "proposal only — nothing executed here"; left unchanged.
- C § "7.6": numbered migration "steps" labelled CANDIDATE and "nothing is moved by this document"; left unchanged.
- B R-table "Default = … (as drawn)" entries are descriptive, as B's own residual-risk note says; left unchanged.
Kind: label_status/decision wording (two sentences in D). Rule: reword D's two sentences.

## T17. Which source names the authoritative Stage 0 document — E vs B (additional topic)

- E [§ "6.1" EFF-006 paragraph; Unresolved question 4; R-11]: "the Owner disposition already names the Design Brief as the 'Authoritative Stage 0 brief' [Chief To-CEO L1554-1556], so the authority question is answered by source".
- B [§ "Source gaps" 2; § "0.3"; R15]: the two COS-CEO-N-023 blocks cite different files as authoritative; the Chief handoff names the Design Brief as the Stage 0 brief that is "NOT active authorization"; the Requirements status line is stale relative to the HOLD; Owner confirmation still required.
- C [§ "4.20"; R9]: "only the Owner can say which document is canonical".
Source check (Chief To-CEO): the first COS-CEO-N-023 block (lines 1482-1500) cites AI_Management_Prompt_Context_Engineering_Stage0_Requirements.md, ID 1k_SD…; the second block (lines 1540-1560) has "Owner disposition: APPROVED TO PROCEED with staged implementation …" (line 1548) and, as a separate field of the Chief-authored item, "Authoritative Stage 0 brief: AI_Management_Prompt_Context_Engineering_Stage0_Design_Brief" (lines 1554-1558); the Owner correction § "COS-CEO-N-023 SEQUENCING HOLD — OWNER CORRECTION" (line 1582) imposes the HOLD. The Chief handoff (line 93) and item 4 also name the Design Brief. So: the later Chief-authored N-023 item names the Design Brief; the "Owner disposition" line itself does not. E's attribution over-states; B's account matches the source.
Kind: factual_numeric (attribution).
Resolution rule: reword E's three sentences to "the later COS-CEO-N-023 block (Chief-authored, carrying the Owner disposition 'APPROVED TO PROCEED …') names the Design Brief as 'Authoritative Stage 0 brief', while the earlier block cited the Requirements file (Draft B § 'Source gaps' 2)"; keep the question open in B R15 / C R9 / E R-11 (merged as RAT-050).

## T18. Is a pointer line on the Stage 0 Requirements file a quick win? — B vs E (additional topic)

- B [§ "Candidate quick wins" 2]: Chief may add a one-line pointer to the Design Brief HOLD on the Requirements file without altering the Owner-approved status line (CANDIDATE; status-line change itself is R15).
- E [§ "6" EFF-006; § "8.2"; R-11]: "NOT a quick win: Chief proposes a status/pointer reconciliation, CEO confirms, no edit to either document before Item #8"; both files sit under the Owner's Item #4 hold (Chief handoff line 229).
- C [R9]: the status line is an Owner decision; the pointer form is not addressed.
Kind: judgement_disagreement.
Resolution rule: preserve and cross-reference (B quick win 2 <-> E EFF-006 / R-11); listed as QW-024 with the disagreement flagged.

## T19. Whether Chief quick wins are executable now — C vs B/D/E (additional topic)

C conditions every Chief quick win on confirming whether the Owner instruction behind "READ-ONLY INBOX CHECK 2026-09-30 … Per Owner instruction, no action or processing was performed" (Chief handoff line 605) was one-off or standing [Draft C § "Quick wins", caveat; Unresolved question 17]. B quick win 1, D QW3/QW4 and E EFF-001/-004/-022/-024 list the same Chief items without that condition (E conditions only on the Checklist #5 guard and archive-first).
Kind: judgement_disagreement (C's caution).
Resolution rule: preserve and cross-reference — one line in B's quick-win 1, D QW3 and E § 8.1 pointing to C's caveat (QW-001 to QW-004 carry the condition in the register).

## T20-T26. Topics checked with no contradiction (for completeness)

- T20 Owner Brief stale "Next item: #5" while #5-#7 are dispositioned; missing AS_OF/FRESHNESS_STATE despite Response-To CEO-COS-029 claim — B § "Disagreements preserved" 5, C § 4.3/4.14, E § 3.2 and § "Disagreements preserved" 8: consistent.
- T21 Owner Notifications: MGMT-NOTIF-002 still OPEN after CEO-COS-016/CEO-OPS-008; MGMT-NOTIF-001 kept "live / TRIGGER_BOUND" by CEO and Delivery statements, reassessment after 2026-09-29 unevidenced — B gap 4/R16, C § 4.4/R11, D U11/RAT-14, E Q3/EFF-004: consistent.
- T22 Lightweight portfolio index: Management Brain "not yet authorized to exist operationally" vs Current Structure "Stage 3 INITIALIZED" and the index file "ACTIVE" — A § "Disagreements preserved" 9, B 10 / Q20, C § 4.17: consistent (all hand it to the CEO as a stale Brain sentence; none resolves).
- T23 Full Work Sweep enumerations (Global Brain 7, Management Brain 7, Chief LP 6 + Opportunity Sweep, Chief handoff gap item 7 with 5 parts; practiced version narrower) — C § 3 row 3; B Diagram 1 draws the seven ratified items; A § 1.3: consistent.
- T24 Mailbox sizes and reconciliation lag (Architect To-CEO 112,881 = 2.8x; From-CEO 92,290 = 2.3x; eight mailboxes 409,888; six active 395,634; 11/11 CEO-OPS and 13/14 or 14-vs-1 MSA-CEO labels OPEN) — C § 1.2/§ 4.16, E § 4.4, D G4: numbers consistent with the manifest.
- T25 Research packet modifiedTime 2026-09-30T21:28:54Z (A § 0; D G1; E gap list): consistent; E notes the brief's "21:27" as immaterial.
- T26 Pointer-first before/after pair (CEO-OPS-011 1,945 chars vs Integration Prompt 6,633) — D § 2; E § 4.5; A § 1.6: consistent with the manifest.

## Cross-draft identifier sync

No draft cites another draft's item identifiers (grep for "Workstream X" / "Draft X" shows only generic hand-offs: A -> B/C, B -> C/E, D -> A). Therefore the E question renumbering (Q4-Q8 shifted; Q9-Q11 new) and the D identifier renaming (QD1-QD10, RT0-RT9, RM1-RM4, RAT-1..15) require no re-sync in other drafts. The register and merged-questions files use the drafts' current identifiers.

## Harmonization instructions derived from this report (applied in the Harmonize phase)

Factual/numeric: T1 (method notes in A § 0, C § 2, E § 3.1); T3 (A disagreement 6 attribution); T9 (dual-count notes in B § 6(c) and E § 2.3); T13 (E § 7.1 attribution); T17 (E EFF-006 paragraph, Q4, R-11 attribution).
Label/status: T8-c (D Q2 option C -> PROPOSED); T8-f (A § 0 example, A § 2.3, A § 4 observation 1; B Diagram 4 F-variant evidence; D § 0 equivalence note); T16 (D § 4.4 and Q8 wording).
Cross-references for judgement disagreements: T6 (A § 5.1, B R6, C Q16, D RAT-3, E § 7.5); T7 (A § 2.1, C § 7.1, B Diagram 7 gap 4, D § 4.4); T10 (C § 3 summary, E § 3.3); T11 (A § 2.3, C § 7.4); T18 (B quick win 2, E EFF-006); T19 (B quick win 1, D QW3, E § 8.1).
Open questions answered or part-answered by a source: see `_open_questions_merged.md` (annotations, not deletions).
No Drive ID correction is needed.
