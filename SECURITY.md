# Security Policy

The Raeburn Group treats security as an operating discipline rather than a marketing claim.

This policy is the organisation-wide default for repositories maintained through **The Raeburn Group** GitHub organisation. Individual repositories may define additional product-specific controls, supported versions or disclosure instructions.

## Reporting a security issue

Please do **not** open a public GitHub issue containing vulnerability details, credentials, personal data or confidential infrastructure information.

Report suspected vulnerabilities or security concerns in good faith to:

**contact@theraeburngroup.com**

Use a clear subject such as `Security disclosure — <repository or service>` and include enough information to understand or reproduce the issue without unnecessarily accessing, retaining or sharing sensitive data.

Canonical Group disclosure information is also published at:

- `https://trust.theraeburngroup.com/.well-known/security.txt`
- `https://trust.theraeburngroup.com`

Where GitHub private vulnerability reporting is enabled for a repository, that route may also be used.

## Scope

Depending on the repository, relevant security issues may include:

- authentication or authorisation bypass;
- secret or credential exposure;
- cross-tenant or cross-workspace access;
- insecure file handling;
- injection vulnerabilities;
- unsafe agent, automation or tool execution;
- prompt-injection or model/tool boundary weaknesses;
- data exposure;
- supply-chain or dependency risks;
- insecure defaults or deployment guidance.

The presence of Group-wide standards does not imply that every subsidiary, repository or product uses identical technology, suppliers or controls.

## Security principles

Projects should apply controls proportionate to their risk, which may include:

- least-privilege access;
- explicit human approval for high-impact automated actions;
- secrets kept out of source control;
- clear trust boundaries for tools, integrations and external systems;
- dependency review and reproducible build practices where practical;
- audit logging for sensitive operations;
- safe deployment defaults;
- documented production assumptions and limitations.

## Responsible disclosure expectations

Please:

- avoid destructive, invasive or availability-impacting testing;
- do not use social engineering, credential stuffing, denial-of-service techniques or brute force;
- minimise access to personal, confidential or customer information;
- do not retain data beyond what is reasonably necessary to demonstrate a finding;
- allow reasonable time for triage and remediation before public disclosure;
- provide reproducible evidence rather than speculative severity claims.

## Supported versions

The authoritative support status is stated by each repository. A default branch, CI workflow or security document should not be interpreted as proof that a project is a supported production service unless the repository explicitly says so.

## No certification claim

Repository policies, automated scans, dependency checks and Trust Centre material do not by themselves constitute a penetration test, SOC report, ISO certification, Cyber Essentials certification or other independent assurance opinion.
