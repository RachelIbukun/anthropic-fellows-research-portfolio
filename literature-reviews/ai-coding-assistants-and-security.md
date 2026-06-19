# Literature Review

## Topic

AI Coding Assistants and Software Security

## Overview

AI coding assistants are increasingly used to generate application code, infrastructure configurations, tests, deployment pipelines, and troubleshooting recommendations. Their adoption is driven by significant productivity gains, but questions remain regarding their impact on software security and long-term engineering quality.

This review examines emerging evidence relating to AI assisted software development and security outcomes.

## Potential Benefits

Research and industry experience suggest that AI coding assistants can:

* Accelerate software development
* Improve developer productivity
* Reduce repetitive work
* Improve onboarding for junior engineers
* Support debugging and documentation

These benefits have driven rapid adoption across engineering teams.

## Security Concerns

Several studies and public evaluations have identified recurring concerns:

### Insecure Code Generation

AI systems may generate:

* Vulnerable authentication logic
* Unsafe input handling
* Weak access controls
* Insecure defaults

### Dependency Risk

AI generated recommendations may include:

* Outdated libraries
* Vulnerable packages
* Unmaintained dependencies

### Overconfidence

Developers may place excessive trust in generated outputs, reducing critical review and increasing the likelihood that vulnerabilities reach production systems.

### Security Debt

AI assisted development may increase productivity while creating future remediation costs.

## Relevance to Frontier Model Evaluation

Traditional coding benchmarks primarily measure correctness and capability.

Security sensitive deployments require additional evaluation criteria:

* Safety
* Reliability
* Security
* Auditability
* Human review effectiveness

## Open Questions

* Which vulnerabilities are most frequently introduced by AI coding assistants?
* How effectively can existing security tools detect these vulnerabilities?
* Does AI assistance affect developer security judgement?
* What governance mechanisms should organisations adopt?

## Personal Reflection

The central challenge is not whether AI coding assistants improve productivity. The more important question is whether organisations can realise those productivity gains without increasing security exposure and long-term operational risk.
