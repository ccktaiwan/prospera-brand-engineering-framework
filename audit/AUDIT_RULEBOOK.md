────────────────────────────────────────
DOCUMENT HEADER (CANONICAL)
────────────────────────────────────────

DOCUMENT_TITLE: Prospera Brand Engineering Framework – Audit Rulebook
DOCUMENT_NAME: AUDIT_RULEBOOK.md
DOCUMENT_TYPE: Engineering Governance Rulebook
DOCUMENT_CLASSIFICATION: Governance / Audit Control
REPOSITORY_NAME: prospera-brand-engineering-framework
REPOSITORY_PATH: /audit/AUDIT_RULEBOOK.md

VERSION: 1.0
STATUS: Active
APPLICABLE_SCOPE: Phase 1 through Phase 6
RULEBOOK_TYPE: Mandatory Audit Rules

AUTHORING_ROLE: Prospera Framework Architecture
AUTHORITY_LEVEL: Canonical
SUPERSEDES: None

EFFECTIVE_DATE: 2026-02-10
CHANGE_CONTROL: Rulebook changes require version increment and audit record

────────────────────────────────────────
PURPOSE
────────────────────────────────────────

This rulebook defines mandatory audit rules governing
the Prospera Brand Engineering Framework.

Its purpose is to ensure that:
- All audits are evidence-based
- No audit relies on inference or intent
- Audit outcomes are reproducible by independent reviewers

This rulebook governs how audits are performed.
It does not define framework content.

────────────────────────────────────────
AUDIT FUNDAMENTAL PRINCIPLES
────────────────────────────────────────

RULE A1: Evidence Supremacy  
Only explicit artifacts constitute valid audit evidence.
Statements, explanations, or intent are invalid.

RULE A2: Artifact Primacy  
Each audit assertion must reference a concrete artifact
with a verifiable repository path.

RULE A3: Non-Inference  
Auditors SHALL NOT infer correctness from structure, tone,
or apparent completeness.

RULE A4: Deterministic Outcome  
Audit results must be PASS, FAIL, or NOT VERIFIED.
No qualitative grading is permitted.

────────────────────────────────────────
AUDIT SCOPE RULES
────────────────────────────────────────

RULE S1: Phase Isolation  
Each phase SHALL be audited independently before
any cross-phase convergence audit.

RULE S2: Boundary Enforcement  
Phase boundaries SHALL be audited for leakage,
implicit promotion, or reverse dependency.

RULE S3: Terminal Authority  
Any phase that defines termination conditions
must demonstrate explicit termination artifacts.

────────────────────────────────────────
ARTIFACT VALIDATION RULES
────────────────────────────────────────

RULE V1: Canonical Authority Check  
A phase is incomplete if no canonical authority artifact exists.

RULE V2: Supporting Artifact Sufficiency  
Supporting artifacts must not redefine canonical scope.

RULE V3: Standalone Verifiability  
Each artifact must be auditable without external context.

RULE V4: Format Integrity  
Artifacts must follow the agreed engineering document format.
Format violations invalidate audit results.

────────────────────────────────────────
COMMIT-LEVEL AUDIT RULES
────────────────────────────────────────

RULE C1: Commit Four-Item Completeness  
Every audited artifact commit must include:
- path
- file content
- commit message
- extended description

RULE C2: Atomic Commit Message  
Commit messages must be single-line, deterministic,
and represent a single change.

RULE C3: Metadata Separation  
Artifact content and VCS metadata must be separated.
Mixed representations are invalid.

RULE C4: Traceable Change Intent  
Extended descriptions must use fixed fields and
describe engineering facts only.

────────────────────────────────────────
AUDIT EXECUTION RULES
────────────────────────────────────────

RULE E1: No Remediation Guidance  
Audit reports SHALL NOT suggest fixes.

RULE E2: No Future Projection  
Audit reports SHALL NOT speculate on future phases.

RULE E3: Evidence Citation  
All audit findings must cite artifact paths.

RULE E4: Append-Only Audit  
Audit reports are immutable once published.
Corrections require new audit versions.

────────────────────────────────────────
AUDIT FAILURE CONDITIONS
────────────────────────────────────────

An audit SHALL be marked FAIL if any of the following occur:

- Missing canonical artifact
- Inference used as justification
- Phase boundary ambiguity detected
- Commit integrity violation
- Format non-compliance

────────────────────────────────────────
AUDIT AUTHORITY STATEMENT
────────────────────────────────────────

This rulebook supersedes individual auditor preference.
Any audit not conforming to these rules
is considered non-authoritative.

────────────────────────────────────────
END OF DOCUMENT
AUDIT_RULEBOOK.md
────────────────────────────────────────
