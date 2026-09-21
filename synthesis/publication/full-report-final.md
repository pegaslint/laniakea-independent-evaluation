# Independent Validator-Led Snapshot Evaluation of Laniakea and Its Relationship to Sky Atlas, STL, and Deployed Infrastructure

**Documentary, governance, implementation, and Mainnet evidence review — 2026 snapshot**

> Selected-claim snapshot evaluation led by an independent human validator; scope is non-exhaustive and does not constitute a security audit or implementation certification.

* Evaluation snapshot: 2026
* Technical/evidence anchor: 8064df6464967ab53a46c07b82f210a069f655e3
* Canonical publication assembly based on frozen report lineage through: 27c5f9575093fd066d16b5982bd021a984ba88f3
* Ethereum Mainnet observations are fixed historical observation points as described in the report; they are not continuous or publication-time monitoring.

## Contents

- [1. Executive Summary](#1-executive-summary)
- [2. Scope, Baseline and Methodology](#2-scope-baseline-and-methodology)
- [3. Laniakea Snapshot Characterization](#3-laniakea-snapshot-characterization)
- [4. Relationship to Sky Atlas](#4-relationship-to-sky-atlas)
- [5. Relationship to STL](#5-relationship-to-stl)
- [6. Implementation and Mainnet Grounding](#6-implementation-and-mainnet-grounding)
- [7. Unresolved Provenance — C06](#7-unresolved-provenance-c06)
- [8. Unverified and Target Architecture](#8-unverified-and-target-architecture)
- [9. Limitations and Future Work](#9-limitations-and-future-work)
- [10. Principal Synthesis Findings](#10-principal-synthesis-findings)
- [11. Overall Synthesis](#11-overall-synthesis)
- [Appendix A — Baseline Manifest](#appendix-a--baseline-manifest)
- [Appendix B — Evaluation Methodology](#appendix-b--evaluation-methodology)
- [Appendix C — L0–L3F Phase Ledger](#appendix-c--l0l3f-phase-ledger)
- [Appendix D — Atlas Binding Ledger](#appendix-d--atlas-binding-ledger)
- [Appendix E — STL / Provenance Ledger](#appendix-e--stl--provenance-ledger)
- [Appendix F — C05 Case Study](#appendix-f--c05-case-study)
- [Appendix G — C06 Unresolved Provenance](#appendix-g--c06-unresolved-provenance)
- [Appendix H — Unverified / Out-of-Scope / Deferred Claims](#appendix-h--unverified--out-of-scope--deferred-claims)
- [Appendix I — Evidence / Checksum Index](#appendix-i--evidence--checksum-index)
- [Appendix J — Terminology Crosswalk](#appendix-j--terminology-crosswalk)

## Evidence-note convention

Evidence notes appear at the end of major sections and appendices. They identify the frozen repository paths and retained evidence supporting the section in which they appear. These notes provide traceability; they are not independent endorsements of the underlying claims. Numbering is local: S1–S11 identify main-report sections, and A–J identify appendices. Each note retains its existing path and any accompanying description or qualification. Appendix I provides the detailed artifact and checksum index, while Appendix J supplies terminology and status definitions. Exact source paths are intentionally retained for reproducibility and should be read in their stated repository context.

## 1. Executive Summary

This independent, human-validator-led evaluation examined selected Laniakea claims against Sky Atlas, STL, implementation sources and deployed Ethereum Mainnet infrastructure. It provides differentiated, claim-specific conclusions from a non-exhaustive frozen snapshot: established documentary relationships, one strongly grounded legacy implementation/deployment case, partial or unresolved governance relationships, unverified current assertions and substantial future design. Its scope is neither a security audit nor implementation-completeness or runtime certification, and its conclusions do not constitute a blanket endorsement or rejection.

The snapshot combines legacy/current descriptions, operational assertions, historical and illustrative material, proposed architecture and ambiguous or conflicting passages. The 53 selected statement units overlap and are not 53 independent propositions. A future target is not missing current implementation; an explicit present-state assertion is not shielded by nearby draft or future labels. These distinctions make the scoped proposition, rather than the entire corpus, the appropriate unit of evaluation.

Laniakea's scoped legacy Mainnet PAU description is materially grounded in implemented and historically deployed Sky/Spark infrastructure.

This C05 result connects the documentary claim to identified implementation source, inspected historical revisions and behavior, then to deployed Mainnet components, wiring, roles, grants and representative configuration. Bounded usage evidence and two fixed Mainnet observations provide further support. Those June and September observations establish tested state at those points, not publication-time conditions or a complete operational history.

Specific attribution of the RateLimits events to the tested MainnetController remains **NOT ESTABLISHED**. Exact source/runtime bytecode equivalence and continuous June→September operation also remain **NOT ESTABLISHED**. All-layer PAU deployment is outside C05; comprehensive security/integration certification is outside scope. C05 is **CLOSED for its scoped Report v1 conclusion**, and exact bytecode reproduction remains optional assurance. This is a substantive grounding result for one defined proposition, not proof of all PAU, Laniakea or target architecture.

The Atlas relationship varies by proposition. C01 establishes documentary witnesses for selected operational-data categories, not deployment, address correctness, runtime use or completeness. C02/C03's exact authority and hierarchy mappings remain **NOT ESTABLISHED**. C04 is **PARTIALLY ESTABLISHED** within the shared Prime scope: some fee-policy dimensions are supported, material policy mechanics differ, and some details remain unestablished. Payment realization is a separate operational question. These documentary relationships do not amount to total equivalence. Laniakea prose is not itself current Sky governance authority, and Atlas policy text is distinct from enactment, execution, approval or payment.

STL supplied useful registry, reference, observer and evidence-discovery material, while the frozen initial result for both C05 and C06 remains **NO MATCHED STL COVERAGE ESTABLISHED**, meaning the evaluated STL evidence did not establish an implementation-source match for either claim. Separate provenance later identified C05's implementation source, enabling static and Mainnet evaluation. The evaluated evidence for C06 did not identify a sufficiently specific legacy source, so static/chain verification did not proceed. STL is a useful evidence layer, not a universal implementation-provenance requirement; an absent match establishes neither STL deficiency nor implementation nonexistence.

The corpus was often sufficiently traceable for substantive evaluation, supported by source-located inventories and local temporal qualifications. Its canonicality and status remain uneven: missing or unclear canonical destinations, broken navigation, stale or ambiguous material and source-authority uncertainty coexist with usable evidence paths. X1 records a documentary conflict without establishing actual operation or selecting a documentary winner. These are documentary and evidence-selection issues; they do not automatically establish code or security defects, implementation failure or runtime failure.

Unresolved evidence limits broader current-state conclusions. C06's legacy implementation identity remains **NOT ESTABLISHED**; **BLOCKED** applies only to the relevant source-access limitation, **HOLD** to the chain prerequisite gate, and **PARKED** to its synthesis disposition. These do not establish falsehood or nondeployment. Eleven selected current-state units remain **NOT INDEPENDENTLY VERIFIED**: three deferred operational questions and eight architecture/provenance-dependent assertions. They are not eleven independent systems or failures, nor evidence of absent implementation. Alongside unresolved authority mappings, C45's all-layer deployment remains **NOT ESTABLISHED**, and X1's operating truth remains unresolved. These boundaries neither negate C05 nor make Report v1 incomplete.

Twenty-three selected units carry **TARGET DESIGN**, covering proposed, future, roadmap or otherwise forward-looking architecture. They are intentionally not treated as failed current implementation. Classification establishes neither current implementation, deployment or governance authority nor technical feasibility, soundness or future adoption. It is a temporal/evidentiary distinction, not an endorsement. Material later implementation or governance changes can be compared with the frozen baseline through delta evaluation.

The evidence supports confidence in specific scoped conclusions, not confidence by extrapolation. Strong assurance can attach to bounded conclusions where evidence layers converge, particularly C05's documentary, source and chain evidence. Equivalent assurance does not extend to all Laniakea implementation, every operational assertion or governance mapping, target implementation, all-layer PAU deployment, complete operational history or project-wide security. Report v1 provides no implementation-completeness or governance-readiness certification, security audit or runtime certification.

Unresolved questions may reopen on qualifying evidence; optional assurance may strengthen an already sufficient conclusion; later project, governance or documentary changes may be evaluated as deltas. These possibilities create neither a mandatory remediation backlog nor a publication dependency. Report v1 can close with its unresolved questions explicitly bounded.

Within this snapshot, Laniakea combines independently grounded legacy/current material, substantive but non-uniform Atlas relationships, useful but non-universal STL evidence relationships, substantial future architecture and unresolved current-state and provenance questions. Its strongest technical case demonstrates correspondence with deployed Sky/Spark infrastructure when provenance becomes specific enough. The unresolved portions explain why that result cannot be generalized to the whole system.

### Evidence notes

- **S1-1.** `synthesis/master-evidence-matrix.md`
- **S1-2.** `synthesis/report-architecture.md`
- **S1-3.** `synthesis/report-sections/02-scope-baseline-methodology.md`
- **S1-4.** `synthesis/report-sections/10-principal-synthesis-findings.md`
- **S1-5.** `synthesis/report-sections/11-overall-synthesis.md`

## 2. Scope, Baseline and Methodology

### Evaluation scope

This report evaluates selected Laniakea claims against independent documentary, governance, implementation and Ethereum Mainnet evidence. Each conclusion is limited to the proposition, source revisions and observations actually examined. An independent human evaluator leads the evaluation and makes the substantive judgments.

The scope is non-exhaustive. Identifying or classifying a statement does not mean that its substantive truth was independently verified. The evaluation is not a security audit, a runtime certification, an implementation-completeness certification or a blanket endorsement or rejection of Laniakea. It does not establish that every described component exists, that every proposed arrangement has governance authority, or that all deployed components operate correctly.

Consequential findings require concrete source evidence, with facts distinguished from claims and inference. This section explains the method; the following sections present the results within their evidence limits.

### Frozen baseline

Freezing a baseline fixes the materials against which a question was asked. A repository is “pinned” when it is fixed to a specific revision. These revisions identify the documentary and source versions consulted; historical comparisons preserve chronology; fixed chain blocks identify the states observed. A baseline identifies the state being evaluated; it does not itself validate that state.

| Baseline | Concise identifier and date | Role |
|---|---|---|
| Laniakea documentation | `f438819`, June 4, 2026 | Subject revision containing the evaluated assertions. |
| Sky Atlas | `4c466eb`, September 17, 2026 | Pinned governance comparison source. |
| STL | `37e56db`, September 18, 2026 | Pinned technical evidence source for questions specifically connected to STL. |
| Historical Atlas comparison | `7fa69a6`, earlier than the evaluated Laniakea revision | Historical documentary context; not a replacement for the pinned Atlas revision or proof of enactment. |
| Historical Ethereum Mainnet observation | Block 25242585, June 4, 2026 | Fixed historical chain state near the time of the evaluated Laniakea revision. |
| Retained current Mainnet observation | Block 26007670, September 18, 2026 | Fixed later chain state, rather than verification as of publication. |

These are distinct dates, not one simultaneous snapshot of every source. “Current” in the chain evidence means the retained September observation. The two observations do not establish what happened throughout the interval between them. Historical comparisons help distinguish earlier documentary presence from later descriptions; they do not establish a component's first deployment or activation date.

Appendix A is designated for the complete baseline record, including full revision identifiers, evaluation freeze identifiers and precise timestamp details.

### Claim-first evaluation

The method is claim-driven, using pre-stated invariants. An invariant is a condition or proposition defined before deeper evidence gathering. The charter requires repositories to be pinned before substantive analysis and invariants to be stated before grading. Initial checks examined which documents belonged to the evaluated corpus, which were intended to be authoritative within it, whether internal references resolved, and how active and historical material were distinguished. Classification recorded what each selected statement asserted before deeper governance or implementation verification.

This discipline helps reduce confirmation bias by keeping the question visible when potentially supportive evidence appears. It also helps prevent evidence gathering from silently substituting an easier proposition. Evidence that a document mentions a component, for example, cannot answer a deployment question merely because it is relevant to that component. Each consequential conclusion must retain its source, scope and applicable test.

The method separates direct support from inference and prefers repeatable extraction and counts where appropriate. These controls support, rather than replace, human judgment.

### Claim and temporal classification

Classification records the status asserted by a source. It does not certify that status. The report distinguishes eight broad classes:

| Class | Meaning for evaluation |
|---|---|
| CURRENT-GOVERNANCE | An assertion about governance represented as current; it requires the appropriate Atlas comparison. |
| CURRENT-IMPLEMENTATION | An assertion that implementation exists; source identity and behavior require separate evidence. |
| CURRENT-OPERATIONAL | An assertion about ongoing use, operation or an operational configuration. |
| PROPOSED/TARGET | Proposed, target-architecture or conceptual/specification material, retaining its qualifications. |
| FUTURE/ROADMAP | Planned, unscheduled or far-future material, rather than an assertion of present operation. |
| HISTORICAL | Earlier or deprecated material, without promotion to current authority. |
| EXAMPLE/ILLUSTRATIVE | Worked examples, hypothetical prerequisites or illustrative patterns. |
| AMBIGUOUS | Wording that does not establish a sufficiently clear temporal or implementation/activation scope. |

Future design was protected from being graded as an implementation failure merely because it was not yet implemented or deployed. Likewise, AMBIGUOUS does not mean false: unresolved current-versus-future wording must not be silently interpreted in the harsher direction. An illustrative pattern may also accompany a separate operational assertion. Establishing its example framing does not independently verify or disprove the asserted operation.

### Evidence hierarchy

The evaluation used the following evidence progression where relevant:

Laniakea documentary assertion → Atlas governance/policy evidence → STL technical evidence → implementation provenance → source/static behavior → historical deployed state → current retained state.

This is not a compulsory route for every claim. Evidence depth depends on the proposition, and examining a layer does not mean that it supplied sufficient support for the claim.

Laniakea supplies the assertions under examination. The charter designates pinned Atlas as the authority for comparison with claims about current Sky governance; Laniakea design prose cannot supply that authority itself. Documentary policy evidence must still be distinguished from enactment or actual execution. STL provides evidence for questions specifically connected to STL. Registry or monitoring records do not automatically identify a component's canonical implementation source.

Implementation provenance means identifying the implementation source that corresponds to the described component. Static inspection examines behavior visible in source code. Chain observations examine deployed state at specified points. Support at one layer cannot substitute for a missing connection at another: naming a repository does not prove deployment, and a deployed address does not by itself establish which exact source revision produced its runtime code.

Direct source support may establish that an assertion appears in a document without establishing its truth. Repeatable extraction results, source assertions, inferences from named facts and retained chain observations therefore remain distinct types of evidence. Their full definitions are allocated to Appendix J, with retention details in the evidence appendix.

### Repository grades versus synthesis dispositions

Historical repository grades record the result reached at the time of a test with a defined scope. Historical working grades included PASS, WARN and FAIL, alongside evidence or workflow states such as NOT ESTABLISHED, BLOCKED and HOLD. Synthesis dispositions express what the accumulated evidence permits the final report to conclude. Later evidence does not rewrite earlier grades.

The complete taxonomy remains preserved in the frozen evidence matrix and is allocated to Appendix J for publication, including the distinction between grades and workflow gates. The principal synthesis terms used in this report are:

| Disposition | Publication meaning |
|---|---|
| ESTABLISHED | The explicitly scoped conclusion is supported; its object may be documentary framing, a discrepancy or bounded implementation/chain support. |
| NOT ESTABLISHED | The accumulated evaluation does not establish the scoped proposition or mapping. |
| TARGET DESIGN | Proposed, conceptual, target or roadmap material remains protected from an implementation-failure inference. |
| NOT INDEPENDENTLY VERIFIED | A source assertion remains without completed independent substantive verification because that work was deferred, blocked or not undertaken. |

PARTIALLY ESTABLISHED means identified parts are supported while material elements remain unresolved or inconsistent. PARKED means further verification is set aside pending a specified new evidence lead. It describes the verification workflow, not a replacement for an insufficient-evidence result. OUT OF SCOPE identifies a broader truth test outside completed substantive verification; documentary ambiguity may still be recorded.

ESTABLISHED must name what was established. Documentary presence, for example, is not shorthand for current operation. These labels describe particular conclusions, not the project as a whole.

### Meaning of NOT ESTABLISHED

NOT ESTABLISHED means the available evidence did not justify asserting the proposition under the scoped test. It does not automatically mean false, nonexistent or disproven. A question may remain unresolved because evidence is insufficient or an identity mapping is missing. An inaccessible source is an access limitation, not evidence of what that source would contain.

Some questions include explicit reopening conditions. Those conditions define what new evidence would justify revisiting the issue; they do not turn an unresolved question into a remediation requirement. Non-verification is not a negative finding. The report retains uncertainty rather than converting absence of evidence into evidence of absence.

### Point-in-time evidence and runtime limits

Fixed historical and current chain observations establish only the state returned for the specified observations and queries. Two snapshots do not automatically establish continuous operation between them. Nor does deployment alone establish active use, first deployment date or uninterrupted availability.

Event evidence has its own boundaries. The presence of an event can support observed component behavior within the query scope without establishing caller attribution: identifying which account or contract caused the event. Conversely, no matching events in a query limited to particular criteria or dates does not prove that no relevant use occurred. Attribution and coverage require their own support.

Source similarity and static behavior likewise do not automatically establish exact runtime bytecode equivalence: demonstrating that deployed machine code exactly corresponds to a particular source build. Provenance, source behavior and observed chain state must retain their separate qualifications. These limits prevent a limited implementation or chain conclusion from becoming a general claim of runtime correctness, integration assurance or security certification.

### Coverage and extraction limits

The claim map selected 53 statement units. That is neither exhaustive corpus coverage nor a count of 53 independent propositions. Some implementation and operational statements overlap, and broader statements can include narrower ones.

Deterministic extraction supports repeatable inventories of candidate references, addresses and status language. It cannot establish semantic completeness—that every relevant meaning or claim has been captured—or the truth of every extracted statement. Canonicality checks identify which document or source is intended to be authoritative within the evaluated corpus. Broken references and canonicality findings concern documentation; they do not independently establish implementation or security defects.

Unavailable source material, or material whose connection to a claim has not been established, cannot be replaced by inference. An external architecture source identified during the evaluation was unavailable in the frozen evidence set. No assumption is made that it contains any particular missing implementation. Extraction, source access and verification limits remain attached to the conclusions they constrain.

### Publication control

The frozen master evidence matrix is the controlling record for publication claims. Narrative wording may summarize or clarify those findings, but it may not exceed their evidence boundaries. The report architecture maps each section to the relevant evidence and findings.

Strong conclusions remain adjacent to their material limitations. Narrative wording cannot turn historical evidence into present-day verification, documentary characterization into implementation proof, or a finding with limited scope into a broader assurance claim.

The next section, “Laniakea Snapshot Characterization,” applies these distinctions to the corpus that was evaluated.

### Evidence notes


- **S2-1.** `EVAL-CHARTER.md` — Central question; Evidence hierarchy; Claim-status classes; Grades; Evidence vocabulary; Method.
- **S2-2.** `expected/L0.md` — Corpus and provenance integrity purpose and invariants.
- **S2-3.** `expected/L1.md` — Claim classes; temporal clarity, proposed-state protection and ambiguity-preservation invariants.
- **S2-4.** `pins/baseline.md` — Subject, Atlas and STL pins; recorded architecture-source availability.
- **S2-5.** `synthesis/master-evidence-matrix.md` — Sections 0–2: baseline, vocabulary, classification crosswalk and counting constraints; section 3 and C05 source/chain boundary for retained evidence limits.
- **S2-6.** `synthesis/report-architecture.md` — Sections 0–3, 12–15 and section-control matrix: scope, baseline, inherited method, limitations and publication controls.

## 3. Laniakea Snapshot Characterization

### A mixed present-and-future corpus

The evaluated June 4, 2026 Laniakea snapshot brings together descriptions of asserted current arrangements, prospective architecture, historical sources and worked examples. Its documentary character cannot be reduced to a single temporal label. A statement describing a component as existing may sit alongside a proposed replacement, while an active document may retain a historical explanation or an illustrative procedure. Those relationships matter when deciding what the text actually asks a reader to believe.

The corpus has a substantial, identifiable structure. The README lists 14 active areas containing 142 Markdown files; the README, summaries and roadstart orientation material add another 20 files to the 162-file consultation scope. Summaries are designated entry points, and earlier baseline and archive material are separately identified as inactive. The README also describes the documents as drafts. Active and draft are compatible labels: inclusion in ordinary consultation does not make every passage a statement of current operation.

The selected claim map records the following distribution. These counts characterize the 53 reviewed statement units, not every sentence or claim in the corpus.

| Documentary class | Selected units | What the count represents |
|---|---:|---|
| Current governance | 4 | Assertions about arrangements represented as current governance. |
| Current implementation | 4 | Assertions that particular implementations exist. |
| Current operation | 11 | Assertions about use, operation or operational configuration. |
| Proposed/target | 16 | Prospective or conceptual architecture and specifications. |
| Future/roadmap | 7 | Planned, unscheduled or later-phase material. |
| Historical | 3 | Statements about earlier terminology, research or documentation. |
| Example/illustrative | 3 | Worked examples or hypothetical prerequisites. |
| Ambiguous | 5 | Statements whose intended status or extent remains unresolved. |

The selection is non-exhaustive, and some units overlap. A current-state classification records what a source asserts; it does not settle whether that assertion is true. Two of the current-operation units also participate in the documentary conflict discussed below. The distribution therefore shows a mixture of documentary purposes, not proportions of verified functionality or a measure of overall coherence.

### Current-state and target-state separation

Useful status distinctions appear across the reviewed material. Contract summaries separate descriptions labeled legacy-live from draft target standards. Sentinel material distinguishes a forward-looking cognitive design from its description of Phase 1 relays. Accounting material distinguishes temporary arrangements from later auction and incentive designs. These are facts about how the documentation frames its subjects, without adopting the underlying claims of operation.

Future designs were not treated as current implementation failures merely because they were not implemented. This is particularly important where a design uses present-tense verbs: a description of what a proposed mechanism “does” can explain its intended behavior without asserting that it is deployed. Labels such as placeholder, post-transition, speculative and unscheduled qualify those descriptions.

A target design can be considered as a design without requiring current deployment. The 23 selected proposed/target and future/roadmap units remain in that category; this section does not assess their technical quality, feasibility or readiness.

The distinction works in both directions. A general draft label cannot erase an explicit claim that a particular instance is running or that a component is implemented today. Historical explanation, current implementation and future activation also need not be mutually exclusive. The relevant question is the status of the specific statement, read with its qualifications, rather than a status inherited automatically from an entire directory.

### Documentary maturity

The documentary review found both useful organization and material limitations. The main distinctions between active areas, orientation material and inactive sources could be reconstructed. Local labels also distinguish documents that mainly point elsewhere, resolved worklists, historical demonstrations and material awaiting rewrite. Those qualifications help readers avoid treating every retained document as an equally current specification.

Two slideshow files remain an exception. Their directory name suggests stale material, and they are not among the README's declared active areas, but the reviewed text does not definitively establish whether they are historical, superseded or still intended for current use. They remain stale/ambiguous and outside ordinary active consultation. This localized uncertainty does not invalidate the principal corpus boundary.

The more direct documentary defects concern a missing canonical Sky Intents destination and broken internal navigation. The reviewed material contains **26 ordinary broken-link occurrences across 13 active source documents, targeting 12 distinct absent destinations**. A separate status issue leaves the authority scope of capital-stack's reference to an inactive canonical whitepaper unresolved. These are distinct limitations within a corpus that also provides useful structure and traceability.

Six reference categories have stable candidate inventories that identify their source locations: Atlas references, implementation-repository references, phase/status terminology, contract addresses, formula-bearing documents and current-state statement candidates. These records provide reproducible starting points for examining source context. Some categories have no matches in particular corpus areas. The inventories do not validate addresses, formulas or extracted assertions, or establish that every relevant claim or reference has been captured.

### Canonicality and navigation

Canonicality asks which document or destination is intended to be authoritative for a topic within the corpus. The review found useful examples of explicit scope: lean roadmap documents point to fuller counterparts, and some local designations identify a particular parameter treatment. Duplication alone is therefore not a documentary conflict. The problem arises where a designation cannot be followed or its intended authority remains unclear.

The Sky Intents case is specific. The active Identity Network document designates a canonical trading protocol that consumes attestations, but both the displayed destination and the literal link destination are absent at the evaluated revision. Historical documents address the same topic. Their existence and the repository's migration notes do not establish a current successor or an explicit ambiguity record for that particular canonical designation. The evaluation does not select an archived namesake as the replacement or infer what the missing document would have said.

Navigation presents a related but distinct problem: readers cannot reach the stated destinations of the 26 confirmed ordinary link occurrences. The count covers those checked links, not every unresolved reference, and is not a count of independent technical defects. Some summary paths also begin with an unexplained `lani/` prefix, leaving their intended starting location unclear. No replacement path is assumed.

Capital-stack illustrates a status question even where the cited treatment can be identified. Its active draft contrasts a simplified four-level account with a seven-step inactive-whitepaper treatment described as canonical. It does not clearly settle whether that designation means historical provenance, conceptual authority or a current documentary role. The forecast-model document also refers to an inactive treatment as canonical, but explicitly frames itself as a pointer to a planning tool. Its intended authority scope also remains uncertain, though that context limits the concern: the reference does not independently show that inactive material is being presented as current authority. Neither case establishes technical superiority or current policy authority for the inactive material.

Missing navigation does not prove missing implementation. These defects limit document selection and traceability; they do not independently establish a security defect, implementation defect or runtime failure.

### Temporal and status consistency

One consequential conflict concerns the documentation's description of Phase 1, or P1, accounting. Here, “closure” refers to the documented settlement output assigned to a Prime. The detailed settlement-cycle document assigns those closure records to P1 and says governance reads them for manual action. The accounting summary instead describes that closure as target work and explicitly excludes it from P1; roadmap material also defers closure. The documents thus assign the same output to different stages of development.

The detail also describes monthly cadence as encoded in an atom and as P1 reality. The disputed “atom” language concerns whether that monthly cadence is represented inside the Phase 1 accounting model. The summary describes a daily clock within that model while placing legacy monthly reconciliation outside it and saying that reconciliation is not represented by atoms. Monthly economic reconciliation and a daily clock can coexist; the disagreement concerns the explicit placement of the monthly atom and closure output in P1.

The detail includes qualifications about manual action and reconciliation outside the model, but does not explicitly withdraw its P1 record or monthly-atom assertions. Its procedural stage headings alone are not evidence of a rollout conflict. The disagreement rests on explicit P1 status language, not an assumption about how the software behaves.

The active documentation contains an unresolved P1 closure/monthly-atom status conflict; this is a documentary finding, not an implementation verdict. Recorded as X1, it underlies the related findings on temporal clarity, present-tense consistency and cross-document status consistency. Those are three tests affected by one conflict, not three independent implementation failures. The conflict is established; actual operating truth and the intended documentary winner remain NOT ESTABLISHED. Neither the detail nor the summary is chosen as the real-world account here.

### Ambiguity preservation

Other passages leave scope uncertain without establishing the same direct contradiction. Their interpretation remains open rather than being forced into current, future, true or false categories. AMBIGUOUS does not mean false, and preserving an unresolved reading does not discard the assertion that prompted it.

The five selected ambiguous units concern capital described as required in a draft model, calibration parameters described as adopted, and deployment breadth across layers. They also cover implementation language alongside future Growth Staking activation, and whether a current specification describes a completed production rollout. “Required” may describe a design requirement; “adopted” may describe design calibration; “implemented” need not mean activated. None of these possibilities is selected as the correct account. Broader all-layer deployment likewise remains unestablished.

These five ambiguous units are already included in the 53-unit selected claim map. X1 and the four questions about the Sky Intents destination, inactive-whitepaper authority, path starting locations and slideshow status are separately retained contextual records, not additional selected claim units. Keeping these questions visible does not imply that every ambiguity in the corpus was detected or resolved.

### Historical and illustrative material

Some established conclusions concern documentary characterization alone. The examples below show why the object of “established” matters: a terminology statement, a user-story prerequisite and a record of actual deployment are different kinds of proposition.

| Material | What the documentary evidence establishes | What it does not establish |
|---|---|---|
| Earlier sentinel terminology | The documentation retires the earlier unified sentinel-formation terminology in favor of relay/sentinel classes. | An implemented migration or a change in STL code. |
| Noemar/synlang research framing | The documentation describes Noemar/synlang as superseding the earlier MeTTa/notation research track. | Implementation or runtime replacement; those were not tested for this historical statement. |
| Configurator onboarding | User Story 1 states PAU deployment and Configurator admin grants as prerequisites. | That those contracts were actually deployed or those roles actually granted. |
| Settlement-cycle sketch | The sketch is explicitly illustrative. | Running settlement. |
| Crystallization pattern | The pattern is explicitly illustrative and noncanonical. | Independent verification of its separate running-instance assertion. |
| Earlier documentation baseline | The README describes the earlier-phase root as an inactive source/baseline for rewrite. | Independently verified verbatim-snapshot fidelity. |

Illustrative does not mean fictional or nonexistent. The crystallization pattern's illustrative status does not disprove its separate, unverified running-instance assertion.

Historical scope is also local. A statement that an earlier research track was superseded does not make its entire enclosing directory historical.

### What the snapshot does and does not support

The snapshot is substantial and structured, with entry points, declared areas, local status qualifications and stable reference inventories. It contains both asserted current arrangements and forward-looking target material. Those features support a differentiated reading of the corpus rather than a single judgment about its coherence or completeness.

Documentary maturity is uneven. Canonicality and navigation defects affect access to the intended sources, and unresolved status questions affect interpretation. The P1 conflict remains visible without a selected winner. These conclusions do not validate every current assertion, establish the soundness of future designs or turn documentation problems into implementation or security defects. Future design is not itself an implementation failure, and documentary characterization is not implementation proof.

The next section, “Relationship to Sky Atlas,” moves from what Laniakea says about itself to how selected governance claims compare with the pinned external authority layer for current Sky governance.

### Evidence notes

- **S3-1.** `synthesis/master-evidence-matrix.md` — Sections 1–3; L0/L1 findings; C43–C47 selected ambiguities; X1 and U1–U4 contextual records; C28 and C49–C53 historical/example framing; C09 separate unverified running-instance assertion.
- **S3-2.** `synthesis/report-architecture.md` — Section 4 and its section-control row.
- **S3-3.** `reports/2026-09-18-f438819/L1-claim-map.md` — Scope and counting method; classifications; X1; ambiguity carry-forward; statement relationships.
- **S3-4.** `reports/2026-09-18-f438819/findings/L0-01-corpus-boundary.md` — Corpus structure, local qualifications and slideshow boundary.
- **S3-5.** `reports/2026-09-18-f438819/findings/L0-02-canonicality.md` — Sky Intents designation and unresolved documentary destinations.
- **S3-6.** `reports/2026-09-18-f438819/findings/L0-03-internal-navigation.md` — Confirmed navigation occurrences, counting scope and exclusions.
- **S3-7.** `reports/2026-09-18-f438819/findings/L0-04-status-integrity.md` — Capital-stack authority scope and mitigated forecast-model context.
- **S3-8.** `reports/2026-09-18-f438819/findings/L0-05-reference-inventory.md` — Six-category candidate inventory and semantic limits.
- **S3-9.** `reports/2026-09-18-f438819/findings/L1-01-temporal-clarity.md` — P1 closure/monthly-atom conflict and unresolved operating truth.
- **S3-10.** `reports/2026-09-18-f438819/findings/L1-02-present-tense-consistency.md` — Explicit status conflict and excluded apparent contradictions.
- **S3-11.** `reports/2026-09-18-f438819/findings/L1-03-proposed-state-protection.md` — Protection of future designs and retained current assertions.
- **S3-12.** `reports/2026-09-18-f438819/findings/L1-04-cross-document-status-consistency.md` — One conflict underlying three related findings.
- **S3-13.** `reports/2026-09-18-f438819/findings/L1-05-ambiguity-preservation.md` — C43–C47, X1 and U1–U4 preservation boundaries.

## 4. Relationship to Sky Atlas

### Atlas as the governance comparison layer

Laniakea supplies the claims examined in this section. For this evaluation, the pinned Sky Atlas snapshot is the external governance-policy source used to compare claims about current Sky governance. A statement does not become current Sky governance authority merely because it appears in Laniakea, even when it uses words such as “live,” “current” or “adopted.”

The comparison uses the June 4, 2026 Laniakea revision and the September 17, 2026 Atlas revision, with earlier Atlas records where relevant. Atlas's own documentary qualifications also matter. Its repository describes itself as in development, and particular passages distinguish active arrangements from future specifications. Atlas policy text alone does not prove enactment or execution, including payments, deployment or runtime behavior.

The results are mixed. A claim about where information is documented can be supported directly. A policy description can match in one respect and differ in another. Related role descriptions can leave the asserted authority relationship unresolved. A proposed arrangement may also depend on future governance action rather than describe present authority. These outcomes require different conclusions; a difference alone is not automatically an error or an implementation defect.

### Overview of the four scoped comparisons

The four comparisons below concern selected assertions, not exhaustive Atlas coverage of Laniakea. They ask whether the evidence supports the particular documentary presence, hierarchy, authority or fee mechanics claimed.

| Question | Laniakea assertion | Atlas comparison result | What the result does NOT establish |
|---|---|---|---|
| Operational-data categories | Four categories of operational data sit in Atlas documentation. | Supported by Atlas records, including records predating the evaluated June 4 Laniakea revision. | Address correctness, actual deployment/use, complete coverage or migration. |
| Ozone / Guardian hierarchy | Ozone is the single operational Guardian, with the Generator and all Primes as direct children. | NOT ESTABLISHED: executor records do not establish that specific hierarchy. | That the hierarchy is false or forbidden. |
| Phase 1 authority | Phase 1 v2 starts with authority concentrated in the Guardian and no Core GovOps role yet. | NOT ESTABLISHED: broader governance roles do not establish this specific starting-authority arrangement. | The actual permission structure or absence of such authority. |
| Entity fees | A current regime combines a creation charge, annual upkeep, rebates and tokenless exemptions. | Split: the annual rate and general rebate entitlement are supported; several mechanics differ; the amount and blanket exemption remain unestablished. | Actual payments, universal entity coverage or overall fee-policy alignment. |

The distinctions in the final column are part of each result. In particular, a documentary match cannot carry an operational conclusion, and an unresolved mapping cannot be converted into a contradiction by substituting a different proposition.

### C01 — Operational-data categories are documented in Atlas

Laniakea describes Prime SubProxy addresses, Core Operator Relayer multisigs, rate-limit types and per-chain deployment records as information contained in Atlas prose. Atlas documents all four categories in its Spark material, including records predating the June 4 Laniakea revision. These include a named SubProxy account record, relayer role and address information, named rate-limit kinds, and contract records organized by chain.

The result is ESTABLISHED for documentary presence. “Rate-limit types” means named kinds of operational limits, without establishing identity with a particular programming-language enumeration. Per-chain deployment records refer here to documentary lists of contract addresses.

These records do not establish address correctness, actual deployment, active use, operational correctness or exhaustive coverage across all Primes. Placeholders elsewhere do not negate the examples, but limit any completeness inference. The proposed move into structured Synome records is a separate question; this comparison does not establish completed migration.

### C02 — Ozone / Guardian hierarchy remains unresolved

The evaluated proposition describes Ozone as the single operational Guardian, with the USGE Generator and all Primes as its direct children. This asserts both an exclusive role and an organizational relationship. Establishing that Ozone appears in Atlas would answer only part of that question.

Atlas separately identifies Ozone and Amatsu as Operational Executor Agents. Executor Accords document executor-service relationships with particular counterparties: Spark's active accord names Amatsu, while Skybase's names Ozone. Those relationships do not establish Laniakea's Guardian/direct-child hierarchy. Service provision, ownership, collateral, authority and organizational parenthood cannot be treated as interchangeable merely because the same names appear nearby.

The documents also retain status qualifications. The descriptions of the named executors include future-specification language, while general Atlas text says Executor Agents are “not yet operational.” Active accord records and that general qualification are both part of the comparison. This section does not choose which description reflects actual operation.

The specific hierarchy therefore remains NOT ESTABLISHED. Different accord counterparties prevent assuming that all such accords name Ozone; they do not disprove a separate organizational hierarchy. Related roles may exist, and later governance could establish or formalize a relationship, but neither possibility supplies the missing mapping in the evaluated evidence. The result concerns insufficient support for the asserted relationship, not proof of its nonexistence.

### C03 — P1 authority mapping remains unresolved

Laniakea's governance summary describes Phase 1 v2 as beginning “fully sudo,” with the Guardian holding the relevant authority at genesis and no Core GovOps role yet. Here, “sudo” expresses the claimed concentration of starting authority, and “genesis” refers to the starting phase or configuration. The exact permissions remain unresolved. The statement is phase-specific; it is not a claim that Core GovOps has no role anywhere in Sky.

Atlas documents broader governance roles. Core GovOps has review obligations relevant to Synome governance, while the Synome Editor has a documented editing role subject to review. These rules show that Atlas is not silent about Core GovOps, but do not establish their applicability to Laniakea's particular P1 v2 starting-authority claim.

Document-editing authority and review obligations do not by themselves identify a runtime's privileged key, permissions or starting authority holder. Related governance concepts require an explicit connection to the relevant phase and authority layer. Appendix D is designated for the detailed role comparisons, including the Executive Process Liaison and Agent Genesis Account references.

The P1 v2 genesis authority mapping remains NOT ESTABLISHED. The comparison establishes neither the claimed authority relationship nor its falsehood. It supplies no implementation-state conclusion or inference about future governance intent. The unresolved issue is applicability: which broader rules, if any, govern the precise authority scope claimed?

### C04 — Entity fee mechanics show a split result

The entity-fee comparison is not a single yes/no result. Laniakea describes a current regime combining a 5% creation charge on every issuance, upkeep at 50 basis points per year, continuous cross-entity rebates and exemptions for tokenless entities. Its explanation specifies payment in the entity's own governance token rather than USDS. These propositions must be separated to show what the Atlas comparison supports and where it differs.

The comparison is limited to the shared Prime scope. Laniakea expressly includes Primes, and Atlas supplies rules for Prime Agents, so there is a direct basis for comparing those obligations. That does not establish a mapping between every Laniakea entity type and every Atlas category, or extend the result universally.

**Supported: the annual rate and general rebate entitlement.** Atlas specifies Prime upkeep at 50 basis points annually, equivalent to 0.50%, and provides a general Prime-to-Prime rebate entitlement. These terms align even though payment denomination and rebate mechanics differ.

**Discrepant: recurring creation mechanics.** Atlas describes a one-time payment from founding teams establishing new Prime Agents. Laniakea's claimed charge on every issuance has a different trigger. The recurring issuance mechanic therefore differs from the compared one-time founding rule. The claimed 5% amount is a separate, unestablished element, discussed below.

**Discrepant: own-token upkeep.** The compared Atlas policy denominates upkeep in USDS, while Laniakea explicitly describes using the entity's own governance tokens. Atlas specifies monthly payment and labels a Spark upkeep instance active, but also leaves operational payment details for later specification. The denomination difference is established at the documentary-policy level. The shared monthly cadence is not an additional contradiction, and neither the policy nor an active label establishes that payments occurred.

**Discrepant: continuous holdings-based rebate mechanics.** Under the compared Atlas policy, the rebate depends on the issuing Prime's actual monthly upkeep payment and is credited in the following calendar month. Laniakea describes continuous credit based on the holder's holdings value. The conditions and timing of credit materially differ, despite the general entitlement match. This compares stated policy mechanics; it does not evaluate the mathematical or economic correctness of the rebate formula.

**Not established: the 5% creation amount and blanket tokenless exemption.** Atlas leaves the required creation amount and payment process to be specified; it does not establish the claimed 5% charge. The comparison also did not establish a universal tokenless exemption across Laniakea's entity types. Both claims remain NOT ESTABLISHED, not disproven. These evidence gaps are distinct from the affirmative differences in mechanics, and the Prime comparison does not settle wider entity eligibility.

**Not tested here: actual fee accrual, payment and operational flows.** The claim that upkeep is currently realized monthly and creation fees routed at issuance, recorded as C11, remains NOT INDEPENDENTLY VERIFIED. The C04 policy comparison establishes neither that payments happened nor that they did not.

The original Atlas test retains its historical L2-04 grade of FAIL for the tested invariant within the shared Prime scope, because several claimed mechanics materially differed from the compared policy. The final C04 synthesis remains PARTIALLY ESTABLISHED: the 50 bps rate and general rebate entitlement are supported while other elements differ or remain unestablished. This mixed conclusion does not rewrite the earlier grade.

For the Primes covered by this comparison, Laniakea's claimed current fee regime is only partially supported by contemporaneous Atlas policy: the 50 bps rate and general rebate entitlement align, several recurring mechanics differ materially, and the 5% amount and blanket tokenless exemption remain unestablished. This conclusion does not establish actual payments, author intent, wider entity coverage or implementation defects, and does not preclude future governance adoption.

### Historical chronology and comparison timing

The comparison uses Laniakea's June 4, 2026 revision and Atlas's later September 17, 2026 revision. To distinguish earlier policy from subsequent edits, the evaluation also examined relevant Atlas material from May 29, 2026. Detailed historical references and the links between reorganized sections are allocated to Appendix D.

For C01, those earlier records establish presence of the categories without backdating later numerical parameters. For C04, the one-time founding fee, USDS monthly upkeep, payment-dependent rebate and unfinished payment procedure were already documented before the June 4 Laniakea revision. The discrepancy is therefore not explained solely by later September Atlas edits.

This determines what a later-edit explanation can account for, not why the texts differ. It does not establish deliberate divergence, accidental error, ratification dates, completed migration or future rejection. Whether the differing fee mechanics were intended as candidate future policy remains unestablished. Documentary chronology cannot substitute for evidence of intent, approval or execution.

### Supported, discrepant and unresolved are different outcomes

These comparisons distinguish documentary support from implementation or operation, an unresolved role mapping from a contradiction, and a policy discrepancy from a general architectural verdict. Discrepant mechanics differ within the tested scope. Laniakea's post-transition governance and proposed Atlas/Synome restructuring remain target material; where a proposal would change current governance meaning, later formalization may be needed. That does not make every future difference an error or require every concept to amend Atlas. Nor does a discrepancy automatically create a remediation requirement: future governance may adopt, modify or reject proposed mechanics.

### What the Atlas comparison supports

Selected Laniakea governance claims can be compared meaningfully with Atlas, but the conclusions differ. One category-presence claim is supported at the documentary level. Two specific hierarchy and authority mappings remain unestablished. The fee-policy claim produces a materially mixed result, with supported terms, discrepant mechanics and unresolved amount and exemption claims kept separate.

Laniakea text is not itself current Atlas authority. The comparison neither validates Laniakea generally nor establishes general conflict with Atlas. It preserves the distinction between descriptions of current policy and future arrangements that may require governance formalization, without treating documentary policy as proof of runtime behavior.

The next section, “Relationship to STL,” changes the question from governance authority to technical and provenance evidence. Atlas supplies the governance comparison in this evaluation; STL was evaluated for a different technical-evidence role.

### Evidence notes

- **S4-1.** `synthesis/master-evidence-matrix.md` — C01–C04, C11; L2-01–L2-04; target/governance boundaries for C20–C22, C29, C30 and C48.
- **S4-2.** `synthesis/report-architecture.md` — Section 5 and its section-control row.
- **S4-3.** `reports/2026-09-18-f438819/L2-atlas-binding-C01-C04.md` — Pins, authority and chronology; standing interpretation; split results; June–September comparison.
- **S4-4.** `reports/2026-09-18-f438819/findings/L2-01-C01-atlas-operational-data.md` — Four category witnesses, historical records and presence-only limitations.
- **S4-5.** `reports/2026-09-18-f438819/findings/L2-02-C02-ozone-guardian.md` — Executor/Guardian distinction, accord records, status qualifications and unresolved hierarchy.
- **S4-6.** `reports/2026-09-18-f438819/findings/L2-03-C03-p1-authority.md` — Phase-specific claim, broader authority rules and missing genesis mapping.
- **S4-7.** `reports/2026-09-18-f438819/findings/L2-04-C04-entity-fees.md` — Shared Prime scope, subclaim results, payment boundary, chronology and future-governance limits.
- **S4-8.** `pins/baseline.md` — Frozen subject and Atlas revisions and dates.

## 5. Relationship to STL

### STL's role in this evaluation

Atlas and STL answered different questions in this evaluation. Atlas supplied the governance-policy comparison discussed in the preceding section. STL was examined for technical evidence and implementation provenance: whether its records and source material could connect Laniakea's descriptions to identifiable implementations.

The inspected STL material included registries, observation and allocation-tracking code, indexing documentation, and references to related technical sources. These surfaces can record a component's name, network and address, show how observation software uses that record, or identify another source worth examining. Their value depends on what they actually contain. A registry that describes an external contract is not automatically the repository containing that contract's implementation.

The two comparisons here concerned Laniakea's legacy PAU stack, tracked as C05, and its legacy Configurator stack, tracked as C06. They tested whether the claimed components and their relationships could be matched to implementation source. They were not a general assessment of STL's usefulness, completeness or runtime correctness. STL contributed materially to discovery and cross-reference, even though neither comparison established the required implementation coverage within STL itself.

### The initial STL result for C05 and C06

For the legacy PAU, Laniakea describes a Controller, ALMProxy and RateLimits working together. The distinction between records about those components and their executable implementation was decisive. STL contained ALM-proxy registry entries and code consuming those entries for tracking. That established the presence and use of registry data within the inspected source, but not the claimed proxy execution behavior, capital-flow limits or combined contract wiring.

For the legacy Configurator, the required match was more specific than a configuration function or a timelock in isolation. Laniakea described Configurator together with BEAMTimeLock, BEAMState and bounded cBEAM operations. STL's PoolConfigurator references concerned address discovery and indexing for other protocol interfaces. Generic configuration code, an unrelated vault timelock and HTTP request limits did not establish this legacy component relationship.

| Scoped claim | Relevant STL material | Initial implementation-coverage result |
|---|---|---|
| Legacy PAU: Controller + ALMProxy + RateLimits (C05) | ALM registry records, allocation tracking and adjacent indexing/observation surfaces | **NO MATCHED STL COVERAGE ESTABLISHED** for the claimed implementation or combined wiring. |
| Legacy Configurator and BEAM components (C06) | PoolConfigurator references, configuration code, unrelated timelocks and request limits | **NO MATCHED STL COVERAGE ESTABLISHED** for the claimed legacy stack and bounded operations. |

Both results remain as recorded in the initial STL review, L3A. In each case, the missing implementation match prevented a subsequent comparison of the claimed behavior against a confidently identified STL implementation. Adjacent tooling was not counted as partial contract implementation merely because it used a related name or address.

NOT ESTABLISHED here does not mean that the contracts did not exist, that STL contained nothing relevant, or that Laniakea's description was false. It identifies an evidentiary limit: the frozen STL material did not supply the required implementation match. The inspected references supported narrower statements about registry and observation code, which remained useful for the next question—where the implementation source could be found.

### What STL did contribute

For C05, STL provided a concrete ALM registry record identifying Spark, Ethereum Mainnet and an ALM-labelled address. It also attached a registry identifier, or UUID, that could be traced to a corresponding documentary record. The later local provenance review established that the identifier and address matched the Atlas Spark ALMProxy record. This made the registry entry's documentary origin more specific without establishing the contract code behind it.

The tracking code showed how registry entries were converted into network and address configurations for observation. Both the records and the code consuming them demonstrated this registry-to-tracking relationship; the external contract implementation remained a separate source to identify.

STL also recorded the origin of the `axis-synome` registry package, including a versioned package archive reference. This offered a concrete source for tracing the registry data. Its package version and upstream metadata did not identify versions of the PAU contracts.

Related STL technical documentation supplied explicit pointers to `sparkdotfi/spark-address-registry`, Spark PSM source and associated documentation. These provided concrete leads through related integration and address information. STL helped identify where to look; it did not itself establish the complete implementation source for the scoped PAU stack.

Some ALM address and tracking references were already present before the evaluated June 4 Laniakea revision. Other registry organization and provenance pointers appeared later in the inspected history. These dates located the supporting records in time; they did not date the contracts' implementation or deployment. Detailed identifiers and chronology belong in the STL/provenance ledger in Appendix E.

For C06, related configuration names and concepts helped distinguish the inspected material from the claimed legacy stack. They did not provide a comparable trail to its implementation source.

### From STL lead to implementation provenance

The C05 progression moved from a registry lead to local provenance investigation, then external retrieval, exact repository identification and static source review. Each step supplied a different part of the connection between Laniakea's description and inspectable implementation code.

The local investigation connected Laniakea's explicit reference to existing Spark ALM Controller contracts with documentary component relationships, STL's registry identifier and package references. Those connections strengthened the trail, but the source of the complete implementation remained unestablished.

External retrieval followed the recorded leads. The retrieved registry package supplied specification and package-origin information rather than the ALM implementation. Spark address-registry annotations went further: they named `spark-alm-controller`, individual component source files, revisions and versions. However, the inspected material did not yet establish the repository's exact owner and location. Those annotations made the source attribution more specific, while leaving the implementation itself to be located and inspected.

Separate repository resolution identified `sparkdotfi/spark-alm-controller` and resolved the recorded component revisions and version tags. The relevant source snapshots predated the June 4 subject revision. This identified the repository and related components needed for implementation review; source dates and version tags did not establish deployment dates or deployed versions.

The following static review examined exact historical source revisions and relevant dependencies. It found material support for the generic legacy PAU description, with explicit behavioral qualifications. This was a source-level result, not proof of live operation. The source components examined came from mixed historical revisions rather than a single unified release. The next section explains the substantive source and Mainnet evidence.

C05's later implementation result came from separately resolving the actual implementation source; it did not turn the earlier STL coverage result into a positive finding. The original STL result remains unchanged.

### Why C05 and C06 diverged

C05 obtained references specific enough to support direct source inspection. This allowed the evaluation to advance into static behavior and subsequently chain validation, without using registry presence as a substitute for either.

C06 did not acquire a comparable legacy source identity or concrete external retrieval target. The local provenance review retained later PAS Configurator, BeamState and Timelock names and addresses as related documentary leads. Their relationship to the legacy Configurator was not established. Similar components and configuration concepts did not demonstrate that the later PAS material represented the same source, a renamed implementation or a migration from the legacy stack.

The named OpenZeppelin timelock family likewise provided only a component-family lead, not an exact source and version for the complete Configurator relationship. Neither that attribution nor the later PAS addresses supplied the missing legacy implementation bridge. C06 could not advance because the legacy implementation source was not sufficiently identified. This was an unresolved identity question, not evidence of nonexistence. Its full disposition and reopening conditions are addressed in the dedicated C06 section.

### Canonical implementation source versus supporting evidence

Here, “canonical implementation source” means the source repository and revisions that can be tied to the scoped component under review. It does not mean governance authority, institutional endorsement or a universal status assigned to all STL material.

Supporting technical evidence serves a different purpose. Registries preserve network-specific address records; observer and tracking code show how those records are used; package references identify data origins; and UUIDs and adjacent documentation connect related records. These contributions improve traceability without automatically identifying the contract implementation.

For implementation provenance, the evaluation needed an identified repository, the relevant source family and components, and revision or version references sufficient to inspect the implementation. Those connections made a behavioral comparison possible. They did not, by themselves, establish deployment, exact correspondence between source and deployed machine code, or comprehensive security and integration assurance.

STL was not established as the implementation-source provenance for every scoped Laniakea component examined here. This leaves open what other STL material might establish; the two comparisons do not support a universal conclusion about its coverage.

### What the STL evaluation supports

STL materially aided discovery and technical cross-reference, especially through the C05 registry and provenance trail. The initial STL review did not establish matched implementation coverage for either scoped stack. C05 later advanced through the separately resolved `sparkdotfi/spark-alm-controller` sources. C06 lacked the comparable legacy identity and retrieval path needed to advance.

C05 illustrates a concise principle: later evidence can establish a proposition that an earlier test left unresolved without rewriting what the earlier test actually found. Neither comparison justifies a general verdict on STL or automatic treatment of registry, address and package references as implementation-source identity.

The next section, **Implementation and Mainnet Grounding**, follows the successfully resolved C05 provenance path into source behavior and deployed Mainnet evidence. The question moves from locating a credible implementation source to what that source and the separately examined chain observations can establish.

### Evidence notes


- **S5-1.** `synthesis/master-evidence-matrix.md` — C05/C06; L3A-C05/C06, L3B-C05/C06, L3C-C05, L3D-C05 and L3E-C05.
- **S5-2.** `synthesis/report-architecture.md` — Relationship to STL; C05 anti-repetition drafting rule; Appendices E–G.
- **S5-3.** `reports/2026-09-18-f438819/L3A-STL-binding-C05-C06.md` — Results; Strongest source evidence and coverage method; Chronology.
- **S5-4.** `reports/2026-09-18-f438819/findings/L3A-01-C05-legacy-pau-stl-binding.md` — STL coverage result; Matched STL source paths / identifiers; Chronology.
- **S5-5.** `reports/2026-09-18-f438819/findings/L3A-02-C06-legacy-configurator-stl-binding.md` — STL coverage result; Matched STL source paths / identifiers; Derivation / inference.
- **S5-6.** `reports/2026-09-18-f438819/L3B-implementation-provenance-C05-C06.md` — Cross-claim provenance map; External source leads; Retrieval decision and chain gate.
- **S5-7.** `reports/2026-09-18-f438819/findings/L3B-01-C05-legacy-pau-provenance.md` — Provenance leads; Cross-repository provenance chain; Chronology.
- **S5-8.** `reports/2026-09-18-f438819/findings/L3B-02-C06-legacy-configurator-provenance.md` — Provenance leads; Cross-repository provenance chain; Counter-evidence/discriminators; Network/chain gate.
- **S5-9.** `reports/2026-09-18-f438819/L3C-C05-external-provenance.md` — Starting pointers and retrieved sources; Source identity; Component coverage and chronology.
- **S5-10.** `reports/2026-09-18-f438819/L3D-C05-repository-resolution.md` — Revision and version binding; Component and family result.
- **S5-11.** `reports/2026-09-18-f438819/L3E-C05-static-binding.md` — Exact sources and dependencies; Behavior and Laniakea fidelity; Chronology and decision gate.

## 6. Implementation and Mainnet Grounding

### The C05 question

Laniakea's legacy PAU description identifies three central components: a Controller directing operations, an ALMProxy providing execution and custody infrastructure, and RateLimits governing operational capacity. The evaluated claim, C05, asked whether this description could be connected to identifiable implementation source and a deployed Ethereum Mainnet instance. It required more than matching contract names or finding addresses in documentation.

The evidence had to answer four questions: whether the implementation source could be identified; whether its behavior materially corresponded to the description; whether the Mainnet components were deployed and connected at the June 4 baseline, with configuration checked through a selected operational example; and whether that state was retained at the later September observation. Source review and chain observations answered different parts of this argument.

This scope is narrower than Laniakea's broader all-layer deployment assertion, tracked separately as C45. C05 does not establish deployment across every Generator, Prime, Halo or Foreign layer. C45 remains NOT ESTABLISHED; neither a reusable implementation pattern nor a tested Mainnet instance resolves its deployment breadth.

### Resolving the implementation source

Separate provenance work identified `sparkdotfi/spark-alm-controller` as the repository containing the component sources named in the documentary records. Exact revisions and their version tags were resolved, and the relevant files were retained for inspection. This source identification came from work beyond the earlier STL coverage review, whose result remains unchanged.

| Component source | Revision shorthand | Source revision date |
|---|---|---|
| MainnetController | `984ec54` | February 16, 2026 |
| ForeignController | `7be9593` | November 7, 2025 |
| ALMProxy | `6058f68` | October 22, 2024 |
| RateLimits | `6058f68` | October 22, 2024 |

These source snapshots all predate the evaluated June 4, 2026 Laniakea revision. The dates come from the resolved repository history; they establish source chronology, not deployment chronology or the first introduction of each component. Full revision identifiers and version associations are allocated to Appendix F.

The components came from mixed historical revisions, rather than a single unified release. MainnetController and ForeignController were inspected as alternatives within the same family, not as two Controllers presumed to form one deployed stack. ForeignController source inspection does not establish a foreign-network deployment. Nor does identifying a repository and revision demonstrate that deployed machine code exactly reproduces a build of that source. That separate equivalence question remained unresolved.

### What the source code supports

The static review found concrete behavior materially corresponding to the generic legacy PAU description. Controller code directed actions through ALMProxy and interacted separately with RateLimits. This relationship was visible in operational call paths, not merely component names or constructor parameters. The proxy did not itself call RateLimits; the Controller coordinated the two components.

ALMProxy provided permission-controlled execution and custody infrastructure. Its `doCall` function forwarded calls from the proxy only after checking that the caller held the required contract role. Ordinary `doCall` forwarded no ETH value; other execution mechanisms also existed, with their details allocated to Appendix F. The source supported the capacity to hold and direct assets, but did not establish any actual custody amount. Permission checks were part of the implementation, rather than an assumption that any contract named Controller could use the proxy.

RateLimits maintained separate records identified by keys, allowing limits to apply to particular operations or combinations of action, asset and destination. For a finite limit, its state recorded a maximum, a replenishment rate, the last stored remaining capacity and the time of that update. Available capacity was calculated from the stored amount plus replenishment over elapsed time, capped at the configured maximum.

This was lazy replenishment: capacity was calculated when read or used, without requiring a scheduled background process to write each increment. Relevant operations consumed capacity, while other operations could restore it. A zero replenishment rate supplied no time-based increase, and an explicit unlimited setting behaved differently from an ordinary finite limit. Finite and unlimited configurations could therefore coexist across keys.

The accounting was action-specific. Some paths consumed capacity before an external call, others accounted afterward, and some checked that a limit existed without consuming a finite budget. Rate-limit parameter replacement was separately restricted to an administrative role. The review did not establish that every Controller method consumed a finite allowance or that Controllers themselves could change all maximum and replenishment parameters.

Relevant interfaces and dependencies were examined at the corresponding historical revisions, including the code supporting call forwarding and access checks. This supported the scoped behavioral correspondence across the selected components. It was not an exhaustive review of every method, external integration or dependency, and did not certify arithmetic safety, security or complete cross-version compatibility. At this stage, actual deployment and configured permissions still required independent chain evidence.

### Historical and current Mainnet observations

The chain review used Ethereum Mainnet, chain ID **1**, at two fixed blocks. The historical observation represented the chain state immediately before the Laniakea subject timestamp. The later observation provided a fixed comparison point during the September evaluation.

| Observation | Block | Date and time, UTC | Purpose |
|---|---:|---|---|
| Historical baseline | 25,242,585 | June 4, 2026, 07:38:47 | Test the scoped legacy description against historical state. |
| Current retained observation | 26,007,670 | September 18, 2026, 23:26:35 | Test whether the same component relationships and representative configuration were retained. |

“Current” throughout this case means the retained September observation, not publication-time monitoring. Substantive state observations were fixed to these blocks, and their block hashes were rechecked. Historical state was tested directly rather than inferred from the age of a later registry entry.

Records of the fixed observations were retained, with baseline checks as described above. Detailed response-retention, state-proof and provider limitations, along with checksums, are allocated to Appendices F and I. Two fixed observations can establish state at those points; they cannot fill the interval between them.

### The deployed stack and wiring

The tested Mainnet components were identified through the Spark address registry. The registry-linked stack comprised:

| Component | Ethereum Mainnet address |
|---|---|
| MainnetController | `0x5c46Fc65855c0C7465a1EA85EEA0B24B601502D3` |
| ALMProxy | `0x1601843c5E9bC251A3272907010AFa41Fa18347E` |
| RateLimits | `0x7A5FD5cf045e010e62147F065cEAe59e5344b188` |

Code existed at each address at both snapshots. Each component's runtime hash—a fingerprint of its deployed machine code—was unchanged between the two observations. This was a comparison of deployed code at each address, not a match to a source build.

Wiring required more than code presence. The registry-linked Controller's stored references returned the tested ALMProxy and RateLimits addresses at both blocks. Both components also reported that this Controller held their required contract permission, named CONTROLLER. Together, these observations established the references and grants necessary for the scoped relationship.

The Controller's relevant operational roles, named RELAYER and FREEZER, were populated at both snapshots: two RELAYER members and one FREEZER member. The counts establish that those role sets were nonempty. Member identities, organizational ownership and control of the corresponding keys were not established, and the review did not enumerate unrelated governance or administrative roles.

The evidence also distinguished this Controller from an alternative listed in Atlas. The alternative had code and returned matching proxy and RateLimits references, but lacked both required component grants at both snapshots. Its role-count calls failed; those failures were not interpreted as zero members. Matching references alone were therefore insufficient to establish it as the wired instance.

This distinction came from historical and September chain observations, not from assuming that a September registry entry must describe June state. It does not establish why the documentary candidates differed, whether or when a migration occurred, or whether the alternative ever operated. Migration cause and date, governance intent and governance approval remain unestablished.

### Representative operational configuration

The evaluation selected `LIMIT_USDS_MINT`, a source-defined identifier for the USDS mint-operation limit, to test representative RateLimits configuration. At both snapshots, its stored parameters described a nontrivial finite limit: a positive finite maximum and replenishment rate, with remaining-capacity and update-time fields. This showed meaningful configured limits for the tested relationship beyond code presence alone.

The maximum and replenishment parameters differed between June and September. Configuration was therefore not simply assumed to be immutable because the runtime hashes were unchanged. The detailed raw values are allocated to Appendix F; no economic judgment about their adequacy follows from the finite classification.

The stored remaining amount referred to its recorded update time. It was not a newly calculated available capacity at the observation block and was not a token balance. This one key provided representative configuration evidence, not a complete inventory: it did not establish equivalent configuration for every key or operational readiness for every integration.

### Evidence of component usage

Bounded event queries added evidence beyond deployment and configuration. For the selected mint key, the retained analysis identified **67 historical consumption events** in blocks 25,235,386–25,242,585 and **122 current-window consumption events** in blocks 26,000,471–26,007,670. Each window covered 7,200 blocks ending at its observation baseline, rather than the whole period since deployment.

These counts were the exact mint-key selections from broader returned event sets. Detailed filtering, event-consistency checks and query qualifications remain in the evidence record and are allocated to Appendix F.

The events support consumption of the relevant RateLimits key within those windows. They do not identify the account or contract responsible for the event-producing call; attribution to the tested MainnetController therefore remains NOT ESTABLISHED. This missing caller attribution means the counts must not be read as 67 or 122 calls by the tested MainnetController.

The evaluation did not trace these transactions through the full system, and actual token transfers were not established from the events. The separate bounded search for the tested Controller's OTC swap event returned no matches. That absence does not prove no Controller use occurred: it concerns one event filter and two limited windows, not every possible action.

The resulting distinction is important. Deployment, wiring and representative configuration were established for the named stack at both baselines. Usage evidence was established separately for the RateLimits component. Combining those observations does not supply the missing caller attribution, comprehensive integration coverage or proof of continuous June-to-September operation.

### What changed and what remained

The comparison found the same tested component addresses, unchanged per-address runtime hashes, retained Controller references to ALMProxy and RateLimits, and the required component grants at both fixed points. Relevant operational roles remained populated. The representative mint key remained finitely configured, while its parameters changed.

This supports retained state at two observations. It does not establish that configuration never changed between them, that roles had uninterrupted membership, or that the system operated continuously throughout the interval. Nor does the June observation identify first deployment or activation. The observations establish what was present at the tested blocks, without reconstructing a complete deployment or migration history.

### Evidence depth reached

C05 is the report's strongest end-to-end grounding case because the evidence progressed from a documentary assertion through provenance and source identification to static behavior, historical chain state and a later retained observation. Each layer answered a different question: what was claimed, where its implementation could be inspected, what that code did, and what the tested Mainnet addresses showed at fixed blocks.

STL was evaluated as an evidence layer, but matched STL implementation coverage for C05 was NOT ESTABLISHED. The positive implementation binding came from separately resolved `sparkdotfi/spark-alm-controller` provenance. Later source and chain evidence did not rewrite the earlier phase results.

### What C05 establishes

Laniakea's scoped legacy Mainnet PAU description is materially grounded in implemented and historically deployed Sky/Spark infrastructure.

That conclusion rests on identifiable pre-June source revisions, behavior materially corresponding to the scoped description, historical Mainnet component deployment, wiring and representative configuration, and retained component state at the September observation. Bounded RateLimits consumption provides additional component-usage evidence. The conclusion is limited by the following exclusions; it is not broader assurance about the entire architecture or its operation.

### What C05 does not establish

| Boundary | Status | Why it matters |
|---|---|---|
| Specific Controller attribution of RateLimits events | NOT ESTABLISHED | Component consumption does not identify the account or contract that caused the event-producing call. |
| Exact source/runtime bytecode equivalence | NOT ESTABLISHED | Resolved source revisions and unchanged deployed hashes do not reproduce or prove an exact source build at each address. |
| Continuous June→September operation | NOT ESTABLISHED | Two snapshots and bounded event windows leave the intervening period unverified. |
| All-layer PAU deployment | OUTSIDE C05 | The Mainnet case does not establish deployment across every Generator, Prime, Halo or Foreign layer. |
| Comprehensive security/integration certification | OUTSIDE SCOPE | Selected source paths and chain observations are not a security audit or certification of every integration. |

First deployment and activation dates, governance approval, and migration cause or date also remain NOT ESTABLISHED. Custody amounts and balances were not comprehensively established, nor were all integrations or corresponding token transfers. Zero OTC matches do not prove that the Controller was unused. Exact source/runtime bytecode reproduction remains optional future assurance; it was not required for the scoped C05 conclusion.

### Why this result matters for the Laniakea evaluation

For this selected legacy claim, independent implementation and Mainnet evidence provide material grounding beyond Laniakea's conceptual description. The case demonstrates that some legacy/current-state narrative can be connected to implemented and historically deployed Sky/Spark infrastructure, subject to the limits immediately above. It does not establish all current claims, implementation of target architecture or governance authorization for every described component. C45's broader deployment claim remains unresolved.

The next section, **Unresolved Provenance: C06**, examines the contrasting case. C05 shows what becomes possible when source identity is sufficiently established to support implementation and chain review; C06 did not reach that provenance threshold. The distinction concerns the evidence available for evaluation, not an inference that an unidentified implementation does not exist.

### Evidence notes


- **S6-1.** `synthesis/master-evidence-matrix.md` — C05, C45, L3D-C05, L3E-C05, L3F-C05, C05-FINAL; C05 source/chain boundary and publication constraint.
- **S6-2.** `synthesis/report-architecture.md` — Implementation and Mainnet Grounding; C05 anti-repetition drafting rule; Appendices F/I.
- **S6-3.** `reports/2026-09-18-f438819/L3D-C05-repository-resolution.md` — Revision and version binding; Component and family result.
- **S6-4.** `reports/2026-09-18-f438819/findings/L3D-01-C05-repository-identity.md` — Revision resolution and versions; Exact source files; Chronology.
- **S6-5.** `reports/2026-09-18-f438819/L3E-C05-static-binding.md` — Exact sources and dependencies; Behavior and Laniakea fidelity.
- **S6-6.** `reports/2026-09-18-f438819/findings/L3E-01-C05-static-implementation-binding.md` — Source identity, integrity and mixed revisions; §§3–11 source behavior and qualifications.
- **S6-7.** `reports/2026-09-18-f438819/L3F-C05-mainnet-chain-validation.md` — Fixed baselines; Component results; Representative configuration; Usage and interpretation.
- **S6-8.** `reports/2026-09-18-f438819/findings/L3F-01-C05-mainnet-chain-binding.md` — §§2–7 provenance, observations and bounded usage; Derivation, impact and limits.
- **S6-9.** `reports/2026-09-18-f438819/L3F-evidence/README.md` — Evidence schemas and retention limits.
- **S6-10.** `reports/2026-09-18-f438819/L3F-chain-log.md` — Log-filter limitation and correction; Retention and reproducibility.
- **S6-11.** `reports/2026-09-18-f438819/leads.md` — C05 closure — L3F.
- **S6-12.** `reports/2026-09-18-f438819/L3F-evidence/address-provenance.tsv` — Documentary candidates recorded before chain testing.
- **S6-13.** `reports/2026-09-18-f438819/L3F-evidence/baseline-historical.txt` — Historical block, timestamp and hash recheck.
- **S6-14.** `reports/2026-09-18-f438819/L3F-evidence/baseline-current.txt` — Retained September block, timestamp and hash recheck.
- **S6-15.** `reports/2026-09-18-f438819/L3F-evidence/code-historical.tsv` — Historical code presence and runtime hashes.
- **S6-16.** `reports/2026-09-18-f438819/L3F-evidence/code-current.tsv` — September code presence and runtime-hash comparison.
- **S6-17.** `reports/2026-09-18-f438819/L3F-evidence/wiring-historical.tsv` — Historical component references.
- **S6-18.** `reports/2026-09-18-f438819/L3F-evidence/wiring-current.tsv` — September component references.
- **S6-19.** `reports/2026-09-18-f438819/L3F-evidence/roles-historical.tsv` — Historical grants, role counts and failed alternative count calls.
- **S6-20.** `reports/2026-09-18-f438819/L3F-evidence/roles-current.tsv` — September grants, role counts and failed alternative count calls.
- **S6-21.** `reports/2026-09-18-f438819/L3F-evidence/ratelimits-historical.tsv` — Historical finite mint-key state.
- **S6-22.** `reports/2026-09-18-f438819/L3F-evidence/ratelimits-current.tsv` — September finite mint-key state and changed parameters.
- **S6-23.** `reports/2026-09-18-f438819/L3F-evidence/usage-historical.tsv` — 67 selected mint-key consumption records, as scoped by the chain finding and log.
- **S6-24.** `reports/2026-09-18-f438819/L3F-evidence/usage-current.tsv` — 122 selected mint-key consumption records, as scoped by the chain finding and log.

## 7. Unresolved Provenance: C06

### The C06 question

Laniakea describes a live legacy Configurator stack involving Configurator, BEAMTimeLock, BEAMState and bounded cBEAM operations. The selected claim, C06, concerns that particular implementation relationship. Its description combines configuration functions, timelocked additions, stored configuration state and operations subject to limits. Those are claims to examine, not observations that the evaluation independently confirmed.

Before assessing the behavior or deployment of this stack, the evaluation needed to identify its implementation source. Which repository and files implemented the named components? Did the source predate the evaluated June 4, 2026 snapshot? Did the components belong to the same legacy implementation, and could that source be connected reliably to addresses for later runtime verification?

Names alone could not answer these questions. A different protocol's Configurator, a general-purpose timelock or requirements text describing bounded operations might resemble part of the claim without identifying its implementation. The supporting Laniakea document contained business requirements and interface sketches; these helped define the question but did not supply the missing source attribution. Future governance arrangements and onboarding prerequisites were not treated as evidence of current deployment.

### The initial STL result

The frozen STL result for C06 was **NO MATCHED STL COVERAGE ESTABLISHED**. PoolConfigurator references concerned other protocol interfaces and address-discovery contexts. Generic configuration material did not identify the required legacy stack, unrelated timelocks did not establish BEAMTimeLock, and HTTP request limits did not establish bounded cBEAM contract behavior.

This result concerns the match required for implementation review. It does not mean the implementation was nonexistent, the Laniakea claim was false or STL contained nothing relevant. As the preceding STL section explains, related technical material can be useful without supplying the implementation source needed for a particular claim.

### Local provenance leads

The local review did identify leads worth retaining. Laniakea named OpenZeppelin TimelockController with pause capability, providing a library-family reference. It did not identify an exact package version or the source of the complete legacy Configurator relationship. A named library could therefore guide further attribution, but could not stand in for the whole stack.

Later Atlas material describing the Diamond PAS architecture recorded Configurator, BeamState and Timelock names and addresses. The descriptions included related configuration concepts, making them more specific leads than the generic STL matches. They remained documentary leads: the records did not identify the exact legacy repository, source files or revisions, or explicitly connect the legacy stack to PAS.

Naming similarity did not supply the source connection needed to identify the later PAS components with the legacy stack. A legacy-to-PAS bridge would be a dated evidence connection linking the legacy Configurator stack to the later PAS components. No such connection established identity, migration or renaming.

### Why the provenance trail stopped

No concrete external retrieval target was established for the legacy implementation. In practical terms, the available evidence did not identify a sufficiently specific repository, package, verified-source artifact or equivalent location that could be retrieved and inspected as that implementation.

Without an adequately identified implementation source, targeted external retrieval was not justified and there was no reliable basis for a static behavioral comparison. Chain verification remained on **HOLD**. This stopping point reflected the missing source connection, not a test result showing defective code or unsuccessful deployment.

This was a bounded review, not an exhaustive search proving that no repository existed elsewhere. Selecting a similarly named repository or constructing a retrieval path from a later address would have substituted an assumption for evidence of identity.

### BLOCKED versus NOT ESTABLISHED

The external architecture source, `archon-research/architecture`, was unavailable to anonymous Git access during setup and remained unaccessed. **BLOCKED** records that access limitation only. No evidence established that this repository necessarily contains the missing Configurator implementation; its unavailable contents cannot be assumed to resolve the source identity.

Local work still proceeded across the available documentary and technical sources. The main C06 evidence result remains **NOT ESTABLISHED**: those sources did not sufficiently identify the legacy implementation. Architecture access was one inspection limitation, not an explanation for every unresolved aspect of C06.

### Later PAS material did not close the legacy gap

The retained chronology placed the inspected Diamond PAS Configurator and BeamState records in August 2026, with addresses and fuller descriptions added later that month. Those documentary additions postdated the June 4 Laniakea snapshot. Their dates locate the records in history, not the first existence or deployment of the underlying contracts.

Later documentation can help assess an earlier claim when a source connection is established. Here, the later names and addresses remained relevant leads, but no dated connection to the legacy source was established. The relationship remains **NOT ESTABLISHED**: the chronology identifies PAS neither as a definite successor nor as unrelated to the legacy stack.

### Why chain validation did not proceed

Chain observations answer questions about particular addresses at particular times. To answer C06, those targets first needed a sufficiently supported relationship to the claimed legacy implementation. Otherwise, a check could examine a different contract while appearing to verify the claim.

Observing a later, similarly named PAS component would not by itself answer whether Laniakea's legacy Configurator was deployed. Conversely, absence at a guessed address would not show that the implementation did not exist elsewhere. No such substitute target was adopted, and no C06 chain verification was performed.

**HOLD** is therefore a workflow gate: the prerequisites for chain verification were not met. It is not a negative implementation finding or evidence of nondeployment. Historical and current runtime remained untested, and the legacy-live assertion remained unestablished.

### Current synthesis disposition: PARKED

The legacy Configurator implementation identity and legacy-to-PAS relationship were not established in this evaluation; C06 is parked pending qualifying new provenance evidence.

**PARKED** describes the synthesis decision to set further verification aside pending a new lead. It is not an original repository grade, a finding of falsehood or nonexistence, or permanent closure. The historical repository result remains NOT ESTABLISHED; architecture access remains BLOCKED where applicable; and the chain gate remains HOLD.

Without a more specific source lead, further inspection of the same kinds of names and related records is unlikely to improve confidence in the legacy identity. Parking the question preserves the unresolved live/deployed status while avoiding unsupported further inference.

### What would justify reopening C06

The existing finding identifies specific kinds of evidence that could justify reconsideration:

- Explicit repository, path or package attribution for the legacy Configurator stack.
- A dated legacy-to-PAS source connection.
- A verified-source artifact identifying all required legacy components.
- Equivalent new provenance evidence meeting the same source-identification requirement described in the finding.

Names or addresses alone remain insufficient. The new evidence must connect the legacy claim to a source identity strongly enough to permit direct inspection and, where appropriate, later component/address and chain verification. Such evidence would justify further inspection; it would not automatically establish implementation behavior or deployment. These conditions define what would justify revisiting C06 without lowering the existing evidence standard.

### What C06 establishes and does not establish

The reviewed evidence left source attribution unresolved, with related leads retained. The evidence results, access limitation and decisions about further work answer different questions:

| Question | Result | Meaning |
|---|---|---|
| Legacy source identity | NOT ESTABLISHED | No sufficiently supported source for the claimed legacy stack was identified. |
| Legacy → PAS bridge | NOT ESTABLISHED | Related later records did not establish a dated implementation-identity connection. |
| Concrete external retrieval target | NONE | No qualifying legacy source target was identified in the reviewed evidence. |
| Static implementation review | NOT OPENED / NOT TESTED | A matched implementation was not available for behavioral comparison. |
| Historical runtime | NOT TESTED | No historical C06 chain verification was performed. |
| Current runtime | NOT TESTED | No current C06 chain verification was performed. |
| Live/deployed assertion | NOT ESTABLISHED | Deployment and operation were not independently established. |
| Repository evaluation result | NOT ESTABLISHED | The evidence did not meet the legacy implementation-identification requirement. |
| Chain gate | HOLD | Verification awaits an adequately identified target. |
| Synthesis disposition | PARKED | Further work is set aside pending qualifying provenance evidence. |
| Architecture source availability | BLOCKED — access limitation only | The external source was unavailable; its contents and necessity for C06 were not established. |

C06 does not establish implementation nonexistence or falsehood of the Laniakea claim. It establishes neither deployment nor nondeployment, neither equivalence nor non-equivalence with later PAS, and no implementation chronology, code/address binding or runtime behavior. Missing provenance and an absent retrieval target describe the evidence available to this evaluation, not proof of a missing implementation or repository.

### Why this result matters

The unresolved result preserves a meaningful evidence threshold. Related documentation was not promoted into implementation proof, and chain observations were not gathered against an inadequately identified substitute. The result identifies what remains missing from the evidence needed to assess the legacy claim, without treating that gap as a failure of Laniakea or STL.

C05 and C06 differ here in evidence maturity: C05 obtained sufficiently specific provenance to continue into source and chain review; C06 did not. This comparison does not rank the underlying implementations as good or bad. The broader synthesis that follows brings these different outcomes together, alongside claims not independently verified in Report v1 and target architecture whose future-state status must remain distinct from current implementation.

### Evidence notes


- **S7-1.** `synthesis/master-evidence-matrix.md` — C06, L3A-C06, L3B-C06 and C06-FINAL; status definitions.
- **S7-2.** `synthesis/report-architecture.md` — Unresolved Provenance: C06; Appendices E/G.
- **S7-3.** `reports/2026-09-18-f438819/L1-claim-map.md` — C06; C50 onboarding-prerequisite boundary.
- **S7-4.** `reports/2026-09-18-f438819/L3A-STL-binding-C05-C06.md` — Results; Decision gate for later chain verification.
- **S7-5.** `reports/2026-09-18-f438819/findings/L3A-02-C06-legacy-configurator-stl-binding.md` — Claim under test; STL coverage result; Live/deployment status; Reopen conditions.
- **S7-6.** `reports/2026-09-18-f438819/L3B-implementation-provenance-C05-C06.md` — Cross-claim provenance map; Retrieval decision and chain gate.
- **S7-7.** `reports/2026-09-18-f438819/findings/L3B-02-C06-legacy-configurator-provenance.md` — Provenance leads; Chronology; Network/chain gate; NOT ESTABLISHED / BLOCKED; Invalidated-by / reopen conditions.
- **S7-8.** `reports/2026-09-18-f438819/leads.md` — L3B C05–C06 provenance results and remaining leads.
- **S7-9.** `pins/baseline.md` — Architecture availability at setup.

## 8. Unverified and Target Architecture

### Not Independently Verified in Report v1

#### Why some current-state claims remain unverified

Some statements in the evaluated Laniakea snapshot assert present implementation or operation but were not advanced through the independent evidence path needed for a substantive finding in Report v1. The report preserves these assertions as **NOT INDEPENDENTLY VERIFIED**. That disposition does not mean they are false, disproven or failed implementations.

Eleven selected statement units fall into this population. Operational verification was deliberately deferred for three. Verification of the other eight depended on unavailable architecture evidence and unresolved source prerequisites. These groups describe different reasons for non-verification, not additional evidence grades.

The population is drawn from the selected claim map, not an exhaustive inventory of every current-state assertion in Laniakea. A source statement can be clear about what it claims while its truth remains unverified. Conversely, an unresolved current-versus-future classification is a different problem and is not silently assigned to this group.

#### Deferred operational verification

The three deferred operational units are C10, C11 and C39. Each retains **NOT INDEPENDENTLY VERIFIED**. They identify concrete policy, configuration or operation questions, but the necessary independent checks were intentionally not completed before Report v1.

The temporary SKY buyback claim describes fixed-amount purchases and distribution to stakers. Its approximately $300,000 daily amount is part of the source assertion, not an independently observed result. Monthly fee realization and issuance-time routing form a separate operational claim: the Atlas fee-policy comparison discussed earlier does not establish that payments occurred. The disabled SKY emissions backstop is likewise an assertion about present configuration; it does not demonstrate either that configuration or an implemented future upgrade.

These remain possible targets for future independent verification if their importance warrants further work. This report does not determine whether buybacks are happening, whether fees are being realized or whether the emissions trigger is disabled. It does not make further verification a mandatory remediation requirement.

#### Architecture/provenance-dependent current claims

The eight architecture/provenance-dependent units retain **NOT INDEPENDENTLY VERIFIED**. Architecture verification was blocked; implementation identity and related prerequisites were insufficient for substantive independent verification. This access limitation is not evidence that the claimed systems were absent or that deployment failed.

The Rule-Author and Noemar assertions concern implemented rule discovery, a specified truth-value framework and an initial running instance. Their current-state language remains visible. In particular, describing the crystallization pattern as illustrative, evolving and noncanonical limits its authority as a definitive design; it does not retract the separate assertion that an instance runs. No equations or implementation code were validated for these units.

The Phase 1, or P1, assertions concern a daily settlement cycle, reporting at each heartbeat, temporary allocation, named Oracle instances and a limited active risk surface. A daily synomic clock is distinct from economic closure or monthly reconciliation. The claimed reporting output, labeled ER, does not by itself establish automated enforcement. The temporary allocation mechanism, labeled SDR, is distinct from later real auctions. A stub specification for an Oracle type neither proves nor disproves the operation of the specifically named instances.

#### Overlap and counting boundaries

The eleven units are selected statements retained for traceability, not eleven wholly independent systems or failures. C07 and C09 overlap as a Rule-Author implementation/operation cluster. C13 and C14 overlap with the broader P1 risk-surface assertion in C16. No count of independent underlying verification propositions is inferred from the row count.

Related gaps retain their separate treatment: C17/C18 remain under the X1 documentary conflict and HOLD; unresolved governance mappings and ambiguous claims are not relabeled; C06 remains PARKED.

#### What “not independently verified” means here

For these eleven selected units, the source assertion is recorded, but Report v1 did not complete the external evidence path required for a substantive affirmative or negative finding. Their disposition therefore remains **NOT INDEPENDENTLY VERIFIED**. This does not convert them to FALSE, FAILED or NOT ESTABLISHED; any separately recorded historical result remains as assigned in the frozen matrix.

#### Current claims left for later verification

The subjects below summarize source claims, not adopted findings. Exact technical propositions remain preserved in the frozen matrix and are allocated to Appendix H for publication traceability. “Architecture” refers to the architecture/provenance-dependent group above.

| Group | Claim ID | Reader-facing subject | Why verification did not proceed in Report v1 | Report v1 disposition |
|---|---|---|---|---|
| Deferred operational | C10 | Claimed temporary fixed SKY buybacks and staker distribution. | Independent Atlas/chain operational verification deferred; amount untested. | NOT INDEPENDENTLY VERIFIED |
| Deferred operational | C11 | Claimed monthly upkeep-fee realization and creation-fee routing at issuance. | Payment verification deferred; policy comparison does not establish realization. | NOT INDEPENDENTLY VERIFIED |
| Deferred operational | C39 | Claimed disabled SKY emissions backstop. | Independent verification of actual policy, configuration and use deferred. | NOT INDEPENDENTLY VERIFIED |
| Architecture | C07 | Claimed current Rule-Author rule discovery with regression checks. | Architecture verification blocked; implementation not independently checked. | NOT INDEPENDENTLY VERIFIED |
| Architecture | C08 | Claimed current implementation of Noemar's strength/confidence framework using PLN truth values. | Architecture verification blocked; equations and code not evaluated. | NOT INDEPENDENTLY VERIFIED |
| Architecture | C09 | Claimed first running Rule-Author/crystallization instances. | Architecture verification blocked; running-instance assertion unverified. | NOT INDEPENDENTLY VERIFIED |
| Architecture | C12 | Claimed live Phase 1 daily synomic settlement cycle. | Architecture verification blocked; production operation not observed. | NOT INDEPENDENTLY VERIFIED |
| Architecture | C13 | Claimed Phase 1 reporting output (ER) at each heartbeat. | Architecture verification blocked; output and formula truth not checked. | NOT INDEPENDENTLY VERIFIED |
| Architecture | C14 | Claimed temporary, ownership-weighted Phase 1 allocation (SDR). | Architecture verification blocked; claimed mechanism not independently checked. | NOT INDEPENDENTLY VERIFIED |
| Architecture | C15 | Claimed Phase 1 operation of Crypto Majors Oracle and Book Attestation Oracle. | Architecture verification blocked; named-instance operation unverified. | NOT INDEPENDENTLY VERIFIED |
| Architecture | C16 | Claimed active Phase 1 risk surface and related controls. | Architecture verification blocked; active risk-surface assertion unverified. | NOT INDEPENDENTLY VERIFIED |

### Target Architecture and Future-State Material

#### Target architecture is a different evidence category

A substantial part of the selected Laniakea material describes proposed architecture, conceptual mechanisms, target specifications or future roadmap work. These statements describe what is proposed or intended, rather than necessarily asserting what operates today. Their **TARGET DESIGN** disposition must remain separate from the current-state claims above.

The proposed-state protection applied in the evaluation was straightforward: a future or target statement was not treated as a current implementation failure merely because it was unimplemented. This does not endorse the design. It identifies the appropriate question before testing begins. Equally, a general draft label cannot erase a specific assertion of present implementation or a running instance.

#### The selected TARGET DESIGN population

The frozen matrix assigns **TARGET DESIGN** to exactly 23 selected units. Their temporal classifications remain 16 **PROPOSED-TARGET** units and seven **FUTURE-ROADMAP** units:

| Existing classification | Exact claim IDs | Count |
|---|---|---|
| PROPOSED-TARGET | C19, C20, C21, C22, C23, C24, C25, C29, C30, C31, C34, C36, C40, C41, C42, C48 | 16 |
| FUTURE-ROADMAP | C26, C27, C32, C33, C35, C37, C38 | 7 |

Detailed propositions and row-specific qualifications remain in the frozen matrix, with publication traceability allocated primarily to Appendix H.

This is the complete TARGET DESIGN population in the selected matrix, not a count of all future-oriented statements in the corpus. Historical, illustrative, ambiguous and unverified-current rows are excluded. In particular, the ambiguous adoption and capital-requirement statements, all-layer deployment claim, and implementation/activation language retain their separate unresolved treatment. A future concept appearing in a passage is not enough to move that passage into this population.

#### Target and future material by theme

##### Post-transition governance and Atlas/Synome structure

The governance proposals include quarterly rotation of six of 24 Council seats through SKY polls and Council enactment (C20), post-transition SpellCore/SpellGuard arrangements replacing legacy voting through Guardian-token and dual-key Prime/Halo mechanisms (C21), and graduated SKY-holder freeze and Council-dismissal powers (C22). These are target arrangements, not observations of current elections or authority.

The information-structure proposals describe a shortened constitutional Atlas of about 10–20 pages (C29) and movement of operational prose into structured Synome nodes (C30). The five-layer model, Atlas/Synome split and beacons are described as live commitments (C48), but remain conceptual/target scope. Their presence in Laniakea establishes neither completed deployment or migration nor current Sky authorization.

##### Contract standards and entity infrastructure

Diamond PAU (C23) is a target replacement for the legacy single Controller, with a placeholder specification. LCTS (C24) is a draft standard for risk-capital token queues and daily locking and settlement. NFATS (C25) describes draft facilities with per-deal tokens and queues; P1 bookkeeping does not establish full facility deployment.

The Yield Splitter/PT-YT rollout (C26) remains unscheduled future work, dependent on unscheduled LCTS interfaces; the native orderbook is also unscheduled. Tentative later-phase discussion is not an operational commitment. Core Entity management and failed-entity wrapping (C40) remain target modes, with the documentation explicitly describing the type as not instantiated in P1. Identity Network registries and transfer-related attestations (C41) are also target services; that classification does not resolve the separate missing canonical Sky Intents destination.

C05's legacy Mainnet result does not establish any of these target implementations or deployments.

##### Cognitive agents and recursive improvement

The general recursive-improvement ladder (C31) describes a target for improving knowledge across artifact levels through feedback. Cognitive Sentinels (C27) are expressly future scope outside P1, while L4 source rewriting (C32) is far-future work. The autonomy level L4 is not an evaluation phase.

These broader designs remain distinct from the limited current Rule-Author assertions. The accompanying description of P1 deterministic relays is not independently verified here. No current Sentinel-authority or autonomy-performance conclusion follows from this classification.

##### Economic closure, activation and incentives

Economic closure per Prime and global aggregation within the Synome are placed outside P1 as target scope (C19). The conflicting P1 assertions remain unresolved in X1: preserving this classification does not select a documentary winner or decide actual operation.

Distribution and tagging incentives (C34) remain target scope; the reward mechanism labeled SDRR depends on fee-paying real auctions. Growth Staking activation (C33) is placed after P1; the source says rewards are not yet distributed through synserv. This documentary timing is distinct from generic SKY staking and is not independent observation of activation or reward flows. Real auctions and the tug-of-war sequence (C35) are Phase 9+ design, separate from the claimed temporary P1 allocation. Dynamic burn behavior (C38) is Phase 2+ future scope conditional on deployment of the SBE BEAM mechanism, distinct from the current buyback assertion.

The phase labels and dependencies specify the proposed sequence; they do not establish an implementation schedule or actual payments.

##### Speculative and broader risk design

The potential feature labeled MDC (C36) is explicitly speculative and may never be implemented. The additional independent-trader metric (C37) is described as planned and not yet implemented. The broader risk-control framework (C42), including capital routing among multiple sub-books and concentration excess, remains target scope distinct from the narrower P1 risk-surface assertion.

No capital formula, equation, implementation or feasibility judgment was made for these units. A speculative feature need not become an implementation commitment simply because it appears in the design corpus.

#### Proposed/target versus future/roadmap

PROPOSED-TARGET describes a desired or specified architecture without establishing current implementation. FUTURE-ROADMAP describes planned, later-phase, unscheduled or far-future work. Both map to TARGET DESIGN here, but their original temporal distinctions remain useful: a draft standard, a phase-dependent activation and a speculative mechanism are not identical commitments.

Neither classification establishes current deployment, and neither supports a missing-implementation failure. The report also does not infer worldwide nonexistence from the absence of independent implementation binding in this evaluation.

#### Governance formalization

Some target arrangements may differ from current Atlas structures or authority mappings. Where they do, future governance formalization may be needed before a proposed arrangement becomes current Sky governance authority. Laniakea design prose does not create that authority by itself.

This conditional dependency does not mean every target claim requires an Atlas amendment, every difference is a defect, or future governance will adopt a proposal. It preserves the distinction already established in the Atlas comparison without making additional comparisons here.

#### Implementation evidence for target material

Testing a target design against implementation becomes appropriate when a relevant implementation exists, its provenance can be established and the claim is concrete enough to test. Source inspection and deployment or operational verification then answer separate questions. A source repository alone does not demonstrate deployment; deployment alone does not establish every described behavior.

The earlier C05 case illustrates the depth that sufficiently identified evidence can support for one scoped legacy claim. It is not evidence that the target architecture has been implemented. Each future assessment would need its own component, revision, scope and evidence relationship.

#### What Report v1 says about target architecture

The evaluated snapshot contains substantial target and future architecture, intentionally separated from current-state assertions. Report v1 does not treat nonimplementation as failure, certify technical feasibility or readiness, or establish future governance adoption. It offers no finding that these designs are sound, unsound or certain to be built.

Their classification preserves what kind of proposition the source makes. A material change in documentary status, governance status or implementation evidence can make a particular unit suitable for later evaluation without changing what the frozen snapshot said.

#### Delta-evaluation principle

Report v1 provides a frozen baseline against which later changes can be assessed. A delta evaluation examines what has changed and which conclusions that change could affect, rather than restarting the entire assessment.

Possible triggers include a target claim becoming current-state language, an implementation source becoming available, a deployment, governance formalization or a material documentary-status change. These are potential grounds for separately authorized review, not findings that such changes have happened or mandatory remediation items. The later Open Questions and Future Work section addresses that process in greater detail.

#### Combined perspective

For the eleven selected current-state units discussed here, incomplete independent verification leaves the Report v1 disposition as **NOT INDEPENDENTLY VERIFIED**. For the 23 selected future or target units, the disposition remains **TARGET DESIGN**. These are different reasons for withholding a current implementation conclusion; neither is a negative verdict.

Together, the two sections make the report's coverage and interpretive limits explicit. They provide context for the broader Principal Synthesis Findings, the Limitations, and Open Questions and Future Work, where supported results and remaining questions can be considered without promoting either unverified assertions or future designs into present fact.

### Evidence notes


- **S8-1.** `synthesis/master-evidence-matrix.md` — Exact NOT INDEPENDENTLY VERIFIED and TARGET DESIGN populations; propositions, classifications, limitations and reopening triggers.
- **S8-2.** `synthesis/report-architecture.md` — Sections 10–11; two populated current-claim groups, empty third category, five target themes and future delta boundaries.
- **S8-3.** `reports/2026-09-18-f438819/L1-claim-map.md` — Selected statement units; classification rules; overlaps; X1 and ambiguity preservation.
- **S8-4.** `reports/2026-09-18-f438819/findings/L1-03-proposed-state-protection.md` — Future/target protection, current-assertion boundary and limits of classification.
- **S8-5.** `reports/2026-09-18-f438819/findings/L1-05-ambiguity-preservation.md` — Unresolved classifications; illustrative versus running-instance distinction.
- **S8-6.** `reports/2026-09-18-f438819/leads.md` — Deferred operational queue; architecture-dependent queue; overlap and retained verification boundaries.

## 9. Limitations and Future Work

### Limitations

The report's conclusions are bounded by the frozen snapshot, selected claim scope and evidence actually obtained. These limitations define how the findings can be interpreted. They neither erase supported findings nor convert unresolved matters into negative findings. A boundary on this evaluation is not automatically a defect in Laniakea or a requirement for further work before publication.

#### Snapshot limitation

Laniakea, Atlas and STL were examined at fixed revisions with different dates. Chain evidence likewise concerns specified observations. Later changes are outside Report v1 unless explicitly incorporated; the report does not describe every source's state at publication time.

For C05, the historical Ethereum Mainnet observation was block 25,242,585 on June 4, 2026; the retained September observation was block 26,007,670 on September 18, 2026. “Current” in that evidence means the fixed September observation, not publication-time monitoring. The two observations do not establish the interval between them.

#### Corpus-coverage limitation

The claim map contains 53 selected statement units, not exhaustive corpus coverage or 53 independent propositions. Some units overlap. X1 and U1–U4 are separately retained conflict and unresolved-context records, not extra selected claim units. Not every sentence received substantive implementation verification.

Selection limits the breadth of the report, but does not prevent strong conclusions about a well-supported, narrowly defined claim. C05 illustrates that distinction. Neither its grounding nor the absence of comparable verification elsewhere establishes the condition of unreviewed material.

#### Documentary-extraction limitation

Deterministic extraction supplied reproducible inventories and candidate references for human interpretation. It did not establish semantic truth or complete recall. Lexical patterns can miss implicit references or select text that is not a substantive claim. Complex linking and anchoring patterns can also require interpretation beyond deterministic extraction.

External destinations were not validated by that extraction. A path missing under one interpretation of the pinned tree is not necessarily absent elsewhere. An address literal does not establish address validity or use; an extracted formula does not establish mathematical or economic correctness. Nor can extraction select the authoritative document or infer a passage's status from its directory alone. Candidate rows therefore cannot be treated as counts of validated claims or defects.

#### Documentary/canonicality limitation

Two slideshow files retain stale/ambiguous status outside ordinary active consultation. The designated canonical Sky Intents destination is missing, ordinary broken internal navigation exists, and capital-stack's use of an inactive whitepaper as canonical remains unclear in authority and scope.

These issues affect document selection and traceability, including which source is intended to be authoritative for a topic. They do not independently establish implementation defects, security defects or runtime failure. The snapshot-characterization section gives their individual scope; no global documentation-failure verdict follows here.

#### Runtime limitation

Source inspection establishes behavior in the inspected source, not live operation. Deployment does not by itself prove active use. In C05, one representative RateLimits key and bounded consumption events support scoped configuration and component-usage findings; they do not establish every key, integration or system activity.

The events do not identify the account or contract responsible for the event-producing call. Attribution to the tested MainnetController remains **NOT ESTABLISHED**. Corresponding token transfers and complete transaction paths were not established, and comprehensive integration verification was outside the evaluation. Zero matches for the bounded Controller OTC-event query do not prove no Controller use. All-layer PAU deployment remains **OUTSIDE C05**, and broader runtime questions were not all attempted.

The retained records support the scoped findings but do not constitute complete raw-RPC retention, cryptographic state proofs or evidence of independent-provider agreement. Report v1 adds no new reproducibility run or evidence-manifest verification beyond the frozen evidence set. Detailed retention limits belong in Appendix I.

#### Provenance limitation

Implementation source identity was resolved for the scoped C05 case, but not for every claim. C06's legacy Configurator implementation identity remains **NOT ESTABLISHED**. Later PAS names and addresses did not establish the missing legacy connection.

STL registry, observer and related technical material can help locate evidence without identifying the complete implementation source. Requirements, examples and source-family similarities have comparable limits. Unavailable or unbound sources cannot be replaced with inference. In particular, architecture-source inaccessibility does not establish that it contains a missing implementation. These are claim-specific limits, not a judgment that provenance is uniformly poor across Laniakea.

#### Chain-history limitation

C05 establishes tested state at two fixed points. Unchanged per-address runtime hashes, retained wiring and relevant configuration do not establish uninterrupted June-to-September operation, continuous role membership or absence of intermediate changes. Continuous operation remains **NOT ESTABLISHED**.

The observations also do not identify first deployment or activation, reconstruct a complete migration history, or settle migration cause and date. Those historical questions differ from whether the tested stack was deployed, wired and configured at the two observations.

#### Bytecode limitation

Exact C05 source/runtime bytecode equivalence remains **NOT ESTABLISHED**. Historical component revisions were identified and deployed runtime hashes were observed, but the evaluation did not reproduce the source build and establish its exact correspondence to deployed bytecode. Identical runtime hashes across observations do not supply that source-to-runtime connection.

This does not invalidate the scoped C05 conclusion. Exact bytecode reproduction remains optional future assurance, not a requirement for C05 closure or Report v1 publication.

#### Governance-authority limitation

Laniakea prose does not itself create current Sky governance authority. Atlas documentary policy must also be distinguished from enactment, execution, payment and approval. The specific C02/C03 hierarchy and authority mappings remain **NOT ESTABLISHED**.

C04 is a mixed comparison within the shared Prime scope, not a universal fee-policy mapping or payment finding. Some target arrangements may require future governance formalization where they differ from current authority structures. This does not imply that every target requires an Atlas amendment, every discrepancy is erroneous or future governance will adopt a proposal.

#### Current-claim verification limitation

The eleven current-state units discussed in the preceding section retain **NOT INDEPENDENTLY VERIFIED**: three concern deferred operational verification and eight depend on architecture/provenance prerequisites. This disposition is not a negative finding and does not imply absent implementation. Their separate reasons for non-verification and overlap warnings remain applicable. Other unresolved claims retain their own dispositions rather than being absorbed into this population.

#### Security / audit boundary

This evaluation is not a security audit, comprehensive code audit, runtime certification, formal implementation-completeness certification or comprehensive integration audit. Selected static and chain evidence cannot be generalized into those assurances. Comprehensive security/integration certification remains **OUTSIDE SCOPE**, including for C05. Documentary findings are not vulnerability findings.

#### Limitations do not all have the same consequence

| Boundary | Consequence for interpretation |
|---|---|
| A selected component, key or snapshot | The supported conclusion stays within that scope. |
| An unresolved source identity or authority mapping | The particular question remains unresolved. |
| Independent verification not completed for the eleven selected current-state units | Those units retain NOT INDEPENDENTLY VERIFIED. |
| A target or future proposition | Present nonimplementation is not treated as a failure. |
| Additional source/runtime reproduction | Stronger optional assurance remains possible without invalidating scoped closure. |

These consequences are not interchangeable. None makes every open question a prerequisite to publishing Report v1.

### Open Questions and Future Work

Future work is organized by why a question would be revisited, rather than treating every unresolved item as remediation.

| Category | Meaning |
|---|---|
| Reopen on qualifying new evidence | New evidence could make an existing unresolved question answerable. |
| Optional assurance | An existing scoped conclusion is already sufficient, but stronger assurance could be added. |
| Delta-evaluate when the project changes | A delta evaluation compares a later material change with the frozen Report v1 baseline. |

#### Reopen on qualifying new evidence

“Reopen” means returning to an unresolved or bounded question when qualifying evidence appears. It does not mean reversing a negative finding or requiring the work to continue now.

##### C06 legacy Configurator provenance

C06 may be revisited if explicit legacy repository/path/package attribution, a dated legacy-to-PAS source connection, a verified-source artifact identifying the required components, or equivalent qualifying provenance becomes available. Similar names or addresses alone are insufficient.

Legacy identity remains NOT ESTABLISHED, architecture access remains BLOCKED only where applicable, chain verification remains HOLD and synthesis remains PARKED. C06 belongs in this evidence-triggered category, not optional assurance or target-design review. The required evidence would permit reconsideration; it would not automatically prove behavior or deployment.

##### X1 / settlement documentary conflict

The conflict could be reconsidered on pinned same-scope clarification, correction or version/retirement evidence that resolves the documentary disagreement. Until such evidence exists, neither documentary account should be selected as the operative one for this evaluation; actual operation also remains unestablished. A later repair is a change against the original snapshot, as described below.

##### Architecture source availability / binding

An accessible implementation or phase-status source would justify reconsideration only if evidence also connects it to the specific claim under review. Availability alone is not enough. The previously unavailable architecture repository is not assumed to contain the missing implementations, and an adjacent repository is not automatically an adequate substitute.

##### Deferred operational claims

C10, C11 and C39 may receive independent verification later if their importance warrants it and appropriate policy, configuration or operational evidence is available. Fee realization requires payment/operation evidence, not inference from C04's policy comparison. These remain optional verification choices; none must be resolved for Report v1 to close.

##### Existing authority mappings / exceptions

Reconsidering C02 would require explicit dated evidence mapping the claimed Guardian, executor and organizational-parent relationships. Reconsidering C03 would require authority-layer/phase evidence and an accessible phase-status source. C04's scoped policy differences could be reconsidered if dated exception, supersession or distinct-obligation evidence becomes available. Testing ambiguous capital-requirement and calibration statements would first require explicit dated clarification of their status and scope. No intentional divergence or new governance test is inferred.

##### Wider existing deployment/completion claims

Reconsidering C45 would require layer- and network-specific clarification together with implementation, address and date binding. Reconsidering existing completion/activation questions such as C46/C47 would require explicit dated scope statements distinguishing design, implementation and activation, with implementation evidence where applicable. These are unresolved existing-state questions, not a reason to treat the separate target-design population as failed deployment.

##### Documentary destinations/status clarification

An explicit current canonical destination, or a record clarifying ambiguity or retirement for the same scope, could resolve the Sky Intents question. Other relevant evidence includes a documented convention for resolving link paths, clarification of inactive-whitepaper authority, or an explicit decision on slideshow status. A similarly named document is not an inferred replacement. Establishing that a document faithfully reproduces an earlier source also requires evidence; documentary characterization alone does not verify an earlier snapshot verbatim.

##### C05 attribution/provenance gaps

Qualifying transaction-path evidence could identify the caller responsible for the RateLimits events. Dated provenance evidence could address a particular migration or source-attribution gap. Such evidence would answer only the specific question it supports, without automatically establishing continuity or complete history.

C05 is already **CLOSED for the current evaluation scope**. Revisiting these limited subquestions does not reopen the entire finding. The closed finding itself would be reopened only by evidence capable of materially changing its basis—for example invalid baseline/provider evidence, reorganization of a tested block, incorrect source-interface attribution, changed documented address scope or reliable bytecode binding that changes interpretation. A remaining limitation alone is not such a trigger.

#### Optional assurance

##### Exact C05 source/runtime bytecode reproduction

Exact equivalence remains NOT ESTABLISHED. Reliable reproduction could add stronger assurance connecting a source build to the deployed runtime. This work was explicitly not required for C05 closure and is not required for Report v1 publication. It is the sole optional-assurance item identified here; leaving it undone does not turn the scoped result into an incomplete or failed finding.

#### Delta-evaluate when the project changes

##### Future governance formalization

A target arrangement becoming current governance language, or being formally adopted or changed, could warrant a dated comparison against the frozen authority baseline. These are possible changes to evaluate, not predictions or recommendations of adoption. A change in wording and a completed governance action would still need to be distinguished.

##### Target-architecture implementation

The 23 TARGET DESIGN units provide a background for later review when a component becomes implemented, source/provenance becomes available, or deployment or operation is asserted. The dated status change and available evidence would determine what could be evaluated. C05 does not establish these target implementations, and the absence of such a change is not an implementation-failure finding.

##### Later documentary repairs/revisions

Changed canonical destinations, repaired status conflicts, explicit retirement or supersession, and revised current/target classifications can be evaluated against Report v1. A later repair does not erase the original snapshot finding; it creates a delta. New evidence clarifying the old snapshot and an actual later change should be recorded separately, even when both concern the same document.

##### Other material post-snapshot changes

A new deployment, governance status, source attribution or documentary status may change which claim can be tested and what evidence is relevant. Any review would compare the changed scope with the retained baseline. Listing these possibilities creates neither a project roadmap nor a new verification obligation.

#### Future work is not a remediation backlog

These categories describe when further evaluation could become useful. They do not mean Laniakea must complete every item, Report v1 remains incomplete, every uncertainty is a defect, or every optional assurance should be undertaken. They imply no priority or urgency. Some questions should wait until evidence or project state changes.

#### Why delta evaluation matters

Report v1 preserves a frozen documentary baseline, evidence matrix and scoped findings. A future revision can identify what changed, which claims that affects, and which evidence paths need reconsideration. This retains earlier snapshot results while distinguishing new evidence, corrections and later changes. It avoids rewriting history merely because the available evidence or evaluated object has evolved.

#### Closing perspective

The limitations define the boundaries of the report's claims. Evidence-triggered reopening, optional assurance and future delta evaluation serve different purposes. Their separation allows Report v1 to close without pretending every question has been resolved or treating unresolved questions as failures. With those boundaries explicit, **Principal Synthesis Findings** can bring the supported results together without extending their scope.

### Evidence notes


- **S9-1.** `synthesis/master-evidence-matrix.md` — Limitations, dispositions and reopening triggers; C05/C06 final boundaries.
- **S9-2.** `synthesis/report-architecture.md` — Sections 12–13; ten limitation groups and three future-work categories.
- **S9-3.** `reports/2026-09-18-f438819/leads.md` — Retained questions, C05 closure and optional bytecode assurance.
- **S9-4.** `reports/2026-09-18-f438819/L1-claim-map.md` — Selected scope, overlaps, X1 and U1–U4.
- **S9-5.** `evidence/f438819/LIMITATIONS.txt` — Extraction coverage and interpretation limits.
- **S9-6.** `reports/2026-09-18-f438819/findings/L0-01-corpus-boundary.md` — Slideshow scope and status clarification.
- **S9-7.** `reports/2026-09-18-f438819/findings/L0-02-canonicality.md` — Missing canonical destination and reopening conditions.
- **S9-8.** `reports/2026-09-18-f438819/findings/L0-03-internal-navigation.md` — Navigation, parser/base limits and reopening conditions.
- **S9-9.** `reports/2026-09-18-f438819/findings/L0-04-status-integrity.md` — Inactive-whitepaper authority scope.
- **S9-10.** `reports/2026-09-18-f438819/findings/L3B-02-C06-legacy-configurator-provenance.md` — C06 status distinctions and qualifying provenance.
- **S9-11.** `reports/2026-09-18-f438819/findings/L3F-01-C05-mainnet-chain-binding.md` — Runtime/history/bytecode boundaries and material reopening triggers.
- **S9-12.** `reports/2026-09-18-f438819/L3F-evidence/README.md` — Retention, event attribution and query limitations.

## 10. Principal Synthesis Findings

The six findings below bring together the frozen documentary, Atlas, STL, provenance, implementation and Mainnet evidence. They synthesize the completed evaluation rather than add new tests or resolve remaining questions. Their scope and strength of support differ: establishing a documentary relationship, identifying an implementation and observing deployed state answer different questions. The frozen master evidence matrix controls each conclusion. Together, these findings provide a differentiated account of the evaluated snapshot, not a project-wide score or verdict.

### 1. The evaluated snapshot combines grounded legacy/current material with protected future target design

The Laniakea snapshot combines legacy and current-state descriptions, present-operation assertions, historical explanations, illustrative material, proposed architecture and explicit future work. It cannot be read as one specification of a currently implemented system. A passage describing a legacy component and another describing its target replacement make different claims, even when both appear in active documentation.

The 53 selected statement units preserve traceability across this mixture. They are neither exhaustive corpus coverage nor 53 independent propositions: some statements overlap or describe related aspects of the same subject. Of these selected units, 23 carry **TARGET DESIGN** and eleven selected current-state units carry **NOT INDEPENDENTLY VERIFIED**. Other rows retain their own ESTABLISHED, PARTIALLY ESTABLISHED or NOT ESTABLISHED dispositions, with historical, illustrative and ambiguous classifications preserved where applicable. These are distinctions about the proposition and the evidence obtained, not counts of functioning or failed systems.

The proposed-state protection applied in the documentary evaluation prevented future designs from being treated as missing current implementation. That protection does not establish design soundness, feasibility, present deployment or governance authorization, and does not place a proposal beyond criticism. It identifies the question that would need to be evaluated. In the other direction, a general draft label does not cancel a specific assertion that an implementation exists or an instance is running.

Ambiguity preservation serves a related purpose. Conflicting or unclear descriptions remain visible instead of being silently resolved into current or future fact. Historical and illustrative passages likewise do not supply deployment evidence merely because they describe concrete mechanisms. C05 shows that some legacy/current material can be grounded independently; it does not establish every assertion sharing that documentary setting. The appropriate interpretation therefore depends on the temporal class and evidence of each selected claim.

### 2. C05 provides a bounded end-to-end implementation and Mainnet grounding case

Laniakea's scoped legacy Mainnet PAU description is materially grounded in implemented and historically deployed Sky/Spark infrastructure.

The conclusion retains five principal limits:

| Boundary | Result |
|---|---|
| Specific attribution of RateLimits events to the tested MainnetController | NOT ESTABLISHED |
| Exact source/runtime bytecode equivalence | NOT ESTABLISHED |
| Continuous June→September operation | NOT ESTABLISHED |
| All-layer PAU deployment | OUTSIDE C05 |
| Comprehensive security/integration certification | OUTSIDE SCOPE |

C05 is the strongest implementation/runtime grounding case in Report v1 because the evidence connected the documentary claim to an identified source family, historical revisions, inspected source behavior and two fixed Ethereum Mainnet observations. The tested legacy stack comprises MainnetController, ALMProxy and RateLimits. Separately resolved provenance identified `sparkdotfi/spark-alm-controller`; historical component revisions predating the June snapshot supported inspection of Controller coordination, permission-controlled proxy execution and keyed rate limits. Those mixed revisions were source witnesses, not a single release or deployment chronology.

The chain evidence independently established code presence, component wiring, required grants, populated operational roles and representative finite RateLimits configuration at the June and September observations. Comparing those two fixed points showed changed configuration parameters and the same tested addresses and per-address runtime hashes. Bounded consumption events supplied evidence of use of the relevant RateLimits key. They did not identify the responsible account or contract and are not Controller call counts. “Current” here means the retained September observation, not publication-time monitoring.

“End-to-end” means traversing the scoped claim-to-source-to-deployment evidence path, within the limits above. First deployment or activation, complete migration history and migration cause/date remain unestablished. Corresponding token transfers and complete transaction paths were not established either.

C05 is **CLOSED for the scoped Report v1 conclusion**. Exact bytecode reproduction remains optional assurance. Converging documentary, source and Mainnet evidence supports this defined legacy proposition; it does not establish the target architecture or Laniakea implementation as a whole.

### 3. Atlas comparison produces supported, discrepant, and unresolved bindings

The selected Atlas comparisons do not yield a single aligned/not-aligned judgment. Atlas provides the governance-policy comparison layer, while Laniakea supplies the claims being compared. Documentary policy remains distinct from enactment, execution, approval and payment. Three kinds of relationship emerge within that scope.

First, C01 establishes documentary presence. All four selected operational-data categories—Prime SubProxy addresses, relayer multisigs, rate-limit types and per-chain deployment records—have Atlas witnesses, including material predating the June Laniakea snapshot. This supports where those categories are documented. It does not establish address correctness, current deployment, runtime use, complete coverage or completed migration. C01 therefore provides documentary context rather than an additional implementation result.

Second, the exact authority mappings in C02 and C03 remain **NOT ESTABLISHED**. Executor service, Guardian identity and organizational parenthood are not interchangeable relationships. Broader Atlas governance provisions do not automatically establish the claimed single-Guardian hierarchy or the specific Phase 1 v2 starting arrangement described as “fully sudo at genesis,” meaning the claimed initial authority was concentrated in the Guardian. The unresolved mappings are not findings that those arrangements are false or forbidden.

Third, C04 remains **PARTIALLY ESTABLISHED**, within the shared Prime scope. The numerical 50 bps annual rate and general rebate entitlement are supported. Concrete mechanics differ: recurring issuance/creation contrasts with one-time founding, own-token upkeep contrasts with USDS upkeep, and continuous holdings-based rebates contrast with payment-dependent rebates. The claimed 5% amount and blanket tokenless exemption remain NOT ESTABLISHED. This split preserves both the supported elements and the material documentary-policy discrepancies.

The historical L2-04 FAIL remains the result of the tested invariant in that shared scope. C04's synthesis disposition does not rewrite it or turn partial support into overall policy alignment. Payment realization was NOT TESTED under C04; the separate C11 operational assertion remains NOT INDEPENDENTLY VERIFIED. Neither the supported rate nor the discrepant mechanics establishes what payments occurred.

The resulting Atlas relationship is heterogeneous. Documentary correspondence, specific policy difference and unresolved authority each require their own interpretation. No intentional divergence, governance rejection, ratification or future amendment is inferred. The comparison does not extend to a global inconsistency verdict or determine what future governance will adopt.

### 4. STL is useful evidence but not universal implementation provenance

STL contributed registry, observer, reference and provenance-discovery evidence. Such material can identify addresses, component names and relationships worth investigating without being the implementation source for the claimed stack. Its evidentiary role depends on the particular claim and the connection established to it.

For both C05 and C06, the frozen initial STL result was **NO MATCHED STL COVERAGE ESTABLISHED**. That result does not say STL contained no related material, that the implementations did not exist, or that the Laniakea claims were false. It records the absence of an established implementation match in the evaluated STL evidence. It is not a judgment that implementation repositories should necessarily reside in STL.

C05 demonstrates why that distinction matters. Matched STL implementation coverage remained unestablished, while separate provenance work identified `sparkdotfi/spark-alm-controller` and enabled source inspection and Mainnet evaluation. Later positive evidence does not rewrite the earlier coverage result. Discovery evidence and implementation identity contributed at different points and answered different questions.

C06 reached a different evidence boundary. Related technical material and later PAS records supplied documentary leads, but no matched legacy Configurator implementation source or dated legacy-to-PAS connection was established. With no sufficiently specific source to inspect, the evaluation did not substitute a similarly named implementation or later contract for the legacy claim. Static and chain verification did not proceed for that claim.

STL is consequently useful as an evidence layer and a place to discover leads, without automatically being authoritative implementation provenance, a comprehensive implementation inventory or a substitute for claim-specific repository/source binding. The contrast between C05 and C06 concerns the specificity of the evidence obtained. It neither diminishes STL nor turns C06's unresolved source identity into proof of nonexistence.

### 5. Documentation maturity and canonicality are uneven

The documentary surface supports precise analysis in some places while retaining unresolved selection, navigation and status issues in others. Stable source-located candidate inventories were produced across the selected reference categories. Corpus entry points and local qualifications allowed many propositions to be traced into documentary, Atlas or implementation analysis. C05 ultimately demonstrates the evidence depth possible when those documentary leads become sufficiently specific provenance.

That useful structure coexists with concrete limitations. Two slideshow files retain stale/ambiguous status outside ordinary active consultation. The designated canonical Sky Intents destination is absent, ordinary broken-link occurrences exist across active documents, and capital-stack's use of an inactive whitepaper as canonical remains unresolved in authority and scope. These issues affect which source a reader can locate and what documentary authority can safely be attributed to it. Similarly named or historical material is not automatically the intended replacement.

X1 adds a substantive documentary conflict about Phase 1 closure records and monthly-atom status. Active detail, summary and roadmap material do not give a consistent account of whether the disputed accounting outputs belong to P1. The conflict is established; actual operating truth and the intended documentary winner remain unresolved. One conflict affects several documentary tests, rather than establishing several independent implementation failures.

Historical and illustrative material also needs its temporal qualifications preserved. A worked procedure may state deployment as a prerequisite without verifying it, and an earlier research description does not establish a current implemented replacement. Meanwhile, candidate inventories identify material for inspection without validating every extracted assertion, address or formula or guaranteeing complete semantic coverage.

“Uneven” thus describes differences in documentary traceability and clarity, not a global documentation score. Some portions provide clear, evaluable propositions; others retain canonicality, navigation or current/future ambiguity. Broken links do not establish broken code, unresolved documentary authority does not establish a security risk, and X1 does not decide runtime behavior. Documentary maturity matters to evidence selection without serving as a proxy for implementation quality.

### 6. Material provenance, operational, and architectural evidence gaps remain

The completed evaluation leaves explicit limits on broader current-state conclusions. These limits arise from different evidence situations and cannot be combined into one failure category. Neither supported documentary relationships nor C05's deeper technical evidence closes every remaining question.

C06's legacy Configurator source identity remains **NOT ESTABLISHED**. Architecture-source access is **BLOCKED** only where that access limitation applies; it is not the main C06 result or proof that the inaccessible source contains the missing implementation. The chain prerequisite remains **HOLD**, and the synthesis disposition remains **PARKED**. Those terms respectively describe an access limitation, a verification gate and a decision to defer further work. None is a historical finding of falsehood or nondeployment. C06 can be reconsidered on qualifying provenance evidence, not naming similarity alone.

Eleven selected current-state units remain **NOT INDEPENDENTLY VERIFIED**. Three are deferred operational questions concerning buybacks/distribution, fee realization/routing and the emissions backstop (C10, C11 and C39). Eight concern current architecture or operation whose evidence paths depend on unresolved architecture/provenance prerequisites (C07, C08, C09, C12, C13, C14, C15 and C16). Their independent evidence paths were not completed for substantive findings in Report v1. These units overlap in places and are not eleven independent systems or failures. Their disposition does not establish absent implementation or silently convert them into NOT ESTABLISHED results.

Other questions retain their own boundaries. C02/C03's exact authority mappings remain NOT ESTABLISHED, as does C45's broader all-layer deployment claim. X1 establishes a documentary conflict while leaving disputed operation unresolved. These examples show why the report cannot extend its strongest scoped result into a general current-state account.

The 23 **TARGET DESIGN** units are different again. They are future or proposed propositions, not current assertions awaiting the same verification. Withholding current implementation conclusions for them does not identify a missing-implementation defect. Their design quality, feasibility and future adoption have not been established by classification.

These gaps are material because they constrain what the report can say, not because they negate C05 or supported Atlas documentary relationships. The frozen future-work model preserves the distinction: unresolved questions may reopen on qualifying evidence; exact C05 bytecode reproduction is optional assurance; target/future material becomes suitable for delta evaluation when its status materially changes. No mandatory remediation backlog follows, and Report v1 can close with these boundaries explicitly retained.

### Combined significance

The six findings connect claim classification to the depth of evidence a conclusion can bear. Mixed temporal material requires interpretation before implementation judgment; specific provenance and runtime targets can then support strong scoped grounding. Atlas and STL contribute different, heterogeneous relationships rather than binary validation. Documentary maturity affects traceability, while remaining gaps limit broader conclusions without erasing supported results. Future designs remain distinct from unresolved current assertions. These relationships provide the basis for the **Overall Synthesis**, with the scope of each finding preserved.

### Evidence notes

- **S10-1.** `synthesis/master-evidence-matrix.md` — Publication control, claim populations, dispositions and conclusion limits.
- **S10-2.** `synthesis/report-architecture.md` — Six principal findings and their interpretive boundaries.
- **S10-3.** `synthesis/report-sections/03-laniakea-snapshot-characterization.md` — Mixed corpus, inventories, canonicality, X1 and temporal protection.
- **S10-4.** `synthesis/report-sections/04-relationship-to-sky-atlas.md` — C01–C04 comparisons and historical/synthesis distinctions.
- **S10-5.** `synthesis/report-sections/05-relationship-to-stl.md` — Frozen STL coverage results and separate implementation provenance.
- **S10-6.** `synthesis/report-sections/06-implementation-and-mainnet-grounding.md` — Scoped C05 evidence progression, conclusion and limitations.
- **S10-7.** `synthesis/report-sections/07-unresolved-provenance-c06.md` — C06 provenance, status distinctions and reopening boundary.
- **S10-8.** `synthesis/report-sections/08-unverified-and-target-architecture.md` — Eleven unverified current units and 23 target/future units.
- **S10-9.** `synthesis/report-sections/09-limitations-and-future-work.md` — Interpretation limits, scoped closure and future-work categories.

## 11. Overall Synthesis

The completed evaluation supports neither blanket validation nor blanket rejection of Laniakea. The frozen snapshot contains propositions with materially different evidence behind them: established documentary relationships, a strongly grounded legacy implementation/deployment case, partial or unresolved governance relationships, unverified current assertions and substantial future design. The report-level interpretation depends on preserving those differences. This synthesis integrates the frozen principal findings under the master evidence matrix's publication limits; it introduces no new tests, grades or resolutions.

### The evaluated object is mixed, not monolithic

The appropriate unit of evaluation is the scoped proposition. Legacy/current implementation descriptions and operational assertions sit alongside historical accounts, worked examples, proposed architecture, roadmap material and ambiguous or conflicting descriptions. Reading all of this as one current implementation specification would obscure what the sources actually assert and what the evaluation could test.

The 53 selected statement units were non-exhaustive and overlap; they were not 53 independent propositions. Within that selection, 23 carry **TARGET DESIGN**, while eleven selected current-state units remain **NOT INDEPENDENTLY VERIFIED**. These counts identify different questions and dispositions, not proportions of a system that work or fail. A future target cannot be penalized simply for lacking current implementation. Conversely, an explicit present-state assertion cannot escape verification merely because nearby material is labeled draft or future. Ambiguity remains unresolved until evidence supports a more definite interpretation.

The documentary surface is usable and often traceable, but uneven in canonicality and status. Stable source-located candidate inventories, local qualifications and temporal labels supported later Atlas, source and chain analysis. Missing or unclear canonical destinations, broken navigation, stale/ambiguous material and unresolved source-authority scope limit that traceability elsewhere. X1 establishes a documentary conflict over P1 accounting status without deciding actual operation or selecting a documentary winner. Historical and illustrative qualifications also remain necessary. These issues affect evidence selection and confidence in documentary authority; they do not automatically establish code, implementation, security or runtime defects.

### What is grounded today

Laniakea's scoped legacy Mainnet PAU description is materially grounded in implemented and historically deployed Sky/Spark infrastructure.

C05 connects a documentary claim to an identified implementation source, historical source revisions and inspected behavior, then to Mainnet components with observed wiring, roles, grants and representative finite rate-limit configuration. Bounded usage events add evidence of consumption of the relevant RateLimits key. The historical June and retained September observations establish tested state at two fixed points. In this section, “today” refers to what the completed evaluation can establish from that retained evidence, not a fresh observation at publication time.

This is a concrete instance of a legacy technical description grounded beyond conceptual prose. The evidence layers contribute different support: source inspection addresses implemented behavior, while chain observations address deployed components and tested state. Their convergence supports the scoped conclusion without making either layer a substitute for the other.

Attribution of the RateLimits events to the tested MainnetController remains **NOT ESTABLISHED**; the events are not Controller call counts. Exact source/runtime bytecode equivalence and continuous June→September operation also remain **NOT ESTABLISHED**. All-layer PAU deployment remains **OUTSIDE C05**, and comprehensive security/integration certification remains **OUTSIDE SCOPE**. Neither unchanged runtime hashes at two observations nor identified historical source revisions closes those gaps.

C05 is **CLOSED for its scoped Report v1 conclusion**. Exact bytecode reproduction remains optional assurance. That closure recognizes sufficient evidence for this proposition, without certifying the complete PAU architecture, target architecture or Laniakea implementation as a whole.

### Relationship to Sky Atlas and STL

Laniakea's relationship to Atlas varies by proposition. C01 has documentary witnesses for the four selected operational-data categories, including pre-June material. That presence does not itself establish deployment, address correctness, runtime use or completeness. C02/C03's exact authority and hierarchy mappings remain **NOT ESTABLISHED**; related governance provisions do not automatically establish the particular relationships claimed.

C04 remains **PARTIALLY ESTABLISHED** within the shared Prime scope. The annual rate and general rebate entitlement have support, several fee mechanics materially differ, and some claimed details remain unestablished. The earlier L2-04 comparison retains its historical FAIL result for the scoped policy invariant tested within the shared Prime scope; C04's final synthesis disposition remains PARTIALLY ESTABLISHED and does not replace that historical result. Payment realization was not tested under C04 and remains a separate operational question; C11 retains NOT INDEPENDENTLY VERIFIED. Documentary agreement or discrepancy cannot supply a payment finding.

Laniakea prose is not itself current Sky governance authority, and Atlas policy text remains distinct from enactment, execution, approval and payment. Some target arrangements may require governance formalization where relevant. No adoption, rejection or future amendment is inferred. The documentary relationships are real but do not amount to total equivalence.

STL serves a different role: registry/reference, observer and discovery material helped locate relevant technical evidence. For both C05 and C06, the initial result remains **NO MATCHED STL COVERAGE ESTABLISHED**. C05's implementation provenance was subsequently resolved elsewhere, enabling source and chain evaluation; the evaluated evidence for C06 did not establish a sufficiently specific legacy source for those steps. STL is therefore an evidence layer, not a universal implementation-provenance requirement. Implementations need not reside there, and an absent match establishes neither STL deficiency nor implementation nonexistence.

### What remains bounded or unresolved

**Provenance.** C06's legacy Configurator source identity remains **NOT ESTABLISHED**. Architecture-source access is **BLOCKED** only where that access limitation applies; inaccessible content is not assumed to contain the missing implementation. The chain gate remains **HOLD**, and synthesis remains **PARKED**. Those labels distinguish evidence insufficiency, access, a prerequisite gate and deferral. They do not establish falsehood or nondeployment, and PARKED is not a historical repository grade.

**Current assertions.** Eleven selected units remain **NOT INDEPENDENTLY VERIFIED**: three deferred operational questions and eight architecture/provenance-dependent assertions. Independent verification was not completed for substantive conclusions about them. Their differing reasons and overlaps remain relevant; they are not eleven independent systems or failures, and the disposition does not establish absent implementation.

**Governance and deployment.** Unresolved C02/C03 mappings and C45's **NOT ESTABLISHED** all-layer deployment claim prevent broader authority or deployment conclusions. X1 separately leaves disputed operating truth unresolved despite the established documentary conflict. An available description is not enough to settle these questions.

**Runtime and history.** Even C05 does not establish continuity, reconstruct complete migration history or establish exact source/runtime bytecode identity. First deployment/activation, migration cause/date, corresponding token transfers and complete transaction paths remain unestablished. Its evidence cannot be expanded into a complete operational history.

Together, these limits prevent a broad statement that the complete Laniakea architecture is currently implemented, deployed or operational. They do not negate C05, supported Atlas documentary relationships or traceable source material. Nor do they turn the unresolved questions into mandatory remediation.

### How to interpret the target architecture

The 23 TARGET DESIGN units form a substantial part of the selected snapshot. They describe proposed architecture, desired future structures, later-phase mechanisms and, where qualified, speculative or roadmap concepts. They are not missing-implementation findings or unresolved current assertions awaiting the same kind of verification.

Classification establishes neither current implementation, deployment or governance authority nor technical feasibility, soundness or future adoption. It also does not establish failure. The distinction preserves the proposition's temporal scope while leaving design evaluation and implementation verification as separate questions. C05's legacy result cannot supply implementation evidence for these targets.

The useful future question is whether a particular target has materially changed status. A documentary revision, governance change, identified source or deployment/operation assertion may make a new comparison appropriate. Documentary status can then be reconsidered, governance relationships compared, and source or runtime evidence inspected where relevant. Such delta evaluation compares the later state with the frozen baseline; it neither predicts implementation nor treats the earlier target classification as a deficiency.

### Overall assurance supported by Report v1

The evidence supports confidence in specific scoped conclusions, not confidence by extrapolation. Report v1 identifies the source revisions, statement scope and fixed observations to which its findings apply. Its documentary and classification conclusions are supported within that selection; its Atlas characterization preserves proposition-level differences; and its STL analysis distinguishes discovery evidence from implementation identity. C05 has the deepest convergence of documentary, source and chain evidence. These provide grounds for confidence in the respective conclusions, without assigning equivalent assurance to untested propositions.

The frozen baseline makes those conclusions traceable; it does not establish exhaustive semantic coverage, complete evidence retention or publication-time conditions. Assurance does not extend to all implementation, operational assertions or governance mappings, target implementation, all-layer PAU deployment, project-wide security or complete runtime history. Report v1 is not an implementation-completeness or governance-readiness certification, a security audit or a runtime certification.

Within this snapshot, Laniakea is best understood as a mixed documentary and architectural corpus: some legacy/current technical material is independently grounded, Atlas relationships are substantive but non-uniform, STL provides useful evidence without universal source binding, and substantial future architecture coexists with explicit unresolved current questions. The strongest technical case demonstrates correspondence with deployed Sky/Spark infrastructure when provenance becomes specific enough. The remaining questions define why that correspondence cannot be generalized to the whole system.

Further evaluation has three distinct bases: reopening on qualifying new evidence, optional assurance, or delta evaluation when project status changes. None makes every open question a prerequisite to closing Report v1. The completed report supports the scoped relationships and infrastructure grounding it established, while withholding broader implementation, authority and operational conclusions that its evidence does not support.

### Evidence notes

- **S11-1.** `synthesis/master-evidence-matrix.md` — Publication control, dispositions and evidence ceilings.
- **S11-2.** `synthesis/report-architecture.md` — Overall Synthesis scope and prohibited overclaims.
- **S11-3.** `synthesis/report-sections/03-laniakea-snapshot-characterization.md` — Mixed corpus, documentary maturity and temporal boundaries.
- **S11-4.** `synthesis/report-sections/04-relationship-to-sky-atlas.md` — Supported, discrepant and unresolved Atlas relationships.
- **S11-5.** `synthesis/report-sections/05-relationship-to-stl.md` — STL evidence role and implementation-provenance distinction.
- **S11-6.** `synthesis/report-sections/06-implementation-and-mainnet-grounding.md` — Scoped C05 grounding and limitations.
- **S11-7.** `synthesis/report-sections/07-unresolved-provenance-c06.md` — C06 identity, access, gate and synthesis boundaries.
- **S11-8.** `synthesis/report-sections/08-unverified-and-target-architecture.md` — Eleven unverified current units and 23 target units.
- **S11-9.** `synthesis/report-sections/09-limitations-and-future-work.md` — Assurance limits and three future-work categories.
- **S11-10.** `synthesis/report-sections/10-principal-synthesis-findings.md` — Immediate frozen basis for the integrated interpretation.

# Appendices

## Appendix A — Baseline Manifest

### A.1 Purpose and scope

This manifest identifies the revisions, observation anchors and evaluation/publication records used by Report v1. It answers what was frozen and evaluated, rather than interpreting what the evidence establishes. Repository revisions identify documentary or source versions; chain anchors identify particular observed states; evaluation and publication commits identify the retained record and its later narrative controls. These forms of identity serve different purposes and are kept separate below.

The manifest supports traceability, not semantic completeness or publication-time freshness. It does not replace the master evidence matrix, supply additional findings or imply continuous monitoring. The source pins, setup capture, historical comparison and Mainnet observations have different dates. They are not one simultaneous observation of every source.

### A.2 Evaluation baseline identity

The report identity is **Independent Validator-Led Snapshot Evaluation of Laniakea and Its Relationship to Sky Atlas, STL, and Deployed Infrastructure**. Its subtitle is **Documentary, governance, implementation, and Mainnet evidence review — 2026 snapshot**. The frozen architecture qualifies it as a selected-claim snapshot evaluation led by an independent human validator, non-exhaustive and not a security audit or implementation certification.

The following values are transcribed from the baseline pins, charter, frozen architecture, matrix and retained comparison/chain records. Source dates reproduce the recorded timestamps rather than substitute an evaluation or publication date.

| Baseline element | Frozen value | Role in evaluation |
|---|---|---|
| Baseline capture | `2026-09-18T17:02:27Z` | Capture timestamp in `pins/baseline.md`; not the subject revision date. |
| Subject repository | `sky-ecosystem/laniakea-docs`; local reference `../laniakea-docs-ref` | Laniakea documentary corpus. |
| Subject revision | `f4388196198df3435b38357bc7f1fccc1c5a1317` | Evaluated subject pin. |
| Subject tree | `5dc1b893176826a3852622c90a7e7f0029f0d666` | Recorded Git tree identity. |
| Subject date / subject line | `2026-06-04T09:38:57+02:00`; `docs: slim focused roadmap framing` | Recorded revision metadata. |
| Atlas repository | `sky-ecosystem/next-gen-atlas`; local reference `../laniakea-atlas-ref` | Pinned governance comparison source. |
| Atlas revision / tree | `4c466eb1c9508abea08412f43011dfd40e1cfb82` / `1679d830b60855d09cd430890e146ebcd68b248c` | Recorded Atlas identities. |
| Atlas date / subject line | `2026-09-17T19:58:05+01:00`; `Atlas Edit Proposal — 2026-09-14 (#331)` | Recorded revision metadata. |
| Historical Atlas comparator | `7fa69a61dc52905e589308709e6260095c45bd78`; May 29, 2026; `Atlas Edit Proposal — 2026-05-25 (#251)` | Historical comparison recorded in the L2 report; not a replacement for the Atlas pin. |
| STL repository | `archon-research/stl`; local reference `../laniakea-stl-ref` | Pinned technical/reference source. |
| STL revision / tree | `37e56db072f9f246fc2f77ed3036e4a8e732aaf7` / `c4f988eb03651afe3e70590dd7dbb96dc9ce3195` | Recorded STL identities. |
| STL date / subject line | `2026-09-18T08:19:30Z`; `deploy(prod): update image tags to 58f6418` | Recorded revision metadata. |
| Architecture availability | `BLOCKED_FOR_ANONYMOUS_GIT_AT_SETUP`; credentials supplied: `NO` | Recorded setup condition for `archon-research/architecture`, not a statement about its contents. |
| Architecture revision | NOT RECORDED IN FROZEN BASELINE | No pinned architecture revision is supplied by the baseline. |
| Selected report directory | `reports/2026-09-18-f438819/` | Retained evaluation record location. |
| Accepted deterministic evidence | `evidence/f438819/`, frozen at `0afd81684eff791073f20f1d8d39f2d6bcc1bd60` | L0 evidence set, distinct from later source/chain records. |
| Technical/evidence anchor | `8064df6464967ab53a46c07b82f210a069f655e3` | Completed historical evaluation through L3F. |
| Main narrative freeze | `102858626092f5282fd43f396c8a911e331ae635` | Executive Summary freeze completing the narrative lineage listed below; not an appendix/publication-release freeze. |
| Chain/network identity | Ethereum Mainnet; chain ID `1` | Network for the retained C05 observations. |

### A.3 Claim-selection baseline

The claim map selected 53 statement units from a consultation scope described as A+A0: 142 files in 14 README Active areas and 20 orientation files. This records the selection context, not substantive verification of all 162 files. Selection was non-exhaustive, and the units are not 53 independent propositions. Related implementation and operational statements overlap; broader statements can include narrower ones.

X1 and U1–U4 remain separately retained comparison/context records. They are not additional members of the 53-unit population. The matrix therefore contains 58 master rows while preserving the original selection boundary. Neither total is a system-coverage percentage. This appendix records the selection frame without reproducing individual propositions or their dispositions; row-level scope and classification traceability are allocated elsewhere.

### A.4 Historical evaluation phase lineage

The table follows the accepted evaluation repository history in order. Full identifiers and subjects are recovered from Git. Role descriptions identify record provenance, not new assessments of external claims. The sequence runs from setup and deterministic evidence through L0–L3F; it does not imply that every claim traversed every phase.

| Full commit SHA | Exact commit subject | Evaluation role / phase |
|---|---|---|
| `52ac5990ae9805817af607db46b8e0bec198e5c6` | Initialize Laniakea eval charter, pins, and L0-L1 invariants | Setup, charter, baseline and pre-stated invariants. |
| `0afd81684eff791073f20f1d8d39f2d6bcc1bd60` | Add validator-run L0 deterministic evidence | Accepted extraction evidence. |
| `3f6fdaa620e3031d02d0d1484f7d8bcba5effd10` | Finalize Laniakea L0 semantic review | L0 documentary review record. |
| `2284442146d831c98b3b27e52a829b7513a1c98f` | Finalize Laniakea L1 status classification | L1 claim/temporal classification. |
| `6b9ce8040b55682a8f2f690640e7c29277afad3b` | Finalize Laniakea L2 Atlas binding C01-C04 | L2 comparison record. |
| `196fb8a2300f3bf92aa22e4accc1d49d374934f4` | Finalize Laniakea L3A STL binding C05-C06 | L3A coverage record. |
| `acb150c496ef2c268177bbeac471c9afafefe280` | Finalize Laniakea L3B implementation provenance C05-C06 | L3B provenance record. |
| `7b05ca0a470212c7f64f13ee87395bedb9814140` | Finalize Laniakea L3C C05 external provenance | L3C external provenance record. |
| `63e2188653318154f86d5bd2ae164f95ed18c047` | Finalize Laniakea L3D C05 repository identity | L3D source/repository identity record. |
| `33188270fa0c4a41b327e269370ae4135dcd2892` | Finalize Laniakea L3E C05 static implementation binding | L3E static review record. |
| `8064df6464967ab53a46c07b82f210a069f655e3` | Finalize Laniakea L3F C05 Mainnet chain binding | L3F record and scoped C05 closure; technical/evidence anchor. |

### A.5 Synthesis and publication freeze lineage

These commits identify publication-control provenance: master matrix, architecture, body sections and Executive Summary. Git records which artifacts were frozen; it is not independent evidence that external Laniakea claims are true. Appendix drafting follows this narrative freeze and is not represented as already frozen by these commits.

| Full commit SHA | Short SHA | Exact commit subject | Role |
|---|---|---|---|
| `325f96ac847314b508887719c36dae805bb28a04` | `325f96a` | Freeze Laniakea master evidence matrix | Publication claim control. |
| `5101fc438626d27ae124b733dd46317493507ace` | `5101fc4` | Freeze Laniakea report architecture | Section and appendix allocation. |
| `5c0f06f33958325c6cca23ec2422e4afab841965` | `5c0f06f` | Freeze Laniakea scope baseline and methodology | Scope and method. |
| `20a5a36656fa25b42c9893acaddea68a5dd5e60d` | `20a5a36` | Freeze Laniakea snapshot characterization | Corpus characterization. |
| `29160bee436308efc51024bfa1a2af0e09aa78c4` | `29160be` | Freeze Laniakea relationship to Sky Atlas | Atlas narrative. |
| `fd49bdf3e80ffdd5646faf05098c4e049cfeefbd` | `fd49bdf` | Freeze Laniakea relationship to STL | STL narrative. |
| `4e9a5b67cf3d8323c1a67734cf15670752120e39` | `4e9a5b6` | Freeze Laniakea implementation and Mainnet grounding | C05 narrative. |
| `70f421aeeacc2463201a4d8ee2ad4f84ce21e204` | `70f421a` | Freeze Laniakea unresolved C06 provenance | C06 narrative. |
| `dd8fe7c40ec8b0a561931b9aad937166d0a26b65` | `dd8fe7c` | Freeze Laniakea unverified and target architecture | Current/target distinctions. |
| `838c9e1d1eafd862dbf54b325e869221ed8f38a5` | `838c9e1` | Freeze Laniakea limitations and future work | Limits and future-work categories. |
| `0fdae2a6b306ecedcb12eac5f66b7f76a49dc2a4` | `0fdae2a` | Freeze Laniakea principal synthesis findings | Six principal findings. |
| `33063ccf5456ffcdde23c879886fe98c1a15991a` | `33063cc` | Freeze Laniakea overall synthesis | Report-level interpretation. |
| `102858626092f5282fd43f396c8a911e331ae635` | `1028586` | Freeze Laniakea executive summary | Condensed frozen narrative. |

### A.6 Mainnet observation anchors

Both retained observations concern Ethereum Mainnet, chain ID 1. UTC values below are the retained block timestamps, not the time a reader consults this report.

| Observation | Block | Retained UTC timestamp | Retained block hash |
|---|---|---|---|
| Historical | 25,242,585 | `2026-06-04T07:38:47.000Z` | `0x3df6a06ce123333e4d84c014cecacd6034ec7bd8e82b6bc24be516beaee368fc` |
| Later retained | 26,007,670 | `2026-09-18T23:26:35.000Z` | `0x815c03207bc7c58958ae0cef5af8d9c10a9a334dd3e58ff8c1b9129a773dee6b` |

The historical baseline record also retains successor block 25,242,586 at `2026-06-04T07:38:59Z`, bracketing the subject timestamp `2026-06-04T07:38:57Z`. This is boundary-selection metadata, not an additional full component-state observation. The later baseline was captured once and subsequent state queries were fixed to that number. “Current” in retained chain records means that September observation.

Two fixed points do not establish uninterrupted operation, publication-time state, first deployment or complete migration history. Detailed component addresses, source revisions, interfaces and query results belong primarily in Appendix F; artifact and checksum indexing belongs in Appendix I.

### A.7 Publication-control hierarchy

1. **Master evidence matrix:** controls each publication claim's disposition, scope and evidence ceiling.
2. **Frozen main narrative:** controls public interpretation within those matrix limits.
3. **Detailed appendices:** supply traceability and technical detail without new conclusions.
4. **Historical reports and evidence:** retain the underlying records and original phase results.

This is a hierarchy for publication wording, not permission to discount historical evidence. Later synthesis does not erase earlier findings, and an appendix cannot silently change either a historical grade or a final disposition. The report architecture allocates material within this hierarchy.

### A.8 Baseline limitations

The selected claims do not exhaust the corpus. Fixed revisions preserve the versions evaluated, while fixed chain observations preserve points rather than continuous history. Documentary extraction does not establish semantic completeness. Later source or project changes are outside this snapshot unless explicitly incorporated as such. The failed directory `evidence/f438819-failed-01/` is excluded from accepted evidence and was not used for this manifest.

No new baseline retrieval, external observation or checksum verification is asserted here. Exact recorded identifiers make the scope inspectable; they do not supply broader implementation, governance or runtime conclusions.

### Evidence notes

- **A-1.** `pins/baseline.md` — Captured pins, trees, revision metadata and architecture availability.
- **A-2.** `pins/repositories.txt` — Reference-source locations and setup availability state.
- **A-3.** `EVAL-CHARTER.md` — Evaluated subject and comparison-source roles.
- **A-4.** `synthesis/master-evidence-matrix.md` — Baseline control, selection and technical anchor.
- **A-5.** `synthesis/report-architecture.md` — Report identity, baseline allocation and publication hierarchy.
- **A-6.** `synthesis/report-sections/02-scope-baseline-methodology.md` — Fixed-revision and observation boundaries.
- **A-7.** `reports/2026-09-18-f438819/L1-claim-map.md` — Selected units and consultation context.
- **A-8.** `reports/2026-09-18-f438819/L2-atlas-binding-C01-C04.md` — Historical Atlas comparator.
- **A-9.** `reports/2026-09-18-f438819/L3F-evidence/baseline-historical.txt` — Historical chain anchor and timestamp bracket.
- **A-10.** `reports/2026-09-18-f438819/L3F-evidence/baseline-current.txt` — Later retained chain anchor.
- **A-11.** `reports/2026-09-18-f438819/L3F-evidence/README.md` — Meaning and retention limits of baseline fields.
- **A-12.** Evaluation repository Git history through `102858626092f5282fd43f396c8a911e331ae635` — Exact commit identities and subjects in A.4–A.5; lineage support only.

## Appendix B — Evaluation Methodology

### B.1 Methodological objective

The evaluation used claim-driven analysis and pre-stated invariants to increase confidence in selected propositions without silently expanding them. The unit of work was a scoped proposition, including its source, temporal qualifications and evidence requirement. Establishing that a description appears in a document is different from establishing its governance authority, implementation, deployment or operation.

The discipline was: identify the claim, identify the relevant evidence requirement, gather evidence within authorized scope, test against pre-stated criteria, preserve unresolved boundaries, and synthesize the accumulated record without rewriting earlier results. Concrete source evidence was required for consequential findings. Assertions, direct observations and inferences remained distinguishable. Neither a persuasive description nor an adjacent technical artifact could substitute for the missing evidence needed to answer the particular question.

### B.2 Evaluation layers

The progression below describes available evidence layers, not a compulsory sequence for every claim or a scale of project quality.

| Layer | Methodological role |
|---|---|
| Baseline/corpus control | Fix revisions and distinguish active consultation material from qualified, historical or inactive sources. |
| Documentary extraction and classification | Locate candidate material, interpret selected statements and preserve their asserted temporal status. |
| Atlas/governance comparison | Compare current-governance claims with the pinned governance-policy source. |
| STL technical/reference coverage | Determine what relevant technical, registry or observer material is present and whether it binds to the claim. |
| Implementation provenance | Identify the implementation source corresponding to the described component. |
| Static implementation/source review | Inspect behavior and relationships in identified source revisions. |
| Runtime/chain verification | Examine specified deployed state and bounded event evidence at fixed observations. |
| Synthesis/publication control | State the accumulated conclusion within the matrix's scope and limitations. |

Progression depended on claim type, available evidence, sufficient provenance, scope authorization and prior prerequisites. A target-design classification did not automatically require a deployment test. C05 advanced when implementation identity became specific enough; C06 did not advance to static/chain verification because the required legacy source identity remained unresolved. The distinct outcomes illustrate evidence prerequisites, not a universal requirement that every claim reach the final technical layer.

### B.3 Claim and temporal classification

The charter and `expected/L1.md` use CURRENT-GOVERNANCE, CURRENT-IMPLEMENTATION, CURRENT-DEPLOYED, CURRENT-OPERATIONAL, PROPOSED, TARGET-ARCHITECTURE, ROADMAP, CONCEPTUAL, DEPRECATED/HISTORICAL and AMBIGUOUS. These describe what a source asserts, not what independent verification has established. Classification therefore precedes implementation judgment.

The frozen L1 reporting vocabulary preserves CURRENT-GOVERNANCE, CURRENT-IMPLEMENTATION, CURRENT-OPERATIONAL and AMBIGUOUS, with PROPOSED-TARGET, FUTURE-ROADMAP, HISTORICAL and EXAMPLE / ILLUSTRATIVE as its other reporting classes. The claim map explains the reporting conversion: proposed, target and conceptual/specification material uses PROPOSED-TARGET; roadmap material uses FUTURE-ROADMAP; deprecated/historical material uses HISTORICAL. A bare deployment-existence assertion maps to CURRENT-IMPLEMENTATION with deployment explicitly noted, without equating source existence with deployment. Appendix J is allocated the formal crosswalk.

Future design is not failed current implementation. Historical or illustrative statements do not establish current deployment. Ambiguous or conflicting statements do not permit selecting a convenient interpretation. Source-local current wording may remain recorded even when the combined documentary account remains unresolved.

### B.4 Historical evaluation grades

Historical repository vocabulary comes from the charter. PASS means the pre-stated invariant is established at the pins. WARN covers risk, ambiguity, incomplete documentation or material staleness without sufficient direct contradiction for FAIL. FAIL means direct refutation of the invariant. INFO records a material observation without an invariant violation. NOT ESTABLISHED records insufficient evidence; BLOCKED records inaccessible required evidence; DEVIATION records intentional divergence separately rather than inferring it from inconsistency.

These terms describe the particular historical test or record, not the project as a whole. Later evidence can support a different accumulated conclusion without changing what the earlier phase established. Thus L2-04 retains its scoped historical FAIL while C04's final synthesis disposition is PARTIALLY ESTABLISHED. The later disposition does not erase the tested discrepancy or turn partial support into a general alignment finding.

### B.5 Workflow and gate states

HOLD is a workflow/prerequisite gate, not a charter failure grade. It records that further verification awaits the required basis. BLOCKED also appears in historical and evidence vocabulary; its object must be stated. An access limitation does not by itself decide the substantive claim or establish what an inaccessible source contains.

C06 demonstrates why these distinctions matter: the main legacy-identity result is NOT ESTABLISHED, architecture access is BLOCKED where that limitation applies, the chain gate is HOLD, and synthesis is PARKED. These are different statements about evidence, access and further work. None supplies a nonexistence or nondeployment finding. The public report retains the distinctions rather than allowing the most visually prominent workflow label to replace the substantive evidence result.

### B.6 Synthesis dispositions

Synthesis dispositions express what the accumulated evidence permits publication to say. ESTABLISHED requires a named object: documentary presence, for example, is not operational proof. PARTIALLY ESTABLISHED preserves supported parts alongside material unresolved or inconsistent elements. NOT ESTABLISHED means the scoped proposition or mapping lacks sufficient support; it does not mean false.

TARGET DESIGN preserves proposed or future scope rather than assigning implementation failure. NOT INDEPENDENTLY VERIFIED records an assertion without completed independent substantive verification; it does not mean failed. OUT OF SCOPE identifies a broader truth test outside completed verification, not a negative finding. PARKED defers further verification pending a qualifying lead; it is neither a historical grade nor permanent closure.

These seven terms are not interchangeable with historical grades. They summarize evidence scope for publication without creating an aggregate score. Their full formal definitions and relationships remain allocated to Appendix J, under the master matrix.

### B.7 Proposed-state and ambiguity protection

#### Proposed-state protection

Future or proposed architecture was not tested as though it necessarily asserted current implementation. Local qualifications, document status and the relevant surrounding passages informed classification. This safeguard did not establish design soundness, feasibility or future adoption. Conversely, a specific assertion of existing implementation or ongoing operation was not erased merely because nearby material was marked draft, illustrative or future.

#### Ambiguity preservation

Where statements conflicted or their temporal meaning was unclear, uncertainty remained visible until qualifying evidence could resolve it. The evaluation did not select the easier account to test, infer a documentary winner or promote ambiguity into current fact. X1 illustrates the distinction: an established documentary conflict can coexist with unresolved operating truth. Recording the conflict does not decide which description describes actual operation.

### B.8 Documentary extraction and deterministic tooling

Validator-run deterministic extraction supplied reproducible candidate inventories and structured material for link/path checks, exact-text matching and comparison. Candidate rows were not accepted propositions merely because a lexical pattern matched. Repeated triggers and source locations required interpretation within their corpus context; counts of occurrences were not counts of independent claims.

Extraction alone could not establish semantic truth, complete recall, canonical authority, formula correctness, address validity or use, implementation identity or deployment. Implicit references can be missed, and complex linking or anchoring can require interpretation beyond deterministic extraction. External destinations were not validated merely by extracting them. Local path existence likewise did not settle the intended reference base.

The human validator controlled semantic acceptance and interpretation. The retained limitations accompany the inventories; these were inputs to evaluation rather than an automated substitute for it. No new extraction or reproducibility run is performed by this appendix.

### B.9 Provenance and source-binding standard

Source identity supplies the link between a documentary implementation claim and the code or deployed target proposed for inspection. Similar names, suggestive interfaces, later contracts using related terminology or adjacent registry material are leads, not sufficient identity by themselves. The connection must be specific enough that the next test examines the implementation claimed rather than an easier substitute.

For C05, separately resolved provenance supported identification of the implementation repository and historical source revisions, allowing source and chain work to proceed. For C06, retained leads did not establish the required legacy identity. The resulting stop did not prove that no source existed elsewhere. Missing provenance remained an evidence boundary; unavailable architecture content was not assumed to contain the missing implementation. Detailed source trails belong in Appendices E–G.

### B.10 Static implementation review

Static review examines what the identified source implements at the inspected revisions: component relationships, access-control logic, configuration semantics and defined functions or events. Its conclusions are tied to the actual inspected material and relevant interfaces or dependencies. A component name or an unbound source family is insufficient to make that behavior attributable to a Laniakea claim.

Source inspection does not itself establish deployment, active use, responsible event callers or continuous runtime behavior. Historical revisions also do not prove exact source/runtime bytecode correspondence. That would require separate reliable reproduction or binding evidence. A source-behavior finding is consequently neither live-operation proof nor comprehensive security/integration assurance. The evaluation preserves the distinction even where source and chain evidence converge on one scoped proposition.

### B.11 Runtime / chain verification

Chain checks answer questions about specified addresses, blocks and query scopes. They can record code presence, returned state, wiring, roles, configuration and bounded events. The block and network anchors are part of the observation, not incidental metadata: they define when and where the returned evidence applies. “Current” in the retained C05 record denotes the fixed September observation, not publication-time monitoring.

A fixed observation does not establish continuous operation; two snapshots do not reconstruct complete history. Deployment alone does not prove active use. Event emission does not identify a caller unless the retained evidence supports that attribution, and an empty bounded query does not establish absence of use. Corresponding token transfers and complete transaction paths were not established by the retained event evidence. No broader operational conclusion follows merely from combining separate observations.

### B.12 Evidence stopping rules

Evaluation stops when the evidence needed for the next scoped question is insufficient, inaccessible or outside authorization. Relevant situations include unresolved source identity, ambiguous claim scope, unavailable prerequisite material, a proposed test requiring speculative source substitution, and a question belonging to a future project state. Continuing through such a gap would change the proposition under test or replace evidence with assumption.

“Stop” here is ordinary methodological language, not an invented grade. HOLD names a prerequisite gate; PARKED describes deferred further verification; OUT OF SCOPE identifies a broader test not included in completed work. Their different meanings remain attached to the record. Stopping can be the correct completion of an evidence-limited inquiry, without making the claim false or creating a duty to continue searching. Reconsideration depends on the existing qualifying conditions and appropriate scope.

### B.13 Human-validator role

An independent human validator led the evaluation and made the substantive judgments. The assistant served as an analyst, not an independent validator, final grader or governance authority. Human judgment controlled claim framing, temporal classification, evidence sufficiency, ambiguity handling, acceptance of synthesis dispositions and publication wording.

Tooling supported extraction, comparison, source inspection, revision control, deterministic checks, authorized chain queries and evidence retention. These functions have different evidence roles: a deterministic inventory, a retrieved source artifact and a returned chain observation are not interchangeable. The original setup restrictions did not themselves authorize later technical work; the retained phase records describe the subsequent scoped work. Automation assisted human review rather than replacing it.

### B.14 Snapshot and historical-integrity discipline

Frozen revisions preserve the evaluated documentary and source versions; fixed chain anchors preserve the observations used. They allow later readers to distinguish the subject snapshot from comparator dates and subsequent evidence collection. The record does not describe every source as simultaneously current.

Later evidence does not rewrite an earlier phase result. Newly discovered evidence about the old snapshot differs from an actual later project change: the first may answer a historical question, while the second creates a delta against the baseline. Likewise, a later documentary repair does not erase the earlier snapshot's finding. This discipline preserves reproducibility and historical grades while allowing later evaluations to identify what changed, which claims are affected and which evidence paths warrant reconsideration.

### B.15 Scope and assurance boundaries

The evaluation selected statements for traceability rather than exhaustive corpus verification. The 53 selected units overlap and are not 53 independent propositions; separate contextual records do not turn the selection into a coverage percentage. Classification or extraction alone does not mean substantive verification was completed for every statement.

The methodology does not provide a security audit, comprehensive code audit, implementation-completeness certification, runtime certification, governance-readiness certification or complete operational history. Strongly supported conclusions are possible for bounded propositions where independent evidence layers converge, with each layer's limits retained. The evidence supports confidence in specific scoped conclusions, not confidence by extrapolation. Neither confidence in one implementation case nor a well-supported documentary comparison supplies equivalent assurance for untested claims, target architecture or the project as a whole.

### B.16 Relationship between historical evaluation and synthesis

The publication pipeline connects historical phase results to the master evidence matrix, human synthesis decisions, the frozen body and then appendices/publication. Historical records preserve what was tested and concluded at each stage. The matrix organizes accumulated support, dispositions, limitations and permitted publication wording. The narrative explains the significance within those controls; appendices expose the supporting detail.

Synthesis can interpret the significance of accumulated evidence without altering a historical result. The matrix remains publication control: if appendix prose conflicts with it, the matrix wins. Frozen narrative interpretation is also preserved. Appendix drafting therefore cannot reopen a claim by implication, turn optional assurance into a closure requirement or convert an unresolved boundary into a negative finding. It adds traceability, not a new evaluation layer with new substantive results.

### B.17 Reproducibility and independent review

The retained materials allow another reviewer to identify the baseline, inspect selected claims, locate phase records, follow source and chain evidence paths, and see why a test proceeded or stopped. They distinguish documentary witnesses, implementation sources, deterministic outputs and observed chain state. Deterministic checks can be reproduced where retained inputs and tools permit, subject to the recorded extraction limitations and human review requirements.

Reproducibility is bounded by retention. Accepted L0 validator-run inventories remain distinct from later retrieved source artifacts and chain records. The L3F schema describes normalized records of successful responses and retained code/log bodies; it does not claim complete raw RPC envelopes. The report does not supply cryptographic state proofs, independent-provider replication or complete RPC replay from retained raw data. Existing manifests support artifact traceability without this appendix asserting a new checksum verification. Appendix I is allocated the detailed evidence and retention index.

### Evidence notes

- **B-1.** `EVAL-CHARTER.md` — Claim-first design, evidence hierarchy, grades and analyst/validator boundary.
- **B-2.** `expected/L0.md` — Pre-stated corpus, canonicality, navigation, status and inventory invariants.
- **B-3.** `expected/L1.md` — Temporal classification, proposed-state protection and ambiguity invariants.
- **B-4.** `synthesis/master-evidence-matrix.md` — Vocabulary, reporting crosswalk, publication dispositions and evidence ceilings.
- **B-5.** `synthesis/report-architecture.md` — Methodology allocation and appendix boundaries.
- **B-6.** `synthesis/report-sections/02-scope-baseline-methodology.md` — Frozen methodological explanation.
- **B-7.** `synthesis/report-sections/09-limitations-and-future-work.md` — Retention, stopping, assurance and delta boundaries.
- **B-8.** `synthesis/report-sections/10-principal-synthesis-findings.md` — Scoped methodological illustrations.
- **B-9.** `synthesis/report-sections/11-overall-synthesis.md` — Report-level assurance rule.
- **B-10.** `reports/2026-09-18-f438819/L1-claim-map.md` — Selection method, reporting classes and source-local qualifications.
- **B-11.** `reports/2026-09-18-f438819/Ledger.MD` — Historical phase and grade record.
- **B-12.** `reports/2026-09-18-f438819/leads.md` — Retained prerequisites, closure and stopping context.
- **B-13.** `evidence/f438819/LIMITATIONS.txt` — Deterministic extraction limits and human-validation requirement.
- **B-14.** `reports/2026-09-18-f438819/L3F-evidence/README.md` — Observational schemas and retention limits.

## Appendix C — L0–L3F Phase Ledger

### C.1 Purpose and reading rule

This appendix preserves the historical evaluation record: what each phase tested, the evidence available at that point, the recorded result, and the prerequisite or authorization boundary at which it stopped. It covers L0 through L3F. The baseline and commit lineage are in Appendix A; the methodological explanation is in Appendix B.

Historical grades are not replaced by final synthesis dispositions. Later evidence can support a stronger accumulated conclusion without changing the result of an earlier, narrower inquiry. For example, L2-04 retains FAIL for its tested policy invariant, while C04's final synthesis is PARTIALLY ESTABLISHED. Those labels answer different questions and are shown separately below.

Not every claim traversed every phase. L2 covered C01–C04; L3A and L3B covered C05/C06; L3C–L3F deepened C05 only. A phase's eligibility decision did not itself authorize the next activity. The retained records document subsequent scoped authorization where work proceeded. Historical stop statements describe their phase boundaries, not an unfinished requirement to continue every inquiry.

For compact artifact references below, **R/** means `reports/2026-09-18-f438819/`. Report titles in the overview reproduce the frozen headings where a dedicated phase report exists. L0's documentary review is recorded in the ledger and five findings rather than a single separately titled phase report. Final dispositions are controlled by the master evidence matrix, not inferred from the historical grade totals.

### C.2 Phase overview

| Phase | Primary objective | Main artifact(s) | Historical result type | Advancement / stopping consequence |
|---|---|---|---|---|
| L0 — documentary / semantic review | Test corpus boundary, canonicality, navigation, status integrity and reference inventories. | R/`Ledger.MD`; R/`findings/L0-*.md` | Five invariant findings: one PASS, two WARN, two FAIL. | Preserve documentary limits; do not infer implementation results. L1 required separate authorization. |
| L1 — L1 claim-status map | Classify selected statements and test temporal consistency and safeguards. | R/`L1-claim-map.md`; R/`findings/L1-*.md` | Two PASS, three FAIL arising from one conflict cluster. | Carry unresolved status forward; conditional progression did not resolve operating truth. |
| L2 — Atlas binding for C01–C04 | Compare four selected propositions against Atlas. | R/`L2-atlas-binding-C01-C04.md`; four L2 findings | PASS, NOT ESTABLISHED, NOT ESTABLISHED, FAIL. | Retain claim-specific comparisons; no operational or implementation test followed automatically. |
| L3A — Static STL coverage and source binding: C05–C06 | Seek implementation coverage in pinned STL. | R/`L3A-STL-binding-C05-C06.md`; two L3A findings | Both NOT ESTABLISHED; NO MATCHED STL COVERAGE ESTABLISHED. | Stage 2 not opened; both chain gates HOLD. |
| L3B — Local implementation provenance for C05/C06 | Trace local documentary, registry and source leads. | R/`L3B-implementation-provenance-C05-C06.md`; two L3B findings | Both NOT ESTABLISHED. | C05 eligible for narrow external provenance retrieval under separate authorization; C06 lacked a concrete target; both chain gates HOLD. |
| L3C — C05 external provenance result | Inspect the exact authorized external leads. | R/`L3C-C05-external-provenance.md`; L3C finding and retained retrieval record | NOT ESTABLISHED. | Source labels became more specific; repository identity unresolved; chain HOLD. |
| L3D — C05 exact repository resolution | Resolve repository, revisions, tags and source files. | R/`L3D-C05-repository-resolution.md`; L3D finding | PASS for source identity. | Static review eligible for separate authorization; chain HOLD. |
| L3E — C05 exact-revision static implementation binding | Inspect behavior and component relationships at the identified revisions. | R/`L3E-C05-static-binding.md`; L3E finding | PASS for scoped static implementation. | CHAIN GATE ELIGIBLE; live/deployed status still NOT ESTABLISHED at phase end. |
| L3F — C05 Mainnet chain validation | Bind the scoped components to two fixed Mainnet observations. | R/`L3F-C05-mainnet-chain-validation.md`; L3F finding and retained chain record | PASS with expressly bounded subresults. | Scoped C05 conclusion closed; caller, exact-bytecode and continuity limits retained. |

The overview counts historical findings, not independent systems or a project success rate. It also distinguishes an available evidence lead from a matched implementation: the existence of the former explains progression without supplying the latter prematurely.

### C.3 L0 — Documentary / corpus review

L0 examined the documentary surface and the accepted deterministic inventories. Its five findings concern the selected corpus and the ability to locate and interpret documentary material. They do not grade governance correctness, implementation, deployment or security.

| Finding | Historical grade | Tested invariant / question | Result | Key limitation | Later synthesis relevance |
|---|---|---|---|---|---|
| L0-01 — Corpus boundary | WARN | Is the consultation boundary clear? | Two slideshow files retain stale/ambiguous status outside ordinary active consultation. | Their treatment does not determine the truth of their technical content. | Documentary selection boundary. |
| L0-02 — Canonicality | FAIL | Can the designated canonical Sky Intents destination be resolved? | The designated destination is absent; no current successor or same-scope ambiguity record was established. | Related historical material is not silently accepted as the canonical replacement. | Canonicality gap, not implementation nonexistence. |
| L0-03 — Internal navigation | FAIL | Do ordinary active-document links resolve? | 26 ordinary broken-link occurrences across 13 active source documents target 12 distinct absent destinations. | Counts concern navigation occurrences, not 26 independent technical defects. | Reproducible documentary-navigation problem; artifact traceability belongs in Appendix I. |
| L0-04 — Status integrity | WARN | Is the authority and scope of inactive canonical material clear? | The capital-stack reference to an inactive whitepaper leaves canonical authority/scope unresolved. | An inactive reference is not by itself proof of a false current claim. | Source-selection uncertainty. |
| L0-05 — Reference inventory | PASS | Are the six reference categories reproducibly inventoried? | Stable source-located candidate inventories exist for all six categories. | Extraction does not establish semantic completeness, validity or use. | Useful documentary capability supporting later claim selection. |

The accepted result is one PASS, two WARN and two FAIL. A reproducible inventory and a broken canonical destination can coexist: they concern different documentary properties. Later source and chain evidence does not repair these historical navigation or status findings. Conversely, these findings do not establish defects in the code subsequently inspected.

### C.4 L1 — Claim and temporal classification

The frozen L1 map selected 53 statement units. Selection was non-exhaustive, units overlap, and they are not 53 independent propositions. X1 and U1–U4 were retained separately as conflict or unresolved contextual records. Their later inclusion in the master matrix is not an expansion of the original selected-unit count into a coverage percentage.

| Finding | Historical grade | Phase outcome |
|---|---|---|
| L1-01 — Temporal clarity | FAIL | X1 prevents a consistent current/future reading of the relevant P1 closure/monthly-atom assertions. |
| L1-02 — Present-tense consistency | FAIL | The same X1 cluster contains explicit operation wording that conflicts with deferred closure language. |
| L1-03 — Proposed-state protection | PASS | Proposed and future statements were protected from being scored as absent current implementation. |
| L1-04 — Cross-document status consistency | FAIL | The same X1 conflict appears across active detail, summary and roadmap material. |
| L1-05 — Ambiguity preservation | PASS | Unresolved classifications were preserved rather than forced into current-state conclusions. |

X1 concerns P1 closure records and monthly atoms in `accounting/settlement-cycle.md`, compared with `summaries/accounting.md` and `roadmap/phase-1-spaces.md` at the subject pin. The documentary conflict exists; actual operating truth and the intended documentary winner remain NOT ESTABLISHED. These are three invariant failures arising from one conflict cluster, not three independent implementation failures. Documentary HOLD remained appropriate for affected interpretations.

Representative classifications also prevented unsupported deployment inferences. C28 records earlier sentinel formation vocabulary; C49 records supersession of an earlier runtime-research track; C53 records the prior documentation baseline. These are HISTORICAL. C50's deployed-contract prerequisites occur inside a user story, C51 is a worked settlement sketch, and C52 illustrates a crystallization realization: these are EXAMPLE / ILLUSTRATIVE. C52 does not erase C09's separate current-instance assertion. Detailed row allocation belongs in Appendix H; here the relevant outcome is preservation of distinct temporal and evidentiary functions.

### C.5 L2 — Atlas binding C01–C04

L2 compared the four selected propositions with pinned Atlas policy and documentary records, including relevant pre-subject witnesses. The historical results below reproduce the finding titles and grades. The final column is a separate publication layer, not a replacement grading of L2.

| Historical finding | Historical phase result | Question and phase boundary | Later synthesis disposition |
|---|---|---|---|
| L2-01 — C01 Atlas operational data | PASS | Four operational-data categories have documentary witnesses; addresses, deployment and use were not validated. | C01: ESTABLISHED for documentary presence. |
| L2-02 — C02 Ozone / Guardian tree | NOT ESTABLISHED | Executor/accord evidence does not bind the claimed single-Guardian/direct-child hierarchy. | C02: NOT ESTABLISHED. |
| L2-03 — C03 Phase 1 authority | NOT ESTABLISHED | Broader governance roles do not establish the specific P1 v2 genesis authority mapping. | C03: NOT ESTABLISHED. |
| L2-04 — C04 entity fees | FAIL | Material policy mechanics differ for the tested invariant within shared Prime scope; payments were not tested. | C04: PARTIALLY ESTABLISHED. |

L2-04 retained the supported numerical upkeep rate and general rebate entitlement alongside discrepant mechanics and unresolved details. Its FAIL is therefore not converted into a uniform rejection of every subclaim. Equally, the later mixed C04 disposition does not soften or replace that historical FAIL. The matrix's separate L2-04 finding row establishes the documentary-policy discrepancy; its C04 claim row records the mixed claim disposition. Appendix D supplies the detailed bindings without expanding L2 into a deployment or payment test.

### C.6 L3A — STL binding C05–C06

For both C05 and C06 the exact coverage result is **NO MATCHED STL COVERAGE ESTABLISHED**. Each main result was NOT ESTABLISHED, and both chain-verification gates remained HOLD. Stage 2 was not opened because the required implementation match was missing. All C05-A–F and C06-A–F subresults remained NOT ESTABLISHED.

STL contained relevant registry, reference and observation material. For C05, ALM address/tracking references were present before the subject timestamp, but registry code was not partial executable PAU coverage. For C06, historical PoolConfigurator references and generic configuration or timelock material did not identify the claimed legacy BEAM/cBEAM stack.

The result was bounded to the evaluated STL evidence. It established neither source nonexistence nor claim falsehood and did not characterize STL as deficient. The missing implementation match prevented chain progression while leaving qualifying provenance leads available for separately authorized investigation. Later external C05 success does not rewrite what STL coverage established in L3A.

### C.7 L3B — Implementation provenance C05–C06

L3B traced local references rather than substituting a plausible repository for a missing source. Both historical main results remained NOT ESTABLISHED; both chain gates remained HOLD, and live/deployed status remained NOT ESTABLISHED.

| Claim | Historical provenance result | Advancement / stopping consequence |
|---|---|---|
| C05 | Concrete documentary/UUID provenance chain and exact external leads; complete implementation source NOT ESTABLISHED. | Eligible only for separately authorized narrow EXTERNAL PROVENANCE RETRIEVAL. |
| C06 | Legacy implementation identity and legacy-to-PAS bridge NOT ESTABLISHED; concrete external retrieval target NONE. | Not eligible for targeted external-source retrieval; chain HOLD. Architecture access remained BLOCKED where applicable. |

For C05, Laniakea named the Spark ALM family, Atlas supplied component relationships, and an STL source UUID resolved to the Atlas ALMProxy record. Package metadata supplied registry provenance. The exact axis-synome archive and Spark address registry were concrete leads; related PSM and audit references were discriminators, not established whole-stack implementation sources.

For C06, later PAS Configurator, BeamState and Timelock records did not supply an explicit bridge to the legacy implementation. An OpenZeppelin component-family attribution did not identify a complete repository, version or source artifact. Architecture's access limitation did not turn the main result into BLOCKED or establish that architecture was the required source. Neither legacy/PAS equivalence nor non-equivalence was inferred. PARKED belongs to later synthesis, not this historical grade.

### C.8 L3C — C05 external provenance

The historical result remained **C05 NOT ESTABLISHED; chain HOLD**. Under its separately granted narrow retrieval scope, L3C inspected the exact L3B pointers. The axis-synome archive matched its recorded hash but supplied specification-package provenance. PSM and audit material remained adjacent evidence. The Spark address registry supplied the decisive new source-attribution text.

Its Ethereum and Base source comments named `spark-alm-controller` and attributed MainnetController to `984ec54`/v1.10.0, ForeignController to `7be9593`/v1.8.0, and ALMProxy/RateLimits to `6058f68`/v1.0.0. Those were specific filename, revision and version labels, stronger than similar names alone. They were facts about registry attribution text, not yet independent proof of source/address/version correspondence.

No owner-qualified implementation URL or qualifying implementation artifact was established in that phase; no onward implementation link was followed and no owner was guessed. All eight implementation-binding subresults remained NOT ESTABLISHED. The ALM source chronology was also unresolved: a pre-subject package hash or an older PSM audit did not date the ALM implementation. L3C stopped for human review or separately authorized source-location resolution, preserving the distinction between attribution discovery and repository resolution.

### C.9 L3D — C05 repository resolution

L3D recorded **PASS** for exact source identity. The matching repository was `sparkdotfi/spark-alm-controller`. The retained discovery and resolution record bound the earlier labels to full commits, exact tags and the four inspectable source files. It did not rely on choosing a repository merely because its name seemed plausible.

| Component witness | Resolved revision | Exact tag | Source witness date |
|---|---|---|---|
| MainnetController | `984ec546fb2c98ed729ae91d2d73e97dedbf111f` | v1.10.0 | February 16, 2026 |
| ForeignController | `7be959378fe48117f7a06796f94e240345428982` | v1.8.0 | November 7, 2025 |
| ALMProxy and RateLimits | `6058f68f79520eb06ea8eded146da13039c47525` | v1.0.0 | October 22, 2024 |

These are mixed component revisions, not an atomic release, first-introduction dates or deployment dates. REPO-1 through REPO-11 passed within source-identity scope. Complete semantics, integration compatibility and address/runtime binding were not established by repository resolution. Static review became eligible for separate authorization; chain HOLD and live/deployed NOT ESTABLISHED remained the phase-end boundaries.

### C.10 L3E — C05 static implementation binding

L3E recorded **PASS — scoped static implementation only**. The exact historical revisions above, their parent interfaces/helpers and retained indispensable dependency witnesses supported the generic legacy PAU description with qualifications. C05-E1–E9 passed within that source-review scope; they are supporting subresults rather than nine independent systems.

The inspected Controller paths interact with keyed RateLimits capacity and call ALMProxy for execution. Proxy access is role-gated; the proxy does not itself call RateLimits. RateLimits implements capped elapsed-time replenishment for finite configurations. Administrative configuration is distinct from runtime consumption/restoration. Action-specific behavior, unlimited configurations and the inspected dependency scope limit generalization from the generic description.

The phase recorded **BEHAVIOR PRESENT WITH QUALIFICATION PRE-JUNE** and **CHAIN GATE ELIGIBLE**. Live/deployed status was still NOT ESTABLISHED. Static source could establish inspected behavior and component relationships, not concrete deployed grants, active use, event-caller attribution, continuity or exact source/runtime bytecode identity. Chain eligibility required a later separately authorized test; it was not deployment proof. Detailed functions, dependencies and technical identifiers belong in Appendix F.

### C.11 L3F — C05 Mainnet chain binding

L3F recorded **PASS** for scoped Mainnet binding. It observed Ethereum Mainnet, chain ID 1, at block 25,242,585 on June 4, 2026, 07:38:47 UTC and block 26,007,670 on September 18, 2026, 23:26:35 UTC. The successor block used to bracket the subject timestamp was metadata, not a third full observation. “Current” in the historical report means the retained September point, not publication-time freshness.

At both points the tested Controller, ALMProxy and RateLimits had code, the expected wiring, relevant Controller grants and observed role configuration. A representative finite RateLimits mint-key configuration was present. Separately retained bounded event windows supported RateLimits component consumption. The report's highest usage level was LEVEL 4 limited to that component; the named Controller independently reached LEVEL 3 deployment/wiring/configuration. Component events did not identify their caller.

| Principal ceiling | Retained boundary |
|---|---|
| RateLimits-event caller attribution to the tested MainnetController | NOT ESTABLISHED. |
| Exact source/runtime bytecode equivalence | NOT ESTABLISHED. |
| Continuous June→September operation | NOT ESTABLISHED. |
| All-layer PAU deployment | OUTSIDE C05. |
| Comprehensive security/integration certification | OUTSIDE SCOPE. |

Unchanged runtime hashes at two points do not establish continuity or reproduce source bytecode. Zero matching OTC events do not prove no Controller use. The Atlas alternative's differing grants do not establish migration cause/date or that it never operated. First deployment, activation and complete operational history remain unresolved.

The historical interpretation was **LIVE-SUPPORTING HISTORICAL STATE; CURRENTLY RETAINED**. C05-F1–F16 and F18 passed within their stated scopes; F17 exact source/bytecode equivalence remained NOT ESTABLISHED. The retained closure record closes C05 for its scoped Report v1 conclusion, with exact bytecode reproduction optional assurance. It does not generalize that conclusion to all PAU, target architecture or all Laniakea implementation.

### C.12 Advancement and stopping logic

L0/L1 established documentary selection and classification boundaries. L2 compared Atlas propositions. L3A tested STL implementation coverage without substituting registry material for executable source. L3B identified different provenance prospects for C05 and C06. C05 advanced through specific attribution, repository resolution, static behavior and Mainnet binding; C06 did not cross the implementation-source threshold.

That sequence explains why L3C–L3F are C05 phases only. C06 was stopped before speculative static or chain substitution, not scored as nonexistent, false or undeployed. Stopping when the evidence threshold is not met is part of completing an evidence-limited evaluation. Later synthesis parks that question pending qualifying provenance; it creates no obligation to keep searching.

Each positive transition preserves its own ceiling. Repository identity justified static inspection, static binding justified a scoped chain test, and two chain observations supported a bounded deployed-state conclusion. None retrospectively made the earlier missing evidence available, and none authorized extrapolation beyond the tested proposition.

### C.13 Historical result versus final synthesis

| Item | Historical result | Later synthesis disposition | Why both remain valid |
|---|---|---|---|
| L2-04 / C04 | FAIL for the tested shared-Prime policy invariant. | C04 PARTIALLY ESTABLISHED; the separate L2-04 discrepancy finding is ESTABLISHED in the matrix. | Mixed support for the claim coexists with an established material discrepancy; historical FAIL is unchanged. |
| C05 | L3A NO MATCHED STL COVERAGE ESTABLISHED; L3B/L3C implementation identity NOT ESTABLISHED at their stops. | C05/C05-FINAL ESTABLISHED for the scoped accumulated conclusion; CLOSED. | Later separately resolved source and chain evidence answers questions earlier evidence could not; initial STL coverage remains unchanged. |
| C06 | Legacy identity NOT ESTABLISHED; architecture access BLOCKED where applicable; chain HOLD. | C06/C06-FINAL PARKED. | Identity, access, gate and synthesis disposition describe different objects; none means nonexistence or permanent closure. |
| X1 | L1-01/-02/-04 FAIL from one documentary conflict. | ESTABLISHED conflict existence; actual operating truth NOT ESTABLISHED. | Establishing conflicting accounts does not select their intended winner or establish runtime behavior. |

This crosswalk preserves representative distinctions rather than replacing Appendix J's formal terminology role. Appendix C supplies historical traceability; the matrix and frozen narrative continue to control public claim interpretation.

### Evidence notes

- **C-1.** `reports/2026-09-18-f438819/Ledger.MD`
- **C-2.** `reports/2026-09-18-f438819/leads.md`
- **C-3.** `reports/2026-09-18-f438819/L1-claim-map.md`
- **C-4.** `reports/2026-09-18-f438819/L2-atlas-binding-C01-C04.md`
- **C-5.** `reports/2026-09-18-f438819/L3A-STL-binding-C05-C06.md`
- **C-6.** `reports/2026-09-18-f438819/L3B-implementation-provenance-C05-C06.md`
- **C-7.** `reports/2026-09-18-f438819/L3C-C05-external-provenance.md`
- **C-8.** `reports/2026-09-18-f438819/L3D-C05-repository-resolution.md`
- **C-9.** `reports/2026-09-18-f438819/L3E-C05-static-binding.md`
- **C-10.** `reports/2026-09-18-f438819/L3F-C05-mainnet-chain-validation.md`
- **C-11.** `reports/2026-09-18-f438819/findings/L3F-01-C05-mainnet-chain-binding.md`
- **C-12.** `synthesis/master-evidence-matrix.md`
- **C-13.** `synthesis/appendices/B-evaluation-methodology.md`

## Appendix D — Atlas Binding Ledger

### D.1 Purpose and scope

This appendix traces the four selected Atlas-binding claims, C01–C04, from the Laniakea proposition to the compared Atlas witnesses. It separates supported dimensions, affirmative differences and unresolved mappings, retaining both the historical L2 result and the final synthesis disposition. It does not extend the comparison to every Laniakea claim or every Atlas provision.

The objects compared are documentary representations and policy rules. Documentary presence does not establish address correctness, deployment or runtime operation. Policy does not establish enacted payments, governance intent or future adoption. Historical grades remain the results of their original tests; final synthesis dispositions characterize the accumulated evidence without replacing those grades.

Subject and Atlas paths below are paths within their respective frozen source repositories, not files in the evaluation repository. Line references reproduce the accepted L2 findings. The evidence notes at the end identify the retained reports supporting these comparisons; no new source inspection or research is introduced here.

### D.2 Atlas source and temporal basis

| Source | Frozen identity | Comparison role |
|---|---|---|
| Laniakea subject | `sky-ecosystem/laniakea-docs`, revision `f4388196198df3435b38357bc7f1fccc1c5a1317`; June 4, 2026 | Supplies the selected propositions. |
| Pinned Atlas | `sky-ecosystem/next-gen-atlas`, revision `4c466eb1c9508abea08412f43011dfd40e1cfb82`; tree `1679d830b60855d09cd430890e146ebcd68b248c`; recorded date `2026-09-17T19:58:05+01:00` | Supplies the frozen governance-policy/documentary comparator. |
| Historical Atlas comparator | `7fa69a61dc52905e589308709e6260095c45bd78`; May 29, 2026 | Supplies relevant witnesses predating the subject snapshot. |

Appendix A records the complete baseline manifest. The historical comparator was the retained latest reachable Atlas ancestor before the subject timestamp used by L2. It helps distinguish pre-existing policy from later edits; it does not make the September comparator contemporaneous with every June operational assertion.

Atlas's August consolidation reorganized paths. The historical findings bind relevant sections through persistent UUIDs rather than assuming identical filenames or numbering. For C04, the one-time founding fee, USDS upkeep, payment-dependent rebate and unfinished payment procedure already appeared before June. The discrepancy is not explained solely by later September edits. Persistence establishes documentary chronology, not intentional divergence, ratification or payment history.

Atlas's own development and local status qualifications remain part of the evidence. An active instance and a deferred payment procedure can both appear in the same policy record; neither qualification is discarded to make the comparison simpler.

### D.3 Master C01–C04 table

| Claim | Laniakea proposition | Atlas relationship | Historical L2 result | Final synthesis disposition | Key ceiling |
|---|---|---|---|---|---|
| C01 | Prime SubProxy addresses, relayer multisigs, rate-limit types and per-chain deployment lists sit in Atlas prose. | All four selected categories have documentary witnesses, including pre-June material. | L2-01 PASS. | ESTABLISHED. | Documentary presence only, not address correctness, deployment, use or migration. |
| C02 | Ozone is the single operational Guardian; USGE Generator and all Primes are direct children, with separate GovOps teams. | Executor/accord records do not establish the exact Guardian and organizational mapping. | L2-02 NOT ESTABLISHED. | NOT ESTABLISHED. | Executor service, Guardian identity and direct-child parenthood are not interchangeable. |
| C03 | Phase 1 v2 starts fully sudo; the Guardian holds everything at genesis and Core GovOps has no role yet. | Broader governance roles do not bind that phase-specific authority layer. | L2-03 NOT ESTABLISHED. | NOT ESTABLISHED. | A genesis-scoped assertion is not a claim that Core GovOps has no role anywhere in Sky. |
| C04 | Live entity fees combine 5% on every issuance, 50 bps/year upkeep, continuous rebates and tokenless exemptions. | Supported rate/entitlement, discrepant mechanics and unresolved details within shared Prime scope. | L2-04 FAIL. | PARTIALLY ESTABLISHED. | Policy comparison does not establish payments, intent or universal entity coverage. |

### D.4 C01 — Operational-data documentary presence

The subject passage is `macrosynomics/atlas-synome-separation.md:73–76`. Its documentary-presence proposition is separable from the proposed migration mentioned at line 76. The historical L2-01 PASS and final ESTABLISHED disposition concern where these categories are recorded.

All pinned witnesses below are in Atlas `content/A.6.1.1.1 - Spark.md`.

| Category | Pinned witness | Binding identifier | Supported meaning |
|---|---|---|---|
| Prime SubProxy addresses | Lines 85–87 | UUID `378950e0-85c9-4f12-94cd-fb36cde59ba9` | A named Prime account record supplies an address. |
| Core Operator Relayer multisigs | Lines 2490–2500 | UUID `8286092a-69f2-46af-a989-c694a1756753` | Role, controller, address and signing-requirement information is documented. |
| Rate-limit types | Lines 2146–2180 | RateLimits UUID `cdf6df73-045a-4bcb-a456-03441aa4530e` | Named operational mint, burn, swap and bridge limit kinds appear. |
| Per-chain deployment records | Lines 1793–1803 and 1833–1859 | ALM Contracts UUID `7db865de-8519-464b-8752-f39ecaf54fd2` | Contract/address records are organized under named chains, including Mainnet and Base. |

“Types” means named operational limit kinds, not a verified programming-language enum declaration. “Deployment records” means documentary chain-specific lists, not independently verified deployments. Named roles and surrounding headings make these more than unexplained address literals, but the presence test does not validate the underlying operational representations.

At historical Atlas revision `7fa69a61`, corresponding witnesses occur in `content/A/6/1/1/1/2/1/1/3/1/1/2/document.md:10–12` for SubProxy; `content/A/6/1/1/1/2/6/1/2/1/2/2/2/1/document.md:10–12` for the relayer address; and `content/A/6/1/1/1/2/6/1/2/1/1/3/1/1/document.md:10–15` for the named mint limit. Mainnet and Base records appear respectively in `content/A/6/1/1/1/2/6/1/2/1/1/1/2/1/document.md:10–12` and `content/A/6/1/1/1/2/6/1/2/1/1/1/2/2/document.md:10–12`.

These references establish pre-June category presence without backdating September numerical parameters. Placeholders elsewhere, such as Spark's Avalanche rate-limit address, prevent a completeness inference without negating the witnessed categories. C01 establishes neither actual use nor exhaustive deployment coverage, address correctness, ratification dates or completed migration into Synome.

### D.5 C02 — Guardian, executor and organizational mapping

The subject proposition in `macrosynomics/atlas-synome-separation.md:258–274`, particularly lines 263 and 270, calls Ozone the single operational Guardian and describes USGE and all Primes as direct children. The table's “Accordant to Ozone” wording accompanies an organizational assertion; it cannot be reduced to a token-holding or service-provider claim.

| Atlas witness at the pinned revision | What it supplies | What it does not bind |
|---|---|---|
| `content/A.0 - Atlas-Preamble.md:204–208,226–238` | Agent/Executor definitions and operational-status qualifications. | Identity between Executor and the claimed Guardian class. |
| `content/A.6.1.2.1 - Operational-Executor-Agent-Amatsu.md:1–11`; `content/A.6.1.2.2 - Operational-Executor-Agent-Ozone.md:1–11` | Separate named executor artifacts, each retaining future-specification language. | One exclusive operational Guardian or a universal organizational parent. |
| `content/A.6.1.1.1 - Spark.md:467–481` | Active Amatsu Executor Accord. | Spark's direct-child relationship to Ozone. |
| `content/A.6.1.1.4 - Skybase.md:435–449` | Active Ozone Executor Accord. | A hierarchy covering every Prime and the Generator. |

Spark and Skybase have different accord counterparties. This prevents silently substituting “all Executor Accords name Ozone” for the actual proposition, but does not disprove a separate organizational hierarchy. Shared Operational GovOps does not merge Amatsu and Ozone. Service relationships, collateral, ownership, Guardian authority and parenthood remain distinct.

General Atlas text describing Executor Agents as “not yet operational” coexists with active accord records. Both were retained; the evaluation did not decide which describes actual operation. Other Atlas Guardian usages, including legal defense and Morpho cancellation authority, do not supply the missing identity bridge.

The historical record already contains Ozone's interim artifact, Spark's Amatsu configuration and the general operational qualification before June. Their coexistence cannot simply be treated as a September rename, but that history still does not establish a June Guardian hierarchy. The historical L2-02 result and final C02 disposition remain NOT ESTABLISHED. This is neither a falsehood finding nor a prohibition or governance rejection. Architecture's access limitation is separate from the available Atlas comparison.

### D.6 C03 — P1 authority and genesis mapping

The proposition appears in subject `summaries/governance.md:3`: Phase 1 v2 begins “fully sudo,” the Guardian holds everything at genesis, and Core GovOps has no role yet. In reader-facing terms, it claims that initial authority is concentrated in the Guardian. “Mostly target,” “Phase 1 v2 reality,” “at genesis” and the subsequent handoff qualify the scope; exact permissions remain unresolved.

| Pinned Atlas witness | Documentary rule | Unresolved connection |
|---|---|---|
| `content/A.0 - Atlas-Preamble.md:248–258` | Defines GovOps and Core Council GovOps; Core GovOps UUID `e512e890-629f-450f-a14d-a3ea06a369c0`. | Applicability to the specific P1 v2 genesis authority layer. |
| `content/A.1 - The-Governance-Scope.md:1092–1138` | Atlas/Synome precedence, Synome Editor designation, review and removal/pause rules. | Document editing/review is not automatically runtime sudo authority. |
| `content/A.1 - The-Governance-Scope.md:2458–2460` | Executive Process Liaison currently held by Core GovOps. | A current broader role does not identify the claimed genesis permissions. |
| `content/A.2 - The-Support-Scope.md:555–559` | Core GovOps validates inputs and creates an Agent Genesis Account and SubProxy. | Agent account creation is not an established definition of Phase 1 v2 genesis. |

The Synome Editor designation names Archon Tech and the review rules give Core GovOps real documentary responsibilities. Thus Atlas is not simply silent about Core GovOps. Those positive rules do not establish the identity of a P1 runtime's privileged key, its EVM permissions or the authority bundle held by a Guardian at genesis. Synome Editor is not silently equated with Guardian.

Core GovOps, the Editor designation and review obligations also have pre-June witnesses. This excludes a simple explanation based only on later-added role text; it cannot bridge different authority layers. Historical L2-03 and final C03 remain NOT ESTABLISHED for all three scoped subclaims. The result supplies no current implementation conclusion, claim-falsehood finding or prediction of future governance adoption.

### D.7 C04 — Entity fee policy

The subject fee model appears in `accounting/entity-fees.md:3,10–18,35–43`. Line 54 expressly includes Primes, establishing the shared scope for comparison with Atlas Prime policy. Lines 138–142 specify own-governance-token payment rather than USDS and current monthly P1 settlement. Lines 79–94 describe holdings-based rebate credit. These passages clarify C04 without verifying C11's operational payment assertions.

Pinned Atlas witnesses are `content/A.2 - The-Support-Scope.md:399–401,927–952,4632–4634`, covering creation, upkeep, rebates and Agent creation fees. Spark's instance in `content/A.6.1.1.1 - Spark.md:727–737,763–793,879–897` supplies active status, USDS terms, rebate entitlement and deferred payment-process detail.

| Dimension | Laniakea | Atlas | Result | Limitation |
|---|---|---|---|---|
| Annual upkeep rate | 50 bps/year. | Prime upkeep at 50 bps, equivalent to 0.50% annually. | SUPPORTED. | Rate support does not establish denomination, actual payment or every entity type. |
| General rebate entitlement | Cross-entity rebate. | Prime Holding/Issuing Agent rebate entitlement. | SUPPORTED within shared scope. | Wider eligibility and the detailed credit conditions are separate. |
| Creation/issuance trigger | Charge on every issuance. | One-time founding payment for establishing new Prime Agents. | DISCREPANT. | The affirmative trigger difference is distinct from an absent amount specification. |
| Upkeep denomination | Entity's own governance token, explicitly not USDS. | USDS upkeep, payable monthly on the first day. | DISCREPANT. | An active instance does not demonstrate realized transfers. |
| Rebate mechanism | Continuous holdings-value-based credit. | Depends on issuer's actual monthly upkeep payment; credited the following month. | DISCREPANT. | Stated conditions/timing are compared, not formula economics or mathematical correctness. |
| Creation amount | 5%. | Required creation amount and process deferred. | NOT ESTABLISHED. | Missing specification is not an affirmative contradiction of the number. |
| Blanket tokenless exemption | Tokenless entities pay neither fee. | No matched universal exemption for Laniakea's entity taxonomy established. | NOT ESTABLISHED. | Absence of the mapping does not prove tokenless entities must pay. |
| Payment realization | Current accrual, monthly upkeep and issuance routing asserted separately. | Policy/active labels with unfinished operational detail. | NOT TESTED under C04; C11 NOT INDEPENDENTLY VERIFIED. | No inference that payments occurred or did not occur. |

Atlas specifies month-end 24-hour TWAP valuation and leaves the destination address to be specified. Spark's active upkeep instance and its future payment-process specification remain visible together. The shared monthly cadence is counter-evidence against adding a monthly-versus-daily contradiction. It does not remove the own-token/USDS difference or establish operation.

Historical L2-04 remains **FAIL** for the tested invariant within shared Prime scope. Affirmatively different triggers, denomination and rebate conditions support that result; the missing 5% amount alone would not. Final C04 remains **PARTIALLY ESTABLISHED**, reflecting supported dimensions alongside material differences and unestablished details. The matrix's separate L2-04 row marks the discrepancy ESTABLISHED; it does not establish the entire claimed fee regime. These are distinct objects of synthesis, and neither rewrites the historical FAIL.

The result does not establish intentional divergence, a governance exception, ratification, supersession, future convergence or payment behavior. Nor does it determine uniform coverage of all Synomic Entity types. The scoped comparison is sufficient without treating every Laniakea entity as an Atlas Prime.

### D.8 Documentary policy versus enactment and operation

Laniakea prose is not itself current Sky governance authority. Atlas policy/documentary presence is also distinct from enactment, execution, approval, payment and runtime deployment. Across C01–C04, the evidence must support the particular relationship being asserted; a documentary witness cannot silently serve as a chain observation.

Consequently, C01's presence result supplies no deployment finding, C02's named executors supply no proven permission tree, and C03's governance roles supply no verified genesis key. C04's policy comparison supplies no payment finding. These limits preserve the meaning of each result rather than cancelling the documentary support that was established.

### D.9 Historical and current comparator discipline

The pinned September Atlas is the fixed comparator used in the evaluation, not a claim about publication-time policy. The May comparator supplies specific historical discriminators. For C04, the retained historical locations are:

| Historical Atlas path at `7fa69a61` | Lines | Witness |
|---|---|---|
| `content/A/2/2/3/1/2/document.md` | 10–12 | Creation amount/process deferred. |
| `content/A/2/3/1/2/1/2/5/document.md` | 10–12 | One-time founding fee. |
| `content/A/2/2/6/1/document.md` | 10–12 | 50 bps, USDS and monthly payment policy. |
| `content/A/2/2/6/2/document.md` | 10–19 | Payment-dependent rebate credited next month. |
| `content/A/6/1/1/1/2/3/1/2/1/2/1/1/document.md` | 10–12 | Spark payment process deferred. |

Persistent upkeep and rebate UUIDs bridge renumbering from A.2.2.6 to A.2.2.7. In the pinned text these are respectively `a21616f4-1611-4e0b-87b2-efbdff9f6f28` and `569e1c2b-0e69-43e7-8491-06cc5f7d2988`. Creation-fee witnesses retain UUIDs `708ad6b6-8e4a-46b3-9848-523d00a57420` and `1b1c9cc0-e410-4bb3-aa37-c639ca392dd7` for the cited structures.

This evidence places the specified C04 discrepancy before the June subject pin. It does not backdate every September parameter, establish execution dates or explain author intent. Historical presence evidence for C01 and the narrower role-history observations for C02/C03 retain their own scopes; C04's result is not generalized into one historical verdict on every dimension of all four claims.

### D.10 Binding summary

C01 is ESTABLISHED for documentary presence. C02's exact Guardian/organizational mapping and C03's exact genesis-authority mapping remain NOT ESTABLISHED. C04 is PARTIALLY ESTABLISHED within shared Prime scope, retaining supported rate and entitlement dimensions, material differences in mechanics and unresolved details.

Together these results describe a heterogeneous Atlas relationship. Documentary presence, exact authority mapping and policy-mechanic correspondence require different evidence. The four results do not combine into a global alignment label, implementation verdict or inference about governance intent.

### D.11 Evidence that could change unresolved Atlas conclusions

The frozen reopening conditions are evidence-triggered possibilities, not remediation obligations. For C02, explicit same-scope entity mappings, a dated hierarchy record or an authoritative identity between the relevant Guardian relationship and Executor Accord relationship could change the binding. For C03, a dated authority-layer/phase mapping identifying genesis holders and Core GovOps inclusion or exclusion could resolve applicability; any architecture review would also depend on source availability and separate authorization.

For C04, a dated authoritative exception or supersession establishing the claimed Prime mechanics, or evidence that the same-named fees concern distinct obligations, could change the policy comparison. Payment evidence alone would not resolve that documentary mismatch. Documented intentional divergence is a frozen discriminator, not an intent finding made here. C01's witnesses could be reconsidered if a source/pin correction invalidated them or the intended proposition required a formal enum or exhaustive live inventory instead of the tested documentary categories.

These conditions preserve the original questions. They neither introduce new governance tests nor require every unresolved issue to be resolved before Report v1 can close.

### Evidence notes

- **D-1.** `reports/2026-09-18-f438819/L2-atlas-binding-C01-C04.md`
- **D-2.** `reports/2026-09-18-f438819/findings/L2-01-C01-atlas-operational-data.md`
- **D-3.** `reports/2026-09-18-f438819/findings/L2-02-C02-ozone-guardian.md`
- **D-4.** `reports/2026-09-18-f438819/findings/L2-03-C03-p1-authority.md`
- **D-5.** `reports/2026-09-18-f438819/findings/L2-04-C04-entity-fees.md`
- **D-6.** `synthesis/master-evidence-matrix.md`
- **D-7.** `synthesis/report-sections/04-relationship-to-sky-atlas.md`
- **D-8.** `synthesis/appendices/A-baseline-manifest.md`
- **D-9.** `synthesis/appendices/B-evaluation-methodology.md`
- **D-10.** `pins/baseline.md`

## Appendix E — STL / Provenance Ledger

### E.1 Purpose and reading rule

This appendix traces how the evaluation moved from STL technical/reference evidence toward implementation-source identity for C05 and C06. It distinguishes five objects: coverage of a claimed implementation, useful discovery leads, source-family attribution, an owner-qualified implementation repository, and exact revision/file binding. A positive result for one object does not automatically establish the next.

STL supplied useful evidence without serving as universal implementation provenance. For C05, local registry and documentary connections led to separately resolved implementation source. For C06, the evaluated evidence did not identify a sufficiently specific legacy source. This difference concerns evidence specificity, not implementation quality, credibility or existence.

The historical L3A–L3D results remain unchanged. This ledger does not itself establish deployment, active use, runtime behavior, security or continuity. Appendix F carries the subsequent C05 static and Mainnet case; Appendix G is allocated the full unresolved C06 trail and reopening conditions. Appendix C preserves the broader phase chronology.

For retained-file references, **R/** means `reports/2026-09-18-f438819/`. References prefixed Laniakea, Atlas or STL identify paths in the corresponding frozen source repository. Leads are identified by their documentary role; they are not upgraded because later evidence succeeded. Exact source paths below come from the retained records, not a new retrieval.

### E.2 Provenance evidence layers

| Layer | Question | C05 historical result | C06 historical result | What would permit progression |
|---|---|---|---|---|
| L3A: STL coverage/source binding | Does pinned STL identify the claimed executable implementation? | NOT ESTABLISHED; NO MATCHED STL COVERAGE ESTABLISHED; chain HOLD. | Same main result and coverage status; chain HOLD. | Claim-specific implementation provenance sufficient for a source-binding test. |
| L3B: local implementation provenance | Do local documentary, UUID and package records identify a source or concrete retrieval lead? | Complete source NOT ESTABLISHED; concrete external leads justified separately authorized narrow retrieval. | Legacy identity and legacy-to-PAS bridge NOT ESTABLISHED; retrieval target NONE; access-specific BLOCKED where applicable. | For C05, inspect exact evidenced leads; for C06, qualifying legacy source attribution or an explicit bridge. |
| L3C: C05 external provenance | Do those leads resolve the implementation source? | NOT ESTABLISHED; specific filename/revision/version attributions recovered; chain HOLD. | No equivalent phase opened. | Owner-qualified source-location resolution under separate authorization. |
| L3D: C05 repository resolution | Can the attributed source files and revisions be resolved? | PASS for exact source identity; static review eligible; chain HOLD. | No equivalent phase opened. | Inspect the resolved C05 sources before considering chain eligibility. C06's missing prerequisite remains unchanged. |

An unopened C06 phase is not a negative test of its implementation. Similarly, a chain HOLD records an unmet prerequisite, not a failed deployment. L3D source identity permitted static review; it did not by itself establish the semantics or deployment later examined in L3E/L3F.

### E.3 Initial STL coverage: C05 and C06

The exact L3A result for both claims is **NO MATCHED STL COVERAGE ESTABLISHED**. Both main grades were NOT ESTABLISHED. Stage 2 was not opened, all C05-A–F and C06-A–F subresults remained unestablished, and both chain gates remained HOLD. These were missing implementation matches within the evaluated STL evidence, not twelve independent implementation failures.

The coverage review used pinned STL revision `37e56db072f9f246fc2f77ed3036e4a8e732aaf7` and retained pre-subject witness `27aa90f7cf888298eef92a41be00f3a30fd1a0cf`, dated June 4, 2026 at 07:27:00Z. The earlier witness predates the subject's 07:38:57Z timestamp. It dates the inspected registry/reference material, not the underlying contracts.

| Claim | Useful or superficially related STL material | Why it did not establish implementation coverage |
|---|---|---|
| C05 | Typed ALM prime/network/address records, JSON registry data, loaders and allocation tracking. | Data and observer relationships do not implement ALMProxy custody/doCall, Controller actions or RateLimits semantics. They are not partial executable PAU coverage. |
| C06 | PoolConfigurator address-discovery/indexer references; generic configuration; a different vault timelock; HTTP request limits. | No claim-specific bridge identifies legacy Configurator, BEAMTimeLock, BEAMState and bounded cBEAM operations as that implementation. |

The C05 record is in STL `stl-verify/python/app/risk_engine/_vendored_synome/spec/entities/alm_proxies.py:28–46`. Related JSON appears in `stl-verify/contracts/axis-synome/axis_synome_entities.json:1005–1027`; its consumers include `stl-verify/internal/pkg/axis_synome_contract/loader.go:16–54,71–75,92–110` and `stl-verify/internal/services/allocation_tracker/config.go:53–94`. Those are explicit data/consumer connections, not contract-source binding.

C06 discriminators include STL `docs/aave_v3_spec.md:735–755`, `docs/sparklend_spec.md:895–914`, `docs/morpho_spec.md:715–737` and `stl-verify/internal/pkg/httpclient/client.go:51–75,108–117`. Similar words describe different objects: a lending-pool configurator, a vault timelock and an HTTP limiter do not identify the claimed stack.

The retained search also found no Solidity/Vyper files, Foundry/Hardhat markers or gitlinks in the inspected pinned tree. That observation was not treated as exhaustive semantic proof or proof of source nonexistence elsewhere. The coverage result means neither that STL was irrelevant or deficient nor that the Laniakea claims were false.

### E.4 STL as a discovery and reference layer

STL's useful contribution was to make some documentary connections inspectable. A typed record named a Prime and network, supplied an address and attached a source UUID. A loader and allocation configuration showed how registry data was consumed. Package metadata named a registry dependency and export provenance. Together these supported questions about where a record came from and which documentary family it concerned.

| Evidence surface | Discovery value | Identity ceiling |
|---|---|---|
| ALM registry record | Component, network and address context. | Not a verified deployment or executable contract source. |
| `source_uuid` | A precise documentary destination to compare with Atlas. | Resolves a record, not automatically a repository or source revision. |
| Package/export metadata | Registry origin and versioned retrieval candidates. | Data revisions are not Solidity revisions. |
| PSM3 reference material | Concrete Spark registry, integration and audit pointers. | Adjacent implementation scope is not whole-PAU identity. |
| Tracking/indexing consumers | Evidence of reference/observation functionality in STL. | Observer code does not implement the observed contract family. |

Chronology prevents treating the September layout as if it existed unchanged in June. The pre-subject JSON and hard-coded tracking defaults already referenced ALM material, while the vendored Python registry arrived in August. September lists with explicit ALM/SubProxy roles differed from June single-object records and hard-coded configuration. These are changes to registry and consumer surfaces; they do not establish PAU contract introduction or modification dates.

This is a description of how the evaluated STL material functioned in these two inquiries. It imposes no universal requirement that STL contain every implementation, and it does not discount registry or observer evidence because it answers a different question from executable-source provenance.

### E.5 C05 local provenance path

L3B retained **NOT ESTABLISHED** for C05's complete implementation source. Its contribution was a more specific provenance chain and exact external leads, sufficient to justify a narrowly scoped retrieval phase under separate authorization.

| Local connection | Frozen witness | Established at this stage | Missing connection |
|---|---|---|---|
| Laniakea → Spark ALM family | Subject `summaries/smart-contracts.md:3,28`; `smart-contracts/architecture-overview.md:5,19–24`. | Explicit existing Spark ALM family attribution and component description. | No owner-qualified repository or implementation path in those passages. |
| Atlas → related components | Atlas `content/A.6.1.1.1 - Spark.md:1793–1823,2594`. | Grouped component records and Controller/ALMProxy/RateLimits relationship. | Documentary relationship does not identify code source. |
| STL → Atlas ALMProxy | STL `alm_proxies.py:37–46`, full path in E.3; Atlas Spark:1817–1819. | Source UUID `a29a6751-4809-446c-a659-0dd93ca40379` resolves to the same documentary record; parent UUID `7db865de-8519-464b-8752-f39ecaf54fd2` resolves at line 1793. | A documentary UUID is not implementation provenance. |
| STL → registry package | Pre-subject STL `stl-verify/python/uv.lock:97–106`. | Exact `axis-synome==0.1.dev188` archive/wheel pointers and recorded hashes. | Registry-package identity does not bind the PAU contracts. |
| STL → Spark reference sources | STL `docs/psm3_spec.md:11,17–22,116–122`. | Concrete address-registry, PSM source and audit pointers. | Their stated integration scope does not establish the complete PAU source. |

The subject's named family was stronger than arbitrary name similarity. The UUID resolution was stronger than finding a nearby address. Nevertheless, the missing connection remained from this documentary/registry family to inspectable implementation source for the combined legacy stack. L3B's descriptive lead states included NAME-ONLY LEAD, UUID-BOUND POINTER and EXPLICIT EXTERNAL POINTER; they were not substitutes for finding grades.

Registry metadata required its own distinctions. The September export named version `0.2.0.dev202607240944` and upstream commit `d136e461f177cad555e0c5fc3f497fc37df9dc5f`. The pre-subject export named `0.1.1.dev152+g1931035e9.d19800101` and `1931035e91cf9fa527292e45f048df533b840013`. The latter was not silently equated with the `0.1.dev188` dependency. None of these data identifiers was promoted to a contract revision.

The retained chronology placed the subject's Spark family description in January and the Atlas relationship/UUID record in May. STL's pre-subject dependency supplied an exact archive lead. Later June PSM pointers and August vendoring supplied additional documentary provenance without backdating implementation. The PSM reference also demonstrated why chain and component identity must accompany address text: its Base PSM3 context was not the Ethereum Mainnet ALMProxy context.

C05 was therefore eligible for **EXTERNAL PROVENANCE RETRIEVAL** of exact evidenced sources and qualifying explicit onward links, not broad repository guessing or chain testing. Concrete leads did not convert L3B to PASS. Complete source identity, implementation chronology and live/deployed status remained NOT ESTABLISHED; chain HOLD remained in force.

### E.6 C06 local provenance path

The C06 proposition concerned legacy Configurator, BEAMTimeLock, BEAMState and bounded cBEAM operations. Subject `summaries/smart-contracts.md:3,46–60` asserted legacy-live behavior, while `smart-contracts/configurator-unit.md` presented business requirements and interface sketches. Its line 164 named OpenZeppelin TimelockController with pause capability. That was an explicit component-family lead, not an exact version or complete implementation source.

Atlas `content/A.2 - The-Support-Scope.md:3401–3428` supplied more distinctive related material: PAS Configurator, BeamState, Timelock and PASMom in Diamond PAU scope. Init defaults and bounded adjustments appeared at lines 3545–3551 and 3623–3629. These were preserved as documentary leads because their roles resembled the question, without treating resemblance as identity.

| C06 evidence object | Retained result |
|---|---|
| Legacy implementation identity | NOT ESTABLISHED. |
| Explicit legacy → PAS source/implementation bridge | NOT ESTABLISHED. |
| Concrete external legacy-source retrieval target | NONE. |
| Architecture-source access | BLOCKED where access applies; not the main claim grade. |
| Chain prerequisite | HOLD. |
| L3B main result | NOT ESTABLISHED; not PARKED. |

The PAS records included names, UUIDs and addresses, but no exact legacy repository, package or verified-source artifact. The Configurator/BeamState documentary entries were added in August, followed by fuller PAS address and role descriptions later that month. Those dates identify documentary additions, not when any implementation first existed. No later address was used to establish June legacy-source identity.

Neither the OpenZeppelin name nor requirements signatures justified selecting a convenient repository. No explicit required-source pointer identified inaccessible architecture as the missing implementation, so access BLOCKED did not become a BLOCKED main grade. The evaluated evidence established neither legacy/PAS equivalence nor non-equivalence, migration, renaming or successor identity.

No corresponding L3C/L3D source-retrieval or resolution phase was opened for C06. Static and chain substitution stopped at the unmet identity prerequisite. This preserves uncertainty rather than implying no implementation existed. Later PARKED is a synthesis disposition pending qualifying provenance; Appendix G carries the detailed unresolved trail and frozen reopening conditions.

### E.7 C05 external provenance: attribution became specific

L3C inspected the separately authorized exact external leads. The retained axis-synome archive matched its recorded hash and supplied specification-package metadata. Spark PSM and audit materials remained adjacent integration evidence. The important additional attribution came from Spark address-registry source at revision `a274288bd344de3c1c8e6d35b95cae094c9b4435`.

| Registry source location | Exact attribution text |
|---|---|
| `src/Ethereum.sol:35` | `spark-alm-controller/MainnetController.sol@984ec54 (v1.10.0)` |
| `src/Base.sol:26` | `spark-alm-controller/ForeignController.sol@7be9593 (v1.8.0)` |
| `src/Ethereum.sol:36`; `src/Base.sol:27` | `spark-alm-controller/ALMProxy.sol@6058f68 (v1.0.0)` |
| `src/Ethereum.sol:38`; `src/Base.sol:29` | `spark-alm-controller/RateLimits.sol@6058f68 (v1.0.0)` |

The relevant retained witnesses are R/`L3C-retrieved/06-ethereum-source.txt:35–38` and R/`L3C-retrieved/07-base-source.txt:26–29`. The annotations identify a common source label, filenames, short revisions and versions. They are stronger than contract-name similarity. They remain source-verified facts about attribution text and documentary claims about source/address/version correspondence.

At phase end, C05 remained **NOT ESTABLISHED** and chain HOLD. The inspected material did not supply an owner-qualified ALM implementation URL or qualifying source artifact; no onward implementation link was followed and no owner prefix was inferred. Address-registry authority was not treated as canonical code authority.

All eight implementation-source-binding subresults remained NOT ESTABLISHED. The first four had more specific attribution leads, but inspected behavior, combined implementation relationships and dated ALM source history were still missing. Neither the older package hash nor PSM audit chronology dated the ALM source. L3C established a precise source-location question for subsequent authorization; it did not establish repository identity, exact source/runtime correspondence, deployment or chain state.

### E.8 C05 repository resolution

L3D recorded **PASS for exact source identity** and resolved the repository as `sparkdotfi/spark-alm-controller`. Its retained exact-name discovery supplied the owner-qualified location. The documented redirect from an older marsfoundation release location and the identification of a differently named fork helped discriminate repository identity; neither was used to invent an alternative implementation lineage.

| Component | Original repository path | Full revision | Exact tag | Retained file under R/ |
|---|---|---|---|---|
| MainnetController | `src/MainnetController.sol` | `984ec546fb2c98ed729ae91d2d73e97dedbf111f` | v1.10.0 | `L3D-retrieved/MainnetController-984ec54.sol` |
| ForeignController | `src/ForeignController.sol` | `7be959378fe48117f7a06796f94e240345428982` | v1.8.0 | `L3D-retrieved/ForeignController-7be9593.sol` |
| ALMProxy | `src/ALMProxy.sol` | `6058f68f79520eb06ea8eded146da13039c47525` | v1.0.0 | `L3D-retrieved/ALMProxy-6058f68.sol` |
| RateLimits | `src/RateLimits.sol` | `6058f68f79520eb06ea8eded146da13039c47525` | v1.0.0 | `L3D-retrieved/RateLimits-6058f68.sol` |

Retained commit and tag responses resolved the full revisions and exact tag bindings, and the four source files were retrieved at those revisions. Their source witness dates are February 16, 2026; November 7, 2025; and October 22, 2024 respectively. These are mixed historical snapshots, not one atomic release, deployment dates, first-introduction dates or a claim to have identified the latest pre-June revision.

The source-identity tests passed within their stated scope. Distinctive source surfaces supported the family identification, but complete static semantics and mixed-version integration compatibility required separate treatment. L3D made static review eligible; chain HOLD and live/deployed NOT ESTABLISHED remained. Resolved filenames and tags did not prove exact bytecode at an address or establish active use. Appendix F begins with these resolved objects and explains the subsequent source and Mainnet tests.

### E.9 Why C05 progressed and C06 did not

| Question | C05 | C06 |
|---|---|---|
| Matched STL implementation? | Not established in L3A. | Not established in L3A. |
| Concrete external lead? | Exact package and Spark registry/reference pointers at L3B. | No concrete legacy implementation retrieval target. |
| Claim-specific source attribution? | Registry filenames/revisions/versions recovered in L3C. | Library-family and later PAS leads lacked a legacy source bridge. |
| Repository identity? | Exact owner/repository/files/revisions resolved in L3D. | NOT ESTABLISHED. |
| Static review eligible? | Yes after L3D, under separate authorization. | No sufficiently specific source for that test. |
| Chain verification eligible? | Not at L3D; became eligible after L3E static binding. | HOLD. |
| Historical results? | L3A/B/C NOT ESTABLISHED; L3D source-identity PASS. | L3A/B main results NOT ESTABLISHED. |
| Final synthesis? | ESTABLISHED for the later scoped accumulated conclusion; CLOSED. | PARKED pending qualifying provenance. |

The difference is not a ranking of the two implementations. C05's evidence identified the object to inspect; C06's evidence did not. A later related contract or familiar library name could not fill that missing connection without changing the proposition being evaluated. Subsequent C05 static/chain work therefore answered questions that were not opened for C06.

### E.10 Historical provenance results and later synthesis

C05's initial **NO MATCHED STL COVERAGE ESTABLISHED** remains the frozen L3A result. L3B and L3C remain NOT ESTABLISHED for complete implementation provenance at their respective stops. L3D remains PASS for exact source identity. Later L3E/L3F evidence supports C05's final scoped ESTABLISHED conclusion without retroactively changing those earlier outcomes.

The matrix separately characterizes the useful documentary leads accumulated in L3B/L3C; that does not turn their historical main grades into PASS. Source identification, behavior and deployed state answer different questions. The positive result did not come from reclassifying STL registry material as executable PAU coverage.

C06 likewise retains its unmatched L3A coverage and L3B identity NOT ESTABLISHED. Architecture BLOCKED is access-specific; HOLD is a chain prerequisite gate. Final PARKED is synthesis-only, not a historical grade, falsehood finding or permanent closure. No missing match is converted into evidence that the source does not exist.

### E.11 Provenance threshold used by the evaluation

The practical threshold required a connection strong enough that the next test would inspect the intended implementation. C05 crossed that threshold through explicit family context, documentary UUID resolution, concrete retrieval pointers, specific source attributions and finally resolved repository/files/revisions. None of those stages alone was silently treated as all the others.

C06 illustrates the same threshold from the stopping side. Similar names, interface sketches, later PAS vocabulary and an adjacent library family were insufficient without a claim-specific identity bridge. The evaluator did not substitute a later implementation for the legacy object or infer a migration. These applied distinctions, rather than a universal rule about repository contents, explain progression and stopping. Appendix B provides the general methodology; this ledger preserves its operation in the retained cases.

### Evidence notes

- **E-1.** `reports/2026-09-18-f438819/L3A-STL-binding-C05-C06.md`
- **E-2.** `reports/2026-09-18-f438819/L3B-implementation-provenance-C05-C06.md`
- **E-3.** `reports/2026-09-18-f438819/L3C-C05-external-provenance.md`
- **E-4.** `reports/2026-09-18-f438819/L3D-C05-repository-resolution.md`
- **E-5.** `reports/2026-09-18-f438819/findings/L3A-01-C05-legacy-pau-stl-binding.md`
- **E-6.** `reports/2026-09-18-f438819/findings/L3A-02-C06-legacy-configurator-stl-binding.md`
- **E-7.** `reports/2026-09-18-f438819/findings/L3B-01-C05-legacy-pau-provenance.md`
- **E-8.** `reports/2026-09-18-f438819/findings/L3B-02-C06-legacy-configurator-provenance.md`
- **E-9.** `reports/2026-09-18-f438819/findings/L3C-01-C05-external-implementation-provenance.md`
- **E-10.** `reports/2026-09-18-f438819/findings/L3D-01-C05-repository-identity.md`
- **E-11.** `reports/2026-09-18-f438819/L3C-retrieved/06-ethereum-source.txt`
- **E-12.** `reports/2026-09-18-f438819/L3C-retrieved/07-base-source.txt`
- **E-13.** `reports/2026-09-18-f438819/leads.md`
- **E-14.** `synthesis/master-evidence-matrix.md`
- **E-15.** `synthesis/report-sections/05-relationship-to-stl.md`
- **E-16.** `synthesis/report-sections/07-unresolved-provenance-c06.md`
- **E-17.** `synthesis/appendices/B-evaluation-methodology.md`
- **E-18.** `synthesis/appendices/C-l0-l3f-phase-ledger.md`

## Appendix F — C05 Case Study

### F.1 Purpose and scoped conclusion

Laniakea's scoped legacy Mainnet PAU description is materially grounded in implemented and historically deployed Sky/Spark infrastructure.

This appendix provides the detailed source and Mainnet traceability supporting that bounded conclusion. It does not certify the full PAU architecture, target architecture, all Laniakea implementation, continuous operation, exact source/runtime bytecode equivalence or comprehensive security/integration completeness. Specific attribution of the observed RateLimits events to the tested MainnetController also remains NOT ESTABLISHED. The definitive five principal limits appear in F.19.

C05 is **CLOSED** for its scoped Report v1 conclusion. Exact bytecode reproduction remains **OPTIONAL ASSURANCE**, not a closure or publication requirement. The positive result rests on converging documentary, source and chain evidence with different functions; it does not require treating one evidence layer as proof of everything the others leave unresolved.

For compact citations, **R/** means `reports/2026-09-18-f438819/`; retained filenames below are relative to that directory unless stated otherwise. Source line references reproduce the frozen findings. Technical values are transcribed from retained records, not obtained through new queries or recomputed hashes.

### F.2 C05 proposition and evidence question

The L1 proposition is: “PAU pattern is live (legacy); Controller, ALMProxy and RateLimits are its components.” The source is subject `summaries/smart-contracts.md:3,28` at revision `f4388196198df3435b38357bc7f1fccc1c5a1317`. Supporting `smart-contracts/architecture-overview.md:5,21–23` connects the model to existing Spark ALM contracts. The descriptions identify MainnetController/ForeignController, proxy custody/doCall and RateLimits maxAmount/slope replenishment.

The evaluation asked whether inspectable implementation source materially corresponded to that legacy description, whether matching Mainnet infrastructure was deployed at the tested observations, whether its wiring and representative configuration supported the scoped description, and whether bounded relevant component use was evidenced. The target-extension context remained distinct.

C45's broader deployment assertion across every Generator, Prime, Halo and Foreign layer was not incorporated into C05. ForeignController was inspected as a source-family variant; it was not presumed to be a second Controller in the tested Mainnet stack or proof of a foreign-network deployment.

### F.3 Resolved implementation provenance

The resolved implementation repository is `sparkdotfi/spark-alm-controller`. Appendix E records the discovery path; this case starts from the exact objects identified by L3D. Initial STL coverage remained unmatched, and historical L3B/L3C results remained NOT ESTABLISHED despite the later resolution.

| Component / original repository path | Full source revision | Tag | Source witness date | Retained file under R/ |
|---|---|---|---|---|
| MainnetController — `src/MainnetController.sol` | `984ec546fb2c98ed729ae91d2d73e97dedbf111f` | v1.10.0 | February 16, 2026 | `L3D-retrieved/MainnetController-984ec54.sol` |
| ForeignController — `src/ForeignController.sol` | `7be959378fe48117f7a06796f94e240345428982` | v1.8.0 | November 7, 2025 | `L3D-retrieved/ForeignController-7be9593.sol` |
| ALMProxy — `src/ALMProxy.sol` | `6058f68f79520eb06ea8eded146da13039c47525` | v1.0.0 | October 22, 2024 | `L3D-retrieved/ALMProxy-6058f68.sol` |
| RateLimits — `src/RateLimits.sol` | `6058f68f79520eb06ea8eded146da13039c47525` | v1.0.0 | October 22, 2024 | `L3D-retrieved/RateLimits-6058f68.sol` |

These are three historical repository snapshots, not one atomic release. Dates establish source witnesses, not deployment, first introduction or activation. Exact tag binding identifies repository versions, not versions independently reproduced at deployed addresses.

L3E used IALMProxy and IRateLimits at each parent revision, RateLimitHelpers at each Controller revision, and the necessary retained OpenZeppelin witnesses at `dbb6104ce834628e473d2173bbc9d47f81a9eec3`. The three parent gitlinks identify that dependency revision. Relevant interface declarations matched across parents; an import-prefix difference did not change those declarations. This supported the inspected interface relationships without establishing exhaustive mixed-version integration compatibility or dependency closure.

### F.4 Static implementation architecture

The inspected Controller coordinates two separate relationships: operational capacity through RateLimits and execution through ALMProxy. MainnetController constructor references are at retained source lines 212–224, while actual mint/burn paths at 364–396 and helpers at 1206–1222 establish behavior beyond naming or constructor assignment. ForeignController provides a related but distinct operation set at its own revision.

Both Controllers directly inherit ReentrancyGuard and AccessControlEnumerable; the inspected declarations do not inherit a BaseController. Operational actions include RELAYER checks. The retained access-control dependency checks caller membership; merely naming a contract “Controller” grants no permission. The review records this implementation structure without claiming security efficacy or identifying deployed role holders from source.

ALMProxy's `doCall` requires CONTROLLER membership and forwards execution through the exact Address dependency. Ordinary `doCall` sends zero ETH value. Separate `doCallWithValue` and delegate-call primitives exist, together with a payable receive function; they are not conflated with ordinary call behavior. Retained ALMProxy lines 31–53 and `L3E-retrieved/OZ-Address.sol:70–89` support these distinctions. Call failure handling and returned data are part of the inspected forwarding behavior. The source supports execution/custody infrastructure, not any observed balance or custody amount.

RateLimits stores a `bytes32`-keyed record containing four `uint256` fields: `maxAmount`, `slope`, `lastAmount` and `lastUpdated`. The field order is retained in `L3E-retrieved/IRateLimits-6058f68.sol:22–27`; the mapping and setters occur in `L3D-retrieved/RateLimits-6058f68.sol:14–16,30–58`.

For ordinary finite configured state on successful evaluation, available capacity follows `min(maxAmount, lastAmount + slope × elapsed seconds)`. It is calculated when read or used, so no scheduled writer is required for each increment. Zero slope produces no time-based replenishment. An explicit `type(uint256).max` sentinel selects unlimited behavior; zero maximum and administrative replacement have separate effects. Finite and unlimited configurations can coexist across keys. This is source correspondence, not an arithmetic-safety or economic audit.

Runtime decreases require sufficient computed capacity and update remaining capacity/time; increases restore capacity up to the cap. These CONTROLLER-gated operations differ from DEFAULT_ADMIN_ROLE-gated parameter configuration. The inspected Controllers demonstrated runtime use, not direct calls to set maximum/slope. Mainnet mint consumes before proxy execution, while burn restores capacity. Other paths differ: Foreign `withdrawPSM` accounts after the proxy call, and Mainnet `wrapAllProxyETH` has no rate-limit call in its body. The description therefore does not imply every method consumes a finite budget before action.

The proxy does not itself call RateLimits. Coordinated Controller paths, matching interfaces and inspected dependency behavior support the combined pattern. They do not turn the source diagram into an observed deployment or prove every integration's external behavior.

### F.5 What static review established — and did not establish

| Static question | Result | Boundary |
|---|---|---|
| Component family and relationships | Mainnet/Foreign Controllers use proxy execution and keyed limits. | Alternative source variants and mixed revisions, not one deployed atomic release. |
| Proxy execution/custody infrastructure | Role-gated call, value-call and delegate-call surfaces; payable receive. | No deployed grant, actual balance or custody amount established by source alone. |
| RateLimits semantics | Four-field state, finite capped lazy replenishment, consumption/restoration and configuration separation. | Unlimited, zero-slope, reset and action-order qualifications remain. |
| Functions, events and interfaces | Retained declarations support the selected getters, tuple decoding and event interpretation. | Matching responses are not exact deployed-bytecode proof. |
| Source chronology | Inspected behavior present with qualification in exact pre-June revisions. | Not first introduction, deployment or activation chronology. |
| Deployment and live use | NOT ESTABLISHED within L3E. | Required the separate L3F chain observations. |
| Caller attribution, continuity and exact bytecode identity | Not established by static review. | Cannot be supplied by reading a plausible call path alone. |
| Comprehensive security/integration assurance | Outside the scoped review. | Selected source paths are not an exhaustive audit. |

L3E's historical main result remains PASS for static implementation binding, with nine scoped supporting subresults. Its end-state CHAIN GATE ELIGIBLE meant that source identity and semantics justified separately authorized chain testing. It did not mean deployed, and later L3F evidence does not retroactively change L3E's phase-local live/deployed result.

### F.6 Tested Ethereum Mainnet components

The frozen registry witness `L3C-retrieved/06-ethereum-source.txt:35–38`, at registry revision `a274288bd344de3c1c8e6d35b95cae094c9b4435`, supplies the documentary addresses. `L3F-evidence/address-provenance.tsv` recorded candidates before component requests. Source-version annotations remain documentary claims of correspondence, distinct from exact bytecode equivalence.

| Component | Address | Source witness | Mainnet role |
|---|---|---|---|
| MainnetController | `0x5c46Fc65855c0C7465a1EA85EEA0B24B601502D3` | Registry attribution to MainnetController `984ec54`; retained source identified in F.3. | Tested coordinating Controller, referenced below as R. |
| ALMProxy | `0x1601843c5E9bC251A3272907010AFa41Fa18347E` | Registry attribution to ALMProxy `6058f68`. | Tested execution/custody component, P. |
| RateLimits | `0x7A5FD5cf045e010e62147F065cEAe59e5344b188` | Registry attribution to RateLimits `6058f68`. | Tested keyed-capacity component, L. |

These three addresses define the tested stack, not a deployment inventory. An alternative Atlas Controller is addressed separately in F.14. The September registry was not assumed to describe June state: historical chain calls independently tested the candidates and their component relationships.

### F.7 Fixed Mainnet observations

Both observations concern Ethereum Mainnet, chain ID 1.

| Observation | Block | Retained UTC timestamp | Block hash |
|---|---:|---|---|
| Historical, H | 25,242,585 | `2026-06-04T07:38:47.000Z` | `0x3df6a06ce123333e4d84c014cecacd6034ec7bd8e82b6bc24be516beaee368fc` |
| Later retained, C | 26,007,670 | `2026-09-18T23:26:35.000Z` | `0x815c03207bc7c58958ae0cef5af8d9c10a9a334dd3e58ff8c1b9129a773dee6b` |

The subject timestamp was June 4 at 07:38:57Z. Historical block H preceded it; successor block 25,242,586 at 07:38:59Z followed it. The successor supplies timestamp-bracketing metadata, not a third full state observation. The retained search selected the greatest eligible historical block, and final hash checks matched H and C.

“Current” in L3F refers only to fixed C, captured once during evaluation. Substantive code/state calls used explicit H or C; event queries used bounded endpoints. No publication-time state or continuous monitoring follows. These are analyst-collected RPC observations, distinct from the earlier validator-run L0 deterministic evidence. Block pins and hash rechecks are not cryptographic state proofs or independent-provider replication.

### F.8 Code presence and runtime identity across observations

The retained code tables report nonempty code at each tested address at H and C. Runtime lengths and per-address keccak256 values below are copied from `L3F-evidence/code-historical.tsv` and `code-current.tsv`; they have not been recomputed for this appendix.

| Component | Bytes at H and C | Runtime keccak256 at H and C |
|---|---:|---|
| R: tested MainnetController | 23,335 | `0x73d5237e373a786f37a7f244672494e16e7ec1827c478d5d62aa8f4ff9513a8f` |
| P: ALMProxy | 2,373 | `0xb1265d0c701f7f2892e7cf370fadbdc3e48cd4585acf8b89a2f9fe69f38e6331` |
| L: RateLimits | 2,864 | `0x8ec294c547963e4aa59bd49f11f5e5b4359d2285a82268b832b99a55edeeaf0a` |

The historical result CODE UNCHANGED BETWEEN BASELINES compares each address with itself at two blocks. It does not prove continuous operation, uninterrupted configuration or no intermediate changes. It also does not identify a source build: runtime hashes are observed code identifiers, not independently verified source-version identifiers. Retained runtime hex bodies support code traceability within the evidence-retention limits described below.

### F.9 Deployed component wiring

At both H and C, source-derived getters on R returned the expected components:

| Getter on tested Controller R | H | C |
|---|---|---|
| `proxy()(address)` | P — MATCH | P — MATCH |
| `rateLimits()(address)` | L — MATCH | L — MATCH |

The exact returned addresses are those in F.6. The records are `L3F-evidence/wiring-historical.tsv` and `wiring-current.tsv`; source declarations are MainnetController lines 175 and 180. Getter matches establish observed references and must be combined with grants and configuration rather than treated as sufficient operational evidence by themselves.

Wiring at two blocks does not identify first wiring, uninterrupted wiring, absence of intermediate changes or governance approval history. It supports the scoped deployed-state relationship at the tested observations. The alternative Controller demonstrates why matching getters alone were insufficient: it returned the same references but lacked the required component grants.

### F.10 Deployed roles and grants

Both P and L returned CONTROLLER identifier `0x70546d1c92f8c2132ae23a23f5177aa8526356051c7510df99f50e012d221529`. At H and C, `hasRole(bytes32,address)(bool)` for R returned true on both components.

| Fixed-state check | H | C | Meaning |
|---|---|---|---|
| P grants CONTROLLER to R | true | true | Tested Controller authorized on the proxy. |
| L grants CONTROLLER to R | true | true | Tested Controller authorized on RateLimits. |
| R RELAYER member count | 2 | 2 | Relevant operational role set populated. |
| R FREEZER member count | 1 | 1 | Relevant operational role set populated. |

The role getters returned RELAYER `0xab4f864e5201b0fde9b5ee3e4cf96384802b0ffdfcf7f9de4699ce21a30afc4f` and FREEZER `0x0ac42a08299cbc4428ec38ad4a8e7d7440779fbbb20ea90bd10c094a406cfa6f`. Source-derived membership/count interfaces and retained role tables support these observations. No member identities or unrelated governance/admin role inventory was established.

Counts show nonempty role sets, not correct organizational ownership, key control or uninterrupted membership. Equal counts at H and C do not prove the same members throughout the interval. The observed grants establish fixed-state permissions, not which permitted caller produced a particular consumption event.

### F.11 Representative finite RateLimits configuration

The selected source-defined key was `LIMIT_USDS_MINT`, declared in retained MainnetController line 166. Both Controller candidates returned `0xcb0537d5e5dba65a8edbac12555995860e5b8e1b70996011edb1ca8173e56d3c` at both snapshots. The key-getter records and `getRateLimitData` tuple supplied one representative configuration test.

| Raw RateLimitData field | H | C |
|---|---:|---:|
| maxAmount | 500000000000000000000000000 | 1000000000000000000000000000 |
| slope | 5787037037037037037037 | 11574074074074074074074 |
| lastAmount | 490002570395622335083950576 | 994845129254454894939957450 |
| lastUpdated | 1780558463 | 1789773539 |
| Retained classification | CONFIGURED FINITE | CONFIGURED FINITE |

These exact raw integers come from `L3F-evidence/ratelimits-historical.tsv` and `ratelimits-current.tsv`. `lastUpdated` is Unix seconds; `lastAmount` is stored remaining capacity at that time. It is neither a newly calculated baseline-time capacity nor a token balance. No decimal-unit conversion or economic adequacy judgment is supplied here.

The maximum and slope differ between H and C, while both configurations are finite. Unchanged runtime hashes therefore do not imply immutable parameters. Together with wiring and populated roles, the selected limit supports representative operational configuration beyond code presence alone. It does not inventory every key, show every action is finitely limited or establish readiness of every integration.

### F.12 Bounded RateLimits usage evidence

The retained event query concerned `RateLimitDecreaseTriggered(bytes32,uint256,uint256,uint256)` at L. Two 7,200-block windows ended at the observation baselines:

| Window | Inclusive blocks | Raw returned events | Exact mint-key selected events |
|---|---|---:|---:|
| Historical | 25,235,386–25,242,585 | 390 | 67 |
| Later retained | 26,000,471–26,007,670 | 391 | 122 |

The original query signature omitted the key's indexed declaration, so the returned results included other keys despite the supplied mint-key argument. The frozen chain log records the limitation and correction: exact local `topics[1]` matching isolated the selected key. Raw bodies remain unchanged; other keys were not inventoried or interpreted. The 67/122 counts are filtered selections, not the complete raw response counts.

The retained review found selected rows within their windows, non-removed, with positive decrease amounts and event values satisfying old capacity minus decrease equals new capacity. That is event-data consistency, not a security or economic audit. The selected events record runtime consumption under the reviewed interface, not administrative parameter-setting events.

These are **RateLimits component consumption events**, not Controller call counts. The event contains no caller identity. Specific attribution to R remains NOT ESTABLISHED, as do corresponding token transfers, a proven USDS mint and complete transaction paths. No transaction trace or receipt expansion was undertaken. The evidence therefore supports component usage independently of configuration while leaving whole-stack invocation unresolved.

The normalized selected rows are in `L3F-evidence/usage-historical.tsv` and `usage-current.tsv`; raw responses are `usage-mint-25242585.json` and `usage-mint-26007670.json`. Their explicit endpoints do not form a deployment-to-present scan, and no deployment/start block was established by these windows.

### F.13 Bounded negative-query evidence

The separate `OTCSwapSent(address,address,address,uint256,uint256)` query on R returned empty arrays in both bounded windows. These results are retained in `L3F-evidence/usage-otc-25242585.json` and `usage-otc-26007670.json`.

Zero matching OTC events does not mean no Controller use. The query was address-specific, event-specific and limited to two windows; it was not a reconstruction of every action or transaction path. It supplies no missing caller attribution for RateLimits events. Its evidentiary role is to preserve the bounded negative result alongside the positive component-consumption evidence, without turning one selected absent event into system-wide inactivity.

### F.14 Alternative Atlas Controller observation

The alternative Atlas Controller was `0x577Fa18a498e1775939b668B0224A5e5a1e56fc3`. It appeared in pre-June Atlas material and remained in the pinned Spark record, alongside the same proxy and RateLimits. Historical and later calls tested it rather than presuming the September registry was correct for June.

| Alternative-Controller check | H and C result |
|---|---|
| Code presence | Present; 17,833 bytes at each point. |
| Runtime keccak256 | `0x99b7b0ac39ba1e1194cd594e7491a7bca978a72dbc0a2ea8ca96d1770de6be5c` at both points. |
| `proxy()` / `rateLimits()` | Match P and L. |
| CONTROLLER grant on P / L | false on both components. |
| RELAYER / FREEZER count calls | NOT ESTABLISHED: calls failed; reasons not retained. |

Failed role-count calls are not zero-member results. The evidence distinguishes this alternative from the tested registry-linked stack: code and matching references did not supply the required grants at either observation. It supports excluding the alternative as the wired instance at those points, not asserting that it never operated.

Migration cause/date, replacement chronology, governance approval and the reason for the documentary discrepancy remain NOT ESTABLISHED. No broader Atlas-binding result is regraded. This observation is a discriminator within the C05 address test, not a new governance conclusion.

### F.15 Source/runtime bytecode boundary

Historical source revisions were identified and inspected; runtime hashes were observed. **Exact source/runtime bytecode equivalence remains NOT ESTABLISHED.** No exact compilation/build reproduction, external verified-source lookup or independently reproduced runtime binding was completed. A registry annotation, matching getter response or unchanged codehash does not by itself establish that a particular source build produced that runtime.

This separates source behavior from exact executable identity while retaining their converging support for the bounded claim. Exact bytecode reproduction is OPTIONAL ASSURANCE. It is not a closure requirement, publication requirement or reason to recast the accepted C05 result as provisional. Reliable future bytecode evidence could affect a specific interpretation under the frozen conditions, but the current absence of reproduction is already an explicit ceiling.

### F.16 Continuity and deployment-history boundary

Two fixed observations and their bounded event windows do not establish continuous June→September operation. First deployment, first activation, complete migration history, migration cause/date and absence of intermediate changes remain NOT ESTABLISHED. Matching runtime hashes at endpoints do not supply the intervening history; matching role counts do not supply continuous membership.

The historical observation establishes tested state present at the June baseline, not the earliest moment it existed. The September observation establishes retained state at another fixed point. Changed representative parameters are observed differences, not a reconstructed sequence of changes. Tested-state grounding remains meaningful without becoming complete historical reconstruction or publication-time monitoring.

### F.17 Scope ceilings beyond C05

All-layer PAU deployment is **OUTSIDE C05**. C45's broader deployment claim remains **NOT ESTABLISHED**. The case does not establish Beacon/facet/full Diamond PAU deployment, every integration, target architecture implementation or complete Laniakea implementation. A reusable pattern and one tested Mainnet instance cannot identify deployment at every Generator, Prime, Halo or Foreign layer.

Comprehensive security/integration certification is **OUTSIDE SCOPE**. Selected access-control bodies, source flows, deployed grants and representative configuration are not a comprehensive code or security audit. Nor does the source inspection of ForeignController supply foreign-chain runtime evidence. These exclusions preserve the scope of the positive conclusion rather than assigning negative grades to untested systems or future designs.

### F.18 C05 evidence ladder

| Evidence level | What was established | What remained unavailable |
|---|---|---|
| Documentary claim | Scoped legacy-live assertion and Spark ALM family context. | Documentary prose alone does not establish source or deployment. |
| Implementation provenance | Exact repository, files, revisions and tags; historical L3D PASS. | Exact deployed source-build identity. |
| Static source behavior | Material correspondence with the scoped legacy pattern; historical L3E PASS. | Static review alone supplied no deployed grants, live use or continuity. |
| Historical deployed state | LEVEL 3 — DEPLOYED, WIRED and CONFIGURED at H; historical L3F scope. | First deployment, activation and full history. |
| Later retained deployed state | Same scoped LEVEL 3 state at C, with representative parameter differences and unchanged per-address code hashes. | Continuous state/operation between H and C or publication-time freshness. |
| Bounded component use | LEVEL 4 limited to RateLimits component consumption in the selected windows. | Specific tested-Controller attribution, corresponding transfers and whole-stack transaction paths. |

Only LEVEL 3 and LEVEL 4 in this table reproduce the L3F formal level terminology. Other rows describe evidence layers, not invented numeric levels. The named Controller/system reaches LEVEL 3; separate component LEVEL 4 does not elevate it to attributed whole-stack use. L3F's main PASS and its supporting subresults remain scoped, not an aggregate project score.

### F.19 Five principal limits

1. Specific attribution of RateLimits events to the tested MainnetController — **NOT ESTABLISHED**.
2. Exact source/runtime bytecode equivalence — **NOT ESTABLISHED**.
3. Continuous June→September operation — **NOT ESTABLISHED**.
4. All-layer PAU deployment — **OUTSIDE C05**.
5. Comprehensive security/integration certification — **OUTSIDE SCOPE**.

### F.20 Scoped closure and optional assurance

C05 remains **CLOSED** for its scoped Report v1 conclusion. Exact bytecode reproduction remains **OPTIONAL ASSURANCE**. Individual provenance, bytecode or transaction-path subquestions may be revisited on qualifying evidence without treating every outstanding limit as a global reopening requirement. The frozen closure record does not require a search backlog or further work before publication.

Reproducibility is bounded by retained material. Runtime hex and log JSON preserve returned bodies; selected baseline, getter, role and tuple records are normalized transcriptions rather than complete raw RPC envelopes. Full initial block responses and per-request wall-clock timestamps were not retained; recorded UTC values are chain timestamps. No cryptographic state proof, independent-provider replication or complete raw-RPC replay is promised. The chain log and evidence README preserve these limitations, while Appendix I is allocated the detailed checksum/retention index.

The case supports a complete scoped conclusion through source correspondence and fixed deployed-state observations, with additional component-use evidence. Its unresolved caller, bytecode, continuity and broader-scope questions remain explicit. None is silently resolved by combining the evidence layers, and none converts the result into assurance about the whole Laniakea system.

### Evidence notes

- **F-1.** `reports/2026-09-18-f438819/L1-claim-map.md`
- **F-2.** `reports/2026-09-18-f438819/L3D-C05-repository-resolution.md`
- **F-3.** `reports/2026-09-18-f438819/L3E-C05-static-binding.md`
- **F-4.** `reports/2026-09-18-f438819/L3F-C05-mainnet-chain-validation.md`
- **F-5.** `reports/2026-09-18-f438819/findings/L3D-01-C05-repository-identity.md`
- **F-6.** `reports/2026-09-18-f438819/findings/L3E-01-C05-static-implementation-binding.md`
- **F-7.** `reports/2026-09-18-f438819/findings/L3F-01-C05-mainnet-chain-binding.md`
- **F-8.** `reports/2026-09-18-f438819/L3F-chain-log.md`
- **F-9.** `reports/2026-09-18-f438819/L3F-evidence/README.md`
- **F-10.** `reports/2026-09-18-f438819/L3F-evidence/address-provenance.tsv`
- **F-11.** `reports/2026-09-18-f438819/L3F-evidence/baseline-historical.txt`
- **F-12.** `reports/2026-09-18-f438819/L3F-evidence/baseline-current.txt`
- **F-13.** `reports/2026-09-18-f438819/L3F-evidence/code-historical.tsv`
- **F-14.** `reports/2026-09-18-f438819/L3F-evidence/code-current.tsv`
- **F-15.** `reports/2026-09-18-f438819/L3F-evidence/wiring-historical.tsv`
- **F-16.** `reports/2026-09-18-f438819/L3F-evidence/wiring-current.tsv`
- **F-17.** `reports/2026-09-18-f438819/L3F-evidence/roles-historical.tsv`
- **F-18.** `reports/2026-09-18-f438819/L3F-evidence/roles-current.tsv`
- **F-19.** `reports/2026-09-18-f438819/L3F-evidence/key-getters-historical.tsv`
- **F-20.** `reports/2026-09-18-f438819/L3F-evidence/key-getters-current.tsv`
- **F-21.** `reports/2026-09-18-f438819/L3F-evidence/ratelimits-historical.tsv`
- **F-22.** `reports/2026-09-18-f438819/L3F-evidence/ratelimits-current.tsv`
- **F-23.** `reports/2026-09-18-f438819/L3F-evidence/usage-historical.tsv`
- **F-24.** `reports/2026-09-18-f438819/L3F-evidence/usage-current.tsv`
- **F-25.** `reports/2026-09-18-f438819/leads.md`
- **F-26.** `synthesis/master-evidence-matrix.md`
- **F-27.** `synthesis/report-sections/06-implementation-and-mainnet-grounding.md`
- **F-28.** `synthesis/appendices/A-baseline-manifest.md`
- **F-29.** `synthesis/appendices/C-l0-l3f-phase-ledger.md`
- **F-30.** `synthesis/appendices/E-stl-provenance-ledger.md`

## Appendix G — C06 Unresolved Provenance

### G.1 Purpose and publication conclusion

The legacy Configurator implementation identity and legacy-to-PAS relationship were not established in this evaluation; C06 is parked pending qualifying new provenance evidence.

**PARKED** does not mean false, nonexistent, undeployed, abandoned, disproven or permanently closed. It is the final synthesis disposition for setting further verification aside pending qualifying evidence, not a historical repository grade. Historical results, the architecture-access limitation and the chain prerequisite gate retain their separate objects and meanings.

This appendix preserves the detailed unresolved provenance case: the legacy proposition, inspected documentary leads, missing source connection, stopping decisions and existing reopening conditions. It does not investigate PAS afresh or turn missing provenance into an implementation judgment. Appendix E supplies the comparative C05/C06 discovery sequence; this appendix explains the C06 stopping point in depth.

References prefixed Laniakea, Atlas or STL are paths in the frozen reference repositories as cited by the retained phase records. **R/** means `reports/2026-09-18-f438819/`. Historical searches and observations below describe completed work in those records. They are not new searches, retrievals, source tests or chain observations undertaken for publication assembly.

### G.2 C06 proposition and evidence requirements

The selected L1 proposition is: “Configurator is live (legacy), with BEAMTimeLock/BEAMState and bounded cBEAM operations.” Its temporal class is CURRENT-IMPLEMENTATION. The Laniakea witness is `summaries/smart-contracts.md:3,46,54` at revision `f4388196198df3435b38357bc7f1fccc1c5a1317`; lines 46–60 provide the surrounding component relationships.

The description combines paused/timelocked additions, init/accordant storage, operational configuration against existing inits, SORL-constrained increases and immediate decreases. These features identify the proposition to be tested. Recording them as a claim does not establish that the described behavior was implemented or operating.

The supporting `smart-contracts/configurator-unit.md` is titled “Business Requirements.” Its definitions and interface sketches help distinguish Configurator, BEAMTimeLock, BEAMState and bounded cBEAM operations from generic configuration systems. Before testing behavior, the evaluation needed an inspectable implementation sufficiently bound to that combined legacy relationship. Source chronology and later source/address binding would then answer additional questions.

The threshold concerned the intended object, not the plausibility of a design with these names. An available contract implementing one familiar operation would not identify the complete claimed stack. Future Council/governance scope and User Story 1 onboarding prerequisites were not promoted to implemented governance or deployment evidence. The later PAS system was not substituted as the object of C06.

### G.3 L3A — STL coverage result

L3A recorded **NO MATCHED STL COVERAGE ESTABLISHED**, with main result **NOT ESTABLISHED** and chain gate **HOLD**. No portion met the Stage 1 requirement for matched Configurator implementation coverage. Stage 2 behavioral comparison did not proceed. This was not partial executable coverage merely because STL contained configuration or timelock vocabulary.

| Inspected STL surface | Retained discriminator | Missing C06 connection |
|---|---|---|
| `docs/aave_v3_spec.md:735–755` | PoolAddressesProvider discovery prose, a `getPoolConfigurator` signature and indexer use. | No legacy Configurator contract body or BEAM bridge. |
| `docs/sparklend_spec.md:895–914` | Similar PoolConfigurator address-discovery context for SparkLend. | No binding to BEAMTimeLock, BEAMState or cBEAM operations. |
| `docs/morpho_spec.md:715–737` | Vault interface, queues and cap changes through a timelock. | Not the specified BEAM configuration relationship. |
| `stl-verify/internal/services/allocation_tracker/config.go:15–28,53–94` | Go tracking configuration and address conversion. | Not the claimed operational Configurator implementation. |
| `stl-verify/internal/pkg/httpclient/client.go:51–75,108–117` | HTTP request throttling. | Not contract-level cBEAM/SORL enforcement. |

The six historical subresults remained NOT ESTABLISHED: Configurator implementation, bound BEAMTimeLock, bound BEAMState, bounded cBEAM operations, the combined legacy architecture and source presence by June 4. They describe different missing bindings within one claim, not six implementation failures.

The pinned STL revision was `37e56db072f9f246fc2f77ed3036e4a8e732aaf7`. The retained pre-subject witness, `27aa90f7cf888298eef92a41be00f3a30fd1a0cf` at June 4, 2026, 07:27:00Z, already contained PoolConfigurator references in external pool/indexing contexts. Their earlier presence did not establish legacy Configurator provenance. No earliest implementation commit or June-to-September implementation change was inferred.

The retained searches used distinctive component/function vocabulary and inspected matching contexts. Negative name and project-marker results remained bounded search observations. **NO MATCHED STL COVERAGE ESTABLISHED** means neither STL irrelevance or deficiency nor source absence, implementation absence or claim falsehood. The required semantic/source match was missing; implementation contradiction was not established.

### G.4 L3B — Local implementation provenance

L3B retained the historical main result **NOT ESTABLISHED**. It asked whether available local documents, source-link context, metadata and history could identify the intended implementation or a sufficiently concrete retrieval target. Its evidence was stronger than generic name resemblance in some respects, but did not identify the complete legacy source.

| L3B question | Historical answer |
|---|---|
| Laniakea source/repository attribution? | Requirements/interface text and a library-family reference; complete source NOT ESTABLISHED. |
| Atlas source/repository attribution? | Related PAS records, without a repository binding for the legacy stack. |
| STL provenance continuation? | No matched source/package/UUID pointer for C06 established in inspected metadata. |
| Combined implementation identity? | NOT ESTABLISHED for the required components and their relationship. |
| Identity by the June subject snapshot? | NOT ESTABLISHED; later documentary records did not establish earlier source identity. |
| Concrete external legacy-source target? | NONE; no exact repository, package or verified-source artifact identified. |

The local work traced the subject's summary and requirements into Atlas PAS material and inspected provenance-bearing STL metadata. Local history tested documentary dates; it did not supply absent implementation attribution. The retained record explicitly limits this to a bounded semantic provenance search, not exhaustive inspection of every historical blob, synonym or implicit reference.

Legacy identity and the legacy-to-PAS bridge remained NOT ESTABLISHED; chain HOLD persisted. Architecture access remained BLOCKED where applicable, without becoming the main result. L3B preserved distinctive leads and the reasons they stopped, rather than promoting them into a likely-source or implementation finding.

### G.5 OpenZeppelin component-family lead

The retained L3B finding identifies `smart-contracts/configurator-unit.md:164` as naming **“OpenZeppelin TimelockController with pause capability.”** Lines 119–164 provide storage/timelock context; other component definitions and sketches appear at lines 13–25, 215–243 and 283–291. The phrase is documentary attribution to a library/component family.

Its descriptive lead state was NAME-ONLY LEAD. It did not specify an exact package version, source revision or complete Configurator implementation repository. Nor did it identify how the cited family, any pause capability, BEAMState and bounded cBEAM operations were combined in the claimed legacy implementation.

A library-family attribution can narrow a provenance question while leaving that question unanswered. Inspecting generic OpenZeppelin source would answer what that selected library implements, not whether it is the code used by the legacy stack. No generic library was substituted to manufacture source/address/runtime binding or to infer the behavior of unidentified companions.

The evaluation therefore retained the name as useful documentary evidence. It neither discarded the lead nor treated the lead's existence as implementation confirmation. Exact family attribution and exact implementation identity remained different evidence objects.

### G.6 Later PAS Configurator / BeamState / Timelock records

Atlas `content/A.2 - The-Support-Scope.md:3401–3428` described PAS Configurator, BeamState, Timelock and PASMom in a Diamond PAU context. Init defaults at lines 3545–3551 and bounded operator adjustments/actions at 3623–3629 made the relationship more distinctive than unrelated configuration hits. These were provenance discriminators, not independently tested code or governance rules.

The retained L3B-02 finding records three principal documentary identifiers:

| Atlas record | Source lines | UUID | Provenance role |
|---|---|---|---|
| PAS_CONFIGURATOR | 3401–3403 | `5e1f82c7-bcd6-46f8-aec0-3e767e55a93c` | Identifies the later PAS Configurator record. |
| PAS_STATE | 3405–3407 | `2e36bb4f-91db-4dca-bdb1-e4aa385b1129` | Identifies the related BeamState record. |
| PAS_TIMELOCK | 3409–3411 | `f6791cf7-f3aa-49da-9691-73e480bf3328` | Identifies the related Timelock record. |

The finding also retains their literal addresses as documentary leads. This appendix uses the record identities and source locations to explain the gap; it does not present those addresses as tested C06 chain targets. Their presence made the leads ADDRESS-BOUND in the historical descriptive vocabulary, not implementation-bound.

| Documentary witness | Date / revision | What the date establishes |
|---|---|---|
| Laniakea named-stack business requirements | January 13; retained short revision `c1ce2b0` | The requirements already contained the names/model. |
| Atlas Configurator/BeamState additions | August 13, 2026; `b9fd09c0b2c46f1c5309620cb5503599c2c05f15` | Addition of the inspected Diamond PAS records, initially with details deferred. |
| Atlas fuller addresses and descriptions | August 27, 2026; `17044094b2054ce3ff52350d09e5fdf7cda4c373` | Addition of inspected addresses and fuller Timelock/init/operator descriptions. |

The August additions postdate the June subject snapshot. Neither those dates nor January's requirements date establishes first implementation or deployment. The searched pre-subject Atlas snapshot lacked the distinctive matches; that lexical observation was not evidence of contract nonexistence. UUIDs preserved documentary traceability across path consolidation without proving an implementation lineage.

### G.7 Legacy-to-PAS relationship

**Explicit legacy → PAS source/implementation bridge: NOT ESTABLISHED.** The observed connection was Laniakea requirements → distinctive Configurator/BEAM/init model → similar later PAS documentary architecture. The last relationship was an inference of relevance, not proven derivation, identity or migration.

The inspected records supplied no implementation URL or explicit legacy-to-PAS source/version bridge. No dated source connection established that the later PAS components were the legacy components under different names, an implementation derived from them, or a replacement. Repository history tying the implementations together was not established because the legacy implementation itself had not been identified.

Similarity in roles and init/bounds vocabulary supported preserving the lead. Later Diamond scope, different identifiers and missing source attribution prevented promotion to identity. These distinctions do not prove difference either. The evaluation established neither equivalence nor non-equivalence, replacement, migration, renaming or succession.

Chronology alone cannot fill this gap. A later document might illuminate an earlier implementation if an explicit source relationship connects them. Without that relationship, the date of a later record cannot be used either to backdate its implementation to June or to deny an earlier legacy implementation. The unresolved bridge remains an evidence requirement, not a choice between speculative histories.

### G.8 Architecture-source access limitation

The frozen baseline records `archon-research/architecture` as **BLOCKED_FOR_ANONYMOUS_GIT_AT_SETUP**. It records **Credentials supplied: NO**. The source remained unavailable and unaccessed under that setup; no access or authentication was attempted for this appendix.

This is an access-specific limitation. No inspected required-source pointer established that the missing legacy implementation necessarily resided there. Consequently, the inaccessible repository was not assigned presumed contents, and architecture BLOCKED did not replace NOT ESTABLISHED as C06's main result.

The distinction matters because local evidence remained available and was examined. C06 did not stop solely because one repository was inaccessible: the available records also lacked qualifying legacy-source attribution. Neither opening an unrelated repository nor knowing that architecture access was blocked supplies that attribution. The access record establishes neither implementation existence nor nonexistence and creates no obligation to acquire credentials or gain access.

### G.9 Why targeted external provenance retrieval was not opened

The concrete external legacy-source retrieval target remained **NONE**. C05 had exact evidence-backed package and registry pointers that could support narrowly scoped external provenance work. C06 had component-family and later PAS documentary leads without an exact legacy repository/package/verified-source artifact. This contrast concerns evidence specificity, not implementation merit.

The retained L3B decision did not recommend broad searches or synthesized explorer URLs from PAS addresses. It did not guess repositories, select similarly named contracts, substitute later PAS components or infer the complete stack from generic OpenZeppelin code. Such substitutions could produce inspectable material without showing that it was the material under evaluation.

Stopping protected proposition identity. Targeted retrieval eligibility was a prerequisite decision, not a requirement to pursue every conceivable source. The absence of an eligible target describes the reviewed evidence, not all possible locations of an implementation. No corresponding C06 L3C/L3D phase was opened, and that absence is not a later negative test result.

### G.10 Why static implementation review was not opened

Static implementation review remained **NOT OPENED / NOT TESTED**. L3A's Stage 2 comparison did not proceed after the coverage gate failed to identify a match; L3B did not supply the missing identity. There was therefore no matched legacy source against which to test the stated component behavior.

The evaluation could read requirements and distinguish unrelated candidates without conducting a static implementation review of C06. These activities answer different questions. Requirements signatures describe intended surfaces; they are not an implementation body, and a plausible library body is not automatically the claimed stack.

No code failure, missing implementation proof or behavioral contradiction follows. The matrix preserves static binding as NOT ESTABLISHED and behavior as NOT TESTED. A later qualifying source could permit an appropriately scoped review, but its identification would not automatically establish its semantics or correctness.

### G.11 Why chain verification remained HOLD

Historical runtime remained **NOT TESTED**, and later/current runtime remained **NOT TESTED**. The chain gate stayed **HOLD** because sufficiently supported implementation and component/address provenance had not been established for the legacy object.

Chain queries would concern particular addresses at particular blocks. Later PAS addresses alone did not demonstrate that those queries would answer C06. Examining a different but similarly named contract could appear to verify the claim while actually changing it. Conversely, absence at a guessed address could not establish nondeployment of the legacy system elsewhere.

No substitute target was adopted and no C06 chain verification was performed. HOLD is a workflow/prerequisite gate, not FAIL. The legacy-live/deployed assertion remained NOT ESTABLISHED because it was unverified, not because a deployment test returned a negative result. C05's later Mainnet evidence cannot supply this claim-specific missing relationship.

### G.12 C06 status separation

| Object | Status | Meaning |
|---|---|---|
| STL matched implementation | NOT ESTABLISHED / NO MATCHED STL COVERAGE ESTABLISHED | Related references did not identify the claimed executable stack. |
| Historical L3A/L3B main results | NOT ESTABLISHED | Each phase stopped below its implementation-identification threshold. |
| Legacy implementation identity | NOT ESTABLISHED | No sufficiently bound inspectable source identified. |
| Legacy → PAS bridge | NOT ESTABLISHED | Related documentary roles did not establish implementation lineage. |
| Architecture access | BLOCKED where applicable | Source-access limitation; no presumed repository contents. |
| Concrete external retrieval target | NONE | No qualifying legacy-source location established. |
| Static review | NOT OPENED / NOT TESTED | No matched source for behavioral comparison. |
| Chain gate | HOLD | Address/source prerequisites unmet. |
| Historical runtime | NOT TESTED | No historical C06 chain verification. |
| Later/current runtime | NOT TESTED | No later C06 chain verification. |
| Live/deployed assertion | NOT ESTABLISHED | Neither deployment nor operation independently established. |
| Final synthesis | PARKED | Further work set aside pending qualifying provenance. |

These labels must retain their objects. The final synthesis does not overwrite either historical grade; access BLOCKED does not become a claim verdict, and an unperformed runtime test cannot become a nondeployment finding. Appendix J consolidates formal terminology across the report; this table applies the distinctions to C06 only.

### G.13 Conclusions the evidence does not support

The evaluation did not establish:

- That the C06 claim is false, disproven, abandoned or permanently unresolvable.
- That its implementation is nonexistent or undeployed.
- That later PAS is equivalent to, or different from, the legacy implementation.
- That migration, replacement or renaming occurred, or that no migration occurred.
- That architecture contains the missing source, or that it does not.
- That later provenance cannot identify the intended implementation.

The accepted positive record here is the existence of the inspected descriptions and leads, together with a bounded account of what they failed to identify. Documentary presence is not implementation truth; missing identity is not evidence of implementation absence. The unresolved result remains meaningful without selecting a speculative explanation.

### G.14 Qualifying provenance that would justify reopening

The frozen L3B finding and main narrative identify the following qualifying evidence:

| Evidence | Question it could make answerable |
|---|---|
| Explicit legacy repository/path/package attribution | Which inspectable source implements the claimed stack? |
| Dated legacy → PAS source connection | How, if at all, do the legacy and later PAS implementations relate? |
| Verified-source artifact identifying all required components | Can the combined legacy relationship be bound to inspectable implementation? |
| Equivalent qualifying provenance meeting the same requirement | Is there another supported route to the intended implementation identity? |

Names or addresses alone remain insufficient. New evidence would justify reconsideration under the existing threshold and appropriate authorization; it would not automatically establish source behavior, deployment or operation. An accessible source must also be explicitly connected to this claim.

Reopening is evidence-triggered, not mandatory remediation, a publication blocker or an obligation to continue searching. C06 is parked rather than permanently closed, while Report v1 can close with that boundary explicit. New evidence about the old snapshot and a later project change would need to be distinguished rather than silently rewriting the historical result.

### G.15 Relationship to the other appendices

Appendix E compares C05/C06 coverage, discovery and source resolution. Appendix G is the definitive unresolved C06 case, including the missing bridge, object-specific statuses, stopping decisions and reopening threshold. Appendix H records C06/PARKED within the wider selected-claim populations and directs readers here for the investigation.

Appendix C retains phase chronology; Appendix B explains the general method. None of those allocations permits an appendix to override the master matrix or frozen narrative. This case supplies detailed traceability without expanding C06 into a general inventory of unresolved claims or altering the historical evidence.

### Evidence notes

- **G-1.** `reports/2026-09-18-f438819/L1-claim-map.md`
- **G-2.** `reports/2026-09-18-f438819/L3A-STL-binding-C05-C06.md`
- **G-3.** `reports/2026-09-18-f438819/L3B-implementation-provenance-C05-C06.md`
- **G-4.** `reports/2026-09-18-f438819/findings/L3A-02-C06-legacy-configurator-stl-binding.md`
- **G-5.** `reports/2026-09-18-f438819/findings/L3B-02-C06-legacy-configurator-provenance.md`
- **G-6.** `reports/2026-09-18-f438819/leads.md`
- **G-7.** `pins/baseline.md`
- **G-8.** `synthesis/master-evidence-matrix.md`
- **G-9.** `synthesis/report-sections/07-unresolved-provenance-c06.md`
- **G-10.** `synthesis/report-sections/09-limitations-and-future-work.md`
- **G-11.** `synthesis/appendices/B-evaluation-methodology.md`
- **G-12.** `synthesis/appendices/C-l0-l3f-phase-ledger.md`
- **G-13.** `synthesis/appendices/E-stl-provenance-ledger.md`

## Appendix H — Unverified / Out-of-Scope / Deferred Claims

### H.1 Purpose and reading rule

This appendix records population-level traceability for selected claims whose current implementation or operation was not independently established, together with the historical, illustrative and target material that must remain distinct from them. It is not a failure ledger. The master evidence matrix controls final disposition; the claim map preserves statement selection and temporal classification.

NOT INDEPENDENTLY VERIFIED does not mean failed; NOT ESTABLISHED does not mean false; OUT OF SCOPE is not a negative finding. PARKED is a synthesis disposition, not a historical grade or permanent closure. TARGET DESIGN does not mean missing current implementation. HISTORICAL and EXAMPLE / ILLUSTRATIVE describe temporal/documentary roles rather than current deployment assertions.

These distinctions apply to scoped propositions. Some documentary conclusions are ESTABLISHED even though the corresponding implementation or runtime question was not tested. Conversely, a clearly worded current assertion can remain independently unverified. Neither a document's confidence nor an appendix heading supplies the missing evidence.

The selection comprises 53 statement units, with overlaps, rather than 53 independent propositions or exhaustive corpus coverage. X1 and U1–U4 are separately retained contextual records; their inclusion gives the matrix 58 rows without creating additional selected claim units. The populations below are traceability groupings, not a denominator for a project score. Source references are retained in the matrix and L1 claim map; **R/** abbreviates `reports/2026-09-18-f438819/`.

### H.2 Population overview

| Population / status family | Selected records | Final treatment | Reading boundary |
|---|---|---|---|
| Deferred current operational assertions | C10, C11, C39 | NOT INDEPENDENTLY VERIFIED | Independent operational verification deliberately deferred. |
| Architecture/provenance-dependent current assertions | C07, C08, C09, C12, C13, C14, C15, C16 | NOT INDEPENDENTLY VERIFIED | Source/access prerequisites insufficient; not evidence of absent implementation. |
| Parked provenance case | C06 | PARKED | Legacy identity unresolved; detailed case in Appendix G. |
| Broader deployment assertion | C45 | NOT ESTABLISHED | All-layer claim not established by C05. |
| Other ambiguous authority/completion assertions | C43, C44, C46, C47 | NOT ESTABLISHED | Status/scope or completion/activation ambiguity retained. |
| Settlement assertions under X1 | C17, C18 | NOT ESTABLISHED | Documentary conflict/HOLD; no operating winner selected. |
| Future/target units | Exact 23-row list in H.8 | TARGET DESIGN | Sixteen PROPOSED-TARGET and seven FUTURE-ROADMAP. |
| Historical/illustrative selected units | C28, C49, C50, C51, C52, C53 | ESTABLISHED for documentary framing only | Not implementation, deployment or runtime establishment. |

OUT OF SCOPE remains a meaningful boundary, but is not substituted for the displayed matrix dispositions. In particular, being outside C05's technical scope does not make C45 an OUT OF SCOPE synthesis row. Likewise, PARKED and the two non-verification groups are not merged into a larger failure count. Unresolved Atlas mappings remain primarily in Appendix D; their relevant reopening conditions are cross-referenced here.

### H.3 Current operational claims not independently verified

Each proposition below is a retained source assertion. The amount, cadence and configuration descriptions are not adopted observations. The three units share a final disposition but ask different operational questions.

| Claim | Proposition | Final disposition | Why not independently verified | Evidence that would justify reconsideration |
|---|---|---|---|---|
| C10 | Current temporary Steps 4/5 perform fixed-amount SKY buybacks, approximately $300K/day, distributed to stakers. | NOT INDEPENDENTLY VERIFIED | Independent Atlas/chain operational verification deferred; the amount is an untested claim. | Separately authorized evidence of actual policy, configuration and use, if importance warrants further verification. |
| C11 | Upkeep currently realizes monthly in P1; creation fees route at issuance. | NOT INDEPENDENTLY VERIFIED | Realized-payment verification deferred. C04 addressed policy, not payments. | Appropriate payment/operation evidence under separate authorization; documentary policy alone is insufficient. |
| C39 | SKY emissions trigger is currently disabled; future upgrade. | NOT INDEPENDENTLY VERIFIED | Actual policy, configuration and use were not independently checked. | Appropriate policy/configuration/operational evidence, if importance warrants separately authorized review. |

C10's source is `accounting/treasury-management.md:159–171`; C11's is `accounting/entity-fees.md:142`. The temporary buyback configuration is described as out-of-band, distinct from future SBE BEAM behavior. Its approximately $300,000 daily figure therefore remains part of the claim, not a measured flow.

C11 is separate from C04's PARTIALLY ESTABLISHED documentary policy relationship within the shared Prime scope. Supported fee-policy dimensions cannot establish monthly payment realization, issuance routing or transfers. Its monthly economic-settlement language does not by itself contradict a daily in-synome clock; daily LCTS realization is conditional/future. C39 similarly preserves two different assertions: a present disabled state and a future upgrade, without establishing either actual configuration or implemented future capability.

These are optional choices about further independent verification, not the report's technical category of OPTIONAL ASSURANCE. That category has one frozen item, exact C05 bytecode reproduction. No operational unit must be resolved before Report v1 can close.

### H.4 Architecture/provenance-dependent current claims not independently verified

The following eight units retain NOT INDEPENDENTLY VERIFIED. The group includes both CURRENT-IMPLEMENTATION and CURRENT-OPERATIONAL temporal classes; “architecture/provenance-dependent” describes their verification constraint, not a new temporal class. Architecture verification was blocked and implementation/phase-status prerequisites were not sufficient for independent truth testing.

| Claim | Retained proposition | Final disposition | Specific evidence ceiling |
|---|---|---|---|
| C07 | Rule discovery with regression gating is implemented today via Rule-Author Agent. | NOT INDEPENDENTLY VERIFIED | Implementation not independently checked. RSI autonomy level L3 is not this evaluation's L3 phase. |
| C08 | Strength/confidence framework is implemented as PLN truth values with Beta semantics and delta-method propagation. | NOT INDEPENDENTLY VERIFIED | Concrete implementation wording retained; equations and code not evaluated. |
| C09 | Fork/regress/promote and LLM Rule-Author are first running instances. | NOT INDEPENDENTLY VERIFIED | Running-instance assertion unverified; illustrative/noncanonical pattern qualification does not retract it. |
| C12 | DSC is live daily: 13:00 cut, 16:00 epoch advance, wall-clock-derived; monthly reconciliation stays out-of-band. | NOT INDEPENDENTLY VERIFIED | Documentary live-state assertion, not observed production; daily synomic clock is distinct from economic settlement. |
| C13 | ER is emitted each heartbeat; penalties are manual/later-phase. | NOT INDEPENDENTLY VERIFIED | Output and formula truth not checked; reporting is distinct from automated closure/enforcement. |
| C14 | P1 uses synserv-triggered ownership-weighted temporary SDR allocation. | NOT INDEPENDENTLY VERIFIED | Claimed temporary mechanism unverified; Phase 9+ real auction remains separate. |
| C15 | Crypto Majors Oracle and Book Attestation Oracle are operational at Phase 1. | NOT INDEPENDENTLY VERIFIED | Named-instance operation unverified; a stub specification neither proves nor disproves those instances. |
| C16 | Live P1 has custodial-crypto stress-envelope risk, SDR capacity/overlay, temporary allocation and real-time ER; only structbook activates. | NOT INDEPENDENTLY VERIFIED | Active risk-surface assertion unverified; design currency does not prove operation. |

For all eight, the frozen reopening requirement is an accessible, explicitly bound implementation/phase-status source and separate authorization. Availability alone is not enough. Architecture inaccessibility neither proves the systems absent nor establishes that the unavailable repository contains their implementations. No substitute inference is permitted merely because another source is adjacent or uses the same terminology.

Overlap is retained: C07/C09 describe a related Rule-Author implementation/operation cluster; C13/C14 overlap with C16's broader P1 risk-surface assertion. These are selected statement units, not eight independent systems. Together with the three operational units, they make eleven units, not eleven failures or a coverage percentage.

Current wording remains consequential even beside broad draft/target labels. C08's implementation assertion is not erased by nearby conceptual material, and C09's running-instance assertion remains separate from C52's noncanonical illustration. Conversely, those current assertions do not establish the wider RSI ladder, every Oracle feature or the full target risk framework.

### H.5 C06 — parked pending provenance

C06's final synthesis disposition is **PARKED**. Legacy implementation identity and the legacy-to-PAS bridge remain NOT ESTABLISHED; the concrete external legacy-source target remains NONE. Architecture BLOCKED is access-specific and chain HOLD is a prerequisite gate. Neither changes the historical main result into failure or nonexistence.

Appendix G is the definitive provenance case and records why targeted retrieval, static review and chain verification did not proceed. C06 is listed here to preserve population-level status separation, not to add it to the eleven NOT INDEPENDENTLY VERIFIED units or to repeat its investigation.

### H.6 C45 — broader all-layer deployment claim

C45 states: “PAU is deployed at every Generator/Prime/Halo/Foreign layer.” Its temporal classification remains AMBIGUOUS and its final disposition **NOT ESTABLISHED**. Blanket deployment wording overlaps legacy-live material and target factory/Core Entity scope; no replacement interpretation is forced.

The frozen synthesis corrected the OUT OF SCOPE characterization to NOT ESTABLISHED because the broader claim was evaluated enough to retain an unresolved substantive disposition. This publication-control distinction does not retroactively regrade historical phases. Broader verification remains outside C05, whose scoped Mainnet grounding at two observations does not identify every layer, factory or foreign deployment.

Reconsideration requires clarification of each claimed layer/network and implementation/address/date binding before separately authorized verification. C45 does not establish falsehood, absence of deployments elsewhere or target-design failure. One reusable implemented pattern cannot establish all instances named by a broader statement.

### H.7 Other broader completion or deployment boundaries

The frozen architecture explicitly allocates C43–C47 and C17/C18/X1 to Appendix H. The following rows retain their matrix statuses rather than being absorbed into the eleven-unit population or the target-design set.

| Claim | Proposition / question | Final disposition | Evidence ceiling and frozen reconsideration requirement |
|---|---|---|---|
| C43 | Portfolio capital and Guardian ORC are both required; P1 uses GovOps cBEAM compromise model. | NOT ESTABLISHED | AMBIGUOUS draft phase-specific normative model; “required” does not prove enacted/enforced requirements. Explicit dated status/scope clarification precedes a truth test. |
| C44 | Calibration adopts SORL 25% and IRL $100K under a current model. | NOT ESTABLISHED | AMBIGUOUS: design calibration is not automatically ratification or deployed settings. Legacy-live contracts do not settle activation; dated status/scope clarification is required. |
| C46 | Whole mechanism is implemented in synlang, with P1 carve-outs limited to parameters and oracle gap filling. | NOT ESTABLISHED | AMBIGUOUS alongside post-P1 activation and speculative/not-yet-distributing framing. A pinned completion/activation/scope statement must distinguish implemented design, runtime implementation and activation. |
| C47 | Deliverable is production-quality ER; as-built specifics belong to implementation canon; rehearsal precedes production. | NOT ESTABLISHED | AMBIGUOUS: current specification/design-of-record does not prove production launch. Requires a pinned completion/activation/scope statement and accessible authorized implementation-canon evidence. |
| C17 | A per-Prime settlement record is produced; P1 governance reads it and acts manually, with beacon execution from Phase 2 onward. | NOT ESTABLISHED | Documentary HOLD under X1; conflicts with C19's exclusion of P1 in-synome closure. Same-scope correction/version/retirement or clarification needed before implementation truth testing. |
| C18 | Cadence is encoded as an atom; monthly is P1 reality, replaced by daily at Phase 3. | NOT ESTABLISHED | Documentary HOLD under X1; conflicts with daily DSC and out-of-band/non-atom monthly framing. Same-scope clarification needed; no code-block execution inferred. |

C46's specification idiom, implementation-before-activation possibility and stale P1 carve-out remain distinguishable unresolved readings; no categorical contradiction is newly asserted. C47's “live” specification likewise does not determine production status. C17/C18 retain their explicit local current-state assertions while the documentary conflict stays unresolved. X1 is one conflict cluster, not three independent implementation failures because multiple L1 invariants recorded FAIL.

### H.8 Target design population

Exactly **23** selected units have final disposition **TARGET DESIGN**. The table preserves their frozen temporal classes and compact proposition summaries. Each ID appears once in this list. None is a finding of current deployment, current governance authority or failed implementation.

| Claim | Frozen temporal class | Target / future proposition |
|---|---|---|
| C19 | PROPOSED-TARGET | Per-Prime closure and global aggregation are target closure; P1 does not run this closure or TMF in synome. |
| C20 | PROPOSED-TARGET | Six of 24 Council seats rotate quarterly through SKY polls and Council enactment. |
| C21 | PROPOSED-TARGET | Guardian-token SpellCore and dual-key Prime/Halo spells replace legacy voting. |
| C22 | PROPOSED-TARGET | SKY holders retain graduated freeze and Council-dismissal powers. |
| C23 | PROPOSED-TARGET | Diamond architecture replaces the legacy single Controller. |
| C24 | PROPOSED-TARGET | LCTS queues and daily lock/settle standard serve risk-capital tokens. |
| C25 | PROPOSED-TARGET | NFATS uses per-deal tokens, facility queues and attestor/book lifecycle. |
| C26 | FUTURE-ROADMAP | Yield Splitter/PT-YT rollout lacks an assigned phase, depends on unscheduled LCTS interfaces; native orderbook is unscheduled. |
| C27 | FUTURE-ROADMAP | Cognitive Sentinels are forward-looking and outside P1; the accompanying P1 deterministic-relay description is not independently verified here. |
| C29 | PROPOSED-TARGET | Human Atlas becomes a short constitutional root, about 10–20 pages target. |
| C30 | PROPOSED-TARGET | Current Atlas operational prose moves into structured Synome nodes. |
| C31 | PROPOSED-TARGET | Knowledge improves across artifact levels through recursive feedback. |
| C32 | FUTURE-ROADMAP | L4 source rewriting is far-future; autonomy levels are not evaluation phases. |
| C33 | FUTURE-ROADMAP | Growth Staking mechanism activates post-P1; rewards are not yet distributed via synserv. |
| C34 | PROPOSED-TARGET | Incentive systems are target, not P1; SDRR waits for fee-paying real auctions. |
| C35 | FUTURE-ROADMAP | Real auction sequence and tug-of-war are Phase 9+ design. |
| C36 | PROPOSED-TARGET | MDC is a potential speculative feature that may or may not be implemented. |
| C37 | FUTURE-ROADMAP | An additional independent-trader metric is planned and not yet implemented. |
| C38 | FUTURE-ROADMAP | Dynamic burn begins after SBE BEAM deployment, Phase 2+. |
| C40 | PROPOSED-TARGET | Halo management and failed-entity wrapping are Core Entity modes. |
| C41 | PROPOSED-TARGET | Identity Networks maintain registries and issue attestations checked on transfers. |
| C42 | PROPOSED-TARGET | Capital flow includes routing among multiple sub-books and concentration excess. |
| C48 | PROPOSED-TARGET | Five-layer model, Atlas/Synome split and beacons are live commitments. |

The split is **16 PROPOSED-TARGET + 7 FUTURE-ROADMAP = 23 TARGET DESIGN**. The original temporal distinctions remain useful even with a common synthesis disposition: specified architecture, phase-dependent activation and unscheduled future work are not identical commitments. Historical, illustrative, ambiguous and unverified-current rows are not silently included in this target list.

### H.9 Target design themes

These five themes reproduce the frozen narrative allocation. Every target ID appears exactly once across them; the grouping creates no new grade or prioritization.

| Retained theme | Exact IDs | Scope qualification |
|---|---|---|
| Post-transition governance and Atlas/Synome structure | C20, C21, C22, C29, C30, C48 | Constitutional/post-transition scope and live commitments are not current authority or completed Synome migration. |
| Contract standards and entity infrastructure | C23, C24, C25, C26, C40, C41 | Placeholder/draft standards, unscheduled rollout and target entity types do not establish deployed instances. |
| Cognitive agents and recursive improvement | C27, C31, C32 | Future Sentinels and broader improvement ladder remain distinct from limited Rule-Author current assertions. |
| Economic closure, activation and incentives | C19, C33, C34, C35, C38 | Proposed sequence/dependencies do not establish actual schedules, activation or payment flows. |
| Speculative and broader risk design | C36, C37, C42 | Potential features and broader risk machinery do not establish feasibility, equations or implementation. |

Within these themes, qualifications remain claim-specific. C23 has a placeholder specification, not a completed Diamond migration. C25's P1 bookkeeping context does not establish the full NFATS facility design. Core Entity is expressly not instantiated in P1 in the frozen summary; describing its functions does not prove use. Identity Networks retain target scope, while the missing canonical Sky Intents pointer remains a separate documentary issue.

C19's target placement does not choose a winner in X1. Growth Staking timing is distinct from generic SKY staking, and C35's real auction is distinct from C14's temporary allocation. C38's later burn mechanism cannot establish C10's current buybacks. These separations prevent a theme summary from silently completing a current-state evidence path.

### H.10 How TARGET DESIGN should be read

TARGET DESIGN identifies future/proposed scope that was not tested as necessarily current implementation. It does not mean failed implementation, a missing-implementation defect, a deployment commitment, demonstrated feasibility, established design soundness or future adoption. Report v1 neither ranks these designs nor concludes they will be built.

Proposed-state protection does not erase an explicit current assertion elsewhere. A draft architecture can coexist with a claimed running instance; each statement retains its own scope. Similarly, “live commitment” or present-tense design prose can describe an intended architecture without proving a launched system. The matrix records the relevant local qualifications rather than applying a blanket tense rule.

Some target governance arrangements may require future formalization where they differ from current authority structures. That is a conditional boundary, not a conclusion that every target requires an Atlas amendment or a recommendation for adoption. A later status change would require its own dated, claim-specific evidence.

### H.11 Historical and illustrative selected units

All six rows below are **ESTABLISHED for their documentary framing only**. Their temporal classes and implementation ceilings remain separate from that synthesis disposition.

| Claim | Temporal class | Documentary proposition established | What was not established |
|---|---|---|---|
| C28 | HISTORICAL | Documentation retires earlier unified sentinel-formation terminology in favor of relay/sentinel classes. | Implemented STL migration or runtime change. |
| C49 | HISTORICAL | Documentation describes Noemar/synlang as superseding the earlier MeTTa/notation research track. | Technical/runtime replacement; supersession does not extend automatically to the whole active directory. |
| C50 | EXAMPLE / ILLUSTRATIVE | Configurator User Story 1 states PAU deployment and Configurator admin grants as onboarding prerequisites. | Actual deployment or grants. Preconditions inside a user story are not observed state. |
| C51 | EXAMPLE / ILLUSTRATIVE | One Prime's seeded state, closure and penalties illustrate synlang machinery. | Running settlement, validated scalars or operational execution. |
| C52 | EXAMPLE / ILLUSTRATIVE | Fork/propose/test/regress/decide/record illustrates one noncanonical realization. | Runtime truth; separate C09 running-instance assertion remains NOT INDEPENDENTLY VERIFIED. |
| C53 | HISTORICAL | README characterizes the earlier-phase root as an inactive source/baseline for rewrite. | Verbatim fidelity of an earlier snapshot; inactive substantive claims are not promoted to active authority. |

Illustrative does not mean fictional or necessarily unimplemented. It identifies what the selected passage establishes. Historical framing similarly records a documentary change without proving the corresponding technical change. These are affirmative scoped documentary results, not six unverified-current implementation claims and not six technical failures.

### H.12 Documentary establishment does not imply runtime reality

C01 establishes that Atlas contains witnesses for selected operational-data categories. That result does not establish address correctness, current deployment, runtime use, completeness or completed migration. C28/C49 establish documentary retirement/supersession; C50–C52 establish prerequisite/example framing; C53 establishes the README's characterization. Their documentary conclusions remain affirmative within scope.

X1 likewise has an **ESTABLISHED documentary conflict**, while actual operating truth and the intended documentary winner remain NOT ESTABLISHED. The conflict-related historical FAILs remain historical invariant results. C17/C18 are not thereby proven false, and C19's target classification does not select its account as the operative one.

The relationship between evidence type and proposition is decisive. A source-verified fact that a passage contains a claim is different from independently establishing the claim's runtime truth. This does not make all documentary evidence unverified; it identifies precisely what its established conclusion covers. H therefore retains affirmative documentary rows alongside unresolved implementation populations without collapsing either category.

### H.13 Status families

| Status / class | What it permits | What it does NOT mean |
|---|---|---|
| NOT ESTABLISHED | Report the specific unresolved proposition and missing evidence relationship. | Falsehood, prohibition or proven absence. |
| NOT INDEPENDENTLY VERIFIED | Record an assertion whose independent verification path was not completed. | Failed implementation or automatic conversion to another disposition. |
| OUT OF SCOPE | Identify a question outside a defined completed test. | Negative finding or permission to relabel C45. |
| PARKED | Set further verification aside pending qualifying evidence. | Historical grade, falsehood or permanent closure. |
| TARGET DESIGN | Preserve proposed/future scope and its qualifiers. | Missing-current-implementation failure, feasibility or adoption. |
| HISTORICAL | Preserve a historical documentary relationship or characterization. | Present deployment or current authority. |
| EXAMPLE / ILLUSTRATIVE | Preserve example, sketch or prerequisite framing. | Observed operation, or proof that implementation cannot exist. |

The first five are synthesis dispositions; the last two are temporal/reporting classes. An ESTABLISHED documentary result can coexist with a HISTORICAL or EXAMPLE / ILLUSTRATIVE classification. This table explains their use in this population; Appendix J remains responsible for consolidated formal definitions and mappings among vocabularies, grades and gates.

### H.14 When these claims may be reconsidered

The frozen future-work model distinguishes reopening on qualifying evidence, optional assurance and delta evaluation after material change. These are reasons for reconsideration, not a remediation backlog, priority ranking or publication dependency.

| Existing unresolved question | Frozen evidence-triggered condition |
|---|---|
| C06 provenance | Explicit legacy source attribution, dated legacy-to-PAS connection, verified-source artifact covering required components or equivalent qualifying provenance; Appendix G. |
| X1 and C17/C18 | Pinned same-scope clarification, correction or version/retirement evidence resolving the documentary disagreement before truth testing. |
| Architecture-dependent units | Accessible source explicitly bound to the implementation/phase-status claim; access alone is insufficient. |
| C10/C11/C39 | Appropriate policy, configuration or operational evidence if importance warrants independent verification; C11 requires payment evidence. |
| C02/C03 and scoped C04 | Explicit dated Guardian/executor/parent mapping; authority-layer/phase evidence; or dated exception, supersession or distinct-obligation explanation, respectively. |
| C43/C44 | Explicit dated status/scope clarification before testing required/adopted language. |
| C45 | Layer/network-specific implementation, address and date binding. |
| C46/C47 | Pinned completion/activation/scope statements; accessible implementation-canon evidence where applicable. |
| Documentary destinations/status | Explicit canonical destination, same-scope ambiguity/retirement clarification, link-resolution convention, inactive-whitepaper authority or slideshow-status clarification. |

The last group preserves U1–U4 and the relevant L0 boundaries without inventing replacement documents. C53's documentary characterization also does not verify verbatim snapshot fidelity. A similarly named destination or newly accessible adjacent source would not automatically satisfy these conditions.

**Optional assurance** remains limited to exact C05 source/runtime bytecode reproduction, primarily treated in Appendix F. C05 is already CLOSED; that item is not assigned to the unverified or target populations. Other unresolved questions are not relabeled optional assurance merely because future work is nonmandatory.

**Delta-evaluate when the project changes** applies to future governance formalization, target-architecture implementation, later documentary repairs/revisions and other material post-snapshot changes. A target becoming a current assertion, a deployment or a changed source attribution can alter the evaluable question. No such change is asserted here. Each would require its own scope and evidence; none creates an obligation to adopt a target or continue evaluation now.

### H.15 Later changes and snapshot integrity

A later documentation repair, deployment, formal governance decision, source release or target implementation creates a delta against the frozen snapshot. It does not erase the original finding or rewrite the historical phase grade. The report can preserve both the earlier boundary and a later supported conclusion when their dates and propositions are explicit.

New evidence about the old snapshot is different from an actual later project change. A source released later might illuminate earlier implementation only if its evidence relationship supports that inference; its availability date alone is not an earlier deployment date. Likewise, a corrected document can change later documentary status without proving which account described prior operation. Reconsideration must preserve that distinction.

### H.16 Population recap

| Population | Count / exact scope | Retained treatment |
|---|---|---|
| Deferred operational | 3 — C10, C11, C39 | NOT INDEPENDENTLY VERIFIED |
| Architecture/provenance-dependent current units | 8 — C07, C08, C09, C12, C13, C14, C15, C16 | NOT INDEPENDENTLY VERIFIED |
| Total of those two current-state groups | 11 selected statement units | Overlaps retained; not an independent-system or failure count. |
| Target design | 23, divided 16/7 by frozen temporal class | TARGET DESIGN |
| Parked provenance | C06 | PARKED |
| Broader all-layer deployment | C45 | NOT ESTABLISHED |
| Historical/illustrative | Six — C28, C49, C50, C51, C52, C53 | Documentary-only ESTABLISHED; three HISTORICAL, three EXAMPLE / ILLUSTRATIVE. |

C43/C44/C46/C47 and C17/C18 remain separately unresolved as recorded above; X1's conflict existence remains established. These categories are not summed into a verified/unverified balance, project percentage or global verdict. They preserve different questions and evidence boundaries while allowing Report v1 to close without resolving every claim.

### Evidence notes

- **H-1.** `synthesis/master-evidence-matrix.md`
- **H-2.** `synthesis/report-architecture.md`
- **H-3.** `reports/2026-09-18-f438819/L1-claim-map.md`
- **H-4.** `reports/2026-09-18-f438819/leads.md`
- **H-5.** `synthesis/report-sections/03-laniakea-snapshot-characterization.md`
- **H-6.** `synthesis/report-sections/08-unverified-and-target-architecture.md`
- **H-7.** `synthesis/report-sections/09-limitations-and-future-work.md`
- **H-8.** `synthesis/appendices/B-evaluation-methodology.md`
- **H-9.** `synthesis/appendices/C-l0-l3f-phase-ledger.md`
- **H-10.** `synthesis/appendices/G-c06-unresolved-provenance.md`

## Appendix I — Evidence / Checksum Index

### I.1 Purpose and reading rule

This appendix indexes already-retained evidence and its integrity records. It creates no evidence, recomputes no checksums and independently verifies no remote source. It does not certify complete raw-RPC replay or assign equal authority to every retained artifact. The master matrix and frozen body control interpretation; this index supplies traceability to the material those conclusions use.

Paths are evaluation-root-relative unless a table explicitly supplies a containing directory. **R/** below means `reports/2026-09-18-f438819/`; filenames in a directory-specific table are relative to that directory. Grouped filenames denote existing records, not proposed additions. Appendix A identifies the baseline, Appendix F interprets C05 technical evidence, and this appendix identifies what a reviewer can inspect and what retention does not support.

Integrity, provenance and interpretation are separate questions. A manifest identifies retained bytes; a retrieval log explains their acquisition; a finding explains their claim-specific significance. None substitutes automatically for the others. No checksum verification or repeat extraction was performed for this appendix.

### I.2 Accepted evidence populations

| Evidence population | Primary location | Evaluation role | Integrity record | Important retention limit |
|---|---|---|---|---|
| Baseline/pins | `pins/` | Identify subject and comparator snapshots and setup conditions. | Revision/tree files and evaluation Git lineage. | Metadata does not verify substantive claims. |
| Accepted deterministic L0 evidence | `evidence/f438819/` | Validator-run documentary inventories and candidate extraction. | `provenance.tsv`, `COMPLETE.txt`, `SHA256SUMS.txt`. | Lexical extraction requires semantic review. |
| Historical phase reports/findings | R/ and R/`findings/` | Preserve questions, evidence, results and gates at each phase. | Frozen evaluation commits; Appendix C chronology. | Prose records are not necessarily raw observations. |
| L3C retrieved provenance | R/`L3C-retrieved/` | Registry attribution, package metadata and contextual source pointers. | `transport-SHA256SUMS.txt`; R/`L3C-network-log.md`. | Manifest coverage is the listed transport artifacts, not every derivative text. |
| L3D resolved source | R/`L3D-retrieved/` | Exact component files and revision/tag responses. | `SHA256SUMS.txt`; R/`L3D-network-log.md`. | Source identity is not deployed-bytecode identity. |
| L3E static-review material | R/`L3E-retrieved/`, with L3D source files reused | Interfaces, helpers and indispensable dependencies. | Both phases' manifests; R/`L3E-network-log.md`. | Not a complete dependency-closure or integration audit. |
| L3F Mainnet evidence | R/`L3F-evidence/` | Fixed block/code/state observations and bounded logs. | `SHA256SUMS.txt`, `README.md`; R/`L3F-chain-log.md`. | Mixed normalized records and raw bodies; no complete RPC envelopes. |
| Synthesis/publication controls | `synthesis/` | Control accumulated dispositions and permitted publication wording. | Evaluation/publication Git freezes. | Report lineage is not external evidence of Laniakea claims. |

These populations have different acceptance histories. Later retrieved source files and RPC observations are not newly validator-run L0 extraction outputs. Conversely, a documentary candidate inventory does not become source or chain verification because it contains a contract name or address. The relevant finding remains necessary to connect each artifact to its scoped conclusion.

### I.3 Baseline and pin records

| Record | What it records | Reading boundary |
|---|---|---|
| `pins/baseline.md` | Baseline capture, repository identities, revisions, trees and dated metadata. | Use Appendix A for the complete manifest and separate observation dates. |
| `pins/repositories.txt` | Local subject, Atlas and STL reference locations; architecture setup/access fields. | A configured location is not a verified implementation binding. |
| `pins/laniakea-docs.sha`, `pins/laniakea-docs.tree`, `pins/laniakea-docs.branch` | Subject revision, tree and branch label. | Branch labels do not replace fixed revision identity. |
| `pins/next-gen-atlas.sha`, `pins/next-gen-atlas.tree`, `pins/next-gen-atlas.branch` | Atlas comparator revision, tree and branch label. | Governance documentary comparison still requires the scoped source witness. |
| `pins/stl.sha`, `pins/stl.tree`, `pins/stl.branch` | STL comparator revision, tree and branch label. | The pin does not establish universal implementation coverage. |

Architecture availability remains BLOCKED_FOR_ANONYMOUS_GIT_AT_SETUP, with no credentials supplied. Its revision is not inferred. The pin records establish evaluated identities and the recorded access condition, not source truth, deployment or runtime behavior. A reviewer needs the corresponding pinned content as well as the identifiers to repeat a source inspection; this index does not claim that every external resource has been reconstructed inside the evaluation repository.

### I.4 Accepted deterministic documentary evidence

The accepted collection is `evidence/f438819/`, frozen at evaluation commit `0afd81684eff791073f20f1d8d39f2d6bcc1bd60`. The following filenames are relative to that directory.

| Artifact(s) | Retained purpose | Limit |
|---|---|---|
| `provenance.tsv` | Subject location, commit, tree and branch. | Identifies extraction input, not semantic validity. |
| `COMPLETE.txt`, `RUN-STATUS.txt` | Completion and acceptance-condition markers. | COMPLETE does not mean semantic validation. |
| `SHA256SUMS.txt`, `LIMITATIONS.txt` | Listed file hashes and extraction/interpretation limits. | No new hash check is asserted here. |
| `tree.tsv`, `top_level.tsv`, `markdown_inventory.tsv` | Tracked-tree, top-level and Markdown inventories. | Corpus inventory is not exhaustive claim verification. |
| `headings.tsv`, `navigation_documents.tsv` | Heading/navigation surfaces. | Heading parsing is heuristic, not complete CommonMark interpretation. |
| `internal_links.tsv`, `external_links.tsv`, `unresolved_local_links.tsv` | Extracted links and bounded local-resolution results. | External destinations and complex anchors are not thereby validated. |
| `local_path_candidates.tsv`, `parser_review.tsv` | Candidate paths and cases needing parser/base interpretation. | Existence under one base does not establish intended reference scope. |
| `status_terms.tsv`, `current_state_candidates.tsv`, `corpus_boundary_candidates.tsv` | Lexical status/current-state/boundary queues. | Not accepted temporal classifications or canonicality judgments. |
| `atlas_refs.tsv`, `implementation_refs.tsv`, `evm_addresses.tsv`, `formula_markers.tsv` | Candidate inventories for reference and semantic review. | No authority, implementation, address-use or formula-correctness conclusion. |
| `.source.txt` | Retained scratch containing the last Markdown blob. | Not an additional independent source. |

COMPLETE states that extraction finished and subject pins/cleanliness were rechecked, with no semantic validation implied. RUN-STATUS retains an INCOMPLETE warning whose acceptance condition requires COMPLETE.txt also to exist. Read together, these records describe the helper's completion convention; neither should be interpreted in isolation as a new evaluation result.

The manifest lists retained outputs, markers, limitations, provenance and scratch content; its `./` paths are relative to this evidence directory. The manifest itself is not one of its listed payloads. This differs from later manifests whose listed paths begin at the evaluation root. A reviewer must preserve that path basis when inspecting integrity records.

Extraction scanned tracked lowercase Markdown files, including inactive/history/example material. Pattern matches can have false positives and negatives; context must be recovered by source path. Complex Markdown links, reference bases and canonical successors require human review. No inherited status propagation, documentary winner selection or network destination validation follows from the inventories. Accepted deterministic output supports reproducible candidate inspection, not automated semantic grading or a corpus-coverage percentage.

### I.5 Excluded evidence directory

`evidence/f438819-failed-01/` is **NOT accepted evidence**. It is excluded from synthesis, appendices, publication findings and this index's accepted-source population. Its name appears only to prevent accidental inclusion. Its contents were not inspected, summarized or checksummed for this appendix. No explanation of its contents or failure is inferred.

### I.6 Historical evaluation records

The accepted report root is `reports/2026-09-18-f438819/`. Its records connect artifacts to the historical questions they answered.

| Record/category | Traceability function |
|---|---|
| `Ledger.MD` | Historical phase/result record, preserving phase-local grades. |
| `leads.md` | Progression, prerequisites, stopping context and later scoped closure. |
| `L1-claim-map.md` | Selected statements, locations, temporal classifications and qualifications. |
| `L0-plan.md` and `findings/` | Documentary plan and detailed historical findings. |
| L2 through L3F phase reports | Scoped comparison, provenance, static and chain records. Appendix C indexes their chronology. |
| L3C/L3D/L3E network logs and L3F chain log | Retained acquisition/query history and execution/retention qualifications. |
| L3C/L3D/L3E retrieved directories and L3F evidence directory | Underlying retained bodies and structured records, indexed below. |

Reports can preserve source quotations, locations and context that do not exist as separate raw artifacts in the technical directories. Their Git history preserves the evaluated record; later synthesis does not overwrite an earlier result. A file's later presence in the report package does not imply that its evidence was available in every earlier phase.

### I.7 L3C external-provenance retrieval records

Within R/`L3C-retrieved/`, the retained population separates transport material from readable derivatives. R/`L3C-network-log.md` supplies retrieval context; `transport-SHA256SUMS.txt` lists ten HTML bodies and the archive below.

| Retained artifacts | Evidence role / form | Integrity and interpretation boundary |
|---|---|---|
| `02-registry.html`, `03-registry-src.html`, `02-registry-readme.txt` | Registry/repository page material and readable README text. | Listed HTML transport bodies and derivative text are distinct. |
| `06-ethereum.html`, `07-base.html`, `06-ethereum-source.txt`, `07-base-source.txt` | Registry source pages and extracted source-attribution text. | Attribution is not, by itself, owner-qualified repository resolution. |
| `04-axis.tar.gz`, `04-axis-PKG-INFO.txt`, `04-axis-pyproject.txt` | Retrieved package archive and extracted package metadata. | Archive digest is listed; package identity is not ALM implementation identity. |
| `05-psm.html`, `05-psm-readme.txt` | PSM context and readable reference material. | Context/discriminator, not substituted ALM source. |
| `08-audit.html`, `09-audit.html`, `10-audit.html` and corresponding `08-audit-source.txt`, `09-audit-source.txt`, `10-audit-source.txt` | Audit-reference pages and readable source text. | Retention of an audit reference does not confer audit coverage on this evaluation. |
| `11-registry-modules.html`, `12-psm-modules.html`, `11-registry-modules-source.txt`, `12-psm-modules-source.txt` | Additional module/reference context. | Interpret with the retrieval report rather than as independent implementation proof. |
| Numbered `.headers` files retained in this directory | Transport-header records for the recorded requests. | Their presence does not extend the transport manifest to every retained file. |

The source-text views decode embedded source lines; README views strip rendered HTML and add provenance context. Their line references therefore belong to the retained derivative identified by the finding. The retrieval log records server-supplied HTTP Date values, not independently verified request-start timestamps. Mutable branch URLs are bounded by saved bodies and recorded page revisions; L3C did not independently verify those repositories' Git objects or release histories.

The frozen L3C report records an archive match to the previously recorded package checksum. That historical check is not repeated here. Transport integrity does not establish semantic correctness, completeness of external retrieval or the implementation identity under test. L3C's source-attribution progress and remaining uncertainty are interpreted in Appendix E.

### I.8 L3D repository/source-resolution records

R/`L3D-retrieved/` holds four resolved source bodies and six commit/tag response files, with `SHA256SUMS.txt`. The associated retrieval log is R/`L3D-network-log.md`.

| Exact retained filename | Source-resolution object |
|---|---|
| `MainnetController-984ec54.sol` | MainnetController historical source. |
| `ForeignController-7be9593.sol` | ForeignController historical source. |
| `ALMProxy-6058f68.sol` | Proxy historical source. |
| `RateLimits-6058f68.sol` | RateLimits historical source. |
| `commit-984ec54.json`, `commit-7be9593.json`, `commit-6058f68.json` | Retained revision metadata responses. |
| `tag-v1.10.0.json`, `tag-v1.8.0.json`, `tag-v1.0.0.json` | Retained version-tag responses. |

The resolved repository is sparkdotfi/spark-alm-controller. Appendix E supplies the exact original file/revision mapping; Appendix F uses those identities for technical interpretation. These are mixed historical component revisions, not one atomic release. A checksum identifies retained file content relative to the manifest, not a deployment date or proof that this source produced an observed runtime. No build-equivalence conclusion is added by indexing these bodies.

### I.9 L3E static-review evidence

The Controller, proxy and RateLimits source bodies remained in L3D-retrieved; L3E did not require a duplicate source set. Its report records historical verification against the L3D manifest. R/`L3E-retrieved/` adds the following material under its own `SHA256SUMS.txt` and R/`L3E-network-log.md`.

| Category | Exact retained filenames |
|---|---|
| Proxy interfaces | `IALMProxy-6058f68.sol`, `IALMProxy-7be9593.sol`, `IALMProxy-984ec54.sol` |
| RateLimits interfaces | `IRateLimits-6058f68.sol`, `IRateLimits-7be9593.sol`, `IRateLimits-984ec54.sol` |
| Key helpers | `RateLimitHelpers-7be9593.sol`, `RateLimitHelpers-984ec54.sol` |
| Dependency pin responses | `openzeppelin-pin-6058f68.json`, `openzeppelin-pin-7be9593.json`, `openzeppelin-pin-984ec54.json` |
| Indispensable dependency sources | `OZ-Address.sol`, `OZ-AccessControl.sol`, `OZ-AccessControlEnumerable.sol`, `OZ-ReentrancyGuard.sol`, `OZ-Context.sol` |

The sixteen bodies comprise six interfaces, two helpers, three metadata responses and five dependency sources. The phase report binds the OpenZeppelin material to revision `dbb6104ce834628e473d2173bbc9d47f81a9eec3` through the parent gitlinks. This index does not independently repeat that binding. Retaining the indispensable inspected dependencies does not claim complete integration or dependency-closure coverage. Appendix F explains the source behavior and its deployment/bytecode limits.

### I.10 L3F Mainnet evidence index

All filenames below are relative to R/`L3F-evidence/`. Its README supplies schemas; `SHA256SUMS.txt` covers every evidence file except itself. H denotes block 25,242,585; C denotes block 26,007,670. “Current” filenames refer to that fixed later observation, not publication time.

| Artifact / category | Evidence role | Raw / normalized | Integrity reference | Key limitation |
|---|---|---|---|---|
| `README.md` | Schemas and retention qualifications. | Explanatory record. | Directory manifest. | Must accompany interpretation of tables. |
| `address-provenance.tsv` | Documentary target/candidate identity before requests. | Prepared provenance table. | Directory manifest. | “Untested” records pre-query state, not eventual result. |
| `baseline-historical.txt`, `baseline-current.txt` | Selected block identity, timestamps, chain ID and hash rechecks. | Normalized fields. | Directory manifest. | Not full initial block responses. |
| `timestamp-search.tsv` | Twenty-five ordered block/timestamp search responses. | Normalized table. | Directory manifest. | Timestamp search, not twenty-five complete state observations. |
| `code-historical.tsv`, `code-current.tsv` | Address/block, length, runtime keccak and endpoint comparison. | Normalized tables. | Directory manifest. | Hash equality is endpoint-specific. |
| Eight `runtime-*.hex` files | Returned code for R, A, P and L at H/C. | Direct code bodies. | Exact filenames in manifest. | No complete transport envelope or source build. |
| `proxy-historical-runtime.hex` | Initial archive-availability code response. | Direct body. | Directory manifest. | Deliberately retained duplicate of later proxy/H code request. |
| `wiring-historical.tsv`, `wiring-current.tsv` | Candidate getter returns for component references. | Normalized tables. | Directory manifest. | Fixed-block wiring, not continuous history. |
| `roles-historical.tsv`, `roles-current.tsv` | Role identifiers, grant checks and member-count results. | Normalized tables. | Directory manifest. | Failed alternative count calls are not zero counts. |
| `key-getters-historical.tsv`, `key-getters-current.tsv` | Returned source-defined mint key. | Normalized tables. | Directory manifest. | One named key, not a complete key inventory. |
| `ratelimits-historical.tsv`, `ratelimits-current.tsv` | Exact maxAmount/slope/lastAmount/lastUpdated fields. | Normalized raw-value tuples. | Directory manifest. | lastAmount is stored capacity, not recomputed available capacity or token balance. |
| `usage-mint-25242585.json`, `usage-mint-26007670.json` | Full returned bounded consumption-log bodies. | Direct JSON bodies. | Directory manifest. | Despite filenames, include other keys. |
| `usage-historical.tsv`, `usage-current.tsv` | Accepted exact mint-key filtered rows. | Derived normalized tables. | Directory manifest. | Component events, not attributed Controller calls. |
| `usage-otc-25242585.json`, `usage-otc-26007670.json` | Bounded Controller OTC-event query returns. | Direct JSON bodies; empty arrays. | Directory manifest. | Zero matches do not establish no use. |
| `SHA256SUMS.txt` | Retained evidence-file digest inventory. | Integrity record. | Frozen Git lineage; excludes itself. | No semantic or provider certification. |

The manifest gives the full address-bearing runtime filenames, avoiding a second deployment inventory here. R/A/P/L are defined in the retained chain log as the tested registry Controller, Atlas alternative, ALMProxy and RateLimits. Appendix F is the location for their exact addresses and technical interpretation.

The chain log preserves the accepted filtering correction: the original signature omitted the indexed-key declaration, so returned bodies included multiple keys. Raw bodies remained unchanged; exact local `topics[1]` filtering produced the accepted tables. The retained counts are 390/391 returned events and 67/122 selected events over the two 7,200-block windows. These figures are transcribed from the frozen record, not recalculated here. They identify the raw-to-derived relationship, not Controller attribution, token transfers or complete transaction paths.

### I.11 Raw and normalized retention

The L3F README and chain log distinguish normalized TXT/TSV transcriptions from directly retained code/log bodies. A raw uint256 tuple in a normalized table preserves returned values; it is not a raw RPC envelope. Likewise, a JSON log body does not establish that request headers, transport metadata and every surrounding response were retained.

Complete raw RPC envelopes were not retained. Initial full block responses were not retained; selected identifying fields and final hash rechecks were recorded. Per-request wall-clock timestamps were not separately captured. Recorded baseline UTC values are chain timestamps. The historical successor supplies timestamp-bracketing metadata, not a third complete state observation.

The sanitized chain log retains invocation templates and result descriptions, without endpoint values or secrets. Suppressed transport errors do not support a retrospective failure diagnosis. Failed alternative-Controller role-count calls remain unknown, not empty membership. No transaction trace or receipt-expansion evidence is supplied by the retained consumption logs. These are specific retention limits of this evidence set, not assumptions about every evaluation artifact.

### I.12 Checksum and integrity model

| Identifier type | Object identified | What it cannot establish alone |
|---|---|---|
| Git revision/tree identifiers | Source snapshots or evaluation/publication history. | External claim truth, deployment or governance enactment. |
| SHA-256 manifest entries | Retained file content relative to a listed digest. | Semantic correctness, canonicality, remote availability or service correctness. |
| Runtime keccak256 | Observed deployed bytecode body at a fixed chain observation. | Exact source-build equivalence or unchanged code throughout an interval. |

A reviewer can compare retained bytes with a manifest to assess consistency with that record. This appendix identifies the existing manifests; it does not report a new comparison. Manifest integrity is not a cryptographic chain-state proof or independent-provider replication. Transport checksums also do not resolve the distinction between useful documentary attribution and exact implementation identity.

### I.13 What can and cannot be reproduced

| From retained material, a reviewer can | The package does not promise |
|---|---|
| Identify pins and locate phase records. | Complete reconstruction of every external resource. |
| Inspect resolved source bodies, interfaces and retained dependencies. | Exact source/runtime build equivalence or comprehensive code audit. |
| Verify file hashes against existing manifests. | Independent authenticity of every remote service response. |
| Inspect normalized tables and retained code/log bodies. | Complete raw-RPC replay, cryptographic state proofs or independent-provider replication. |
| Follow the recorded raw/filtered event relationship and its limitations. | Caller attribution, token-transfer proof or complete transaction paths. |
| Reproduce deterministic extraction where retained inputs/tools permit. | Semantic completeness without human review. |
| Inspect fixed observation identities and returned state. | Publication-time state, continuous chain history or complete migration history. |

Reproduction remains conditional on available inputs and suitable tools. This index neither executes them nor supplies authorization for new retrieval or chain testing. An unavailable raw envelope cannot be recovered merely by having a command template; a later repeat request would be a separate observation, not the original response.

### I.14 Evaluation and publication freeze provenance

| Freeze | Exact evaluation-repository commit | Role |
|---|---|---|
| Technical/evidence anchor | `8064df6464967ab53a46c07b82f210a069f655e3` | Completed L0–L3F record through C05 Mainnet binding. |
| Master matrix | `325f96ac847314b508887719c36dae805bb28a04` | Accumulated dispositions and publication controls. |
| Report architecture | `5101fc438626d27ae124b733dd46317493507ace` | Main-body and appendix allocation. |
| Main narrative through Executive Summary | `102858626092f5282fd43f396c8a911e331ae635` | Completed narrative freeze. |
| P1 | `676b6246ff47e89be18a75651c5b62ea6e4cf869` | Appendix architecture and A/B. |
| P2 | `bec6ce665a3a2351dd5d3b4cf93a75f9ab2afd94` | Appendices C/D. |
| P3 | `879b3d5dd87376cfeb1f8d1ecc4e9dc48e62d904` | Appendices E/F. |
| P4 | `cffd90f137be0abaf74e0cd87702197a0f148b32` | Appendices G/H; lineage through P4 before I/J drafting. |

These commits establish evaluation/report lineage, not external Laniakea claims. Appendix A retains the earlier detailed historical and publication lineage. Later appendix freezes add traceability without replacing the technical anchor or retroactively changing phase results. This table records publication lineage through P4, before I/J drafting. The publication front matter identifies the later P5 baseline; evaluation-repository publication history records subsequent assembly freezes.

### I.15 Index limitations

This index is not exhaustive proof of every evaluated fact. Contextual evidence also lives in reports/findings, and artifact presence does not establish proposition truth. No new checksum verification, extraction or external reconstruction is asserted. Excluded evidence remains excluded. Evidence notes retain exact paths; the frozen evidence ceilings remain controlling.

### Evidence notes

- **I-1.** `pins/baseline.md`
- **I-2.** `pins/repositories.txt`
- **I-3.** `evidence/f438819/provenance.tsv`
- **I-4.** `evidence/f438819/COMPLETE.txt`
- **I-5.** `evidence/f438819/SHA256SUMS.txt`
- **I-6.** `evidence/f438819/LIMITATIONS.txt`
- **I-7.** `reports/2026-09-18-f438819/Ledger.MD`
- **I-8.** `reports/2026-09-18-f438819/L3C-network-log.md`
- **I-9.** `reports/2026-09-18-f438819/L3C-retrieved/transport-SHA256SUMS.txt`
- **I-10.** `reports/2026-09-18-f438819/L3D-network-log.md`
- **I-11.** `reports/2026-09-18-f438819/L3D-retrieved/SHA256SUMS.txt`
- **I-12.** `reports/2026-09-18-f438819/L3E-C05-static-binding.md`
- **I-13.** `reports/2026-09-18-f438819/L3E-network-log.md`
- **I-14.** `reports/2026-09-18-f438819/L3E-retrieved/SHA256SUMS.txt`
- **I-15.** `reports/2026-09-18-f438819/L3F-evidence/SHA256SUMS.txt`
- **I-16.** `reports/2026-09-18-f438819/L3F-evidence/README.md`
- **I-17.** `reports/2026-09-18-f438819/L3F-chain-log.md`
- **I-18.** `synthesis/master-evidence-matrix.md`
- **I-19.** `synthesis/appendices/A-baseline-manifest.md`
- **I-20.** `synthesis/appendices/F-c05-case-study.md`

## Appendix J — Terminology Crosswalk

### J.1 Purpose and reading rule

The evaluation uses several vocabularies for different objects: historical grades/results, workflow gates, original temporal classifications, normalized reporting classes and final synthesis dispositions. They are not interchangeable. This appendix consolidates their frozen meanings without introducing a grading system, changing a claim classification or assigning a global project verdict.

One claim can legitimately carry several labels. C06 has a historical NOT ESTABLISHED result, access-specific architecture BLOCKED, chain gate HOLD and final synthesis PARKED. Those labels concern a proposition, an evidence-access condition, a prerequisite and a publication disposition. Their coexistence is not a contradiction.

Read each term with its object, scope, phase and date. The master matrix controls final dispositions; historical records retain their original results. Appendix B explains the method, Appendix H applies statuses to populations, and this appendix supplies the consolidated lookup. A definition cannot supply evidence missing from a claim row or resolve disputed Guardian, executor or genesis mappings by terminology alone.

### J.2 Historical evaluation grades and result terms

The charter lists the following seven terms under Grades. They have differing functions even within that list: an invariant result, evidentiary insufficiency and inaccessible evidence are not identical kinds of judgment. Later phases apply the vocabulary to their named source/provenance/static/chain questions, with the scope qualification retained.

| Term | Historical function | What it does NOT mean | Example |
|---|---|---|---|
| PASS | The pre-stated invariant is established at the pinned snapshots. | Universal correctness, completeness or project approval. | L0-05 candidate inventories; L3E scoped static binding. |
| WARN | Invariant at risk, ambiguous, incompletely documented or materially stale without direct contradiction sufficient for FAIL. | Proven falsehood or an implementation defect. | L0-01 slideshow scope/status. |
| FAIL | The pre-stated invariant is directly refuted. | Automatic final overall failure of the claim or project. | L2-04 tested fee-policy invariant. |
| INFO | Material observation that does not violate an invariant. | A weaker PASS or independent truth certification. | Charter-defined observation category; no new finding is assigned here. |
| NOT ESTABLISHED | Available evidence is insufficient to decide the tested proposition or mapping. | Falsehood, nonexistence or proven nondeployment. | L2-02/C02 exact organizational mapping; L3B C06 identity. |
| BLOCKED | Required evidence is inaccessible; the affected object must be named. | A substantive negative verdict about the whole claim. | Architecture access under the recorded setup. |
| DEVIATION | Intentional divergence worth recording separately. | Intent inferred from inconsistency, silence or persistence. | Charter-defined category; no intentional divergence is newly assigned. |

The examples locate usage rather than create additional grades. A selected L1 unit that was classified but not individually graded does not inherit the phase's aggregate results. Likewise, a parent finding does not automatically grade each associated contextual record. INFO and DEVIATION remain defined vocabulary without requiring an invented example finding.

Related evidence terms retain the charter's distinctions: SOURCE-VERIFIED FACT is directly supported by a pinned path/location; DETERMINISTIC EVIDENCE is accepted validator-run helper output; CLAIM identifies an asserted proposition; INFERENCE derives from named facts. Source-verified wording is not automatic verification of the asserted runtime truth. The matrix also preserves L3F's RPC-OBSERVED FACT / collected evidence usage, subject to the retention limits indexed in Appendix I.

### J.3 Workflow and gate states

| Term / recorded usage | Object and meaning | Boundary |
|---|---|---|
| HOLD | Further verification awaits documentary, source or other prerequisites. | Workflow gate, not charter FAIL and not a negative deployment result. |
| BLOCKED, when attached to access | Required evidence cannot be accessed under the recorded conditions. | Does not establish the inaccessible source's contents. |
| CHAIN GATE ELIGIBLE | Historical L3E recommendation that the basis exists for separately authorized component/address and chain work. | Eligibility is not authorization or proof of deployment. |
| NOT OPENED / NOT TESTED | A review or test was not performed for the named object. | Not a performed test returning a negative result. |
| CLOSED | C05's scoped Report v1 conclusion is complete. | Not exhaustive verification of every related implementation or history question. |

The same word BLOCKED appears in charter grades, evidence vocabulary and access descriptions. Its meaning depends on the named object, not its capitalization. Architecture BLOCKED cannot replace C06's substantive NOT ESTABLISHED identity result. HOLD similarly records why a next test did not proceed, rather than assigning a result to an unperformed test.

These are retained usages, not a new mandatory workflow. “Stop” is ordinary descriptive language, not a formal STOP grade. PARKED belongs to synthesis below; the matrix does not assign PARKED or WAIT as historical repository grades. Later publication definitions do not retrospectively authorize earlier retrieval or chain work.

### J.4 Original charter / pre-stated temporal classes

The charter and `expected/L1.md` use ten classes. They classify the source's asserted scope or framing before truth testing; none independently establishes the claim.

| Original class | Asserted temporal/source scope |
|---|---|
| CURRENT-GOVERNANCE | Current governance. |
| CURRENT-IMPLEMENTATION | Existing implementation. |
| CURRENT-DEPLOYED | Current deployment. |
| CURRENT-OPERATIONAL | Ongoing operation or use. |
| PROPOSED | Proposed rather than established current scope. |
| TARGET-ARCHITECTURE | Intended architectural arrangement. |
| ROADMAP | Future or phase-dependent scope. |
| CONCEPTUAL | Conceptual/specification framing. |
| DEPRECATED/HISTORICAL | Deprecated or historical material. |
| AMBIGUOUS | Insufficiently clear temporal/scope interpretation. |

The charter protects proposed, roadmap, target and conceptual statements from implementation-failure grading merely because they are not implemented today. That protection does not establish feasibility, design soundness or adoption. Conversely, explicit present-state assertions remain testable against appropriate evidence. Ambiguity must not be silently interpreted in the harsher direction or resolved by selecting a convenient account.

### J.5 Frozen L1 reporting classes

The claim map records eight normalized reporting classes. This reporting vocabulary did not amend the charter or pre-stated invariants and is not an independent substantive result.

| Reporting class | Frozen reading |
|---|---|
| CURRENT-GOVERNANCE | Source-local assertion about current governance or governance documentation. |
| CURRENT-IMPLEMENTATION | Assertion of existing implementation; bare deployment-existence wording is included with deployment explicitly noted. |
| CURRENT-OPERATIONAL | Assertion of ongoing operation, use or operational configuration. |
| PROPOSED-TARGET | Proposed, target or conceptual/specification material with its qualifications preserved. |
| FUTURE-ROADMAP | Roadmap, unscheduled or far-future scope. |
| HISTORICAL | Historical/deprecated documentary framing, not current authority. |
| EXAMPLE / ILLUSTRATIVE | Worked example, sketch or hypothetical prerequisite. |
| AMBIGUOUS | Wording does not establish clear current/future or implementation/activation scope. |

Source-local classification does not select a documentary winner. C17/C18 retain local CURRENT-OPERATIONAL assertions while the combined X1 account remains AMBIGUOUS. A running-instance assertion and an illustrative pattern can also be separate selected units: C09 and C52 are not forced into a single class. Context and proposition boundaries govern the distinction.

### J.6 Original-to-reporting temporal crosswalk

This table reproduces the conversion stated in the L1 claim map's Classification and evidence rules and carried into matrix §1. The contextual rows describe the recorded reporting rule, not a deterministic conversion of every sentence bearing a particular word.

| Original class or source framing | Frozen reporting class | Qualification retained |
|---|---|---|
| CURRENT-GOVERNANCE | CURRENT-GOVERNANCE | Current authority/documentary assertion, not proof of enactment. |
| CURRENT-IMPLEMENTATION | CURRENT-IMPLEMENTATION | Existing-source/implementation assertion remains unverified until tested. |
| CURRENT-DEPLOYED: bare deployment-existence assertion | CURRENT-IMPLEMENTATION, deployment explicitly noted | Does not equate code existence with deployment. |
| Ongoing use assertion, including deployed-and-operating wording | CURRENT-OPERATIONAL | Operational assertion classified by its substance. |
| CURRENT-OPERATIONAL | CURRENT-OPERATIONAL | Source-local ongoing state/use qualification preserved. |
| PROPOSED | PROPOSED-TARGET | Proposed scope remains explicit. |
| TARGET-ARCHITECTURE | PROPOSED-TARGET | Target architecture remains distinct from a current implementation. |
| CONCEPTUAL / conceptual-specification material | PROPOSED-TARGET where applicable | Context preserves conceptual versus prospective meaning. |
| ROADMAP | FUTURE-ROADMAP | Timing, phase dependencies and unscheduled scope retained. |
| DEPRECATED/HISTORICAL | HISTORICAL | Does not promote old material to active authority. |
| Hypothetical worked examples, sketches or user-story prerequisites | EXAMPLE / ILLUSTRATIVE where recorded | Contextual reporting class, not an additional original charter class. |
| AMBIGUOUS | AMBIGUOUS | Unresolved scope preserved rather than guessed. |

Conceptual/specification framing and a hypothetical worked example need not receive identical treatment. The claim map records which proposition was selected and its local qualification. No one-to-one rule is invented for every possible conceptual passage. Similarly, a deployment statement that also asserts ongoing use must preserve that operational question rather than disappear into a source-existence label.

This crosswalk describes reporting normalization, not synthesis. PROPOSED-TARGET and FUTURE-ROADMAP remain temporal classes even where both receive final TARGET DESIGN. CURRENT-IMPLEMENTATION is likewise not a synonym for ESTABLISHED. The source's tense, evaluation of its truth and final publication characterization remain separate columns.

### J.7 Final synthesis dispositions

Exactly seven dispositions summarize what accumulated evidence permits publication to say. They are subordinate to each matrix row's proposition and ceiling, not conversions from historical grades by a scoring rule.

| Disposition | Publication meaning | What it does NOT mean | Example |
|---|---|---|---|
| ESTABLISHED | The explicitly scoped conclusion/evidence relationship is supported. | Unstated universal implementation or runtime truth. | C01 documentary presence; scoped C05 accumulated conclusion. |
| PARTIALLY ESTABLISHED | Identified support coexists with material unresolved or inconsistent dimensions. | Historical FAIL erased or full equivalence established. | C04 fee-policy comparison. |
| NOT ESTABLISHED | Accumulated evaluation does not establish the scoped proposition or mapping. | Falsehood or absence. | C02/C03 exact mappings; C45 broader deployment. |
| TARGET DESIGN | Proposed, conceptual, target or future/roadmap scope. | Failed current implementation or demonstrated feasibility. | The 23 target-design units in Appendix H. |
| NOT INDEPENDENTLY VERIFIED | Source assertion preserved; independent substantive verification deferred, blocked or not undertaken. | Failed implementation. | C10/C11/C39 and eight architecture/provenance-dependent units. |
| OUT OF SCOPE | Broader truth test lies outside completed substantive verification. | Negative finding or authority to relabel an evaluated unresolved claim. | All-layer PAU deployment lies outside C05; C45 nevertheless has NOT ESTABLISHED disposition. |
| PARKED | Further verification set aside pending qualifying evidence/lead. | Historical grade or permanent closure. | C06. |

An example can illustrate a boundary without assigning that disposition to an entire row: OUTSIDE C05 is not C45's final status. The matrix's actual disposition must be retained. “Established” always needs its object: documentary framing, a discrepancy and bounded implementation/chain grounding have different evidentiary content.

### J.8 Why multiple labels can coexist

| Item | Historical labels | Final synthesis / publication state | Why both remain valid |
|---|---|---|---|
| C04 | L2-04 FAIL within shared Prime scope. | PARTIALLY ESTABLISHED. | The tested invariant encountered material discrepancy; accumulated support also includes supported and unresolved dimensions. |
| C05 | L3A NO MATCHED STL COVERAGE ESTABLISHED; L3B/L3C NOT ESTABLISHED; L3D source PASS, L3E static PASS, L3F scoped Mainnet PASS. | ESTABLISHED scoped conclusion; CLOSED for Report v1. | Coverage, provenance, static behavior and fixed chain observations answered successive distinct questions. |
| C06 | Identity NOT ESTABLISHED; architecture access BLOCKED where applicable; chain HOLD. | PARKED. | Substantive insufficiency, access, prerequisite and disposition have different objects. |
| X1 | L1-01/L1-02/L1-04 conflict-related FAILs. | Documentary conflict ESTABLISHED; actual operating truth and intended winner NOT ESTABLISHED. | Establishing disagreement does not identify the operating account. |

Later synthesis does not “correct” these earlier results. L3D source resolution cannot create a matched STL implementation result retroactively; L3F cannot make deployment established at the end of L3E. C04's supported annual-rate and general-rebate dimensions do not remove its historical tested mechanics discrepancy. Dates and tested invariants remain part of each historical label.

The X1 FAILs concern the same documentary conflict under different invariants, not three independent implementation failures. Neither the conflict's existence nor C19's target classification chooses the intended documentary winner. These coexistence examples explain the frozen record; they introduce no new truth test.

### J.9 NOT ESTABLISHED versus NOT INDEPENDENTLY VERIFIED

For final synthesis, NOT ESTABLISHED records an evaluated scoped truth/mapping question whose support remained insufficient. NOT INDEPENDENTLY VERIFIED preserves a source assertion whose independent substantive verification was deferred or not completed. Both preserve uncertainty; neither means failure or falsehood. Historical NOT ESTABLISHED retains the broader charter meaning of insufficient evidence and should not be mechanically converted into a final disposition.

| Treatment | Relevant examples | Reason for separation |
|---|---|---|
| NOT ESTABLISHED | C02/C03; C45; C46/C47; C17/C18 | Exact mapping, broader deployment, completion/activation or documentary conflict was evaluated enough to retain a substantive unresolved status. |
| Underlying provenance NOT ESTABLISHED, final PARKED | C06 | Historical identity result remains distinct from synthesis's decision to defer further work. |
| NOT INDEPENDENTLY VERIFIED | C07, C08, C09, C12, C13, C14, C15, C16 | Architecture/provenance-dependent current assertions without completed independent verification. |
| NOT INDEPENDENTLY VERIFIED | C10, C11, C39 | Deferred operational verification. |

The last two groups comprise eleven selected units, not eleven independent systems or failures. C11 payment realization remains separate from C04 documentary policy. C45's final NOT ESTABLISHED corrected an earlier synthesis OUT OF SCOPE characterization; it did not rewrite a historical test. These row-specific distinctions prevent a blanket relabeling of all unknowns.

### J.10 TARGET DESIGN versus OUT OF SCOPE

TARGET DESIGN preserves a proposition's future/proposed character in synthesis. OUT OF SCOPE describes a truth test outside a completed evaluation boundary. Classification of a target can be completed without testing its feasibility or implementation. Those unperformed tests do not turn the target into a failed current claim or require replacing its disposition with OUT OF SCOPE.

Object specificity also matters for existing-state claims. All-layer PAU deployment is OUTSIDE C05, while C45's broader claim remains NOT ESTABLISHED. The successful scoped C05 case cannot establish every layer; the boundary of that case cannot erase the separate unresolved C45 row. Neither term is a global project exclusion or negative grade.

### J.11 Temporal class and disposition can coexist

| Unit | Temporal class + disposition | Established object | Separate ceiling |
|---|---|---|---|
| C28 | HISTORICAL + ESTABLISHED | Documentary terminology retirement. | Implemented migration not established. |
| C50 | EXAMPLE / ILLUSTRATIVE + ESTABLISHED | User-story deployment/admin-grant prerequisites. | Actual deployment or grants not established. |
| C52 | EXAMPLE / ILLUSTRATIVE + ESTABLISHED | Noncanonical illustrative realization. | C09's separate runtime assertion remains NOT INDEPENDENTLY VERIFIED. |

Historical and illustrative describe the selected passage's framing; ESTABLISHED identifies the supported documentary proposition. Neither pairing implies current deployment. Nor does the absence of runtime proof downgrade the documentary conclusion: the evaluation can establish what a passage says without establishing that the described operation occurred. Appendix H preserves the full six-unit historical/illustrative population.

### J.12 Closure and future-work terms

| Term | Frozen use | Boundary |
|---|---|---|
| CLOSED | C05's scoped Report v1 conclusion is complete. | Remaining limitations alone do not make it provisional. |
| OPTIONAL ASSURANCE | Exact C05 source/runtime bytecode reproduction. | Sole frozen item in this category; not required for closure or publication. |
| REOPEN ON QUALIFYING NEW EVIDENCE | Reconsider a specified unresolved question when its evidence condition is met. | Not mandatory remediation or perpetual searching. |
| DELTA-EVALUATE | Evaluate a later project change against the frozen snapshot. | Later repair does not erase the historical finding. |

C06 remains PARKED, not CLOSED, and may reopen on qualifying provenance: explicit legacy attribution, a dated legacy-to-PAS source connection, a verified-source artifact covering required components or equivalent qualifying evidence. Names/addresses alone do not meet that threshold. This is distinct from optional assurance for an already closed C05 conclusion.

New evidence about an old snapshot and an actual later project change answer different questions. Limited C05 attribution or history subquestions can be revisited without globally reopening C05; reopening its closed conclusion requires evidence capable of materially changing its basis. The frozen future-work model does not create a priority list or require resolution of every uncertainty. These are publication/workflow concepts, not grades.

### J.13 Non-equivalences

| Terms that must remain distinct | Why |
|---|---|
| NOT ESTABLISHED ≠ false | Insufficient support is not refutation. |
| NOT INDEPENDENTLY VERIFIED ≠ failed | Deferred verification is not an adverse test result. |
| TARGET DESIGN ≠ failed implementation | Future scope is protected from present-implementation assumptions. |
| OUT OF SCOPE ≠ negative finding | Test boundary is not substantive rejection. |
| PARKED ≠ historical grade; PARKED ≠ permanent closure | Synthesis defers work pending evidence. |
| HOLD ≠ FAIL | A prerequisite gate does not grade an unperformed test. |
| BLOCKED ≠ substantive claim verdict | The inaccessible object must be identified. |
| Documentary ESTABLISHED ≠ runtime ESTABLISHED | Evidence supports different propositions. |
| Fixed observation ≠ continuity | A block-specific response does not describe the entire interval. |
| Deployment ≠ active use | Code presence and activity are different questions. |
| Event ≠ caller attribution | RateLimits consumption events do not identify the tested Controller as caller. |
| Source identity ≠ deployed bytecode identity | Identified revisions do not establish exact build equivalence. |
| Same endpoint hash ≠ continuously unchanged code | Endpoint equality leaves intermediate history unestablished. |
| Historical FAIL ≠ final overall FAIL | An invariant result does not determine every accumulated claim dimension. |

These distinctions constrain wording rather than add uncertainty to already supported scoped conclusions. C05 remains CLOSED, and C01's documentary presence remains ESTABLISHED. Keeping evidence objects separate preserves the positive results as well as their limits.

### J.14 Consolidated terminology crosswalk

This lookup groups terms by function. Detailed definitions and claim-specific examples above remain controlling; coexistence always requires separately named objects.

| Family | Term | Object classified | Can coexist with | Must not be read as |
|---|---|---|---|---|
| Historical evaluation | PASS / WARN / FAIL / INFO | Phase-local invariant or observation. | A distinct final disposition. | Global project grade. |
| Historical evaluation | NOT ESTABLISHED | Insufficient phase-local evidence. | Later scoped support or PARKED. | Falsehood or erased history. |
| Historical evaluation | BLOCKED / DEVIATION | Inaccessible evidence / separately supported intentional divergence. | Other object-specific results. | Generic failure / inferred intent. |
| Workflow/gate | HOLD | Unmet prerequisite. | NOT ESTABLISHED and PARKED. | FAIL. |
| Workflow/gate | CHAIN GATE ELIGIBLE | Readiness recommendation. | Deployment still NOT ESTABLISHED at that stage. | Permission or deployment proof. |
| Workflow/gate | NOT OPENED / NOT TESTED | Review/test activity. | Unresolved claim disposition. | Negative test outcome. |
| Temporal classification | Original ten classes in J.4 | Source's asserted current/proposed/historical/ambiguous scope. | Later substantive results. | Truth verification. |
| Reporting classification | Eight classes in J.5, mapped in J.6 | Normalized selected-statement framing. | Any appropriate scoped synthesis disposition. | New charter or grade. |
| Synthesis disposition | ESTABLISHED / PARTIALLY ESTABLISHED | Supported scope / mixed support and limits. | Historical FAIL on a different tested invariant. | Universal approval. |
| Synthesis disposition | NOT ESTABLISHED / NOT INDEPENDENTLY VERIFIED | Evaluated insufficiency / uncompleted independent verification. | Current-state source classification. | False / failed. |
| Synthesis disposition | TARGET DESIGN / OUT OF SCOPE | Future proposition / completed-test boundary. | Temporal qualifiers or separate claim questions. | Missing-implementation defect. |
| Synthesis disposition | PARKED | Deferred verification pending qualifying evidence. | Historical NOT ESTABLISHED, access BLOCKED, gate HOLD. | Permanent closure. |
| Publication/future-work | CLOSED / OPTIONAL ASSURANCE | Complete scoped conclusion / nonrequired additional assurance. | Exact bytecode equivalence NOT ESTABLISHED. | Provisional C05 closure. |
| Publication/future-work | REOPEN ON QUALIFYING NEW EVIDENCE / DELTA-EVALUATE | New evidence about a question / changed project state. | Preserved historical results. | Mandatory backlog or retroactive erasure. |

### J.15 Terminology limitations

Vocabulary evolved from the charter to normalized reporting; historical records retain their original labels. Synthesis does not rewrite those labels or supply a mathematical conversion between grades and dispositions. Exact meaning depends on the status object's column, phase and scope. No global project grade or numerical confidence score exists. Historical documentary-reading confidence must not be promoted into confidence in implementation truth. Disputed authority terminology remains unresolved where the evidence does not establish its mapping.

### Evidence notes

- **J-1.** `EVAL-CHARTER.md`
- **J-2.** `expected/L0.md`
- **J-3.** `expected/L1.md`
- **J-4.** `reports/2026-09-18-f438819/L1-claim-map.md`
- **J-5.** `reports/2026-09-18-f438819/Ledger.MD`
- **J-6.** `reports/2026-09-18-f438819/leads.md`
- **J-7.** `synthesis/master-evidence-matrix.md`
- **J-8.** `synthesis/report-sections/02-scope-baseline-methodology.md`
- **J-9.** `synthesis/report-sections/03-laniakea-snapshot-characterization.md`
- **J-10.** `synthesis/report-sections/08-unverified-and-target-architecture.md`
- **J-11.** `synthesis/report-sections/09-limitations-and-future-work.md`
- **J-12.** `synthesis/appendices/B-evaluation-methodology.md`
- **J-13.** `synthesis/appendices/C-l0-l3f-phase-ledger.md`
- **J-14.** `synthesis/appendices/H-unverified-out-of-scope-deferred-claims.md`
