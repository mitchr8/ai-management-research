# AI Management — Executive Startup Context Baseline (Draft)
Status: RESEARCH DRAFT / STAGING ONLY / NOT AUTHORITATIVE — a measured baseline and a pilot proposal; it sets no budget and changes no file.
Purpose: give Item #8 section A3 and register row RAT-002 (size budgets and character measure) a per-role startup-context baseline derived from the existing provenance manifest and the existing research measurements, state what the numbers can and cannot support, and say what should be measured empirically before any budget is fixed.
Prepared: 2026-10-01, Claude cloud research session (bounded worker). Inputs: SOURCES_MANIFEST.md (clean character and paragraph counts, sha256, modified times, as mirrored 2026-09-30/10-01); Draft A § 0; Draft C §§ 2, 3, 5, 7.2; Draft E §§ 3.1–3.4, 4.5, EFF-003/-024/-028/-029/-030; Draft D §§ 6.1–6.2 (QD3) and QW5; Consistency Report T1, T10; the READ FIRST / Read / RESTART lists in the four launch prompts, the CEO bootstrap, the Project Instructions and the four role handoffs (re-read from the mirrors to confirm the file lists). No new source mirroring.
Labels: FACT (measured), CURRENT RULE (ratified or Owner-accepted text), CANDIDATE (this document's reading or arithmetic), DECISION REQUIRED (register row).

## 0. Measurement caveats — read before the numbers
1. Characters are "clean chars": the Drive text export after unescaping and blank-line normalisation, recorded in SOURCES_MANIFEST.md. Google Docs' own character count is lower; the one paired observation is the Chief handoff, which the Chief measured at about 49k document characters pre-compaction where the mirror method gives 71,454 for the current file (different versions, so not a clean ratio) [Draft A § 0; Report § 3]. Every threshold comparison below holds under either measure. Which measure counts is itself a sub-question of RAT-002.
2. Two inclusion methods exist for AI_Management_Project_Instructions.txt (2,325 chars): Draft C includes it in every role row because ChatGPT injects Project Instructions into every chat of the Project; Drafts A and E exclude it (except E's CEO row), because only the Chief launch prompt states that the role runs "inside the dedicated AI Management ChatGPT Project" and the inclusion for the other roles is an inference from folder placement (Consistency Report T1). Both totals are shown; the difference is always 2,325.
3. Token figures are estimates, not measurements. No source and no draft contains a measured token count for any Management file on any platform. The drafts use chars ÷ 4; structured text dense in stable IDs, underscores and headings tokenises less efficiently, so a second figure at chars ÷ 3.5 is shown as an upper band. ChatGPT and Claude tokenisers differ; the four executive roles run as ChatGPT chats and the figures are therefore only indicative of relative weight. Nothing here should be quoted as "N tokens" without the word "approximately".
4. "Required startup files" means the literal READ FIRST / Read / RESTART list of the role's launch prompt, bootstrap or handoff, plus the launch prompt itself when the role is activated by it, plus the role's own handoff where its HANDOFF MODE requires it. From-CEO mailboxes are listed where a launch prompt or handoff names them; otherwise they appear as a separate "conditional, de facto required" row, because the passive-inbox rule means a role must read its inbox to learn of directives [Draft A § 0]. Whether a chat actually reads everything it is told to read is not observable from the sources (see § 4).
5. The counts are of instructed reading. They say nothing about what a ChatGPT chat retains, re-reads or truncates; the Reliability Contract itself is restated in several of these files, so the unique information content is smaller than the character count (see § 2 duplication notes).

## 1. Shared kernel (FACT)
| Kernel definition | Files | Clean chars | Paragraphs | ≈ tokens (÷4 … ÷3.5) |
|---|---|---|---|---|
| Common to all five roles: Project Instructions + Global Brain + Management Brain | 3 | 73,185 | 675 | 18,300 … 20,900 |
| Four governance files read by every executive role: Global Brain 40,841 + Management Brain 30,019 + Current Structure 17,658 + Interface Standard 14,833 | 4 | 103,351 | 1,108 | 25,800 … 29,500 |
| The four plus Project Instructions | 5 | 105,676 | 1,147 | 26,400 … 30,200 |

Composition of the kernel (FACT, from Draft C § 2 finding 3): of the Global Brain's 40,841 chars, the seven dated Management sections total 17,985 (44%), rising to 24,388 (60%) if four borderline headings are counted as Management-related; the remainder, 16,453–22,856 (40–56%), is generic chat and ecosystem behaviour read by every ecosystem chat, not only Management. Of the Management Brain's 30,019, the Reliability Contract v1 section is 7,203 and the identity gate 1,541, leaving 21,275 of other content. The Interface Standard's operative sections for the Chief are about 5,600 of its 14,833; the rest is project-PM instruction [Draft E § 4.5]. CURRENT RULE: the Global Brain is ecosystem-wide and Management may not modularise it on its own authority (RAT-012, Owner-level); the ratified CURRENT thresholds (target <= 12,000 chars / <= 150 paragraphs; compaction > 15,000 / > 200; hard fail-visible > 25,000 / > 300) apply to operational CURRENT and restart surfaces, not to Class A authority documents or to read stacks [Source: AI_Global_Brain.md § "Compact CURRENT / fail-visible stale state"; Draft C § 2].

## 2. Per-role baseline
Each role: required files with size and class (ALWAYS = named in the role's READ FIRST/Read/RESTART list or the activation prompt itself; HANDOFF = the role's own restart surface under HANDOFF MODE; CONDITIONAL = not in the list but required de facto by the mailbox/passive-inbox contract or by a sweep rule), totals under both inclusion methods, largest contributors, duplication, and the pointer-first reduction opportunity (CANDIDATE arithmetic on options that already exist in the register; not a prediction and not a budget).

### 2.1 CEO / Executive Control Room
Required files (Bootstrap "Read:" list, 2026-09-26) [Source: AI_Management_CEO_Bootstrap_Prompt.md § "Read:"]:
| File | Chars | Class |
|---|---|---|
| AI_Global_Brain.md | 40,841 | ALWAYS |
| AI_Management_Brain.md | 30,019 | ALWAYS |
| AI_Management_Current_Structure.md | 17,658 | ALWAYS |
| AI_Ecosystem_Project_Registry.md | 7,612 | ALWAYS |
| AI_Project_Management_Interface_Standard.md | 14,833 | ALWAYS |
| AI_Management_Owner_Notifications_Current.md | 2,288 | ALWAYS |
| "AI Frontier Lab Portfolio/lifecycle/graduation state" | not on disk | ALWAYS (outside the Management read set) |
| AI_Management_CEO_Bootstrap_Prompt.md (the prompt itself) | 2,028 | ALWAYS |
| AI_Management_Handoff_Current.txt (CEO handoff) | 4,646 | HANDOFF |
| AI_Management_Project_Instructions.txt | 2,325 | ALWAYS under method C; excluded under A/E |
| AI_Management_CEO_Execution_Checklist_Current.md | 7,448 | CONDITIONAL (its own rule: one temporary checklist per initiative) |
| The eight executive mailboxes (four To-CEO it reconciles, four From-CEO it owns) | 409,888 | CONDITIONAL, de facto: the CEO cannot process a Chief item without the Chief pair (Draft E: + 135,158 for one Chief item) |

Totals (FACT): Bootstrap list + prompt + handoff 119,925 (122,250 with Project Instructions) ≈ 30,000 … 34,900 tokens. The handoff's own RESTART RULE ("Read Global Brain, Management Brain, this handoff, then only current executive/project Management evidence relevant to the triggering event" [Source: AI_Management_Handoff_Current.txt § "RESTART RULE"]) is a different and leaner list: 75,506 (77,831 with Project Instructions) ≈ 18,900 … 22,200 tokens. The two CEO lists disagree by about 40k characters and the later, leaner one is the RESTART RULE [Draft C § 2 finding 5]. Practical operating surface if the CEO reconciles all eight mailboxes: 487,719 ≈ 121,900 … 139,300 tokens [Draft C § 2].
Largest contributors (Bootstrap list): Global Brain 34.1%, Management Brain 25.0%, Current Structure 14.7%; kernel share 86%. Under the RESTART RULE the two Brains are 94% of the read.
Duplication (FACT): the Reliability Contract appears in the Global Brain, the Management Brain and Current Structure (three of the CEO's always-read files) [Draft E § 3.2; Draft C § 3 rows 1–2, 9–12]; the three-file interface is restated in eight files including the Brain twice and the Bootstrap [Draft C § 3 row 16]; the Bootstrap's "First mission" appears complete yet it remains the startup prompt (EFF-030, inference, no source states completion); Owner Notifications is stale (one item RESOLVED elsewhere, one fired) [Draft C § 4.4].
Pointer-first opportunity (CANDIDATE): the CEO already has a pointer-first list in its handoff; honouring the RESTART RULE instead of the Bootstrap list saves about 44k chars with no file change. The dominant CEO lever is not its read list but the mailboxes it must reconcile: six active mailboxes total 395,634, all over at least one containment trigger, with zero mailbox archives [Draft E § 4.4]; archiving closed traffic (QW-018 on the >60% trigger; RAT-015/037 for the size triggers) is where the CEO's practical surface shrinks. Register rows: RAT-014 (archive or compact the checklist and bootstrap), RAT-015, RAT-037, RAT-012 (Global Brain, Owner).

### 2.2 Chief of Staff / Owner Briefing
Required files (launch prompt READ FIRST 1–7) [Source: AI_Management_Chief_of_Staff_Launch_Prompt.md § "READ FIRST"]:
| File | Chars | Class |
|---|---|---|
| AI_Global_Brain.md | 40,841 | ALWAYS |
| AI_Management_Brain.md | 30,019 | ALWAYS |
| AI_Management_Current_Structure.md | 17,658 | ALWAYS |
| AI_Management_Chief_of_Staff_Handoff_Current.txt | 71,454 | ALWAYS (READ FIRST item 4) and HANDOFF |
| AI_Project_Management_Interface_Standard.md | 14,833 | ALWAYS |
| AI_Management_Lightweight_Portfolio_Current.md | 7,095 | ALWAYS |
| AI_Management_Owner_Notifications_Current.md | 2,288 | ALWAYS |
| AI_Management_Chief_of_Staff_Launch_Prompt.md (itself) | 7,221 | ALWAYS |
| AI_Management_Project_Instructions.txt | 2,325 | ALWAYS under method C (the only role whose prompt states the Project placement) |
| AI_Management_Chief_of_Staff_From_CEO_Current.md | 57,855 | CONDITIONAL, de facto always: Full Work Sweep item 2 and the passive-inbox rule |
| AI_Management_Chief_of_Staff_To_CEO_Current.md | 77,303 | CONDITIONAL: own open items; sweep item 2 |
| The other six executive mailboxes, Delivery state, project interfaces, portfolio evidence | about 416k | CONDITIONAL: the Full Work Sweep as written (sweep total about 610k) |
| AI_Management_Owner_Brief_Current.md | 1,225 | written, not read (display-only) |

Totals (FACT): READ FIRST + launch prompt 191,409 (193,734 with Project Instructions) ≈ 47,900 … 55,400 tokens; with the From-CEO inbox 249,264; with both Chief mailboxes 326,567 ≈ 81,600 … 93,300; the Full Work Sweep as written about 610,327 ≈ 152,600 … 174,400 [Draft A § 0; Draft C § 2; Draft E § 3.1]. The rehydration before the launch prompt is read is 184,188 [Draft E § 3.2]. Two fresh Chief chats were opened on 2026-09-29 alone [Draft E § 3.1].
Largest contributors: the Chief handoff 37.3%, Global Brain 21.3%, Management Brain 15.7%; kernel share 54% (the only role where its own restart surface, not the kernel, is the largest item).
Duplication (FACT): the Reliability Contract is read at least four times in this one set (Global Brain, Management Brain, Current Structure, Chief launch prompt) and a fifth time in the handoff's own "RELIABILITY CONTRACT" and "DELIVERY / EVENT SEMANTICS" sections, about 2,000 chars of ratified rule text already in the Brain [Draft E § 3.2, EFF-024]; the handoff is 2.86x the hard fail-visible threshold and about 49% of it is one day's event chain [Draft E § 3.2; Draft C § 4.11]; the Lightweight Portfolio's always-read value "is a few lines, and one of those lines is currently wrong" (header/update contradiction on LW-HANDYMAN-001) [Draft E § 3.2]; Owner Notifications is stale [Draft C § 4.4]; the Interface Standard's Chief-operative content is about 5,600 of 14,833 [Draft E § 4.5].
Pointer-first opportunity (CANDIDATE arithmetic; each step is an existing register or quick-win option, none decided):
| Scenario | What changes (register row) | Chief READ FIRST total | Reduction |
|---|---|---|---|
| S0 today | — | 191,409 | — |
| S1 Chief-owned levers only | handoff compacted to the 12,000 target (QW-001, conditioned; regrowth expected until RAT-008); launch prompt to a <= 4,000 kernel plus pointer (RAT-002/RAT-006; EFF-003) | about 128,700 | about 33% |
| S2 plus Management-owned kernel modularisation | Management Brain to an L1 core of about 8,000 (Draft C's CANDIDATE L1 budget; RAT-003); Current Structure to pointer-first authority/structure of about 6,000 (Draft C § 7.2); Interface Standard read via its operative sections (about 5,600) through a router (RAT-001/003) | about 85,800 | about 55% |
| S3 plus a Global Brain split (Owner-level) | Global Brain generic rules only (16,453–22,856) with Management sections moved to the Management L1 (RAT-012) | about 67,800 | about 65% |
These are sums of candidate numbers, not forecasts; the mailbox surface (another 135k for the two Chief mailboxes) is addressed separately by containment (RAT-015/037, QW-018) and by the event ledger question (RAT-008), which the drafts identify as the structural cause of regrowth.

### 2.3 Management Systems Architect
Required files (launch prompt READ FIRST 1–5 plus HANDOFF MODE) [Source: AI_Management_Systems_Architect_Launch_Prompt.md § "READ FIRST"; AI_Management_Systems_Architect_Handoff_Current.txt § "RESTART"]:
| File | Chars | Class |
|---|---|---|
| AI_Global_Brain.md | 40,841 | ALWAYS (both lists) |
| AI_Management_Brain.md | 30,019 | ALWAYS (both lists) |
| AI_Management_Current_Structure.md | 17,658 | ALWAYS (launch prompt list only) |
| AI_Project_Management_Interface_Standard.md | 14,833 | ALWAYS (launch prompt list only) |
| AI_Management_Systems_Architecture_Current.md | 7,080 | ALWAYS (launch prompt list only) |
| AI_Management_Systems_Architect_Launch_Prompt.md (itself) | 4,445 | ALWAYS |
| AI_Management_Systems_Architect_Handoff_Current.txt | 3,423 | HANDOFF (RESTART step 4) |
| AI_Management_Systems_Architect_From_CEO_Current.md | 92,290 | ALWAYS under the handoff RESTART (step 3); CONDITIONAL under the launch prompt |
| AI_Management_Project_Instructions.txt | 2,325 | method C only |
| AI_Management_Systems_Architect_To_CEO_Current.md | 112,881 | CONDITIONAL: own outbox (write side; read for Response-To history) |

Totals (FACT): launch-prompt set + prompt + handoff 118,299 (120,624 with Project Instructions) ≈ 29,600 … 34,500 tokens; handoff RESTART set 166,573 (168,898) ≈ 41,600 … 48,300; union of both lists 210,589 (212,914) ≈ 52,600 … 60,800 [Draft A § 0; Draft C § 2].
Largest contributors (union): Architect From-CEO 43.8%, Global Brain 19.4%, Management Brain 14.3%; kernel share 49% of the union, 87% of the launch-prompt set.
Duplication (FACT): the two Architect lists disagree on four files (Current Structure, Interface Standard, Architecture Current versus From-CEO); Architecture Current deliberately points to rather than restates the CEO-owned contract sections but restates the Architect-owned parts (INV list, cadence) [Consistency Report T10]; the From-CEO mailbox is 2.3x the proposed 40k containment limit with 14 OPEN labels against one genuinely open directive (MSA-CEO-018) [Draft E § 4.4; Draft C § 4.16]; the three ratified-by-reference details and the A–D class labels live only in the 112,881-char To-CEO mailbox [Draft C § 4.22].
Pointer-first opportunity (CANDIDATE): the dominant lever is mailbox containment, not the read list — bringing From-CEO under 40k (archive closed items to an index; RAT-015/037; QW-018 on the >60% trigger) would take the union from about 210,600 to about 158,300 (−25%); adding the S2 kernel modularisation gives about 115,400 (−45%). Reconciling the two restart lists into one router is RAT-006/RAT-001 territory and costs nothing in content.

### 2.4 Executive Operations & Delivery Assurance
Required files (launch prompt READ FIRST 1–7) [Source: AI_Management_Executive_Operations_Delivery_Assurance_Launch_Prompt.md § "READ FIRST"]:
| File | Chars | Class |
|---|---|---|
| AI_Global_Brain.md | 40,841 | ALWAYS |
| AI_Management_Brain.md | 30,019 | ALWAYS |
| AI_Management_Current_Structure.md | 17,658 | ALWAYS |
| AI_Project_Management_Interface_Standard.md | 14,833 | ALWAYS |
| AI_Management_Executive_Delivery_Current.md | 6,705 | ALWAYS (role CURRENT) |
| AI_Management_Executive_Operations_From_CEO_Current.md | 28,182 | ALWAYS (READ FIRST item 6 — the only role whose list names its inbox) |
| AI_Management_Executive_Operations_Handoff_Current.txt | 2,884 | ALWAYS (item 7 "This role handoff") |
| AI_Management_Executive_Operations_Delivery_Assurance_Launch_Prompt.md (itself) | 9,327 | ALWAYS — the largest launch prompt |
| AI_Management_Project_Instructions.txt | 2,325 | method C only |
| AI_Management_Executive_Operations_To_CEO_Current.md | 27,123 | CONDITIONAL: own outbox |
| The seven packet files it owns (CEO-OPS-010/011/012, PRODUCT003, three NOIDLE) | 19,858 | CONDITIONAL: read when a lane is touched |

Totals (FACT): 150,449 (152,774 with Project Instructions) ≈ 37,600 … 43,600 tokens [Draft A § 0; Draft C § 2; Draft E § 3.1].
Largest contributors: Global Brain 27.1%, Management Brain 20.0%, Executive Operations From-CEO 18.7%; kernel share 69%.
Duplication (FACT): the Delivery launch prompt "restates most of the contract" and is the file whose restatement diverges most from the Brain (eight lane states including DELIVERED; five-step precedence; SCOPE_UNKNOWN and SENT_EVENT_UNBOUND tokens; a superset resumption field list) [Draft C § 3 rows 9, 10, 12, 27; § 5 rank 14]; it is also the only role file with a testable rubric (eleven INV-* invariants) and functions as a de facto domain module [Draft A § 1.6]; the From-CEO inbox is 100% answered but 0% closed by header (11/11 CEO-OPS labelled OPEN with COMPLETE responses) [Draft E § 4.4; Draft C § 5 rank 8].
Pointer-first opportunity (CANDIDATE): compacting the From-CEO inbox to OPEN items plus an index (QW-008 for the CEO's labels; QW-018 on the >60% trigger) and reducing the launch prompt to a kernel plus a pointer to one contract module (EFF-003; RAT-003/038) would give about 121,900 (−19%); with the S2 kernel modularisation about 79,000 (−47%). Because this launch prompt is the only place the eleven invariants are written as a rubric, Draft C's module map would make it (or an M-RC1 extract) the module other roles point to, not a file to shrink blindly (RAT-038 must settle the eight-versus-seven states first).

### 2.5 Portfolio & Capacity Planner
Required files (launch prompt READ FIRST 1–8 plus handoff) [Source: AI_Management_Portfolio_Capacity_Planner_Launch_Prompt.md § "READ FIRST"; AI_Management_Portfolio_Capacity_Planner_Handoff_Current.txt § "EXACT RESUME POINT"]:
| File | Chars | Class |
|---|---|---|
| AI_Global_Brain.md | 40,841 | ALWAYS |
| AI_Management_Brain.md | 30,019 | ALWAYS |
| AI_Management_Current_Structure.md | 17,658 | ALWAYS |
| AI_Ecosystem_Project_Registry.md | 7,612 | ALWAYS |
| AI_Project_Management_Interface_Standard.md | 14,833 | ALWAYS |
| AI_Management_Owner_Notifications_Current.md | 2,288 | ALWAYS |
| AI_Management_Portfolio_Capacity_Current.md | 13,978 | ALWAYS (role CURRENT; above the 12,000 target, below the compaction line) |
| AI_Management_Portfolio_Capacity_Planner_From_CEO_Current.md | 9,452 | ALWAYS (READ FIRST item 8) |
| AI_Management_Portfolio_Capacity_Planner_Launch_Prompt.md (itself) | 6,124 | ALWAYS |
| AI_Management_Portfolio_Capacity_Planner_Handoff_Current.txt | 4,751 | HANDOFF |
| AI_Management_Project_Instructions.txt | 2,325 | method C only |
| Project Executive Status surfaces | not in the Management read set | CONDITIONAL: "Re-read only the affected project/domain Management evidence" |

Totals (FACT): 147,556 (149,881 with Project Instructions) ≈ 36,900 … 42,800 tokens. The handoff's EXACT RESUME POINT ("Read From-CEO mailbox first … Re-read only the affected project/domain Management evidence") is 28,181 (30,506 with Project Instructions) ≈ 7,000 … 8,700 tokens — the only role instruction that already behaves like an L0 router [Draft C § 2 finding 4]. The role has been dormant since 2026-09-28 (last From-CEO modification 2026-09-28T18:45) with one deferred item (CEO-PORT-003) [Draft A § 1.5; Draft E EFF-028].
Largest contributors (launch-prompt list): Global Brain 27.7%, Management Brain 20.3%, Current Structure 12.0%; kernel share 70%. In the resume-point list: Capacity Current 49.6%, From-CEO 33.5%.
Duplication (FACT): the tier / A-band model and tie-break list are restated in eleven files, three of them in the Planner's own set (Brain, Current Structure, Capacity Current) with a numbered variant in Capacity Current that diverges in wording [Draft C § 3 row 18]; the Registry text is physically fragmented [Draft C § 4.6]; Capacity Current still lists "CEO disposition of CAP-CEO-002" as a pending trigger although it was accepted [Draft A § 1.5]; the Planner launch prompt predates the Reliability Contract and does not restate it, so a rewrite should add the contract pointer rather than a restatement [Draft E EFF-028].
Pointer-first opportunity (CANDIDATE): the Planner is the cleanest demonstration case — its own handoff already specifies a 30k resume set against a 148k launch set (an 80% difference between the two instructions for the same role). Making the launch prompt point to the EXACT RESUME POINT for a dormant role (EFF-028; RAT-006) requires no new module. Launch-prompt ownership is stated in no source (Draft A unresolved question 2), so even this needs a named owner (CEO assumed by Draft E).

## 3. Cross-role summary (FACT; CANDIDATE where marked)
| Role | Instructed startup set (chars, method A/E) | With Project Instructions (method C) | ≈ tokens (÷4 … ÷3.5) | Kernel share | Largest single item | Role's leaner in-house list, if any |
|---|---|---|---|---|---|---|
| CEO | 119,925 | 122,250 | 30,000 … 34,900 | 86% | Global Brain 34% | RESTART RULE 75,506 |
| Chief of Staff | 191,409 | 193,734 | 47,900 … 55,400 | 54% | own handoff 37% (71,454) | none; the handoff is the problem surface |
| Architect | 118,299 (launch) / 210,589 (union) | 120,624 / 212,914 | 29,600 … 60,800 | 87% / 49% | From-CEO 44% of the union | two lists that disagree |
| Delivery Assurance | 150,449 | 152,774 | 37,600 … 43,600 | 69% | Global Brain 27%; From-CEO 19% | none |
| Portfolio Planner | 147,556 | 149,881 | 36,900 … 42,800 | 70% | Global Brain 28% | EXACT RESUME POINT 28,181 |

Observations (CANDIDATE readings of the facts):
1. For four of five roles the shared kernel is 69–87% of the instructed read, so no role-level change can take a fresh session much below about 105k until the kernel itself is modularised (RAT-001/002/003; Global Brain part is RAT-012, Owner-level). For the Chief the order is reversed: its own handoff is the first lever.
2. Three roles already carry a leaner list written by the role itself (CEO RESTART RULE; Planner EXACT RESUME POINT; the Architect's handoff RESTART). These are working pointer-first precedents and the cheapest evidence that the pattern is accepted in practice.
3. The Reliability Contract is the single largest duplicated element in every set (two to five copies per role) and every launch-prompt copy diverges from the Brain (Consistency Report T10; Draft C § 3), so a single contract text (RAT-038) and a contract module (RAT-003) remove both characters and drift.
4. Mailboxes, not governance text, dominate the practical surface for the CEO, the Architect and the Chief; containment (RAT-015/037; QW-018) is the largest lever that needs no architecture decision beyond whether the MSA-CEO-015 thresholds bind.
5. Every always-read total is an order of magnitude above the 12,000-character CURRENT target; the target applies to single restart surfaces, so this is the quantitative case for Checklist #3/#6, not a contract breach [Draft C § 2 finding 1; Report F1].

## 4. What should be measured empirically before a budget is fixed (CANDIDATE list; none exists today)
1. Actual tokens per file per platform. No measured token count exists for any Management file on ChatGPT or Claude. A one-time measurement of the 44 live files with the platform's own counter (or an API token count where available) would replace the ÷4 convention; the ratio is likely to differ between prose (Global Brain) and ID-dense text (mailboxes).
2. Files actually read versus files instructed. QW-015 (capture "files read at startup" when a recipient handoff reports it, on DONE_EVENT) and Draft E's EFI-STARTUP indicator are the existing proposals; for ChatGPT roles the only observable is what the chat reports having read, which is weak evidence and should be labelled as such.
3. Google Docs characters versus clean mirror characters for the same version of the same file. One paired reading per file class (Brain, handoff, mailbox) would settle RAT-002's measure sub-question; today the only pair compares different versions of the Chief handoff.
4. Rehydration frequency and cost. Fresh-chat resets per role per day (two Chief resets on 2026-09-29 are the only datum), with the startup set size at each reset.
5. Regrowth rate of restart surfaces after compaction. The Chief handoff regrew to 71k within about six hours of the 2026-09-30 compaction and changed 26 times that day [Draft E EFF-016; Draft C § 4.11]; a write counter or modifiedTime series per CURRENT surface would show whether compaction alone can hold a budget without an event ledger (RAT-008).
6. Unique-content ratio. The share of each always-read set that is restatement of another file in the same set; Draft C's 28-rule table gives the qualitative map, but a quantitative figure needs the Architect's module cut (RAT-003).
7. Time to first productive action and Owner corrections per fresh session, as the behavioural counterpart of the size numbers (Stage 0 success criteria 1, 3, 5).
8. For Claude lanes separately: Draft D's QD3 "startup read budget <= 40,000 characters" is UNVERIFIED and concerns lane packets, a different object from role startup sets; it should be measured in the Relay pilot, not inferred from this baseline (RAT-045).

## 5. What a useful before/after pilot would look like (CANDIDATE design; Architect to accept, change or reject; CEO ratifies any pilot; Owner for quota)
- Candidate subjects, in increasing order of risk and value: (a) the Portfolio Planner — dormant, with an in-house 30k resume list already written; the intervention is a launch-prompt pointer to the EXACT RESUME POINT plus a contract pointer (EFF-028); lowest risk, cleanest control, lowest value. (b) The Architect — intervention is mailbox containment of From-CEO to OPEN items plus an index (QW-018) and one reconciled restart list; medium risk (a 92k file is archived, archive-first), high value for the Item #8 reviewer's own startup. (c) The Chief — intervention is QW-001 (archive-first compaction to target, header trio) plus EFF-024 (pointer-replace Brain duplicates) with the Checklist #5 guard and a migration ledger; highest value, highest risk, and conditioned on the scope of the 2026-09-30 read-only instruction (Draft C Q17) and on RAT-008 for regrowth.
- Baseline before any change: the per-role tables above (instructed set), plus measurements 1–5 of § 4 for the subject role over a defined window of activations.
- Intervention rules: same CURRENT file IDs; archive-first with the archive ID recorded before any removal; every removed passage gets a migration-ledger row (source file, section, archive ID, pointer target), which is the mechanical form of the Owner's preservation guard [Draft C § 7.6 steps 1, 6; § 8]; no canonical text is rewritten beyond the subject role's own files without the file owner's action; nothing is globalised.
- Measures after: instructed startup characters and, where observable, tokens; files actually read; time to first productive action; Owner corrections per session; missed-obligation count (for the Chief: Full Work Sweep misses); header-trio compliance; regrowth after N activations; and a retrieval test — can the role answer a question whose evidence was moved behind a pointer (Stage 0 criterion 2, "no loss of unique Owner/project intent")?
- Acceptance: Stage 0 success criteria 1 (materially smaller startup/resume context), 2 (no loss of intent), 3 (restart reliability), 4 (fewer repeated/contradictory instructions) and 9 (no excessive bureaucracy), measured, not asserted; the pilot does not set a global budget — it produces the measured set from which RAT-002 option E ("per-role budgets set by the Architect at P4 from measured startup sets") could be exercised.
- Decision mapping: RAT-002 (budgets and measure), RAT-006 (launch prompt versus ROLE CORE), RAT-015/037 (containment), QW-001/QW-018/EFF-028 (interventions), RAT-008 (regrowth cause), RAT-045 (Claude-lane thresholds, separate pilot).

## 6. Support for RAT-002 and the Item #8 context-budget discussion
What this baseline can support: the order of magnitude (every executive startup set is 118k–211k clean chars; the kernel alone is 103k); the ranking of levers per role (kernel for four roles, own handoff for the Chief, mailboxes for CEO/Architect/Chief); the existence of three in-house pointer-first precedents; the fact that the drafts' CANDIDATE budgets (CORE <= 4,000; ROUTER 2,000–3,000; MODULE <= 8,000; L1 <= 8,000; bundle <= 20,000) are far below today's sets and would need the S2-class kernel change to be reachable.
What it cannot support: any token figure as a measurement; any claim about what a chat actually reads or retains; a choice between the drafts' budget options; a Global Docs-versus-mirror conversion factor; a budget for Claude lanes (different object, RAT-045).
Options this baseline informs (listed, not chosen): RAT-002 (A) Draft A's numbers; (B) Draft C's numbers; (C) apply 12k/15k/25k to Class A documents — would put the Global Brain (40,841) and Management Brain (30,019) at immediate hard fail; (D) no numeric budgets; (E) per-role budgets from measured startup sets at P4 — the option this baseline and the § 5 pilot are designed to feed. Measure sub-question: clean mirror versus Google Docs characters.
DECISION REQUIRED: RAT-002 (Architect proposes -> CEO ratifies -> Owner for kernel size); RAT-001 and RAT-038 gate it; RAT-012 for the Global Brain share.

## 7. Unresolved and uncertain
- Whether Project Instructions are injected for the non-Chief roles (inference from folder placement; 2,325 chars per role).
- Launch-prompt ownership (no source), which gates every launch-prompt change.
- The Google Docs-to-mirror character ratio (one unpaired observation).
- Whether the 2026-09-30 read-only inbox instruction was one-off or standing (gates the Chief pilot option).
- Whether the MSA-CEO-015 containment thresholds bind today (gates the mailbox levers at the 40k/50-item triggers; the >60% trigger is usable either way).
- No draft measured the CEO Execution Checklist or the packet files as part of any startup set; they are shown as CONDITIONAL from their own rules.

## 8. Sources
SOURCES_MANIFEST.md (clean_chars and clean_paragraphs for all 44 live files; Drive IDs); the four launch prompts, the CEO bootstrap, the Project Instructions and the four role handoffs (READ FIRST / Read / RESTART / EXACT RESUME POINT lists); AI_Global_Brain.md § "Compact CURRENT / fail-visible stale state"; Draft A § 0 and § 1.5–1.6; Draft C §§ 2, 3, 4.4, 4.6, 4.11, 4.16, 4.22, 5, 7.2, 7.6, 8; Draft E §§ 3.1–3.4, 4.4, 4.5, 6 (EFF-003, -016, -024, -028, -029, -030); Draft D §§ 6.1–6.2, QW5; Ratification Register rows RAT-001, 002, 003, 006, 008, 012, 014, 015, 037, 038, 045; Consistency Report T1, T10.
