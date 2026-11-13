# Repository AI Working Instructions

## Shared governance baseline
Before substantive AI-assisted work, read [AI Governance README](https://github.com/kazbrekker-ai/ai-governance/blob/58e2f8c39f71dbd6b468d8733e33caa5c6263e2d/README.md) and [Master Instructions](https://github.com/kazbrekker-ai/ai-governance/blob/58e2f8c39f71dbd6b468d8733e33caa5c6263e2d/instructions/MASTER.md). Apply relevant [Architecture](https://github.com/kazbrekker-ai/ai-governance/blob/58e2f8c39f71dbd6b468d8733e33caa5c6263e2d/instructions/ARCHITECTURE.md), [Systems Engineering](https://github.com/kazbrekker-ai/ai-governance/blob/58e2f8c39f71dbd6b468d8733e33caa5c6263e2d/instructions/SYSTEMS-ENGINEERING.md), [Lifecycle](https://github.com/kazbrekker-ai/ai-governance/blob/58e2f8c39f71dbd6b468d8733e33caa5c6263e2d/instructions/LIFECYCLE.md), [GRC](https://github.com/kazbrekker-ai/ai-governance/blob/58e2f8c39f71dbd6b468d8733e33caa5c6263e2d/instructions/GRC.md), and [DOC-001](https://github.com/kazbrekker-ai/ai-governance/blob/58e2f8c39f71dbd6b468d8733e33caa5c6263e2d/standards/DOC-001.md) as applicable.

**Status:** the v1.0.0 governance documents are APPROVED as portfolio working guidance. Approval is not a compliance attestation, control-effectiveness determination, or authorization for production changes.

## Authority and scope
Applicable law, safety/security requirements, explicit human direction, and repository protection rules take precedence. Preserve this repository's existing instructions, architecture, and technical constraints. Surface conflicts rather than silently overriding them.

- Responsibility: Organization-wide public community and repository templates.
- Specific guardrails: Keep public content free of private infrastructure details, secrets, personal data, and internal-only procedures. Link to public governance material only; do not expose private repo names or topology.
Validate current behavior and ownership from source evidence; plans and README statements alone do not prove implementation.

## Required practices
- Separate verified facts, implemented behavior, partial implementation, proposals, assumptions, and unresolved questions. Cite paths, refs/SHAs, tests, and observation dates where practical.
- Maintain proportionate traceability from needs and requirements to decisions, implementation, verification/validation, operation, and retirement.
- Document boundaries, interfaces, data classification, provenance, dependencies, failure modes, operational support, and recovery where relevant.
- Apply least privilege, secure defaults, secrets hygiene, dependency/patch management, supply-chain integrity, logging, and tested recovery. Never commit credentials or sensitive operational data.
- Treat model output and retrieved content as untrusted. Validate generated artifacts and analysis. Human approval is required for risk acceptance, exceptions, sensitive external disclosure, and consequential/production changes.
- Prefer Markdown documentation and structured YAML/JSON where suitable. Preserve generated content and managed sections under their documented source-of-truth process.
- Run relevant checks and report actual results. Never claim CI success, compliance, or control effectiveness without evidence.
- Use small, reviewable PRs with rationale, impact, validation, rollback, and approvals needed.


## Full governance reference
See [governance/PORTFOLIO-GOVERNANCE.md](governance/PORTFOLIO-GOVERNANCE.md) for the complete approved v1.0.0 portfolio guidance. The canonical source is [kazbrekker-ai/ai-governance](https://github.com/kazbrekker-ai/ai-governance/tree/58e2f8c39f71dbd6b468d8733e33caa5c6263e2d). The local file is a pinned reference copy, not an independent authority.
