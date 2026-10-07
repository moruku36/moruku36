# Kentaro Mori

[English](README.md) | [日本語](README.ja.md)

I build and document hands-on experiments across cloud, AI, and security.  
My work focuses on validating real-world architectures, AI-assisted workflows, and security technologies through practical implementation and testing.

## Cloud validation — start here

- **[Level 2: Multi-cloud Terraform Validation](https://github.com/moruku36/cloud-validation-level2-multicloud)** — a consolidated comparison of AWS, Azure, and Google Cloud infrastructure lifecycles, with implementation evidence, CI/CD, monitoring, failure tests, and cleanup records.
- **[Level 3: Cloud Architecture Validation](https://github.com/moruku36/cloud-validation-level3-astra-light)** — phased architecture decisions, cost and risk reviews, and verification records. The current C-1 phase is safely halted; no live resources have been created for that phase.
- **Provider-specific records:** [AWS](https://github.com/moruku36/aws-ai-terraform-validation) · [Azure](https://github.com/moruku36/azure-ai-terraform-validation) · [Google Cloud](https://github.com/moruku36/gcp-ai-terraform-validation).

## AI and security projects

- [AI Engineering Factory](https://github.com/moruku36/ai-engineering-factory) — a **MANUAL_ONLY experiment** for reviewing AI coding-agent outputs, with bounded artifact receipts and JUnit report checks. [Verification evidence](https://github.com/moruku36/ai-engineering-factory/blob/main/docs/defensive-evidence.md).
- [Local AI Sidekick](https://github.com/moruku36/local-ai-sidekick) — a bounded local coding worker powered by Ollama.
- [Qwen Multimodal Colab](https://github.com/moruku36/qwen-multimodal-colab) — a Colab-based Qwen app for chat, image understanding and generation, speech input, and web search.
- [PQC Crypto Inventory Lab](https://github.com/moruku36/pqc-crypto-inventory-lab) — an **educational lab** for reviewing cryptography in source and configuration, with bounded-read and export regression tests. Findings do not establish runtime use or quantum safety. [Verification evidence](https://github.com/moruku36/pqc-crypto-inventory-lab/blob/main/docs/defensive-evidence.md).

These repositories include experiments and learning projects as well as more developed work. Check each README for its current status and limits before reproducing infrastructure or running an AI workflow.

More writing: [Zenn](https://zenn.dev/kentaro36) · [LinkedIn](https://www.linkedin.com/in/kentaro-mori-4592a1169/).
