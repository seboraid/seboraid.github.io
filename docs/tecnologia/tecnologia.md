---
title: Tecnología (Sebastian Perez)
---

# Tecnología

Todo está en constante construcción, asi que empezaré por los temas que tengo más a mano.

- [Lecturas](lecturas.md)
- [Logros](metas-y-logros.md)

## Infraestructura Cloud

Algunas herramientas y snippets de utilidad.

### Herramientas

Scripts para analizar el código IaC.

Un muy buen artículo sobre las herramientas en (gitlab)[https://about.gitlab.com/blog/2022/02/17/fantastic-infrastructure-as-code-security-attacks-and-how-to-find-them/] y como implementarlas en los pipelines de CI/CD

(Checov)[https://www.checkov.io/]
It is for analyzing static codes for IaC. To detect cloud misconfigurations, it scans your cloud infrastructure, which is managed in Kubernetes, Terraform, and Cloudformation.

Checkov is a Python-based software. Therefore, writing, managing, codes, and version control become simpler. The built-in policies of Checkov cover the best practices for compliance and security for Google Cloud, Azure, and AWS.

- Includes hundreds of out-of-the-box policies from frameworks (CIS, PCI, HIPAA, and more) and community-sourced checks
- Integrates with VS Code, Jenkins, GitHub, and GitLab
- Open source and fully extensible by adding custom checks, skip lists, and integrations with other tools

(Terrascan)[https://runterrascan.io/]

(tfsec)[https://github.com/aquasecurity/tfsec]
- ☁️ Checks for misconfigurations across all major (and some minor) cloud providers
- ⛔ Hundreds of built-in rules
- 🪆 Scans modules (local and remote)
- ➕ Evaluates HCL expressions as well as literal values
- ↪️ Evaluates Terraform functions e.g. concat()
- 🔗 Evaluates relationships between Terraform resources
- 🧰 Compatible with the Terraform CDK
- 🙅 Applies (and embellishes) user-defined Rego policies
- 📃 Supports multiple output formats: lovely (default), JSON, SARIF, CSV, CheckStyle, JUnit, text, Gif.
- 🛠️ Configurable (via CLI flags and/or config file)
- ⚡ Very fast, capable of quickly scanning huge repositories
- 🔌 Plugins for popular IDEs available (JetBrains, VSCode and Vim)

