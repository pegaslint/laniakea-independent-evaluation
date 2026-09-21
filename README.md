# Laniakea Independent Evaluation — Public Release Package

## 1. What this package is

This is a sanitized, history-free public release package derived from a private validator workspace. It supports the independent human-validator-led 2026 snapshot evaluation of selected Laniakea claims. The scope is selected-claim and non-exhaustive.

The canonical report remains the controlling publication. The public matrix and selected normalized records provide additional traceability within its evidence ceilings.

## 2. What this package is not

This package is not the private validator repository, a security audit, implementation certification or runtime certification. It is not a complete reproduction of every acquisition request or a release of every retained working artifact. It supplies no project-wide grade or endorsement.

## 3. Snapshot and revision basis

The identifiers below are transcribed from the frozen evaluation/publication record. They are plain-text evidence identifiers, not distributed Git history.

| Object | Frozen identifier |
|---|---|
| Canonical technical/evidence anchor | `8064df6464967ab53a46c07b82f210a069f655e3` |
| Canonical publication report freeze | `a632c4cfc1e50b3b51ba5878e9c6f69c31c5b12b` |
| Evaluated Laniakea — `sky-ecosystem/laniakea-docs` | `f4388196198df3435b38357bc7f1fccc1c5a1317` |
| Atlas — `sky-ecosystem/next-gen-atlas` | `4c466eb1c9508abea08412f43011dfd40e1cfb82` |
| STL — `archon-research/stl` | `37e56db072f9f246fc2f77ed3036e4a8e732aaf7` |

These identify distinct frozen source revisions, not a simultaneous observation of every source. Appendix A in the full report provides the baseline detail. The content-final Forum brief is a later derivative; the publication freeze identifier above does not claim that the Forum brief was committed in that freeze.

## 4. Full report

Read [the canonical full report](synthesis/publication/full-report-final.md).

It contains the main report, Appendices A–J, evidence notes, the evidence/checksum index and the terminology crosswalk. Its evidence notes retain original repository-relative paths. Only paths listed as included in the public manifest are distributed here. Other references identify private retained records or external frozen-source material; their presence in the report does not mean every referenced artifact is included in this minimized package.

## 5. Forum brief

Read [the Forum brief](synthesis/publication/forum-post.md).

The Forum brief contains commit-pinned links to the canonical full report, the public master evidence matrix, and the sanitized public release repository snapshot. The brief does not replace the canonical report.

## 6. Claim matrix

Read [the public claim matrix](synthesis/master-evidence-matrix.md).

This is a public derivative of the frozen private matrix with obsolete drafting/staging language removed. No claim disposition or evidence-bearing matrix content was changed for publication. The derivation is recorded in the public manifest.

## Public evidence crosswalk

Look up claim IDs in the [public master evidence matrix](synthesis/master-evidence-matrix.md). Some evidence-note paths refer to modular or private source components that are not separately distributed. The [Public Evidence Crosswalk](PUBLIC-EVIDENCE-CROSSWALK.md) shows where their evaluated content can be inspected in this minimized public package.

## 7. Public technical evidence

The package includes 14 normalized Ethereum Mainnet evidence records in `reports/2026-09-18-f438819/L3F-evidence/`: seven historical/current pairs.

| Pair | Recorded object |
|---|---|
| `baseline-*.txt` | Fixed historical/later observation identity, block hashes and chain timestamps |
| `code-*.tsv` | Runtime code presence, byte lengths and runtime hashes |
| `wiring-*.tsv` | Component references returned by selected getters |
| `roles-*.tsv` | Required grants, role counts and failed-call distinctions |
| `key-getters-*.tsv` | Selected rate-limit key returned by the Controller candidates |
| `ratelimits-*.tsv` | Representative finite rate-limit configuration and stored values |
| `usage-*.tsv` | Selected RateLimits component event rows and their recorded identifiers |

These are normalized records, not complete raw RPC envelopes. “Historical” refers to block 25,242,585 on June 4, 2026; “current” refers to the retained later block 26,007,670 on September 18, 2026, not publication-time monitoring. Recorded UTC baseline values are chain timestamps.

For configuration, `lastAmount` is stored capacity, not a token balance or recomputed available capacity at the observation block. For selected event rows, the encoded data contains amountToDecrease, oldRateLimit and newRateLimit as uint256 words in that order. Failed alternative-Controller role-count calls do not mean zero members. Appendices F and I retain the full interpretation and limitations.

## 8. Evidence intentionally not distributed

The private validator workspace contains additional retained acquisition, transport, source-resolution and raw response records that are intentionally not distributed publicly because they are unnecessary for understanding the published conclusions and/or contain unnecessary session metadata, transport metadata, contributor/contact metadata, local working information or internal publication-control material.

Other omitted artifacts provide deeper technical reproduction beyond this package's minimum-traceability purpose. The [public manifest](PUBLIC-MANIFEST.md) identifies the omitted categories without exposing their private contents.

`evidence/f438819-failed-01/` is excluded evidence and is not part of this public package. Its contents are not described or distributed.

## 9. Privacy and minimization policy

The release uses an explicit allowlist. Nothing is included merely because it existed in the private workspace. Git history, original Git objects and author/committer metadata are intentionally not distributed. Raw session/header/browser metadata is intentionally omitted.

The publication documents and 14 normalized records are unchanged copies. Only the public matrix is a sanitized derivative of an existing source file; this README and the public manifest are new navigation documents. No evidence checksum was recomputed for this build, and this package does not claim a new checksum verification.

## 10. Reproducibility limits

The public package allows readers to inspect selected normalized observations and the complete published reasoning. These records do not themselves provide cryptographic chain-state proofs or independent-provider replication.

It does not allow readers to reproduce every original HTTP/RPC request, inspect all private working history, recount the 390/391 raw event totals from withheld raw JSON, reconstruct excluded evidence, establish continuous chain history or establish exact source/runtime bytecode equivalence beyond the report ceiling.

The public `usage-*.tsv` files contain the selected RateLimits event rows: 67 historical and 122 later-window events. The raw 390/391 returned-event bodies are not publicly distributed. Those raw totals therefore remain reported retained-evidence facts rather than independently recountable from this minimized package. The public rows do not permit repetition of the full raw-to-selected filtering step.

No Controller attribution, corresponding token-transfer proof or complete transaction path follows from these selected rows. The two 7,200-block windows are bounded observations, not continuous history. C05 remains closed for its scoped conclusion; exact source/runtime bytecode reproduction remains optional assurance.

The full report's Appendix I describes the broader private retention record. Its references to retained files and existing manifests must not be read as an inventory of this smaller public distribution.

## 11. Corrections

Evidence-specific corrections should identify the affected report section or claim ID, the public artifact involved, and the proposed correction with supporting evidence. Distinguish new evidence about the frozen snapshot from later project changes. No contact identity or destination is designated by this package.
