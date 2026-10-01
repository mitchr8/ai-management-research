# Merged ratification register (Reconcile phase)

Status: RESEARCH / STAGING ONLY — a deduplicated list of decision questions raised by the five research drafts. Nothing here is decided, recommended or routed. Where drafts hold different CANDIDATE preferences, every option appears; no option is marked preferred.
Source lists merged: Draft A "Items requiring … ratification" 1-12; Draft B R1-R18; Draft C R1-R15; Draft D RAT-1..RAT-15; Draft E R-1..R-14 (plus E's §8.2 list). Identifiers are the drafts' current ones.
Row format: **RAT-### — Decision question** · Options (from the drafts) · Evidence / consequence per option · Who decides and why that level · Raised by · Depends on (other RAT rows; Checklist Item #8 sections A1-A7) · Urgency as the drafts describe it ("not assessed by drafts" where none gives one).
Decider vocabulary: Architect = Management Systems Architect design review (Item #8); CEO = CEO / Executive Control Room ratification; Owner = Owner decision. "Chief" / "Delivery" / "PM" appear where a draft names them as the executing or proposing role.

---

## Theme 1 — Context architecture and documentation

**RAT-001 — Which layer vocabulary and mapping becomes the single Context Architecture Standard: is ROLE CORE -> KNOWLEDGE ROUTER -> DOMAIN MODULE -> DEEP SOURCE one profile of L0-L5, or do the four Owner-accepted vocabularies need an Architect-chosen replacement?**
- Options: (A) one scheme — ROLE CORE = L1 role profile, KNOWLEDGE ROUTER = L0, DOMAIN MODULE = L3, DEEP SOURCE/EVIDENCE = L4/L5 [Draft A § "2.1"; Draft C § "7.1"]; (B) keep Checklist #3 (corpus) and Checklist #6 (L0-L5) as two schemes [Draft A item 1]; (C) defer until Item #8 A3 produces the Architect's own layout [Draft A item 1]; (D) the Architect selects one of the four vocabularies (Requirements six layers; Checklist #6 L0-L5; Design Brief § 5 four-step chain; Checklist #3 chain) or defines a merged one with mapping notes for every existing document [Draft B R14; Draft D RAT-12, § "4.4"]; plus: who writes each role's L0 and what triggers router review; whether to create a global standard at all [Draft B R14].
- Evidence/consequence: A — one standard to maintain, corpus becomes a profile of it [A § 2.1]; B — faster start, two owners and duplicated metadata rules [A item 1]; C — nothing named before Item #8 [A item 1]; D — every existing document then needs a mapping note; without a choice "routers cannot be reviewed because no trigger owns them" [B R14 default]; D's four vocabularies differ on router placement, handoff layer and archive layer [D § 4.4].
- Who decides: Architect designs (Item #8 A3) -> CEO ratifies (mandatory standard) -> Owner (Checklist #6 accepted "in principle, subject to Item #8"); creates a global standard.
- Raised by: A (1), B (R14), C (R1 context, § 7.1), D (RAT-12, Q8).
- Depends on: Item #8 A3; RAT-004 (L0 ownership); RAT-017 (router-review trigger belongs to Trigger Assurance).
- Urgency: not assessed by drafts (B: "Default = no standard, four vocabularies coexist").

**RAT-002 — What size budgets, if any, apply to ROLE CORE / launch prompts, KNOWLEDGE ROUTER / L0, DOMAIN MODULE / L3, the always-read bundle, and Class A authority documents — and which character measure counts?**
- Options: (A) A's numbers: CORE <= 4,000 chars / 60 paragraphs; ROUTER <= 3,000; MODULE <= 8,000 / 120 paragraphs; CORE + ROUTER + L2 <= ~20,000 [Draft A item 2; § 2.2-2.4]; (B) C's numbers: router <= 2,000; Management L1 <= 8,000; L3 module <= 8,000; launch prompt <= 4,000 [Draft C R4 option B; § 7.4]; (C) apply the ratified CURRENT thresholds (12k/15k/25k) to Class A documents as well [C R4 option A]; (D) no numeric budgets — only Checklist #6 rule 7 [A item 2 option B; C R4 option C]; (E) per-role budgets set by the Architect at P4 from measured startup sets [A item 2 option C]; measure: mirrored clean text vs Google Docs document characters [A Q3/Q11; C Q1; C § 0].
- Evidence/consequence: A — bundle stays under the 25,000 hard threshold but today's 9,327-char Delivery LP must split [A item 2]; B — gives the Architect a target without declaring today's files in breach [C R4]; C — Global Brain (40,841) and Management Brain (30,019) would be at immediate hard-fail, four authority files rewritten at once [C R4]; D — no measurable INV for the audit; the Owner's "very small" kernel has no enforceable measure [A item 2; C R4]; E — most accurate, slowest [A item 2]; the two character measures differ (Chief ~49k vs mirror 71,454 for the handoff) [A § 0].
- Who decides: Architect proposes -> CEO ratifies (extends a ratified contract) -> Owner for kernel size (an Owner preference) [A item 2; C R4].
- Raised by: A (2), C (R4, Q1, Q3), D (QD1-QD3 for lanes — see RAT-045).
- Depends on: Item #8 A3; RAT-001; A Q11 / C Q1 (character measure).
- Urgency: not assessed by drafts (C: "No decision = C").

**RAT-003 — Adopt the shared write-once module set (M-AUTH, M-RC1, M-MAIL, M-ACT, M-LIFE, M-TIER, M-IDG, M-PCE, M-CTX, M-PHASE) and per-role L0 routers, including the Reliability Contract as one module with pointers in launch prompts and canonical files?**
- Options: (A) adopt the full set as designed by the Architect under Item #8 A3/A4 [Draft C R1 A]; (B) adopt a subset — M-RC1 + M-LIFE, the two with most restatements/integration gaps [C R1 B]; (C) keep the flat corpus and rely on compaction alone [C R1 C]; for the contract module specifically: (D) module + pointers in the two migrated launch prompts only [Draft E R-6 a]; (E) full WRITE ONCE / REFERENCE MANY across Brain / Current Structure / prompts after Item #8 [E R-6 b]; (F) leave restated [E R-6 c]; (G) extraction of SHARED modules with RATIFIED sources only, before P4 [Draft A item 8 option B].
- Evidence/consequence: A — ~190 restatements collapse to ~10 texts; migration cost is C § 7.6 [C R1]; B — removes contract/lifecycle drift but leaves authority/front-door/tier duplication [C R1]; C — two compactions in 25 h did not hold; sweep surface stays ~610k chars [C R1]; D — small blast radius, two of 4-5 contract copies per Chief startup removed [E R-6]; E — every role benefits, three canonical edits (CEO) [E R-6]; F — contract read 4-5x per startup persists [E R-6]; Owner held globalisation of the router pattern for Item #8 [E R-6].
- Who decides: Architect designs (Item #8 A3/A4) -> CEO ratifies as a mandatory Management standard -> Owner final (changes what every role reads first; "Cross-project management standards designed by this role require CEO review or ratification before they become mandatory" [Source: AI_Management_Brain.md § "Management systems architecture"]).
- Raised by: C (R1), E (R-6, EFF-003, EFF-029), A (1, 8).
- Depends on: RAT-001; RAT-002; RAT-004; RAT-038 (one contract text first); Item #8 A3/A4.
- Urgency: not assessed by drafts (C: "No decision: drift continues to accrue at each edit").

**RAT-004 — Who writes SHARED modules and each role's L0 router, and where is the learning-wave autonomy boundary?**
- Options: (a) Architect writes every SHARED module, roles supply operational input [Draft A item 3 (a)]; (b) the role that operationally owns the content under a ratified rule writes the SHARED module, Architect reviews structure, CEO ratifies mandatory content, with an explicit exception list [A item 3 (b); A § 4 matrix drawn this way]; L0: role owner writes its own L0 vs Architect writes all L0s [Draft B R14]; autonomy boundary: Stage 0 § 7 "governing principle" test [A Q9].
- Evidence/consequence: (a) one writer class, clean write-once, Architect bottleneck for content it does not operate [A item 3]; (b) matches current practice (Delivery writes packets; Planner defined the bands) but creates per-module exceptions [A item 3]; without an L0 owner "routers cannot be reviewed" [B R14].
- Who decides: Architect -> CEO (allocates writer authority) [A item 3]; Owner conditioned Checklist #6 on Item #8 [B R14].
- Raised by: A (3, Q9), B (R14), C (§ 7.3 owner column).
- Depends on: Item #8 A1/A5; RAT-001; RAT-003.
- Urgency: not assessed by drafts.

**RAT-005 — Create a shared-module folder (`Executive Team > _Shared Modules`) and adopt the file/naming template now, later, or never?**
- Options: (A) create now as low-risk structural work [Draft A item 4 A]; (B) create only when the first ratified module is written [A item 4 B]; (C) no new folder — modules live in the owning role's folder and the router points across folders [A item 4 C].
- Evidence/consequence: A — folder exists before any module; risk of an empty structure inviting premature authoring; B — no empty structure; C — no Drive change, cross-folder pointers [A item 4].
- Who decides: Architect may create low-risk structure (Brain permits Architect-owned structural work), but adopting the scheme is CEO (Drive structure is canonical state) [A item 4].
- Raised by: A (4).
- Depends on: RAT-001; RAT-004.
- Urgency: not assessed by drafts.

**RAT-006 — Do ROLE CORE documents replace launch prompts, or do launch prompts remain bootstraps pointing to them?**
- Options: (A) replace — one always-read file per role [Draft A item 10 A]; (B) retain launch prompt as a bootstrap pointing to ROLE CORE [A item 10 B]; (C) ROLE CORE is a section inside the launch prompt [A item 10 C]; related: C § 7.4 has launch prompts shrink to ROLE + READ FIRST (router pointer) + FIRST ASSIGNMENT [Draft C § 7.4 L0 row].
- Evidence/consequence: A — launch prompt owner is stated in no source (GAP) and every role would be re-launched; B — two files where one would do, drift risk; C — launch prompt grows against RAT-002 budgets [A item 10].
- Who decides: CEO (launch prompts are durable role files; owner to be confirmed) with Architect structural review (canonical mutation) [A item 10].
- Raised by: A (10, Q2, source gap on launch-prompt ownership), C (§ 7.4).
- Depends on: RAT-001; RAT-002; the launch-prompt ownership gap (open question OQ-10).
- Urgency: not assessed by drafts.

**RAT-007 — Should any role reference corpus be authored before P4, and which roles first?**
- Options: (A) none before P4 [Draft A item 8 A]; (B) SHARED modules with RATIFIED sources only, as extraction not authoring [A item 8 B]; (C) "highest-value context-heavy roles first" (Chief, then Architect) per Checklist #6 rollout rule [A item 8 C].
- Evidence/consequence: A — no premature structure, the Delivery LP keeps serving as an unlabelled de facto module; B — low risk, measurable startup-size reduction, still touches what roles read; C — follows the Owner's rollout wording [A item 8].
- Who decides: CEO priority pass after Item #8; Owner final sequencing ("no final priority setting" is a packet boundary) [A item 8].
- Raised by: A (8).
- Depends on: Item #8 complete; RAT-003.
- Urgency: not assessed by drafts (A: sequencing reserved to the Owner).

**RAT-008 — Introduce an event ledger (L2-EVENT per role, or one Management-wide ledger) so SENT/DONE narrative leaves the Chief handoff?**
- Options: (A) one event log per role [Draft C R6 A]; (B) one Management-wide append-only ledger owned by Delivery Assurance, CURRENT surfaces hold pointers only [C R6 B; Draft E R-3 b]; (C) none — keep events in handoffs and compact more often [C R6 C; E R-3 a]; (D) fold the ledger into Delivery Current [E R-3 c].
- Evidence/consequence: A — five new surfaces, each role-owned [C R6]; B — one new surface; Chief writes to a Delivery-owned file (writer-ownership question); one extra write per event for a token/duplicate-I/O gain across all CURRENT surfaces [C R6; E R-3]; C — § 4.11 regrowth to 71k within six hours of compaction recurs after every busy day [C R6; E R-3]; D — Delivery becomes a "second Chief", which its launch prompt forbids [E R-3].
- Who decides: Architect (Item #8 A2 overlap with Delivery ledger / Trigger Assurance) -> CEO (new surface; Brain forbids new mailboxes/roles without ratification; Owner forbids duplicate subsystems) [C R6; E R-3].
- Raised by: C (R6, Q13), E (R-3, EFF-010).
- Depends on: Item #8 A2; RAT-017; RAT-010 (handoff class).
- Urgency: not assessed by drafts (C: "No decision = C"; E: handoff "regrows past 25k after every busy day").

**RAT-009 — Introduce a single phase / hold / trigger register (M-PHASE) and retire the replication of the COS-CEO-N-023 HOLD state across 15 files?**
- Options: (A) new register owned per Item #8 A4/A5 placement [Draft C R7 A]; (B) fold phase/hold flags into the existing Owner Notifications file [C R7 B]; (C) none [C R7 C].
- Evidence/consequence: A — one place to lift a HOLD; needs an owner (C Q16); B — no new surface, Owner Notifications becomes a mixed register; C — a lifted HOLD requires 15 edits or files contradict [C R7; C § 3 row 25].
- Who decides: Architect (Item #8 A4 canonical intake/trigger/watchdog; A5 placement); CEO [C R7].
- Raised by: C (R7, § 7.3 M-PHASE), E (§ 3.4 ritual restatement; EFF-019).
- Depends on: RAT-017 (owner); RAT-035 (Owner Notifications disposition); Item #8 A4/A5.
- Urgency: not assessed by drafts.

**RAT-010 — What class are handoffs (Class A "durable current handoffs/state" vs compactable restart state), and what archive-location, archive-index and ID-change-redirect conventions apply?**
- Options: class — (A) "file ID is Class A, content is Class C" [Draft C R5 A, § 4.23]; (B) Class A throughout [C R5 B]; (C) Class C throughout [C R5 C]; archive location — one folder (90 Archive) + index / per-role folders + one index / leave as practised [C R5]; ID change — redirect line in successor + archive / no rule [C R5, § 4.7].
- Evidence/consequence: class A — both ratified texts stand, compaction lawful; B — each compaction becomes a "deliberate revision", handoff stays at 71k; C — contradicts MSA-CEO-006; location A/B enable the archive index and INV-POINTER, "leave" perpetuates § 1.4 inconsistency; ID rule "none" means § 4.7 dead pointers recur at every Markdown->Doc conversion [C R5].
- Who decides: Architect (lifecycle design owner) -> CEO ratifies (extends MSA-CEO-006, a ratified standard) [C R5].
- Raised by: C (R5, Q2, Q14), B (Diagram 7 gap 6), E (§ "Disagreements preserved" 4: compact CURRENT vs preservation guard).
- Depends on: RAT-008; Item #8 A3.
- Urgency: not assessed by drafts.

**RAT-011 — Add INV-POINTER to the Architect structural audit?**
- Options: (A) add as a seventh invariant with dedup/reset/Owner-friction elements [Draft C R8 A]; (B) fold pointer checks into INV-CURRENT [C R8 B]; (C) none [C R8 C].
- Evidence/consequence: A — audit contract text changes once; B — pointer failures reported under a freshness label; C — dead pointers found by accident [C R8].
- Who decides: Architect proposes -> CEO ratifies (audit contract is ratified text under MSA-CEO-015) [C R8].
- Raised by: C (R8, § 7.5).
- Depends on: RAT-010 (ID-change rule).
- Urgency: not assessed by drafts.

**RAT-012 — Is any Global Brain generic-rule modularisation in scope, and who may edit the Global Brain (including its stale "Version: 2026-09-26" header) outside a specific directive?**
- Options: (A) Owner authorises a Global Brain split (generic L1 + modules) [Draft C R14 A]; (B) Global Brain stays monolithic; Management modularises only its own files [C R14 B]; (C) Architect proposes header/version corrections to the CEO for ratification, no direct edit [C R14 C].
- Evidence/consequence: A — every ecosystem chat's always-read set changes; B — every Management role keeps reading 16-23k chars of generic rules; C — one-line correction waits a ratification cycle but stays inside OWNER-MSA-001's boundary ("do NOT modify the Global Brain … solely from this directive") [C R14; C Q4].
- Who decides: Owner (Global Brain is ecosystem-wide, not Management-owned); CEO for option C [C R14].
- Raised by: C (R14, Q4, § 4.19).
- Depends on: RAT-001; RAT-003.
- Urgency: not assessed by drafts.

**RAT-013 — Extend AI_Management_Current_Structure.md § "Authority" to name the Architect and the Portfolio & Capacity Planner?**
- Options: (A) CEO adds the two roles to the opening authority list [Draft C R15 A]; (B) CEO replaces the enumeration with a pointer to the executive-team sections [C R15 B]; (C) leave as is [C R15 C].
- Evidence/consequence: A/B — a Class A chain-of-command statement is deliberately revised (MSA-CEO-006 "preserve; revise deliberately"); C — the file's first section continues to omit two ACTIVE roles [C R15; § 4.18].
- Who decides: CEO (file owner; authority text, not hygiene — moved out of C's quick-win list) [C R15].
- Raised by: C (R15).
- Depends on: none stated.
- Urgency: not assessed by drafts.

**RAT-014 — Archive or compact AI_Management_CEO_Execution_Checklist_Current.md and AI_Management_CEO_Bootstrap_Prompt.md?**
- Options: checklist — (A) archive (initiative at steady state) / (B) compact to open gates only / (C) update stale boxes now and archive at Stage 4 / (D) leave as is [Draft C R10; Draft E R-12]; bootstrap — (A) archive and move the READ list into the CEO L0 router / handoff RESTART RULE / (B) keep as the CEO READ-list source [C R10].
- Evidence/consequence: checklist A — open gates (CEO-COS-023, CEO-PORT-003, Stage 4) must first be homed elsewhere; B/C — file stays, § 4.5 stale boxes fixed; E: archive-now "loses the live tracking the close condition requires"; leave — stale boxes mislead sweeps [C R10; E R-12]; bootstrap A — Current Structure durable-state line changes; B — two CEO read lists of different size persist [C R10; C § 2 finding 5].
- Who decides: CEO (file owner; "genuinely complete" is a CEO judgement; close condition depends on Stage 4 review) [C R10; E R-12].
- Raised by: C (R10, Q10), E (R-12, EFF-008).
- Depends on: Stage 4 review of the whole-life initiative.
- Urgency: not assessed by drafts.

**RAT-015 — Approve batch archiving of closed mailbox traffic with compact indexes, and is one index format ratified first?**
- Options: (A) each owner compacts under the existing containment rule with an ad-hoc index [Draft C R12 A]; (B) CEO first ratifies one index format (stable ID, disposition, Response-To, one-line outcome, archive ID), then owners compact [C R12 B]; (C) defer until the RAT-003 modules exist [C R12 C]; E's quick-win variant: archive on the >60%-resolved trigger only until RAT-037 settles the size triggers [Draft E EFF-002].
- Evidence/consequence: A — fastest, eight index styles; B — one more ratification, one format; C — § 4.22 integration gap and 409,888 chars of mailbox text persist [C R12]; E — all six active mailboxes meet at least one containment trigger today [E § 4.4].
- Who decides: each mailbox owner executes; CEO closes CEO-owned items first; CEO ratification only if the index format becomes a standard [C R12].
- Raised by: C (R12), E (EFF-002, EFF-023).
- Depends on: RAT-037 (whether the 40k/50 triggers bind); RAT-010 (archive conventions).
- Urgency: not assessed by drafts (E: thresholds "executable now" on the >60% trigger).

**RAT-016 — Do these research deliverables enter Item #8 as inputs, and through which route?**
- Options: (A) Chief routes the documents to the CEO as Item #8 inputs [Draft C R13 A]; (B) CEO routes selected sections only [C R13 B]; (C) not used [C R13 C]; for the Stage-1 draft specifically: pass as input now before the A1-A7 reconciliation vs archive as evidence until Item #8 [Draft D RAT-1 (a)/(b)].
- Evidence/consequence: A/B — findings reviewed under the existing approval chain; C — the duplication catalogue and candidates are re-derived later [C R13]; D (b) — the Architect reads Stage-1 research before A1-A7 "with a risk of pre-empting Item #8" [D RAT-1].
- Who decides: Chief -> CEO (commissioning Item #8); the documents have no standing to insert themselves [C R13]; Owner sequencing for the Stage-1 draft [D RAT-1].
- Raised by: C (R13), D (RAT-1), A (§ 0 "preparation for Item #8").
- Depends on: RAT-040 (HOLD).
- Urgency: not assessed by drafts.

## Theme 2 — Roles and functions

**RAT-017 — Who owns Trigger Assurance detection, what is the authoritative clock, and does a central trigger registry / watchdog (with trigger-complete schema, last-sweep timestamp and missed-run catch-up) get created?**
- Options (owner / mechanism): (A) Executive Operations & Delivery Assurance [Draft A § 5.1; Draft D RAT-3 A (EODA); Draft E § 7.1 b]; (B) Chief of Staff — proactive sweep [A § 5.1; D RAT-3 C; Draft B R6 ownership A "Chief/Delivery as today, no new role"]; (C) Architect — audit safety net [A § 5.1; D RAT-3 B; E § 7.1 a]; (D) shared registry module with split ownership — a function, not a role [A § 5.1; B R6 registry A "one central registry/watchdog" (P2)]; (E) external clock (scheduled task / cloud job) as executor but not sole authoritative clock [A § 5.1; B R7 — see RAT-018; E § 7.1 c]; (F) future Agent Relay durable workflows, backlog only [A § 5.1]; (G) the Efficiency function's wake-up path (Checklist #7 item 5) [B R6 ownership B; Draft C Q16]; (H) a dedicated Trigger Assurance function [B R6 ownership C]; (I) defer detection until the Trigger Assurance model exists (P2) [D RAT-3 D]; registry alternative: keep the four existing durable homes and ratify only a sweep-order rule [B R6 registry B]; schema: six fields (Chief handoff) vs eight (Design Brief § 6) [B R6; B Q8]. Combinations are possible (A notes "D plus E").
- Evidence/consequence: Delivery already owns WAIT_TRIGGER lanes and NEXT_DUE tracking but is bounded as "operational assurance only" and is blind to session-internal triggers [A § 5.1; D RAT-3]; Chief owns the sweep but "cannot be both the forgetter and the watchdog" and its CURRENT is 71k [A § 5.1]; Architect's 7/30-day cadence "cannot catch hour-scale drift" [A § 5.1; E § 3.3]; a registry "converts forgotten into visible on next activation" but creates no clock [A § 5.1]; external jobs "should not be the sole authoritative trigger clock" [Source: Chief handoff § "GLOBAL TRIGGER-COMPLETE DESIGN PRINCIPLE"]; "No new Auditor role" and CEO-COS-029 item 12 constrain new roles [E § 7.5; B R6]; undecided: "missed-run detection is impossible (no last-sweep timestamp) and the three overlapping trigger proposals stay unreconciled" [B R6]; every learning-wave trigger is trigger-incomplete while the detection-owner cell is empty [A § 2.7].
- Who decides: Architect (Item #8 A4 canonical intake/trigger/watchdog; A2 overlap; A5 placement) -> CEO -> Owner if a new role, external automation, cadence or reminder-slot cost is involved (Owner reserved this for Item #8) [A item 5; B R6; D RAT-3; E R-5].
- Raised by: A (5, Q1, § 5.1), B (R6, Q8-Q10, Q19), C (Q16, R7 owner cell), D (RAT-3, Q2), E (R-5, § 7.5, Q2).
- Depends on: Item #8 A2/A4/A5; RAT-018; RAT-019; RAT-009; RAT-024.
- Urgency: not assessed by drafts (B: registry is "P2 in a priority plan that is itself not ratified").

**RAT-018 — Which external clock mechanism, if any, provides the recurring sweep, and is any scheduled read-only sweep authorised?**
- Options: (A) ChatGPT scheduled task / reminder slot [Draft B R7 A]; (B) Agent Relay durable recurring job ("Backlog only, post-stabilization") [B R7 B]; (C) external cloud scheduled job (Claude/Codex) as executor, not sole clock [B R7 C; Draft E R-4 b "read-only notifier that writes one scan file, never executes"]; (D) Owner routine — the Owner opening a Chief or Delivery chat is the clock (status quo) [B R7 D; E R-4 a]; (E) executing automation [E R-4 c — E notes it conflicts with the Brain's "only an Owner-notification surface" rule].
- Evidence/consequence: D — every detection edge depends on an Owner activation; the Architect 7/30-day cadence is a policy without a clock [B R7]; C/B — new runtime and credential surface; missed runs must be catch-up detectable; Stage 0 "not the sole authoritative clock" warning [E R-4]; reminder-slot explosion warned against [A § 5.1].
- Who decides: Architect -> CEO -> Owner (tool/subscription/reminder-slot constraints and any new runtime are Owner-weighed) [B R7; E R-4].
- Raised by: B (R7, Q10), E (R-4, EFF-011), A (item 5 option E).
- Depends on: RAT-017; Item #8 A4.
- Urgency: not assessed by drafts.

**RAT-019 — Where does the Efficiency / System Optimization function sit, who detects its triggers, what cadence applies, and how does it relate to the parked "Director of Efficiency" idea?**
- Options: (A) extension of the Architect's Layer-2 structural audit [Draft A item 6 A; Draft E R-5 c "Architect only"]; (B) a separate shared function with its own scan indicator set and change-rate-aware cadence [A item 6 B]; (C) the parked executive "Director of Efficiency" role [A item 6 C]; (D) Delivery hosts event triggers, Architect hosts structural/cadence checks [E R-5 a]; (E) disposable cloud/Relay worker fed a pointer packet [E R-5 b]; cadence: reserved by the Owner to Item #8; Owner's "candidate daily while ecosystem is actively changing" carried as input only [E § 7.2].
- Evidence/consequence: A — no new function, but the Architect audits its own designs and 7-day latency misses hour-scale drift [A item 6; E R-5]; B — independence preserved, new function to trigger, Trigger Assurance dependency [A item 6]; C — resolves ownership in one place, but the Chief warned against conflating four efficiencies and A § 5.0 thresholds (measured workload) are unmet; the CEO disposition records the Owner's idea as "PARKED FOR FUTURE REVIEW" [A item 6; A § 5.2]; D — no new runtime, scope-creep risk for Delivery; E — lowest latency, runtime cost and the Stage 0 clock warning [E R-5]; P5 sequencing: stand up "after enough of the new architecture exists to measure" [A item 6; E § 7.4].
- Who decides: Architect (Item #8 A2/A5) -> CEO -> Owner (role/function decision; cadence reserved by the Owner) [A item 6; E R-5].
- Raised by: A (6, Q5), E (R-5, § 7, EFF-013..017), B (§ "Disagreements preserved" 9).
- Depends on: Item #8 A2/A5; RAT-017; P5 sequencing after P0A-P4 (proposed plan).
- Urgency: not assessed by drafts (P5 sequencing is from the PROPOSED priority plan).

**RAT-020 — Where is the Prompt + Context Engineering function placed and who owns its artifacts (manifest, stage packets, router)?**
- Options: (A) on-demand shared service on the Marketing-pilot pattern (Stage 0 proposal) [Draft A item 7 A; Draft D RAT-2 C "ownerless shared function"]; (B) specialist capability under the Architect with Delivery Assurance owning operational packet delivery (COS-CEO-N-021 item 6 question) [A item 7 B; D RAT-2 A]; (C) inside EODA [D RAT-2 B]; (D) merged with the Efficiency function [D RAT-2 D]; (E) keep HOLD until Items 5-8 complete (current state) [A item 7 C — see RAT-040].
- Evidence/consequence: A — admission gate, slot, engagement cap and exit review already have a worked template; no trigger detector [A item 7; D RAT-2]; B — fewer surfaces, concentrates design and context engineering in one chat; passive 7/30-day cadence [A item 7; D RAT-2]; C — operational fit, but EODA's boundary excludes architecture [D RAT-2]; D — one scan, risks conflating four "efficiency" meanings [D RAT-2].
- Who decides: Architect designs at Item #8 A5 / Stage 1; CEO ratifies (organizational fit); Owner lifts the HOLD first (RAT-040) [A item 7; D RAT-2].
- Raised by: A (7, Q4, § 5.3), D (RAT-2, Q1, Q5), B (§ 0.3), C (§ 4.20), E (EFF-027 held with N-023).
- Depends on: RAT-040; RAT-017 (trigger detection for T1-T9, D RAT-3 — merged in RAT-017); RAT-019; Item #8 A5.
- Urgency: not assessed by drafts (explicit HOLD).

**RAT-021 — What is the disposition of COS-CEO-N-021 (superseded by the checklist, or still open)?**
- Options: (A) close as ABSORBED into Checklist Items #1-#4 with a Response-To [Draft A item 9 A]; (B) keep OPEN until Item #8 and disposition items A-G explicitly [A item 9 B]; (C) treat the Owner addendum "Do not treat … as sent" as current and do nothing until a SENT_EVENT [A item 9 C].
- Evidence/consequence: A — removes an OPEN item whose content has moved, but the "organizational vs knowledge specialization" finding and items A-G need a new home; B — explicit dispositions; C — status quo [A item 9]. No Response-To exists in the Chief From-CEO mirror (grep confirmed).
- Who decides: CEO (mailbox item reconciliation is CEO-owned) [A item 9].
- Raised by: A (9, Q6).
- Depends on: none stated.
- Urgency: not assessed by drafts.

**RAT-022 — May the Chief's knowledge corpus contain whole-life domain modules, given the ratified metadata-first privacy rule?**
- Options: (A) routing metadata only [Draft A item 12 A]; (B) bounded domain modules for PRIORITY_VISIBLE domains with metadata-first content [A item 12 B]; (C) domain knowledge lives only in the domain's own root and the Chief's router points there [A item 12 C].
- Evidence/consequence: A — no sensitive content in Management; the Opportunity Sweep works from abstract metadata; B — richer sweep but Management holds knowledge the Brain says to leave at the source; C — pointer-first as the Brain's "Prefer pointers to the authoritative domain source over copied content" [A item 12; A § 2.5].
- Who decides: CEO -> Owner (privacy policy) [A item 12].
- Raised by: A (12, Q8).
- Depends on: AI_Management_Brain.md § "Selective whole-life Management inclusion" (RATIFIED).
- Urgency: not assessed by drafts.

**RAT-023 — Run, waive or archive the Chat Title Stability test, and close OWNER-MSA-001?**
- Options: (a) Owner runs the manual UI test [Draft E R-7 a; Draft C R11 test A "keep (still to run)"]; (b) Owner waives it and the CEO closes title-control mitigation as product-limited [E R-7 b; C R11 test B "archive (superseded)"]; (c) leave BLOCKED [E R-7 c].
- Evidence/consequence: (a) one Owner session of manual UI work then closure; (b) immediate closure, data never collected; (c) one permanently BLOCKED item in Architect To-CEO and in every sweep [E R-7]; the test file is 12,440 chars under a CURRENT name above target [C R11]. Source: CEO disposition "ACCEPTED / BOUNDED TEST AUTHORIZED" and test file "PREPARED / MANUAL UI EVIDENCE REQUIRED".
- Who decides: Owner (OWNER-MSA-001 is Class: OWNER_DECISION); CEO records the disposition; Architect for keep-vs-archive of the test file [E R-7; C R11].
- Raised by: E (R-7, EFF-018), C (R11, Q11).
- Depends on: none stated.
- Urgency: not assessed by drafts.

## Theme 3 — Routing and intake

**RAT-024 — What is the canonical meaning of "Chief inbox" and the sweep surface set, and is the single recurring Management intake/trigger sweep (EFF-012) Owner-directed or a Chief requirement awaiting disposition?**
- Options: (A) keep the seven-item Full Work Sweep and define "Chief inbox" as exactly that list [Draft B R1 A]; (B) the Owner's five-part definition — CEO mailbox + project intake surfaces + central lightweight/non-integrated intake + due trigger registry + Delivery state [B R1 B; Chief handoff § "ARCHITECTURE GAP …" item 7]; (C) B minus the new surfaces — a stricter reading of "relevant project Management interfaces" plus Owner Notifications [B R1 C]; EFF-012 status: (a) Owner confirms it as directed / (b) Owner declines or amends / (c) leave as a Chief requirement into Item #8 [Draft E R-14].
- Evidence/consequence: A — a repeat of the F-150 miss remains possible for any domain without a Management interface [B R1]; B/C — changes a ratified Global Brain sweep list and may create a new surface [B R1]; EFF-012 (a) becomes ACCEPTED_IN_PRINCIPLE input to Item #8, one sweep instead of per-project reminders; (b) per-project reminders persist; (c) ambiguity carried into Item #8 [E R-14]; the gap section carries an "Owner observation:" and a requirement list but no Owner disposition line (consistency report T8-c).
- Who decides: Architect designs (Item #8 A4) -> CEO ratifies -> Owner if Owner-facing behaviour changes [B R1]; Owner disposition for EFF-012 [E R-14].
- Raised by: B (R1, Q1, Q2), E (R-14, Q9, EFF-012), C (§ 3 row 3 four sweep enumerations), A (§ 1.3).
- Depends on: Item #8 A4; RAT-025; RAT-017.
- Urgency: not assessed by drafts.

**RAT-025 — Create one central Management-owned intake surface for non-integrated chats, and with what minimal field schema?**
- Options: (A) new central intake surface with the eight minimal fields [Draft B R2 A; Chief handoff gap items 4-5]; (B) extend the lightweight index with a project-writable intake section (rule change: today "not a project mailbox") [B R2 B]; (C) fold intake into the Trigger Assurance registry so there is one surface [B R2 C]; (D) no new surface — Owner Notifications remains the only Management-side obligation file [B R2 D].
- Evidence/consequence: A — conflicts with the ratified "one owner briefing surface" unless reconciled; needs a Global Brain delta so brains know where to write [B R2]; B — a rule change to the lightweight index; C — one surface; D — requirement 6 ("brains must say where to write") cannot be written, so chats keep inventing destinations [B R2].
- Who decides: Architect -> CEO [B R2].
- Raised by: B (R2, § "Disagreements preserved" 8), A (§ 1.12), E (EFF-012).
- Depends on: RAT-024; RAT-017; Item #8 A4.
- Urgency: not assessed by drafts.

**RAT-026 — Where is the cross-project PM identity gate enforced and what is the "canonical project identity" data structure (MSA-CEO-018)?**
- Options: (A) shared/global reusable identity-check contract referenced by every project [Draft B R3 A; MSA-CEO-018 item 8]; (B) long prose duplicated per project (disfavoured by the CEO) [B R3 B]; (C) A plus an L3 shared module (M-IDG / Diagram 7 M7, CANDIDATE) [B R3 C; Draft C § 7.3 M-IDG].
- Evidence/consequence: default today — gate enforced inside each PM chat by Brain obligation, no shared module; no negative test exists for the GO10 -> ULTUSB class [B R3]; the Brain already asks for a module rather than restatement while the CEO handoff restates it in full [C § 3 row 20].
- Who decides: Architect (already commissioned by MSA-CEO-018, OPEN) -> CEO [B R3].
- Raised by: B (R3, Q4), C (§ 4.21, row 20, M-IDG), D (RT-table), E (§ 5.3).
- Depends on: RAT-003 (module set).
- Urgency: not assessed by drafts (MSA-CEO-018 is OPEN).

**RAT-027 — Should Claude worker destinations have an identity check analogous to the PM gate?**
- Options: (A) extend the PM identity gate to Claude worker destinations (title + durable identity evidence) [Draft B R13 A]; (B) rely on the recipient's scope discipline (status quo) [B R13 B]; (C) require Delivery to hold NOT_READY / BLOCKED_DESTINATION_BINDING until the exact chat is durably proven (already applied once for CEO-OPS-009) [B R13 C].
- Evidence/consequence: binding relied on a chat title the corpus says is not a trusted identity signal; a misroute into the wrong Claude chat would be caught only by the recipient's own scope discipline [B Diagram 6 gap 6].
- Who decides: Architect -> CEO (extends the identity gate beyond PMs) [B R13].
- Raised by: B (R13, Q15).
- Depends on: RAT-026.
- Urgency: not assessed by drafts.

**RAT-028 — May any two consecutive roles in the execution-packet chain be collapsed, or a named fast path be defined for narrow tactical / in-scope / PM-vetted packets?**
- Options: (A) keep every role in a separate passive chat (status quo, 6-8 hops per packet) [Draft B R12 A; Draft E R-2 a "full CEO + Delivery chain for every execution packet"]; (B) allow Delivery verification inside the CEO turn for narrow tactical packets [B R12 B]; (C) allow the Chief to render directly from a CEO-verified packet when Delivery has nothing to add [B R12 C]; (D) named fast path for in-scope continuations and PM-vetted project packets, keeping Delivery's destination/duplicate check wherever a worker is the recipient [E R-2 b]; (E) PM-vetted project path only [E R-2 c].
- Evidence/consequence: A — hop cost stays at the evidenced level (B: eight chat switches for CEO-OPS-010, ~fourteen for the two-stage plan; E: ten Owner transport turns for Chain A, 19 activations + ~20 report-backs across the day — two counting rules, see consistency report T9); B/C — each weakens an independence the Brain ratified [B R12]; D — saves roughly 2 transport hops and 4 Drive writes per narrow packet at the risk the Owner's process correction guards against; two unnamed fast paths already ran (in-scope follow-up write at Chief handoff L1077; PRODUCT003 PM -> Delivery -> Owner) [E R-2; E § 2.4]; the verification hops "changed the outcome twice and returned no change four times" on one day [E § 2.4].
- Who decides: Owner (the full chain is an Owner-prompted process correction), then Architect design (Item #8 A2 overlap / A5), CEO [E R-2; B R12].
- Raised by: B (R12, Q13), E (R-2, EFF-009, § "Disagreements preserved" 1), D (D6, D12).
- Depends on: RAT-029; RAT-033; RAT-046.
- Urgency: not assessed by drafts.

**RAT-029 — Promote the six-step execution-packet chain, the "alters a running lane" test and in-scope completion repair into a written standard?**
- Options: (A) write the six steps into the Brain / Destination Contract as mandatory for any packet that alters a running lane [Draft B R10 A]; (B) keep as an Owner disposition in the Chief handoff (ACCEPTED_IN_PRINCIPLE, enforced by Chief discipline only) [B R10 B]; (C) A plus a written rule for in-scope remediation (Diagram 6 REP) [B R10 C].
- Evidence/consequence: B — the next "moved too quickly" event is caught only by the Owner [B R10]; the repair hop class is unnamed in the packet model [B Diagram 6 gap 3]; D records the collision between the process correction and "Owner must not be the continue button" (D6).
- Who decides: Architect -> CEO (would become a mandatory cross-role process) [B R10].
- Raised by: B (R10), D (D6, D12), E (§ 5.2).
- Depends on: RAT-028; RAT-046.
- Urgency: not assessed by drafts.

**RAT-030 — Which surface is written first when the Owner reports SENT in the Chief chat (Chief CURRENT vs Delivery CURRENT)?**
- Options: (A) the chat that receives the Owner event persists first and Delivery reconciles at next activation [Draft B R5 A]; (B) Delivery is the only writer of delivery truth and the Chief records only a pending event [B R5 B]; (C) both persist independently and the precedence ladder resolves reads (de facto today) [B R5 C].
- Evidence/consequence: C — the two ledgers diverge between activations and stale READY prompts can survive, as happened for CEO-OPS-011 [B R5].
- Who decides: Architect -> CEO adjudication (cross-role conflict) [B R5].
- Raised by: B (R5, Q7), C (§ 4.26 ownership drift), E (§ 4.3 CEO-OPS-010 on six surfaces).
- Depends on: RAT-008.
- Urgency: not assessed by drafts.

**RAT-031 — Ratify the Owner's packet preferences (platform/app + exact chat; recommended model + effort/mode; deliberate model selection; copyable prompt blocks) into the Owner Activation Destination Contract / Brain?**
- Options: (A) add all four fields to the Contract [Draft B R11 A; Draft C R3 A]; (B) add platform + chat only (identity) and leave model/effort to Delivery packet construction [B R11 B]; (C) leave as Owner preference in the Chief handoff / Chief-Delivery practice [B R11 C; C R3 B]; (D) decline [C R3 C]; writer: CEO adds the rules vs Architect adds them under an MSA-CEO-016-style delegation vs leave as dated handoff blocks [Draft E R-10].
- Evidence/consequence: A — Brain contract grows by three lines; packets already comply [C R3]; B — identity fields only; C — contract and practice diverge indefinitely; operating de facto via CEO-OPS-012 item 7 [B R11; C R3]; D — packets must be stripped against stated Owner preference [C R3]; E — preferences re-read only by the Chief and at risk in the next compaction, with the Owner re-asked [E R-10].
- Who decides: CEO (Global Brain and Brain sections are ratified content) [B R11; C R3]; or Architect under delegation [E R-10].
- Raised by: B (R11, Q14), C (R3, Q7), E (R-10, EFF-032), D (§ 7.2, QW2), A (quick win 4).
- Depends on: RAT-003 (M-ACT if adopted).
- Urgency: not assessed by drafts.

**RAT-032 — Which executive roles are authorized From_Management writers for project inboxes, and may the Chief write directly into project From_Management inboxes?**
- Options: (A) CEO only [Draft B R17 A; Draft E R-9 b "all executive writes go via CEO"]; (B) CEO plus Architect within delegated scope [B R17 B]; (C) CEO, Architect and Chief for routing-only items [B R17 C]; (D) any executive role with a stable ID and a delegation record [B R17 D]; (E) Chief may write for Owner-originated items [E R-9 a]; (F) Chief may write with a CEO notification via Chief To-CEO [E R-9 c].
- Evidence/consequence: the Standard names a class ("explicitly authorized executive-management authority or higher-level PM/Control Room"), not a role set [B R17; Source: AI_Project_Management_Interface_Standard.md § "3."]; the Chief wrote into project inboxes five times on 2026-09-30 [E Q5]; (E) saves one CEO hop per project item but two executive writers per inbox; (A) +1 Owner activation per item, single writer; (F) traceability with one extra write [E R-9].
- Who decides: Architect proposes (Interface Standard writer rule; Item #8 A1/A5) -> CEO ratifies [B R17; E R-9].
- Raised by: B (R17, Q18), E (R-9, Q5, EFF-026).
- Depends on: Item #8 A1/A5.
- Urgency: not assessed by drafts.

**RAT-033 — May an Owner return hop be dropped by deriving SENT from recipient durable evidence at the next activation instead of explicit Owner confirmation?**
- Options: (A) keep Owner-reported SENT mandatory (status quo) [Draft B R18 A]; (B) allow SENT to be derived from recipient durable evidence at the next Chief/Delivery activation [B R18 B]; (C) B for Claude-worker destinations only [B R18 C].
- Evidence/consequence: A — half the hops in Diagram 6 remain returns that carry activation, not information [B R18; B Diagram 6 gap 2]; B/C — changes the ratified "same handling turn" SENT_EVENT rule and the Destination Contract completion condition; interacts with the 24-hour READY staleness rule, duplicate suppression and RAT-030 [B R18]; E's observation: the report-back is practised for wake-up, not proof [E § 2.4].
- Who decides: Architect -> CEO (changes a ratified Global Brain / Brain rule) [B R18].
- Raised by: B (R18, Q21, § "Disagreements preserved" 11), E (§ 2.4).
- Depends on: RAT-030; RAT-017 (a sweep would be the alternative wake-up).
- Urgency: not assessed by drafts.

**RAT-034 — Does "Preserve these authorities/boundaries" in CEO-OPS-011 / CEO-OPS-013 require the COS-CEO-N-023 HOLD line to be repeated inside worker packets?**
- Options: (a) "preserve" = repeat verbatim in every packet [Draft E R-13 a]; (b) "preserve" = do not violate; no repetition needed [E R-13 b]; (c) CEO issues a packet-template rule [E R-13 c].
- Evidence/consequence: (a) ~25 restatements persist; (b) EFF-019(b) becomes a writer quick win; (c) one-time Architect/CEO work, then (b) [E R-13]; the identical sentence occurs in 11 files / 25 lines [C § 3 row 25; E § 3.4].
- Who decides: CEO (interpretation of its own directives) [E R-13].
- Raised by: E (R-13, Q10, EFF-019(b)), C (row 25).
- Depends on: RAT-009.
- Urgency: not assessed by drafts.

**RAT-035 — Which surface is authoritative for MGMT-NOTIF-001 and similar dormant obligations (Owner Notifications file vs Delivery's dormant trigger-bound index), has the fired 2026-09-29 trigger been evaluated, and what is the disposition of the old AgentRelay Integration Prompt?**
- Options: surface — (A) Owner Notifications file authoritative, Delivery's index mirrors it / (B) Delivery's index authoritative, file is display / (C) fold both into the trigger registry [Draft B R16]; Integration Prompt — (a) RESOLVED / SUPERSEDED by the pointer-first standard, prompt archived, notification closed / (b) keep live and revise to pointer-first / (c) route as a question to the CEO [Draft D RAT-14]; keep until MGMT-NOTIF-001 is reassessed vs archive as consumed/overtaken [Draft C R11 prompt half].
- Evidence/consequence: the file shows MGMT-NOTIF-002 OPEN after CEO-COS-016 ordered its compaction, so it is already stale [B R16; C § 4.4; E § 3.2]; the CEO and EODA re-affirmed MGMT-NOTIF-001 "live / TRIGGER_BOUND" while the Owner-approved pointer-first standard contradicts the prompt's content [D U11, D10]; its purpose may already be met by Response-To: MGMT-AR-MAINT-001 (unverifiable without project files) [E Q3].
- Who decides: Chief and Delivery reconcile -> CEO (surface named in Project Instructions and CEO Bootstrap; retiring it is a structure change) [B R16]; Chief (notification owner) -> CEO for the prompt [D RAT-14; C R11].
- Raised by: B (R16, Q3), C (R11, Q9), D (RAT-14, U11), E (Q3, EFF-004).
- Depends on: RAT-017 (registry); RAT-009.
- Urgency: not assessed by drafts.

**RAT-036 — Retire or redefine the Owner Brief file?**
- Options: (a) keep the file and refresh it with AS_OF / FRESHNESS_STATE as CEO-COS-029 directed [Draft E R-8 a]; (b) render the brief on demand from Chief CURRENT and retire the file [E R-8 b]; (c) keep it with AS_OF plus a fail-visible staleness rule [E R-8 c].
- Evidence/consequence: (a) one more Chief write per material event; (b) one surface fewer, breaks "One owner briefing surface" unless redefined; (c) status quo plus honesty about staleness [E R-8]; the Brief lags the Chief handoff by three checklist items and carries no AS_OF [B § "Source gaps" 5; C § 4.3].
- Who decides: CEO (Brain principle "One owner briefing surface") [E R-8].
- Raised by: E (R-8, EFF-022, § "Disagreements preserved" 5), C (§ 4.3, 4.14), B (Diagram 5 gap 3).
- Depends on: none stated.
- Urgency: not assessed by drafts.

## Theme 4 — Reliability thresholds and measurement

**RAT-037 — Are the ratified-by-reference MSA-CEO-015 details binding and where are they published: the 15-minute runtime re-check, the mailbox containment thresholds (>40,000 chars / >50 closed / >60% resolved), the Owner-evidence-does-not-replace-PM-acceptance caveat, the K state sequence, the "does not outrank" sentence, and the A-D artifact class labels?**
- Options: (A) transcribe each into the Brain / Standard [Draft B R8 A; Draft E R-1 a "publish the §A thresholds into Management Brain / Current Structure"]; (B) retire them explicitly as non-binding proposal detail [B R8 B; E R-1 b "leave as an Architect proposal"]; (C) declare that a mailbox entry ratified "without modification" is enforceable as written, so no transcription is needed [B R8 C]; (D) ratify different numbers [E R-1 c]; sub-question: a minimum-volume guard on the >60% criterion [Draft C Q15].
- Evidence/consequence: A — EFF-002 executable now on all three triggers; six mailboxes (395k chars) affected [E R-1]; B — mailboxes keep growing (2.8x the proposed limit today), only the >60% trigger usable [E R-1]; C — a rule that lives only in a To-CEO entry may be unknown to roles whose launch prompts omit it [B R8]; the thresholds exist only inside the 112,881-char Architect mailbox [C § 4.22].
- Who decides: Architect proposes text -> CEO ratifies (Global Brain and Brain edits; the ratification record) [B R8; E R-1].
- Raised by: B (R8, Q11, gap 1), C (§ 4.22, row 11, Q15), E (R-1, Q1, EFF-002), A (§ 4 matrix M-SHARED items).
- Depends on: RAT-015; RAT-003 (M-RC1 / M-LIFE).
- Urgency: not assessed by drafts (E: "executable now" if (a)).

**RAT-038 — Resolve the Reliability Contract token/field divergences in one text: DELIVERED as a lane state or a transition label; DELEGATED_IN_FLIGHT vs IN_FLIGHT; nine-step vs five-step precedence; SCOPE_UNKNOWN and SENT_EVENT_UNBOUND tokens; the resumption-packet field set; packet sub-states; a transition matrix.**
- Options: lane set — (A) the Brain's seven are canonical, DELIVERED is a transition marker, Delivery LP edited [Draft A item 11 A; Draft B R4 B; Draft C R2 lane A]; (B) Delivery's eight are canonical, Brain / Global Brain / Current Structure / Chief LP edited [A item 11 B; B R4 A; C R2 lane B]; (C) leave as is and let the shared module list all three vocabularies [A item 11 C]; token — confirm DELEGATED_IN_FLIGHT per ratified MSA-CEO-015 and correct the Global Brain line (confirm-only) vs ratify IN_FLIGHT as an alias [C R2]; precedence — Delivery LP points to the full nine-step ladder vs ratify the five-step abbreviation as Delivery's scope [C R2; C Q6]; new tokens — ratify into the contract vs strike from the Delivery LP [C R2]; sub-states — formalize READY_FOR_CEO_REVIEW etc. as sub-states vs leave role-level; matrix — write entry/exit rules for DO_NOT_DISTURB, SENT_EVENT_UNBOUND, BLOCKED_SCOPE return vs declare implementation detail [B R4].
- Evidence/consequence: lane A — one role file changes; lane B — three or four ratified documents gain a state; C — preserves text, perpetuates drift [A item 11; C R2]; token A — one Global Brain line changes [C R2]; no decision — "three ratified/role-owned files keep disagreeing and a router cannot key on a single vocabulary" [C R2]; roughly a third of Diagram 3a is inferred and tagged CANDIDATE for want of a matrix [B gap 11].
- Who decides: Architect proposes -> CEO ratifies (standard change; the IN_FLIGHT wording also sits in the CEO-authored MSA-CEO-016) [A item 11; B R4; C R2].
- Raised by: A (11, Q10), B (R4, Q5, Q6), C (R2, Q5, Q6, § 4.2, 4.12, 4.13).
- Depends on: RAT-003 (M-RC1 needs one list).
- Urgency: not assessed by drafts.

**RAT-039 — Is a Claude lane recovery handoff an "operational CURRENT / restart-state surface" under the ratified anti-bloat contract, and how is PM next-touch adoption routed?**
- Options: (a) confirm — QD2's inherited numbers apply with no new rule [Draft D RAT-13 a]; (b) classify as project-local needing explicit adoption via next-touch activation [D RAT-13 b]; (c) exempt [D RAT-13 c].
- Evidence/consequence: the ratified scope sentence already covers project chats; (c) lets lane handoffs bloat (E5-class risk) [D RAT-13; D U5].
- Who decides: Architect confirms the classification; PMs adopt via next-touch activation per the Current Structure migration policy [D RAT-13].
- Raised by: D (RAT-13, U5).
- Depends on: RAT-002; RAT-045.
- Urgency: not assessed by drafts.

## Theme 5 — Stage-1 Prompt + Context Engineering specifics

**RAT-040 — Keep or lift the Stage-1 routing HOLD on COS-CEO-N-023, and may the Stage-1 research draft reach the Architect before Item #8?**
- Options: (a) keep the hold and archive the draft as evidence until Item #8 [Draft D RAT-1 a]; (b) keep the hold but pass the draft as input now [D RAT-1 b]; (c) lift the hold [D RAT-1 c; Draft A item 7 "C is the current state"].
- Evidence/consequence: (a) the Architect sees it only at Item #8; (b) risk of pre-empting Item #8; (c) contradicts the Design Brief disposition — Owner-only [D RAT-1]; the HOLD is an Owner disposition recorded in the Design Brief, the Chief handoff and the N-023 Owner correction, not a ratified standard [A item 7].
- Who decides: Owner (sequencing), via Chief -> CEO [D RAT-1; A item 7].
- Raised by: D (RAT-1, U10, D1), A (7, § 0), B (§ 0.3), C (§ 4.20), E (§ "Disagreements preserved" 3).
- Depends on: Items 5-8 complete; RAT-016.
- Urgency: not assessed by drafts (explicit HOLD).

**RAT-041 — Do Claude cloud sessions count as "ChatGPT-side curation"?**
- Options: (a) yes — "ChatGPT-side" means any non-scarce, non-executing capacity [Draft D RAT-4 a]; (b) no — this document class is itself a tension and cloud curation stops [D RAT-4 b]; (c) yes only while separate credit lasts (to 2026-11-04), a time-bound rule needing a dated trigger [D RAT-4 c].
- Evidence/consequence: Stage 0 says "ChatGPT project specialists, not scarce external agents" curate; the Design Brief says "Claude usage should not be spent maintaining its own context architecture"; the Owner/Chief used cloud credit for prompt/context research [D D5, AP-15].
- Who decides: Owner intent; CEO [D RAT-4].
- Raised by: D (RAT-4, U6, Q3).
- Depends on: RAT-040.
- Urgency: not assessed by drafts (credit expiry 2026-11-04 is a dated fact in the sources).

**RAT-042 — Adopt, trim or reject the master-manifest and stage-packet schemas (D § 4.1-4.2) as the artifact model?**
- Options: (a) adopt as the pilot's CANDIDATE baseline [Draft D RAT-5 a]; (b) adopt only the seven Stage 0 per-stage fields and defer the header [D RAT-5 b]; (c) reject and let the Architect re-derive [D RAT-5 c].
- Evidence/consequence: (a) M10 becomes measurable; (b) header questions move to RAT-043/RAT-039; (c) § 4 becomes evidence only [D RAT-5]; the related recovery-handoff template (ten CEO-OPS-010 fields + header + four Stage 0 preservation items) and launch-packet template are in D § 7.1-7.2.
- Who decides: Architect; CEO if any part becomes a mandatory standard ("artifact model" is a Stage 1 output) [D RAT-5].
- Raised by: D (RAT-5).
- Depends on: RAT-040; RAT-020.
- Urgency: not assessed by drafts.

**RAT-043 — Where does a lane manifest live?**
- Options: (a) project-local file under the project's durable state [Draft D RAT-6 a]; (b) a section of the L2 handoff [D RAT-6 b]; (c) an EODA-folder packet file [D RAT-6 c]; (d) transient inside each packet [D RAT-6 d].
- Evidence/consequence: (a) Management loses direct visibility; (b) future-stage pointers are loaded as text; (c) needs its own lifecycle rule; (d) duplication across packets; it must not become a fourth project mailbox [D § 4.4].
- Who decides: Architect; project PM for project-local placement; CEO for any Management-folder lifecycle rule [D RAT-6].
- Raised by: D (RAT-6, Q1).
- Depends on: RAT-042; RAT-010.
- Urgency: not assessed by drafts.

**RAT-044 — Adopt the gate semantics: acceptance-evidence classes AC-1..9, REVIEW_REQUIRED triggers RR-1..11, STOP_ON_EXCEPTION criteria SX-1..10?**
- Options: (a) adopt only the RATIFIED / OWNER-grounded rows, dropping CANDIDATE rows (AC-3, AC-8, RR-10/11, SX-8) [Draft D RAT-7 a]; (b) adopt all as pilot-only gate semantics [D RAT-7 b]; (c) replace with the Architect's own [D RAT-7 c].
- Evidence/consequence: (a) smallest change; (b) testable in the pilot, not a standard; (c) § 5 becomes evidence only [D RAT-7]; the two Stage 0 texts word the gate classes differently (D11).
- Who decides: Architect (design); CEO (standard); PM (project-local adoption) [D RAT-7].
- Raised by: D (RAT-7, D11).
- Depends on: RAT-040; RAT-049.
- Urgency: not assessed by drafts.

**RAT-045 — Which, if any, quantitative thresholds QD1-QD10 (launch packet size, handoff size, startup read budget, context fraction, tool-call count, elapsed time, stages per session, handoff cadence, maximum age, usage-per-progress) enter a pilot?**
- Options: (a) instrument all ten in the pilot [Draft D RAT-8 a]; (b) adopt none and rely on the named signals S1-S8 [D RAT-8 b]; (c) adopt only QD2, which reuses the ratified CURRENT numbers [D RAT-8 c].
- Evidence/consequence: every number is UNVERIFIED; the Owner asked for "a bounded pilot/eval before globalizing a fixed refresh cadence"; a per-session threshold does not protect a shared provider pool [D RAT-8; D § 6.2].
- Who decides: Architect designs the pilot measurement; CEO ratifies the pilot; Owner for anything that spends quota [D RAT-8].
- Raised by: D (RAT-8, U1, U7).
- Depends on: RAT-040; RAT-048; RAT-002 (role-side budgets are a different object).
- Urgency: not assessed by drafts.

**RAT-046 — May a pre-verified per-lane rotation packet be re-sent without a new CEO decision (rotation activation contract)?**
- Options: (a) pre-verified per-lane template, re-validated by EODA on each SENT_EVENT [Draft D RAT-9 a]; (b) full cycle every time [D RAT-9 b]; (c) surface-dependent rule [D RAT-9 c].
- Evidence/consequence: (a) fewer CEO decisions, a change of practice; (b) matches the process correction but the Owner becomes the continue button; (c) added complexity [D RAT-9]; rotation on the Claude app surface always costs at least one Owner send because Drive mailboxes do not wake chats [D § 6.4].
- Who decides: CEO (changes the Destination Contract's application); Owner [D RAT-9].
- Raised by: D (RAT-9, Q7, D6).
- Depends on: RAT-028; RAT-029.
- Urgency: not assessed by drafts.

**RAT-047 — Who independently evaluates that a compacted handoff preserved intent, under "No new Auditor role is authorized"?**
- Options: (A) EODA [Draft D RAT-10 A]; (B) Architect [D RAT-10 B]; (C) project PM [D RAT-10 C]; (D) a separate model session [D RAT-10 D].
- Evidence/consequence: (A) extends bounded checks, no architecture judgement; (B) independent but 7/30-day cadence; (C) Relay has no PM (RAT-048); (D) spends capacity and a durable form would collide with the Auditor-role rule [D RAT-10]; no evaluation step exists today for the over-compression failure mode [D § 2.2].
- Who decides: Architect; CEO [D RAT-10].
- Raised by: D (RAT-10, Q4, U2).
- Depends on: RAT-017; RAT-040.
- Urgency: not assessed by drafts.

**RAT-048 — May a Relay pilot proceed before a Relay PM / Control Room exists?**
- Options: (a) wait for a Relay PM (after P1/P0C) [Draft D RAT-11 a]; (b) proceed with the CEO as interim acceptance authority [D RAT-11 b]; (c) start with ULTUSB instead [D RAT-11 c].
- Evidence/consequence: (b) conflicts with "Do not centralize implementation authority in Chief, CEO, or another management role"; (c) conflicts with "Second candidate after Relay evidence" [D RAT-11]; the Registry records "Authority: PM / Control Room NOT YET ESTABLISHED" (D U4, settled by source).
- Who decides: CEO (sequencing); Relay authority of record; Owner (P0/P1 ordering) [D RAT-11].
- Raised by: D (RAT-11, U4).
- Depends on: RAT-040; P0C/P1 of the proposed plan.
- Urgency: not assessed by drafts.

**RAT-049 — Which success-criteria list is canonical for Prompt + Context Engineering: the Requirements' ten or the Design Brief's nine?**
- Options: (a) the Requirements' ten — the pilot gains M10 (durable restartability) [Draft D RAT-15 a]; (b) the Brief's nine — the pilot cannot claim restartability [D RAT-15 b]; (c) the Chief reconciles both files first [D RAT-15 c].
- Evidence/consequence: source check confirms the Design Brief § "10." omits "durable restartability after every bounded work stage" (Requirements item 10); both documents are Owner-approved [D D4].
- Who decides: Chief with Owner (Stage 0 authors) [D RAT-15].
- Raised by: D (RAT-15, U9, D4).
- Depends on: RAT-050.
- Urgency: not assessed by drafts.

**RAT-050 — Which Stage 0 document is authoritative, is the Requirements file's "STAGE 1 READY FOR ARCHITECT DESIGN" status line corrected, and are the two files merged or re-labelled?**
- Options: (A) Owner confirms the Design Brief governs and the Requirements status line is corrected (archive-over-delete) [Draft B R15 A; Draft C R9 A]; (B) Owner confirms the Requirements file governs (would contradict the HOLD) [B R15 B; C R9 B]; (C) add a one-line pointer to the HOLD on the Requirements file without altering the Owner-approved status text [B R15 C — B also lists this as a CANDIDATE quick win, which Draft E disputes; see QW-024]; (D) merge into one document [C R9 C; Draft E R-11 b "merge after Item #8"]; (E) re-label the Requirements file as deep source now (status line only) [E R-11 a]; (F) leave both [E R-11 c].
- Evidence/consequence: the later COS-CEO-N-023 block (Chief-authored, carrying the Owner disposition "APPROVED TO PROCEED") names the Design Brief as "Authoritative Stage 0 brief", the earlier block cited the Requirements file, and the Chief handoff names the Design Brief [B § "Source gaps" 2; E EFF-006; consistency report T17]; A — matches five CURRENT surfaces and the later timestamp; B — lifts the HOLD recorded in the Chief handoff / Owner Brief; D — an Owner-frozen text is rewritten; E — touches an Item #4 artefact under hold; F — two documents claiming authority in the read set [C R9; E R-11]; default — HOLD governs by freshness and the misleading status line persists [B R15].
- Who decides: Owner (via Chief) — both documents record Owner dispositions; Chief proposes, CEO confirms the file handling [B R15; C R9; E R-11].
- Raised by: B (R15, Q17), C (R9, Q8, § 4.20), E (R-11, Q4, EFF-006), D (D2), A (§ "Disagreements preserved" 1).
- Depends on: RAT-040; Item #4 hold.
- Urgency: not assessed by drafts.

---

## Quick wins the drafts say need no ratification — file owner decides (QW-###; proposal only, nothing executed)

Each row: owner the drafts name; what; raised by; conditions the drafts attach. Draft C conditions every Chief item on first confirming the scope of the Owner's read-only instruction recorded at Chief handoff line 605 (C Unresolved question 17); that condition is carried here on QW-001 to QW-004, QW-021 and QW-023.

- **QW-001** Chief — add the AS_OF / FRESHNESS_STATE / ROUTING_AUTHORITY header to the Chief handoff and archive-first compact it under the ratified thresholds and the Checklist #5 preservation guard. Raised by B (quick win 1; R9 pointer), C (quick win 7), D (QW3), E (EFF-001). Conditions: C's caveat (Q17); C notes it "will not hold without R6" (RAT-008); E "expect regrowth until EFF-010 is decided" (RAT-008); the Owner wants checklist items handled one at a time (D QW3).
- **QW-002** Chief — compact AI_Management_Owner_Notifications_Current.md (MGMT-NOTIF-002 -> RESOLVED with Response-To: CEO-OPS-008; reassess MGMT-NOTIF-001) as CEO-COS-016 already directed. Raised by C (quick win 5), E (EFF-004), D (QW4 reconciliation of MGMT-NOTIF-001 against the pointer-first standard). Conditions: C caveat; the NOTIF-001 outcome may be RESOLVED/SUPERSEDED or a routed question (RAT-035).
- **QW-003** Chief — refresh AI_Management_Owner_Brief_Current.md and add AS_OF / FRESHNESS_STATE / display-only line. Raised by C (quick win 6), E (EFF-022 first half). Conditions: C caveat; retirement of the file is RAT-036.
- **QW-004** Chief — update statuses of COS-CEO-N-006 … N-020 in Chief To-CEO from the CEO's responses. Raised by C (quick win 8), E (EFF-023). Conditions: C caveat.
- **QW-005** CEO — fix the two split sentences in AI_Ecosystem_Project_Registry.md and AI_Management_Current_Structure.md. Raised by C (quick win 1), E (EFF-005).
- **QW-006** CEO — in Current Structure: date-stamp or remove "CURRENT as of 2026-09-26"; replace the Agent Relay WAIT_TRIGGER operational note with a pointer to lane state; move the two archived-file lines into an archive-pointer paragraph; add missing root files to the durable-state list. Raised by C (quick win 2), E (EFF-025 text de-duplication). Conditions: extending § "Authority" is RAT-013, not a quick win (C).
- **QW-007** CEO — in Management Brain: correct the stale lightweight-index sentence; add a date to "Version: CEO-ACTIVE-1". Raised by C (quick win 3), E (EFF-025), A (§ "Disagreements preserved" 9 hand-off), B (gap 10).
- **QW-008** CEO — close answered directives in the three CEO-owned inboxes using the ratified closure vocabulary; reconcile the CEO Execution Checklist boxes for MSA-CEO-012/-013/-014. Raised by C (quick win 9), E (EFF-023, EFF-008). Conditions: archive-vs-compact of the checklist itself is RAT-014.
- **QW-009** Architect — in Architecture Current and the Architect handoff: update or remove "MGMT-AR-MAINT-001 = WAIT_TRIGGER". Raised by C (quick win 4), D (D7). Conditions: the Global Brain header is NOT a quick win (RAT-012 option C) (C).
- **QW-010** Portfolio Planner / Architect — add the ratified header trio to the Portfolio handoff, Capacity Current, Lightweight Portfolio, Architect handoff and Architecture Current. Raised by C (quick win 10).
- **QW-011** Delivery Assurance — archive the consumed packets (CEO-OPS-010, -012, PRODUCT003 and the fourth consumed packet) with their stable IDs; keep the three READY ULTUSB packets. Raised by C (quick win 11), E (EFF-007).
- **QW-012** Delivery Assurance — include platform, exact chat title, model and effort lines in Claude-destined packets as CEO-OPS-012 item 7 already required, so the Chief does not add them at rendering time; recognise the existing practice as the seed of a destination-registry module. Raised by B (quick win 3), A (quick win 4), D (§ 7.2). Conditions: ratifying the fields into the Contract is RAT-031.
- **QW-013** EODA — packet template additions within EODA's packet ownership: an "Environment precondition" line (how the read-first pointer is reachable) and "write durable files with a file-write tool, not a shell heredoc". Raised by D (QW1).
- **QW-014** EODA — ledger fields recording recommended model/effort/mode and the Owner's actual choice separately on SENT_EVENT. Raised by D (QW2).
- **QW-015** EODA — DONE_EVENT capture of "files read at startup" when a recipient handoff reports it, so a startup-cost baseline accrues before any pilot. Raised by D (QW5).
- **QW-016** Architect — add to the next structural audit rows: Chief handoff size and Owner Brief header (INV-CURRENT / INV-FRESH), archive placement, the lightweight-index wording conflict; use Draft A's § 0 size table as a measured INV-CURRENT baseline (recomputing in Google Docs characters if the manifest is not staged). Raised by B (quick win 4), A (quick win 3).
- **QW-017** Research staging only — stage Draft A § 3 unchanged as `AI_Management_External_Reference_Index_Draft.md` (DRAFT name; no role told to read it) and apply the § 2.6 metadata header to new staging documents. Raised by A (quick wins 1-2).
- **QW-018** Mailbox owners (Chief, Architect, Delivery for To-CEO; CEO for From-CEO) — archive resolved mailbox traffic on the >60%-resolved trigger only, until RAT-037 settles whether the 40k / 50-item triggers bind. Raised by E (EFF-002). Conditions: C R12 (RAT-015) asks whether one index format is ratified first — disagreement on sequencing preserved.
- **QW-019** Each writer — stop writer-originated HOLD / P0 / authority restatements in responses and packets (EFF-019(a)); boundary lines a From-CEO directive asked Delivery to preserve are RAT-034. Raised by E (EFF-019(a)), C (§ 3 row 25).
- **QW-020** Chief / CEO — mark the Shared Marketing & Communications pilot dormant. Raised by E (EFF-021).
- **QW-021** Chief — pointer-replace Brain-rule duplicates inside the Chief handoff, archive-first, together with QW-001. Raised by E (EFF-024). Conditions: C caveat; whether duplicated rule text falls inside the Checklist #5 preservation guard is read one way by E (CANDIDATE: it does not) and left for Chief/Architect to confirm (E § "Disagreements preserved" 10).
- **QW-022** CEO — normalise the CEO-OPS-010 directive format. Raised by E (EFF-031).
- **QW-023** Chief — record where the two Chief handoff archives live (filename, Drive ID, folder) so a later archive index starts complete; relocating them is RAT-010, not a quick win. Raised by C (quick win 12). Conditions: C caveat.
- **QW-024** Chief — add a one-line pointer on the Stage 0 Requirements file to the Design Brief HOLD without altering the Owner-approved status line. Raised by B (quick win 2, CANDIDATE). **Disputed:** Draft E (EFF-006, R-11) holds this is NOT a quick win because both files sit under the Owner's Item #4 hold and no edit should precede Item #8; Draft C treats the status line as RAT-050 and does not address a pointer. Listed with the disagreement preserved; see RAT-050 option C.

---

## Counts

Ratification register rows: **50** (RAT-001 … RAT-050) — Theme 1 context architecture and documentation: 16; Theme 2 roles and functions: 7; Theme 3 routing and intake: 13; Theme 4 reliability thresholds and measurement: 3; Theme 5 Stage-1 Prompt + Context specifics: 11.
Quick-win rows: **24** (QW-001 … QW-024), of which 1 is disputed between drafts (QW-024) and 6 carry Draft C's Owner-instruction condition.
Decider summary (primary level named by the drafts): Owner-level or Owner-involved rows: RAT-001, 002, 003, 007, 012, 017, 018, 019, 020, 022, 023, 024, 028, 040, 041, 045, 046, 048, 049, 050 (20); CEO-level without Owner: RAT-006, 008, 009, 010, 011, 013, 014, 015, 021, 025, 026, 027, 029, 030, 031, 032, 033, 034, 035, 036, 037, 038, 042, 044, 047 (25); Architect-level gating others: RAT-004, 005, 016, 039, 043 (5). These are the drafts' allocations, reproduced, not this register's judgement.
Source lists fully absorbed: A items 1-12 (12/12); B R1-R18 (18/18; R9 recorded as QW-001 pointer as B itself specifies); C R1-R15 (15/15); D RAT-1..15 (15/15; D RAT-3 merged into RAT-017, D RAT-12 into RAT-001); E R-1..R-14 (14/14).
