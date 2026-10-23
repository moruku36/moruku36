# Kentaro Mori

[English](README.md) | [日本語](README.ja.md)

I build and document hands-on experiments across cloud, AI, and security.  
My work focuses on validating real-world architectures, AI-assisted workflows, and security technologies through practical implementation and testing.

## AI, Cloud, and Security Projects

### AI workflows

- [Local AI Sidekick](https://github.com/moruku36/local-ai-sidekick) — a bounded local Ollama coding worker that returns changes for lead review. [A real local GPU end-to-end run](https://github.com/moruku36/local-ai-sidekick/pull/16) passed on synthetic repositories; production use is unverified.
- [AI Governance Control](https://github.com/moruku36/ai-governance-control) — an experimental **MANUAL_ONLY** framework for checking task artifacts and recording human approvals. Its [status notification contract](https://github.com/moruku36/ai-governance-control/pull/49) does not send notifications; merge and deployment remain human decisions.
- [Multi-cloud SRE Agent Research](https://github.com/moruku36/multicloud-sre-agent-survey-2026) — a source-linked survey and a [packaged, offline synthetic demo](https://github.com/moruku36/multicloud-sre-agent-survey-2026/pull/5) using fake AWS, Azure, and Google Cloud responses. Execution and recovery verification were not run; no live cloud remediation was tested.

### Cloud validation

- [Level 2: Multi-cloud Security Validation](https://github.com/moruku36/cloud-validation-level2-multicloud) and [Level 3: Cloud Security & Architecture Validation](https://github.com/moruku36/cloud-validation-level3-architect) — Terraform-based infrastructure checks in Level 2; architecture decisions and cost and risk records in Level 3. See each repository for its validation scope.
- [OCI Validation Lab](https://github.com/moruku36/oci-validation-lab) — foundations study and offline models. A [limited OCI Console exercise](https://github.com/moruku36/oci-validation-lab/pull/2) created and deleted a temporary VCN and private subnet; Level 1 completion and live Terraform deployment remain unverified.

### Defensive security

- [Personal Security Auditor](https://github.com/moruku36/personal-security-auditor) — a local CLI for selected workstation checks without collecting secret values. Its [read-only Linux adapter](https://github.com/moruku36/personal-security-auditor/pull/9) has synthetic test coverage but no physical Linux device validation.
- [Web Security Control Lab](https://github.com/moruku36/web-security-control-lab) — a localhost-only educational lab for observing, scanning, fixing, and rechecking six web controls in vulnerable and hardened modes. The hardened lab is not a production security guarantee.

## Research & Reports

I also publish and continuously update independent research, technical surveys, and analysis reports alongside my hands-on projects.

- [2026 Company Analysis](https://github.com/moruku36/nri-2026-company-analysis) — company analysis and research notes.
- [Security Landscape 2026](https://github.com/moruku36/security-landscape-2026) — security technology and industry landscape research.
- [Independent CS Research 2026](https://github.com/moruku36/independent-cs-research-2026) — independent computer science research and survey notes.

These repositories include experiments and learning projects as well as more developed work. Check each README for its current status and limits before reproducing infrastructure or running an AI workflow.

More writing: [Zenn](https://zenn.dev/kentaro36) · [DEV Community](https://dev.to/moruku36) · [note](https://note.com/moruku1887) · [Medium](https://medium.com/@kentaro.mori36).
