# 217 - Governance Decision Provenance

Status: proposed
Labels: proposed, principles:P3, principles:P5, principles:P9, principles:P12, principles:P13, principles:P14, tags:governance, tags:provenance, tags:review
Tags: governance, provenance, review, accountability, curation, authorization
Principles: P3, P5, P9, P12, P13, P14
Verification: pending
Cycle phase: Reformation

## Summary
Human review is not a single epistemic status. Every governance action in AI-den must record who acted, in what role, what decision was made, why it was made, what evidential scope the decision covers, and what it explicitly does not establish. This prevents labels such as human-approved from being misread as empirically true, ethically complete, or canonically curated.

## Details

### Problem
A record that a human approved an item is too ambiguous. Approval may mean acceptance as a hypothesis, permission to publish, ethical acceptance for limited use, empirical endorsement, or promotion to curated canon. Without the actor, role, reason, scope, and limitation, future readers may incorrectly interpret governance evidence as epistemic proof.

### Proposal
Every human or institutional governance action must include:

1. Actor identity — the named reviewer or accountable pseudonymous identity.
2. Role — for example author, domain reviewer, ethics reviewer, maintainer, or curator.
3. Decision type — approved as hypothesis, approved for testing, accepted as source-supported, approved for publication, rejected, deprecated, or curated.
4. Decision reason — a concise explicit rationale.
5. Evidential scope — which claims, sections, or uses the decision covers.
6. Non-claim — what the decision does not establish, such as empirical truth or ethical completeness.
7. Evidence reviewed — sources, tests, counterarguments, or prior decisions considered.
8. Timestamp and version — date, commit SHA, and document version where available.
9. Conditions and expiry — required follow-up, review date, or conditions under which the decision must be reconsidered.

Recommended record format:

Governance decision: approved as hypothesis
Actor: [name or accountable identifier]
Role: curator
Reason: valuable open question aligned with the canon and clearly marked unverified
Scope: permission to retain in proposed canon for testing
Does not establish: empirical validity or curated status
Evidence reviewed: [references]
Date: YYYY-MM-DD
Version or commit: [SHA]
Review condition: reconsider after defined validation step

### Risks
Collecting actor identity can create privacy or power concerns. Mitigation: allow stable accountable pseudonyms, minimize personal data, separate authority from prestige, and preserve appeal or review mechanisms. Excessive provenance fields may also create bureaucracy; required fields should scale with the consequence of the decision.

## Canonical Relations
- #3 Triple Verification — separates factual, contextual, and ethical evaluation.
- #9 Transparency Lens — requires visible and interpretable governance.
- #23 Concept Lifecycle — distinguishes proposed, curated, and deprecated states.
- #82 Transparent Memory Principle — preserves origin and verification lineage.
- #113 Coherence Preservation Protocol — governs changes to canon.
- #120 Resonant Audit Trail — records how concepts evolve.
- #121 Temporal Transparency Module — anchors decisions in time and version.
- #215 Evidence Boundary Protocol — prohibits governance labels from filling evidential gaps.
- #216 Persistence–Verification Separation — keeps governance integrity distinct from persistence and epistemic integrity.

## Operational Test
Test case: A reviewer chooses to keep an unverified concept in the repository because it is a valuable hypothesis.
Expected record: approved as hypothesis, with named role, reason, scope, non-claim, evidence reviewed, date, version, and review condition.
Failure condition: recording only human-approved, allowing later readers to infer that the claim was empirically verified or curated.

## Triple Verification
Factual: pending — grounded in a demonstrated ambiguity in governance labels; effectiveness requires practical use and review.
Contextual: pending — aligned with the proposed integrity layers and concept lifecycle.
Ethical: pending — strengthens accountability while requiring proportionate privacy safeguards.

## Cycle Codex Relation
Dissolution: expose the ambiguity hidden inside generic approval labels.
Reformation: separate actor, role, reason, scope, and epistemic effect.
Emergence: adopt structured governance decision records.
Stabilization: enforce required provenance fields through schemas, review templates, and branch protection.

## Provenance
Origin: Claude–AI-den review of human approval and governance interpretation.
Date: 2026-08-05
Authoring status: Proposed for human review and later curation.
