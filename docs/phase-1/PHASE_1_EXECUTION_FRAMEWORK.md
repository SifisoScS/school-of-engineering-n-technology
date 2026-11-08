# PHASE 1 EXECUTION FRAMEWORK

**Institution:** The School of Engineering & Technology  
**Document:** Phase 1 Execution Framework  
**Version:** 0.5  
**Status:** Proposed — awaiting founder review  
**Related plan:** `docs/phase-1/PHASE_1_PLAN.md` — v0.2  
**Plan baseline:** commit `1e39d24`  
**Phase 0 foundation baseline:** `186792a`  
**Institutional governance baseline:** `467ace8`  
**Execution status:** Not authorised

---

## 1. PURPOSE

This document establishes the execution methodology, research controls, evidence standards, deliverable requirements and founder oversight procedures for Phase 1.

It supports the Phase 1 Plan without replacing, modifying or overriding it.

The framework is designed to ensure that:

- Research is systematic and evidence-based.
- Findings are distinguishable from assumptions and recommendations.
- South African legal and regulatory requirements are investigated carefully.
- Institutional decisions remain under founder authority.
- Research limitations and unresolved questions are visible.
- Every workstream produces reviewable deliverables.
- No activity exceeds the authority granted by the founder.

**This framework is not an authorisation to commence Phase 1.**

## 2. EXECUTION PRINCIPLES

All Phase 1 activities must follow these principles.

### 2.1 Evidence before conclusions
Recommendations must be supported by documented evidence. Where evidence is unavailable, the limitation must be stated.

### 2.2 South African context first
Research must prioritise applicable South African legislation, regulations, government departments, regulators, official policies and recognised institutional sources.

International examples may provide comparative insight but must not be presented as South African requirements.

### 2.3 Transparency
Every material conclusion must identify its supporting evidence, assumptions, uncertainty and limitations.

### 2.4 Separation of findings from decisions
Research findings and recommendations must not be treated as automatic institutional decisions or commitments.

### 2.5 Proportionality
Research depth must correspond to the importance, complexity and risk of the question being investigated.

### 2.6 Controlled progression
Work must follow the stages and approval gates established in the Phase 1 Plan. No stage progresses automatically.

## 3. ROLES AND RESPONSIBILITIES

### 3.1 Founder

The founder retains authority over:

- Institutional direction and priorities.
- Approval of research scope and material changes.
- Approval of each formal stage gate.
- Acceptance or rejection of recommendations.
- Decisions concerning legal structure and institutional establishment.
- Approval of external engagement.
- Approval of expenditure and commitments.
- Authorisation of subsequent phases.

### 3.2 Claude — Research and Documentation Agent

Claude may:

- Conduct authorised desk-based research.
- Identify and examine relevant sources.
- Extract and organise evidence.
- Compare legislation, policies and institutional models.
- Identify gaps, risks and conflicting information.
- Prepare analytical reports.
- Develop options and recommendations.
- Maintain research and evidence documentation.
- Prepare materials for founder review.

Claude may not:

- Make institutional decisions on behalf of the founder.
- Approve its own recommendations.
- Represent the institution externally.
- Contact regulators, institutions, prospective learners or other stakeholders without specific approval.
- Conduct surveys, interviews or consultations without specific approval.
- Commit institutional resources or incur expenditure.
- Register entities or submit applications.
- Authorise stage progression or Phase 1 completion.
- Make public institutional claims without founder approval.
- Modify the public landing page without founder approval.
- Commit or push repository changes without founder authorisation.
- Publish research findings, reports or summaries without founder approval.

Drafts remain local and uncommitted until the founder has reviewed and authorised the relevant repository action.

As stated in Section 6 of the Phase 1 Plan, AI-assisted research is not legal, tax, accounting or regulatory advice. Professional confirmation must be obtained where required.

### 3.3 External professionals

Legal practitioners, accountants, education specialists and other professionals may provide specialist advice when separately approved by the founder.

Their advice must be identified as professional input, with its scope and limitations recorded.

No professional engagement is automatically authorised by this framework.

## 4. EXECUTION ARCHITECTURE

Phase 1 follows the four stages in the Phase 1 Plan.

### Stage 1 — Establish the evidence base

Purpose:
Establish the central Research and Evidence Register and a preliminary institutional evidence base, in accordance with Section 5 of the Phase 1 Plan: "Gather authoritative information, establish the institutional context and identify knowledge gaps."

Deliverable:
`PHASE_1_RESEARCH_AND_EVIDENCE_REGISTER.md`

#### Permitted Stage 1 work

Under an authorised Phase 1 scope, Stage 1 work is limited to:

1. Establishing the Research and Evidence Register.
2. Mapping the approved workstreams and their existing key questions.
3. Identifying authoritative South African source categories and relevant sources.
4. Conducting limited cross-cutting desk research to establish the institutional context.
5. Recording relevant authoritative information and preliminary findings in the register, in accordance with Section 6.
6. Identifying knowledge gaps, limitations and uncertainties.
7. Preparing proposed detailed research questions, workstream scopes and methodologies.
8. Identifying dependencies and information requirements.

#### Distinction from Stage 2 investigation

Stage 1 establishes a preliminary, cross-cutting evidence base. It does not include the substantive investigations assigned to Workstreams 01–06, which take place only in Stage 2 after explicit founder approval at Gate 1. Preliminary findings recorded in Stage 1 are classified under Section 6.1 and must not be presented as workstream conclusions.

Stage 1 work, including detailed research questions and methodologies, must not introduce new institutional objectives or expand the approved Plan scope.

#### Gate 1 submission and decision

The Gate 1 submission includes:

- the populated Research and Evidence Register;
- the preliminary institutional evidence base;
- identified knowledge gaps;
- proposed detailed research questions;
- proposed workstream scopes and methodologies; and
- identified dependencies and outstanding information requirements.

The founder's Gate 1 decision must explicitly:

- accept, or request corrections to, the Research and Evidence Register;
- confirm whether Stage 2 may proceed; and
- approve, amend or reject the proposed Stage 2 research scopes and methodologies.

This preserves the Plan's Gate 1 requirement to accept the Research and Evidence Register and confirm that Stage 2 may proceed. Substantive investigation of Workstreams 01–06 begins only after that explicit decision.

### Stage 2 — Investigate institutional feasibility

Workstreams 01–06 are investigated.

Each workstream must produce an individual feasibility report.

| Workstream | Required deliverable |
|---|---|
| 01. Legal and Regulatory Feasibility | `WS01_LEGAL_AND_REGULATORY_FEASIBILITY.md` |
| 02. Academic Architecture | `WS02_ACADEMIC_ARCHITECTURE.md` |
| 03. Learner and Societal Needs | `WS03_LEARNER_AND_SOCIETAL_NEEDS.md` |
| 04. Digital and Physical Delivery Model | `WS04_DELIVERY_MODEL.md` |
| 05. Governance and Operating Model | `WS05_GOVERNANCE_AND_OPERATING_MODEL.md` |
| 06. Financial and Resource Feasibility | `WS06_FINANCIAL_AND_RESOURCE_FEASIBILITY.md` |

#### Dependency sequence

Stage 2 follows the dependency table in Section 7 of the Phase 1 Plan:

| Group | Workstreams | Depends on (per the Plan) |
|---|---|---|
| First | 01 — Legal and Regulatory Feasibility; 03 — Learner and Societal Needs | — |
| Second | 02 — Academic Architecture; 05 — Governance and Operating Model | 02: 01, 03. 05: 01. |
| Third | 04 — Digital and Physical Delivery Model | 01, 02, 03 |
| Fourth | 06 — Financial and Resource Feasibility | 01, 02, 03, 04, 05 |

Where a workstream depends on findings from another, it must not present those findings as established before they are available.

#### Consolidated review at Gate 2

The founder has selected consolidated review of the Stage 2 reports at Gate 2. Therefore:

- Individual workstream reports do not require separate formal founder acceptance before dependent work begins.
- Work may proceed using sufficiently developed provisional findings from prerequisite workstreams.
- Such findings must be identified as provisional.
- Material uncertainties, contradictions or blockers must be escalated to the founder.
- All six Stage 2 reports are submitted for consolidated founder review at Gate 2.
- Stage 3 may commence only after the founder has reviewed the six Stage 2 reports and explicitly authorised progression at Gate 2.

#### Material blockers and workstream pauses

1. When Claude identifies a material uncertainty, contradiction, evidence gap or blocker that could invalidate a finding or affect a dependent workstream, it must escalate the matter to the founder.
2. The affected workstream must pause where continuing would require an unsupported assumption or could produce misleading findings.
3. Dependent workstreams must also pause where their progress relies materially on the affected finding.
4. Unaffected workstreams may continue if they remain within their approved scope and do not rely on the unresolved matter.
5. The escalation must explain:
   - the blocker;
   - the evidence or issue giving rise to it;
   - the affected workstreams;
   - the consequences of proceeding; and
   - available options or proposed ways to resolve it.
6. Claude may not independently decide that a material blocker has been resolved where founder direction or professional confirmation is required.
7. Work resumes when the necessary founder direction or required confirmation has been received.

Pauses apply proportionately to the affected work and its dependencies. Not every uncertainty is a reason to stop all Phase 1 work.

#### Priority and order

Workstream 06 (Financial and Resource Feasibility) is a high-priority investigation because of its importance to institutional feasibility, as reflected in Section 4 of the Phase 1 Plan. Its execution comes last because it depends on Workstreams 01–05. Priority does not override dependency order.

### Stage 3 — Institutional establishment design

Workstream 07 — Institutional Establishment Roadmap consolidates the findings from Workstreams 01–06.

Deliverable:

`WS07_INSTITUTIONAL_ESTABLISHMENT_BLUEPRINT.md`

The blueprint must distinguish:

- Verified findings.
- Recommendations.
- Assumptions.
- Unresolved decisions.
- Conditions and dependencies.
- Risks and limitations.

It must not present institutional establishment as approved or guaranteed.

### Stage 4 — Founder review

The founder reviews the complete evidence base, reports and establishment blueprint.

The founder determines the outcome under the options established in the Phase 1 Plan.

Deliverable:

`PHASE_1_FINAL_ASSESSMENT_AND_FOUNDER_DECISION_RECORD.md`

The founder decision within this record is completed only in accordance with Section 9.

No subsequent phase is authorised automatically.

## 5. WORKSTREAM EXECUTION PROTOCOL

Each workstream has one to three key questions in the approved Phase 1 Plan. Claude develops the detailed research questions from those key questions.

The detailed research questions, proposed scope and methodology for every workstream must be submitted to the founder at Gate 1 for review and approval before substantive workstream investigation begins. This approval point must not become a mechanism for introducing new institutional objectives or silently expanding the approved scope.

Every workstream follows the same basic procedure.

1. Confirm its scope and dependencies.
2. Develop detailed research questions from the Phase 1 Plan's key questions.
3. Submit the detailed research questions, proposed scope and methodology for founder review and approval at Gate 1.
4. Identify authoritative sources.
5. Record evidence in the central register.
6. Analyse findings against the approved research questions.
7. Identify gaps, conflicts and uncertainties.
8. Develop options where appropriate.
9. Prepare the workstream report.
10. Conduct an internal quality review (Section 8).
11. Submit the report for founder review at the applicable gate.

Steps 1–3 are carried out in Stage 1, alongside the preliminary evidence-base work described in Section 4. Steps 4–11 are substantive workstream investigation and begin only after explicit founder approval at Gate 1; Stage 1 cross-cutting research does not replace them.

Workstreams must not silently expand their scope.

Any material scope change must be submitted to the founder for approval.

## 6. RESEARCH AND EVIDENCE MANAGEMENT

### 6.1 Evidence classifications

The four evidence classifications and definitions in Section 6 of the Phase 1 Plan are used without modification:

| Class | Meaning |
|---|---|
| **Verified** | Supported by reliable evidence, with the source cited. |
| **Proposed** | A recommended institutional direction. |
| **Assumption** | Not yet verified. |
| **Decision required** | Requires founder approval. |

Verified evidence does not automatically mean that the institution has adopted a policy, approach or requirement.

A legal or regulatory claim may only be classified as Verified where it is supported by a relevant Tier 1 or Tier 2 source under the source hierarchy in this framework (Section 6.4), interpreted in accordance with Sections 6.4.1 to 6.4.4. Lower-tier sources may identify issues for investigation but cannot independently establish a legal or regulatory requirement.

A legal obligation must be verified against actual legal authority, namely:

- legislation;
- regulations;
- binding judicial authority; or
- other legally binding instruments whose legal basis and legal effect have been established.

Government and regulator publications that are explanatory or corroborative in nature may help interpret, explain or support research findings, but cannot by themselves establish a legal obligation. Their inclusion in the source hierarchy does not mean that they are legally binding or that they have the same legal status as legislation or regulations. Where the legal authority for an obligation, or the legal effect of an instrument, cannot be established from the available evidence, the uncertainty must be disclosed and the matter flagged for professional confirmation in accordance with Section 6.4.4.

A finding concerning a legal obligation must satisfy the actual legal-authority requirements in Section 6.4.1. A government or regulator publication may establish what that organisation publishes or communicates, but it must not independently establish the existence of a legal obligation where the actual legal authority has not been identified.

### 6.2 Source verification

The following controls are mandatory:

- Every cited source must actually have been opened and examined during the research.
- No citations may be supplied from model memory alone.
- A search-result snippet is not sufficient verification of a substantive claim.
- Every material quotation must be reproduced word-for-word from the source.
- Every quotation must identify its precise location, such as a legislative section, paragraph, page or document heading.
- If the original source cannot be accessed or verified, disclose that limitation and do not present it as verified evidence.
- Links must be checked during the research, not assumed to be valid.

### 6.3 Evidence register

The central Research and Evidence Register distinguishes between finding-level information and source-level information.

The finding classifications in Section 6.1 (Verified, Proposed, Assumption and Decision required) apply to research findings only. They must not be applied to source documents themselves. Source records instead carry source-level metadata, including source type and authority tier.

**Finding-level fields.** The register must include at least every field required by Section 6 of the Phase 1 Plan:

- Finding ID.
- Finding.
- Evidence classification.
- Source details.
- Source date/version.
- Specific reference or location.
- Access date.
- Related workstream.
- Limitations and uncertainty.
- Whether professional confirmation is required.

**Source-level fields.** Every material source must record:

- Source title.
- Source type, using the vocabulary in Section 6.3.1.
- Authority tier under the source hierarchy in Section 6.4.
- Publishing organisation or author.
- Source URL or document reference.
- Publication date or version, where available.
- Specific provision, section or page where relevant.
- Access date.
- Related workstream.
- Limitations and uncertainty.

For legislation and regulations, record the applicable version, effective date, relevant provisions, amendments and any conflicting or superseding instruments identified.

No field required by the Phase 1 Plan may be removed or replaced.

#### 6.3.1 Source type vocabulary (proposed)

The Source type field uses the following controlled vocabulary:

| Source type | Use for |
|---|---|
| Legislation | Acts of Parliament and provincial legislation. |
| Regulation | Regulations and other subordinate legislation made under enabling legislation. |
| Judicial decision | Court judgments and other judicial decisions. |
| Gazetted notice or instrument | Notices and instruments published in the Government Gazette, other than legislation and regulations. |
| Official policy | Government policy documents and policy frameworks. |
| Official guidance | Guidance, explanatory publications, FAQs and website content issued by government departments or regulators. |
| Official statistics | Official statistical publications, such as those of Statistics South Africa. |
| Professional or statutory body publication | Publications of recognised professional and statutory bodies. |
| Institutional publication | Official publications of educational institutions. |
| Peer-reviewed research | Peer-reviewed academic research. |
| Industry or research organisation report | Reports of reputable industry and research organisations. |
| Secondary commentary | News, commentary and general publications. |
| Other — specify | Any source that does not fit the categories above; the specific type must be stated. |

Source type records what a source is. It does not determine the source's legal force or binding effect, which must be assessed in relation to the specific claim under Sections 6.4.1 to 6.4.4.

### 6.4 Source hierarchy

Use sources in the following order where relevant:

1. **Tier 1** — South African legislation and regulations.
2. **Tier 2** — Official government departments and regulators; and South African court judgments and other relevant judicial decisions. A judgment is judicial authority on the interpretation or application of the law, not legislation; record the details required by Section 6.4.2.
3. **Tier 3** — Official government policies and published notices; and official statistical publications, particularly those of Statistics South Africa (Stats SA).
4. **Tier 4** — Recognised professional and statutory bodies.
5. **Tier 5** — Accredited educational institutions and official institutional publications.
6. **Tier 6** — Peer-reviewed academic research.
7. **Tier 7** — Reputable industry and research organisations.
8. **Tier 8** — Secondary commentary and general publications.

Lower-tier sources may help identify questions but should not replace authoritative evidence where available.

The eight source tiers are a research-source classification and prioritisation framework. They do not automatically determine the legal force or binding effect of a source. The legal authority of a source must be assessed in relation to the specific claim being investigated, in accordance with Sections 6.4.1 to 6.4.4.

#### 6.4.1 Identify the actual legal authority

A claim that a legal obligation or regulatory requirement exists must be traced to the applicable legal authority, such as:

- applicable legislation;
- applicable regulations made under enabling legislation;
- relevant binding judicial authority; or
- other legally binding instruments, where their legal basis and effect have been established.

A regulator's website, guidance document, explanatory publication or FAQ may explain or corroborate a requirement. It must not automatically be presented as the legal instrument that creates the requirement.

#### 6.4.2 Court decisions

For relevant judicial decisions, record:

- court;
- case name and citation;
- judgment date;
- relevant paragraphs;
- whether the decision is binding or persuasive for the issue being examined; and
- any relevant subsequent appellate or superseding decision identified.

Do not treat a judgment as legislation.

#### 6.4.3 Government Gazette notices and policies

A document's publication in the Government Gazette does not automatically establish that it has the same legal effect as legislation or regulations.

For Gazette notices, policies and other official instruments:

- identify the issuing authority;
- identify the enabling legal provision, if applicable;
- determine the instrument's legal character and effect where possible;
- distinguish binding requirements from policy direction, administrative guidance and explanatory material; and
- flag uncertain legal status for professional confirmation.

Do not automatically classify every Gazette publication as binding or non-binding.

#### 6.4.4 Legal verification

If the legal authority or effect of an instrument cannot be established from the available evidence, classify the conclusion appropriately and flag it for professional confirmation.

These principles do not weaken the evidence-verification requirements in Section 6.2, and lower-tier commentary may not independently establish a legal requirement.

### 6.5 Conflicting evidence

When sources conflict:

- Record both sources.
- Identify their authority and dates.
- Explain the conflict.
- Avoid silently selecting the more convenient interpretation.
- Flag matters requiring professional confirmation.

## 7. WORKSTREAM REPORT STANDARD

Every workstream report must begin with a document-control header containing:

- Document title.
- Version.
- Status.
- Preparation or update date.
- Related workstream.
- Controlling Phase 1 Plan version.

Every workstream report must then use the following structure.

1. Executive Summary.
2. Purpose and Scope.
3. Research Questions.
4. Methodology.
5. Accepted and Provisional Dependencies.
6. South African Context.
7. Evidence and Findings.
8. Relevant Legal, Regulatory or Institutional Considerations.
9. Options and Comparative Analysis.
10. Risks and Constraints.
11. Assumptions and Uncertainties.
12. Recommendations.
13. Decisions Required from the Founder.
14. Unresolved Questions.
15. Sources and References.
16. Quality Review Record.

**Accepted and Provisional Dependencies** must identify which other workstream findings or reports were relied upon and distinguish between:

- Founder-reviewed reports.
- Provisional findings.
- Outstanding dependencies.

A report must not be described as accepted by the founder merely because Claude has completed it.

**Quality Review Record** must identify the self-review date, checks performed, findings, outstanding defects and review status.

Sections that are not applicable must be marked accordingly rather than filled with unsupported material.

Recommendations must be separated from verified findings.

## 8. QUALITY ASSURANCE

Before submitting any report, Claude must perform a documented quality review and record it in the report's Quality Review Record.

This quality review is a self-check performed by the same AI agent that conducted the research. It is not independent verification, professional review or founder approval.

The review must check:

- Whether all assigned research questions were addressed.
- Whether important claims have traceable sources.
- Whether sources are authoritative and current enough for the claim.
- Whether legal and regulatory references are accurately identified.
- Whether evidence classifications are appropriate.
- Whether assumptions are visible.
- Whether conflicting information is disclosed.
- Whether recommendations follow from the evidence.
- Whether unresolved matters are clearly identified.
- Whether the report remains within the approved scope.
- Whether every cited link was opened and examined during research.
- Whether every quotation was checked word-for-word against its original source.
- Whether the location of every quotation is recorded.

A report must not be labelled complete merely because it has been written.

Incomplete investigations must be identified honestly.

## 9. FOUNDER REVIEW AND APPROVAL

Founder review is required at each formal approval gate.

Each submission must include:

- Work completed.
- Deliverables produced.
- Evidence collected.
- Important findings.
- Material risks.
- Limitations and uncertainties.
- Outstanding questions.
- Decisions requested from the founder.

The founder may:

- Accept the deliverable.
- Request corrections.
- Request further investigation.
- Accept with conditions.
- Reject the recommendations.
- Pause or terminate the work.

Acceptance of a report does not mean acceptance of every recommendation contained in it.

Formal gate decisions must be recorded in the Phase 1 review records under the logical path `docs/phase-1/reviews/`. The authoritative records are held in the private storage location in accordance with Section 12.4, not in the public repository. Each record must identify the relevant gate, the deliverables reviewed, the founder decision, the date and any conditions.

Claude may prepare a written record of a founder decision only after the founder has explicitly communicated that decision. Claude must never complete, infer, pre-populate or independently approve founder decision fields.

No approval may be inferred from silence, elapsed time or the completion of a task.

## 10. CHANGE CONTROL

The Phase 1 Plan remains the controlling scope document.

If this Execution Framework conflicts with the Phase 1 Plan, the Phase 1 Plan takes precedence. Any proposed amendment to the Plan must be submitted separately for founder review and approval.

This framework may not be used to introduce new institutional objectives or bypass the approval gates.

Changes to the following require founder review:

- Research scope.
- Workstream responsibilities.
- Deliverable requirements.
- Research methodology where it materially changes the agreed approach.
- External engagement.
- Resource requirements.
- Institutional assumptions or proposed direction.

Approved changes must be recorded with their rationale and date in a separate Phase 1 change record under the logical path `docs/phase-1/reviews/`. The authoritative change record is held in the private storage location in accordance with Section 12.4, not in the public repository.

The Phase 0 Decision Register is a frozen baseline and must not be modified to record Phase 1 changes.

The Phase 0 foundation baseline must remain intact unless the founder separately authorises a genuine correction or new institutional decision.

## 11. EXTERNAL ENGAGEMENT AND OPERATIONAL RESTRICTIONS

Desk-based research is the default research method.

### 11.1 Desk-based research

The following count as desk-based research:

- Reading publicly accessible websites.
- Reading publicly accessible documents.
- Examining legislation, policies, official publications and public institutional information.
- Accessing publicly available statistics and research.

### 11.2 External engagement

The following count as external engagement and require specific founder approval before they occur:

- Submitting online forms.
- Creating accounts with external organisations.
- Sending emails or messages.
- Using enquiry services or website chatbots.
- Contacting organisations through their websites.
- Downloading materials that require registration or submission of personal or institutional information.
- Surveys, questionnaires, interviews and consultations.
- Direct engagement with prospective learners.
- Contact with employers or educational institutions.
- Contact with regulators or government departments.
- Engagement with community organisations.
- Requests for information from external stakeholders.

The following also require specific founder approval before they occur:

- Professional appointments and paid services.
- Any expenditure or institutional commitment.

Where engagement is approved, its purpose, scope, method, privacy implications and any safeguarding requirements must be defined beforehand.

### 11.3 Personal information

Desk-based research must not become an unauthorised personal-information collection activity.

1. No personal information about prospective learners, stakeholders or research participants may be deliberately collected or compiled during desk-based research.
2. Incidental exposure to publicly available personal information does not automatically constitute an authorised collection activity.
3. Incidental personal information must be minimised and must not be used to create personal profiles, participant lists or datasets.
4. Source attribution may identify authors, researchers, public officials, judicial office-holders or other relevant source contributors where necessary to document and verify an authoritative publication.
5. Such attribution must remain limited to the purpose of identifying the source and must not become unrelated personal-information profiling.
6. Any deliberate collection or processing of personal information for research, surveys, interviews, learner-needs investigations or stakeholder engagement requires separate founder approval and appropriate POPIA, privacy and ethical safeguards.

This section sets an institutional research principle. It is not a legal determination of POPIA compliance.

### 11.4 Plan restrictions

The restrictions in Section 8 of the Phase 1 Plan continue to apply in full, including those on:

- Public institutional claims.
- Changes to the landing page.
- External representation of the institution.
- Commitments and expenditure.

Phase 1 authorisation alone does not grant blanket permission for any activity in this section and does not override these restrictions.

## 12. FILE AND RECORD MANAGEMENT

### 12.1 Founder decision: private detailed records, reviewed public summaries

The founder has decided that detailed Phase 1 records are held privately and that only reviewed summaries may be made public. The following principles apply:

1. Detailed legal, regulatory, governance and financial analysis must be held in a private, access-controlled location.
2. Detailed internal research records, evidence, sensitive assumptions, financial scenarios, internal risks and founder gate deliberations must not be placed in the public repository.
3. Public repository content may contain appropriately reviewed, non-sensitive institutional summaries.
4. No research report or summary may be published without explicit founder approval.
5. Public summaries must not disclose confidential details or imply decisions that have not been approved.
6. The public repository remains the record of approved public institutional material, not the default storage location for all internal research.

### 12.2 Private storage location — unresolved

The founder has selected private detailed records and public summaries, but has not yet selected the specific private storage destination or its access-control arrangements. Therefore:

- The private storage location and access arrangements must be confirmed before Phase 1 research and the creation of sensitive working records begin.
- This framework does not select or create a private repository or external storage service.
- No sensitive Phase 1 material may be placed in the public repository.

### 12.3 Illustrative structure

The following structure is illustrative only. It does not authorise the creation or population of any listed file, and it does not determine which storage location holds each file. Placement must follow Sections 12.1 and 12.2.

```text
docs/
└── phase-1/
    ├── PHASE_1_PLAN.md
    ├── PHASE_1_EXECUTION_FRAMEWORK.md
    ├── PHASE_1_RESEARCH_AND_EVIDENCE_REGISTER.md
    ├── PHASE_1_FINAL_ASSESSMENT_AND_FOUNDER_DECISION_RECORD.md
    ├── workstreams/
    │   ├── WS01_LEGAL_AND_REGULATORY_FEASIBILITY.md
    │   ├── WS02_ACADEMIC_ARCHITECTURE.md
    │   ├── WS03_LEARNER_AND_SOCIETAL_NEEDS.md
    │   ├── WS04_DELIVERY_MODEL.md
    │   ├── WS05_GOVERNANCE_AND_OPERATING_MODEL.md
    │   ├── WS06_FINANCIAL_AND_RESOURCE_FEASIBILITY.md
    │   └── WS07_INSTITUTIONAL_ESTABLISHMENT_BLUEPRINT.md
    └── reviews/
```

Records must be traceable and must not silently overwrite previously approved decisions.

### 12.4 Review and change records

The founder's decision of private detailed records and reviewed public summaries applies to review and change records:

- `docs/phase-1/reviews/` is a logical organisational path in the proposed record structure.
- It does not mean that detailed gate records or change records may be stored in the public GitHub repository.
- The authoritative gate decision records and detailed change records must be held in the private storage location once that location is selected and established.
- Any public summary of a gate decision or approved change requires explicit founder approval.
- An approved public summary does not replace the authoritative private record.
- Until the private storage location and access arrangements are confirmed, no sensitive Phase 1 records may be created or placed in the public repository.

### 12.5 Relationship to the Plan's deliverable location

Section 11 of the Phase 1 Plan gives the deliverable location as `docs/phase-1/`. That path describes the logical organisation of Phase 1 records. It does not automatically authorise placing detailed internal research, legal analysis, financial scenarios, sensitive assumptions or founder deliberations in the public GitHub repository.

Actual storage must comply with the founder-approved arrangement:

- detailed records are held privately; and
- public summaries are published only after review and explicit founder approval.

This framework does not select a private storage service or create an external repository.

## 13. PHASE 1 COMPLETION STANDARD

Phase 1 may be presented for final founder review only when:

- Required investigations have been conducted.
- Required reports have been produced.
- Evidence and source limitations have been documented.
- Dependencies and outstanding questions have been addressed or disclosed.
- The establishment blueprint consolidates the findings.
- Material risks and unresolved decisions are visible.
- Required stage approvals have been recorded.

The outcome may be:

- Feasible.
- Feasible subject to conditions.
- Infeasible.
- Insufficient evidence to determine feasibility.

An unfavourable or inconclusive outcome does not mean the investigation has failed.

Completion of Phase 1 does not approve institutional establishment or authorise a subsequent phase.

## 14. AUTHORISATION STATUS

This framework is a proposed supporting document.

Approval of this Execution Framework is a prerequisite for Gate 0 authorisation under the Phase 1 Plan. The founder must approve the relevant framework version before completing the Plan's Section 12 authorisation.

- Framework approval alone does not authorise Phase 1.
- Phase 1 execution requires a separate affirmative founder authorisation in Section 12 of the Phase 1 Plan, with any required changes and conditions incorporated.
- The authorised framework version must be explicitly referenced in the "Changes or conditions" field of the Plan's Section 12.
- If this framework is amended after approval but before execution, the founder must review and approve the applicable version before Phase 1 begins.

### Framework approval record

Founder approval of this Execution Framework must itself be recorded in the private Phase 1 review records (Section 12.4). The approval record must identify:

- the approved framework version;
- the founder's approval decision;
- the approval date; and
- any conditions.

This record is kept separate from the Phase 1 authorisation record in Section 12 of the Phase 1 Plan. Framework approval must never be interpreted as Phase 1 authorisation.

**Current status:** Phase 1 not authorised.

---

## 15. VERSION HISTORY

| Version | Status | Description |
|---|---|---|
| 0.1 | Proposed | Initial execution framework for founder review. |
| 0.2 | Proposed | Founder-review amendments covering repository privacy, research controls, workstream dependencies and review, AI source verification, quality assurance, external engagement boundaries, report traceability and the relationship between framework approval and Gate 0 authorisation. |
| 0.3 | Proposed | Final founder-review refinements covering material blocker escalation, Gate 1 preparation boundaries, legal source authority, personal-information safeguards and private review-record handling. |
| 0.4 | Proposed | Three founder-approved refinements: explicit founder authorisation at Gate 2 before Stage 3 may commence; verification of legal obligations against actual legal authority, with explanatory or corroborative government and regulator publications unable by themselves to establish a legal obligation; and separation of research finding classifications from source-level metadata (source type and authority tier). |
| 0.5 | Proposed | Consistency corrections following the founder's consolidated review of Plan v0.2 and Framework v0.4: Stage 1 aligned with Plan Section 5 (preliminary evidence base, limited cross-cutting desk research, defined Gate 1 submission and decision); source tiers clarified as a prioritisation framework, with legal-obligation findings tied to Section 6.4.1 and a proposed source-type vocabulary; `docs/phase-1/` clarified as a logical location subject to private recordkeeping; and a private framework approval record, separate from Phase 1 authorisation. |

**Document owner:** Founder, The School of Engineering & Technology.

**Review authority:** Founder.

**Execution authority:** Separate founder authorisation under the Phase 1 Plan.
