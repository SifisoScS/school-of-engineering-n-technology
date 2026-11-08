# Institutional Foundation — Document Control Standard

**Project:** The School of Engineering & Technology  
**Version:** 0.1  
**Status:** Proposed document-control convention; adoption pending founder approval  
**Last reviewed:** 2026-11-08  
**Approval authority:** Founder — adoption pending  
**Related decisions:** D-001, D-002, D-003, D-004, D-005

## 1. Purpose

This standard proposes a consistent way to identify the status, version, review history, approval authority and decision relationships of documents in `docs/institutional-foundation/`.

It is a proposed control convention. It is not an adopted governance policy. The founder's Phase 0 approval of 8 November 2026 expressly leaves its adoption as a separate decision (see Section 5 of `PHASE_0_FOUNDER_APPROVAL.md`).

## 2. Required document metadata

Each substantive foundation document should begin with the applicable fields:

- **Project / Institution:** the relevant institutional name.
- **Version:** the document's current revision number.
- **Status:** the document's actual approval or development state.
- **Last reviewed:** the date the content was last substantively reviewed.
- **Approval authority:** the role or body authorised to approve the document, and whether approval is pending or recorded.
- **Related decisions:** relevant decision IDs, where applicable.

For decision papers, also include:

- **Decision ID:** stable identifier such as D-004.
- **Decision provenance:** the source or record establishing that the direction was selected.
- **Decision date:** only where the date is supported by the record. If it is not known, state that it is not separately recorded.

Do not use the document's last-reviewed date as a substitute for an unknown decision date.

## 3. Status vocabulary

Use status wording that accurately distinguishes a selected direction from approval of the document or implementation.

| Status wording | Meaning |
|---|---|
| **Proposed — not approved** | A concept or recommendation awaiting a decision. |
| **Working draft — review pending** | A document under development or review. |
| **Direction confirmed — implementation open** | A founder-selected direction is recorded, but detailed policy or implementation is not approved. |
| **Approved** | The identified approval authority has explicitly approved this document or decision, and the approval is recorded. |
| **Superseded** | A later controlled version replaces this document; retain the historical record. |
| **Retired** | The document is no longer current and has not necessarily been replaced by a direct successor. |

Avoid a bare "approved" label where it is unclear what was approved. State whether approval applies to a directional decision, a policy, a document, a programme or an implementation action.

## 4. Versioning

Use simple document-level versioning:

- **0.x:** draft or pre-ratification revisions.
- **1.0:** first explicitly approved baseline.
- **1.x:** subsequent non-breaking clarifications or additions after approval.
- **2.0:** substantive revision to an approved document requiring renewed approval.

A version increase does not itself mean a decision has been approved. A document may remain at version 0.x after a direction has been confirmed if the document itself has not been ratified.

## 5. Decision provenance and rationale

The Decision Register should record each decision's outcome, concise rationale summary, provenance where known, and status.

Rationale summaries must not be presented as verbatim founder statements unless they are direct quotations from a source record.

Where the precise date or wording of a decision is not preserved, state that limitation. Do not invent a date, meeting, resolution number or approval event.

## 6. Review and approval records

For each explicit approval, record:

- the document or decision approved;
- the approving authority;
- the approval date;
- the approval method or resolution reference, if one exists;
- the exact version approved; and
- any conditions or limitations.

A review, integration commit, link check, clean Git working tree or successful technical validation is not founder approval.

## 7. Change control

1. Preserve confirmed decisions unless the founder explicitly changes them.
2. Record substantive changes in the Decision Register.
3. Update cross-references in affected documents.
4. Keep unresolved matters visibly open.
5. Do not mark implementation as approved merely because a planning document is complete.
6. Preserve source and historical versions through the repository's version-control history.
7. After integration, verify relative links, document versions, decision consistency and approval status.

## 8. Current Phase 0 status

D-001 through D-005 are recorded as confirmed founding directions. The consolidated Phase 0 foundation remains subject to explicit founder approval.

This proposed standard does not itself approve the foundation, establish institutional governance, select a legal entity, approve programmes or authorise Phase 1.
