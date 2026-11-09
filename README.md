# kazbrekker-ai

A portfolio of practical tools and platforms spanning AI-assisted engineering, infrastructure operations, security automation, compliance mapping, and personal productivity.

The projects share a common direction: **make complex technical work easier to plan, operate, secure, and explain**—with an emphasis on automation, local-first or self-hosted deployment where practical, and human review for consequential changes.

> Repository visibility varies. Some projects are private and may not be accessible to visitors.

## Project areas

### AI and engineering tools

| Project | What it does |
| --- | --- |
| [Cairn](https://github.com/kazbrekker-ai/cairn) | A local platform hub for product discovery, plugin integration, task coordination, and controlled automation. |
| [AI Deployment Planner](https://github.com/kazbrekker-ai/ai-deployment-planner) | Helps evaluate AI model deployment options against hardware and capacity constraints. |
| [Datacenter Modeler](https://github.com/kazbrekker-ai/datacenter-modeler) | Models datacenter, rack, and floor capacity, with AI-assisted workflows. |
| [License Modeler](https://github.com/kazbrekker-ai/license-modeler) | Evaluates software licensing scenarios and produces explainable reports. |

### Infrastructure and security

| Project | What it does |
| --- | --- |
| [Homelab Ops](https://github.com/kazbrekker-ai/homelab-ops) | Infrastructure-as-code and operational workflows for a self-hosted environment, including Kubernetes and secrets management. |
| [NetDefender](https://github.com/kazbrekker-ai/netdefender) | Network and platform security operations, monitoring, and automation. |
| [Asset Inventory](https://github.com/kazbrekker-ai/asset-inventory) | Collects and reports on infrastructure and technology assets. |
| [Security Workflows](https://github.com/kazbrekker-ai/security-workflows) | Reusable CI security, software supply-chain, scanning, and provenance workflows. |

### Governance, research, and knowledge

| Project | What it does |
| --- | --- |
| [Control Mapper](https://github.com/kazbrekker-ai/control-mapper) | Organizes and maps security, AI, and governance controls across frameworks. |
| [RegWatch](https://github.com/kazbrekker-ai/regwatch) | Tracks regulatory developments and proposes relevant control-catalog updates for human review. |
| [Arch Digest](https://github.com/kazbrekker-ai/arch-digest) | Aggregates technical reading and produces AI-assisted digests. |
| [Study Coach](https://github.com/kazbrekker-ai/study-coach) | Supports structured learning and spaced-repetition study workflows. |
| [Privacy Brief](https://github.com/kazbrekker-ai/privacy-brief) | A desktop-oriented personal briefing tool with privacy-conscious local integrations. |

### Shared repository resources

- [Personas](https://github.com/kazbrekker-ai/personas) — reserved for persona-related resources; currently an empty repository.
- [.github](https://github.com/kazbrekker-ai/.github) — shared GitHub community and repository-level documentation.

## Architecture and engineering themes

Across the portfolio, recurring technologies and patterns include:

- **Python** for automation, APIs, data processing, and command-line tools.
- **Docker Compose** for reproducible local services and one-shot jobs.
- **Kubernetes / RKE2, Helm, and Ansible** for infrastructure operations.
- **Ollama and local models**, with optional hosted model integrations where appropriate.
- **GitHub Actions and supply-chain controls**, including scanning, SBOM generation, signing, and provenance.
- **Structured data and portable outputs** such as YAML, JSON, CSV, Markdown, and reports.
- **Human approval gates** for proposed governance changes and other consequential actions.

The projects are not one monolith. They are separate tools with their own responsibilities. Where integration is useful, the intent is to exchange versioned, documented data and keep ownership of each product's runtime with that product.

## Repository lifecycle

Some earlier experiments have been consolidated into maintained projects:

- **jarvis-brief** is archived; relevant collectors were absorbed into [NetDefender](https://github.com/kazbrekker-ai/netdefender).
- **homelab-secrets** is archived; its operational history and workflows were incorporated into [Homelab Ops](https://github.com/kazbrekker-ai/homelab-ops).

Archived repositories remain useful as historical context, but are not the recommended starting point for new work.

## Working principles

1. **Prefer useful automation over automation for its own sake.**
2. **Make decisions inspectable** through documented inputs, outputs, and reports.
3. **Keep sensitive operations bounded**, with explicit permissions and human review where warranted.
4. **Favor repeatable deployments** and infrastructure-as-code.
5. **Design for maintainability**, clear ownership, and incremental integration.

## Getting started

Choose the repository closest to the problem you want to solve and start with its README and documentation. For infrastructure projects, review deployment and security notes before applying changes to a live environment.

Questions, issues, and contributions should be directed to the relevant project repository.