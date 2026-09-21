# Public Release Manifest

## Release model

This is a history-free, explicit-allowlist release of exactly **19 regular files**. The private validator repository is not distributed. No original Git history, objects, commit identity metadata, reflogs, branches, tags or remotes are included.

Plain-text revisions and freeze SHAs are evidence identifiers. They do not distribute the corresponding Git objects. The full report remains the controlling publication; this manifest describes the minimized distribution, not the entire private evidence collection.

## Included files

### Publication — 2 files

| Public path | Public role | Source category | As-is or derivative | Privacy treatment |
|---|---|---|---|---|
| `synthesis/publication/full-report-final.md` | Canonical report, embedded A–J and evidence notes | Frozen publication | As-is | Public-facing content; no acquisition metadata added |
| `synthesis/publication/forum-post.md` | Reader-facing brief | Content-final publication derivative | As-is copy | Commit-pinned publication links inserted |

### Public controls/navigation — 2 files

| Public path | Public role | Source category | As-is or derivative | Privacy treatment |
|---|---|---|---|---|
| `README-public.md` | Navigation, schemas and distribution limits | New public navigation | New | No private identity, endpoint or workspace information |
| `PUBLIC-MANIFEST.md` | Exact allowlist and omission policy | New public navigation | New | Category-level omissions; no sensitive values |

### Public matrix derivative — 1 file

| Public path | Public role | Source category | As-is or derivative | Privacy treatment |
|---|---|---|---|---|
| `synthesis/master-evidence-matrix.md` | Claim-level propositions, results and evidence ceilings | Frozen private matrix | Process-wording-only derivative | Obsolete drafting/staging wording removed |

### Normalized Mainnet evidence — 14 files

| Public path | Public role | Source category | As-is or derivative | Privacy treatment |
|---|---|---|---|---|
| `reports/2026-09-18-f438819/L3F-evidence/baseline-historical.txt` | Fixed block identity and chain timestamps | Retained normalized L3F record | As-is | No transport/session envelope; evidence values preserved |
| `reports/2026-09-18-f438819/L3F-evidence/baseline-current.txt` | Fixed block identity and chain timestamps | Retained normalized L3F record | As-is | No transport/session envelope; evidence values preserved |
| `reports/2026-09-18-f438819/L3F-evidence/code-historical.tsv` | Recorded runtime presence and hashes | Retained normalized L3F record | As-is | No transport/session envelope; evidence values preserved |
| `reports/2026-09-18-f438819/L3F-evidence/code-current.tsv` | Recorded runtime presence and hashes | Retained normalized L3F record | As-is | No transport/session envelope; evidence values preserved |
| `reports/2026-09-18-f438819/L3F-evidence/wiring-historical.tsv` | Recorded component references | Retained normalized L3F record | As-is | No transport/session envelope; evidence values preserved |
| `reports/2026-09-18-f438819/L3F-evidence/wiring-current.tsv` | Recorded component references | Retained normalized L3F record | As-is | No transport/session envelope; evidence values preserved |
| `reports/2026-09-18-f438819/L3F-evidence/roles-historical.tsv` | Recorded grants and role counts | Retained normalized L3F record | As-is | No transport/session envelope; evidence values preserved |
| `reports/2026-09-18-f438819/L3F-evidence/roles-current.tsv` | Recorded grants and role counts | Retained normalized L3F record | As-is | No transport/session envelope; evidence values preserved |
| `reports/2026-09-18-f438819/L3F-evidence/key-getters-historical.tsv` | Selected key getter results | Retained normalized L3F record | As-is | No transport/session envelope; evidence values preserved |
| `reports/2026-09-18-f438819/L3F-evidence/key-getters-current.tsv` | Selected key getter results | Retained normalized L3F record | As-is | No transport/session envelope; evidence values preserved |
| `reports/2026-09-18-f438819/L3F-evidence/ratelimits-historical.tsv` | Representative stored limit configuration | Retained normalized L3F record | As-is | No transport/session envelope; evidence values preserved |
| `reports/2026-09-18-f438819/L3F-evidence/ratelimits-current.tsv` | Representative stored limit configuration | Retained normalized L3F record | As-is | No transport/session envelope; evidence values preserved |
| `reports/2026-09-18-f438819/L3F-evidence/usage-historical.tsv` | Selected component-event rows | Retained normalized L3F record | As-is | No transport/session envelope; evidence values preserved |
| `reports/2026-09-18-f438819/L3F-evidence/usage-current.tsv` | Selected component-event rows | Retained normalized L3F record | As-is | No transport/session envelope; evidence values preserved |

Only these paths are included. Report/matrix references to other evaluation-repository paths identify retained private records unless listed here. External source-repository references identify their stated upstream repositories, not missing files promised by this package.

## Intentionally withheld categories

| Category | Reason |
|---|---|
| Git history, `.git`, original objects and commit identity metadata | PRIVACY MINIMIZATION |
| Internal publication-control maps and architecture controls | INTERNAL PROCESS |
| Raw L3C HTTP headers | RAW TRANSPORT METADATA |
| Raw L3C HTML/browser captures | RAW TRANSPORT METADATA |
| Raw commit/tag response JSON | NONESSENTIAL PERSONAL METADATA |
| Dependency-pin response JSON | NOT REQUIRED FOR MINIMUM TRACEABILITY |
| Package archive/contact metadata | NONESSENTIAL PERSONAL METADATA |
| Historical process/network logs not needed publicly | INTERNAL PROCESS |
| Raw mint-event JSON | NOT REQUIRED FOR MINIMUM TRACEABILITY; raw totals cannot be recounted here |
| Raw OTC query JSON | NOT REQUIRED FOR MINIMUM TRACEABILITY; report retains the bounded result |
| Runtime bytecode bodies, including duplicate archive-check body | NOT REQUIRED FOR MINIMUM TRACEABILITY |
| Unselected source/interface/helper/dependency bodies | NOT REQUIRED FOR MINIMUM TRACEABILITY; exact source references remain in the report |
| Large L0 lexical inventories and other unselected deterministic artifacts | NOT REQUIRED FOR MINIMUM TRACEABILITY |
| Private pins/setup files | REDUNDANCY; baseline identities remain in Appendix A |
| Redundant report versions | REDUNDANCY |
| Separate appendix copies | REDUNDANCY; A–J are embedded in the full report |
| Complete private acquisition/evidence checksum manifests | NOT REQUIRED FOR MINIMUM TRACEABILITY; they cover a larger retained population |
| Other files not on this allowlist | NOT REQUIRED FOR MINIMUM TRACEABILITY |
| `evidence/f438819-failed-01/` | OUTSIDE ACCEPTED EVIDENCE; never included |

The private workspace retains additional records; their omission does not change a finding or evidence ceiling. No session value, contributor contact value or private working-history content is reproduced in this manifest.

## Matrix derivation

Public matrix source: private `synthesis/master-evidence-matrix.md`, from the frozen evaluation/publication lineage.

Public treatment: obsolete drafting/staging language removed only. No claim/result/disposition/evidence-bearing content changed. All master rows, table cells, source anchors, numeric values and technical identifiers are preserved.

The exact process-wording transformations are:

| Private source wording | Public derivative wording |
|---|---|
| `draft incorporating S1.4 evaluator decisions` | `frozen synthesis incorporating S1.4 evaluator decisions` |
| `### Review before freeze` | `### Frozen synthesis qualifications` |
| `; the corrected artifact remains unstaged and uncommitted` | Removed; the preceding historical-grade qualification and final period remain |
| `by this draft` | `by this matrix` |

The source file remains unchanged in the private workspace. The public matrix is explicitly a derivative, not a newly graded evaluation.

## L3F limitation

Exactly 14 normalized files are distributed. The 67 historical and 122 later selected RateLimits event rows are directly inspectable in the public TSVs. Raw mint JSON is withheld, so the 390/391 raw returned-event totals are not independently recountable from this public package; they remain reported retained-evidence facts. The original raw-to-selected filtering cannot be fully reproduced from the selected rows alone.

No Controller attribution follows from the selected event rows. The named Controller/system and limited RateLimits component usage retain their separate evidence ceilings. No corresponding transfer, full transaction-path, continuous-operation or source/runtime-build-equivalence conclusion is added.

No evidence checksum was recomputed for this release-candidate build. The exact-copy files were compared byte-for-byte with their private sources; that comparison is not independent verification of the underlying chain observations or remote evidence.
