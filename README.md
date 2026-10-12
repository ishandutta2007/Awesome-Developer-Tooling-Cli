# Awesome-Developer-Tooling-Cli

# Top Developer Tooling CLI Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Command-Line Interfaces, Cloud SDKs & Development Workflows*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Developer Tooling CLI**. These tools enable developers to manage cloud infrastructure, deploy applications, interact with APIs, and automate workflows directly from the terminal — streamlining development, operations, and release processes.

**Examples** include Salesforce Platform Developer Tools, GitHub CLI, AWS CLI, Azure CLI, Google Cloud SDK, HashiCorp Terraform CLI, Vercel CLI, Netlify CLI, Stripe CLI, and Supabase CLI (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom CLI frameworks, and open developer tooling — ideal for platform engineers, DevOps teams, and developers seeking transparent, vendor-independent command-line solutions.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesforce Platform Developer Tools (Salesforce CLI)](https://developer.salesforce.com/tools/salesforcecli)**  
  Modern CLI (`sf`) for Salesforce development, deployment, and org management. Answers to both `sfdx` and `sf` commands, knows all legacy and current commands. Distributed via npm under `@salesforce` scope. Docker images available in `salesforce/cli` with slim and full flavors .

- **[GitHub CLI](https://cli.github.com/)**  
  GitHub's official command line tool (`gh`) bringing pull requests, issues, releases, and workflows to the terminal. Supports GitHub.com, Enterprise Cloud, and Enterprise Server. Releases are published as immutable with Build Provenance Attestation since v2.93.0 .

- **[AWS CLI](https://aws.amazon.com/cli/)**  
  Universal Command Line Interface for Amazon Web Services. 16,857+ GitHub stars, 4,510+ forks. Enables managing all AWS services from the terminal with extensive bash scripting examples available .

- **[Azure CLI](https://learn.microsoft.com/cli/azure/)**  
  Cross-platform command line tool for managing Microsoft Azure resources and services. Next-generation multi-platform experience with install guides, Docker tags, and sample repositories available .

- **[Google Cloud SDK](https://cloud.google.com/sdk)**  
  Suite of libraries and tools including `gcloud` CLI for managing Google Cloud resources. Includes Cloud Client Libraries for Java, Python, Node.js, Go, .NET, and more, plus emulators for local development and Cloud Code IDE extensions .

- **[HashiCorp Terraform CLI](https://developer.hashicorp.com/terraform/install)**  
  Infrastructure as Code CLI for provisioning and managing cloud resources. Current version 1.16.5 with SHA256 checksums and GPG signatures for verification. Core Terraform CLI is open source under MPL-2.0 .

- **[Vercel CLI](https://vercel.com/docs/cli)**  
  Frontend cloud CLI for deploying and managing applications. Install via `npm i -g vercel`, then `vercel` to deploy. Features MCP integration for AI agents, storage provisioning via `vercel install`, and plugin support for Claude Code, Cursor, and GitHub Copilot .

- **[Netlify CLI](https://docs.netlify.com/cli/get-started/)**  
  Command line tool for Netlify deployments, functions, and site management. 11,282+ dependent repositories, 768,172+ downloads. Ranked in top 0.24% by dependent repos on npm .

- **[Stripe CLI](https://stripe.com/docs/stripe-cli)**  
  Command-line tool for Stripe (`stripe`). Apache-2.0 licensed with 1,397+ GitHub stars, 351+ forks. Features webhook forwarding, logs tailing, resource commands, fixtures, and plugin system for extending functionality .

- **[Supabase CLI](https://supabase.com/docs/guides/cli)**  
  Open source Firebase alternative CLI (`supabase`). Features local development stack, database migrations, edge functions deployment, type generation, and project management. Install via npm, Homebrew, Scoop, or Go .

## Open-Source GitHub Projects

- **[GitHub CLI (gh)](https://github.com/cli/cli)**  
  GitHub's official command line tool (MIT license). 40k+ GitHub stars. Agent skills available for driving `gh` from coding agents via `gh skill install cli/cli gh`. Supported on macOS, Windows, and Linux with weekly updates on GitHub Actions runners .

- **[AWS CLI](https://github.com/aws/aws-cli)**  
  Universal Command Line Interface for Amazon Web Services (Apache-2.0). 16,857+ GitHub stars, 4,510+ forks, 8,300+ commits. Allows forking and viewing source code, with community feedback and contributions welcome .

- **[Azure CLI](https://github.com/Azure/azure-cli)**  
  Microsoft's cross-platform command line experience for Azure (MIT). Features IntelliSense for `.ps1` and `.sh` files, Docker tags via MCR, and sample repositories. Authoring command modules and code generation tools available .

- **[Terraform](https://github.com/hashicorp/terraform)**  
  Infrastructure as Code tool (MPL-2.0). Core Terraform CLI contains the main engine. Build with Go compiler and Git. Unit tests with `go test ./...`. Development environment targets Linux and macOS .

- **[DevKit](https://github.com/azlanabdulla/dev-kit)**  
  Swiss Army Knife for Developers (MIT). Modern, extensible CLI toolbox with 17 plugins: password generation, UUID, hashing, Base64, archives, encryption, system monitoring, network tools, env management, image/PDF processing, QR codes, JSON formatting, text utilities, time parsing, and web converters. Built with Typer and Rich .

- **[go-tool-base](https://gitlab.com/phpboyscout/go-tool-base)**  
  Go framework for building CLIs with Cobra (license varies). Features changelog, docs browser (Bubble Tea TUI), config management, doctor diagnostics, man page generation, telemetry, self-update from GitHub/GitLab, and MCP integration .

- **[Hoppscotch](https://github.com/hoppscotch/hoppscotch)**  
  Open-source API request builder (MIT) — alternative to Postman. 70k+ GitHub stars. Lightweight browser-based UI with collections, environments, and team collaboration.

- **[Insomnia](https://github.com/Kong/insomnia)**  
  Open-source API client (Apache-2.0) for REST, GraphQL, and gRPC. Cross-platform desktop app with environment variables, code generation, and plugin ecosystem.

- **[Bruno](https://github.com/usebruno/bruno)**  
  Fast, Git-friendly API client (MIT). Stores collections as plain files for version control. Alternative to Postman/Insomnia.

- **[k9s](https://github.com/derailed/k9s)**  
  Kubernetes CLI to manage clusters in style (Apache-2.0). Terminal UI for cluster management with resource views, logs, and shell access.

- **[kubectl](https://github.com/kubernetes/kubectl)**  
  Kubernetes command-line tool (Apache-2.0). Essential for managing Kubernetes clusters, deployments, and services from the terminal.

- **[helm](https://github.com/helm/helm)**  
  Kubernetes package manager (Apache-2.0). CLI for managing charts, releases, and repositories.

- **[Docker CLI](https://github.com/docker/cli)**  
  Docker's command-line interface (Apache-2.0). Manages containers, images, volumes, and networks from the terminal.

### Additional Strong Open-Source Options

- **[fzf](https://github.com/junegunn/fzf)** — Command-line fuzzy finder (MIT) for interactive filtering.
- **[ripgrep](https://github.com/BurntSushi/ripgrep)** — Fast recursive search tool (MIT/Unlicense).
- **[bat](https://github.com/sharkdp/bat)** — Cat clone with syntax highlighting (MIT/Apache-2.0).
- **[exa](https://github.com/ogham/exa)** — Modern replacement for `ls` (MIT).
- **[zoxide](https://github.com/ajeetdsouza/zoxide)** — Smarter `cd` command (MIT).
- **[lazygit](https://github.com/jesseduffield/lazygit)** — Terminal UI for Git (MIT).
- **[delta](https://github.com/dandavison/delta)** — Syntax-highlighting pager for Git (MIT).
- **[httpie](https://github.com/httpie/cli)** — User-friendly HTTP client CLI (BSD-3-Clause).

**Frameworks for building custom systems**: Combine **Cobra** or **Typer** for CLI structure with **go-tool-base** for Go-based tooling, **DevKit** for utility plugins, **Hoppscotch** or **Bruno** for API interaction, and **k9s** for Kubernetes management — creating a fully self-hosted, enterprise-grade developer CLI toolkit.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- CLIs managing cloud resources and credentials must follow security best practices (token rotation, least privilege, secure storage).
- Self-hosted open-source solutions require proper security hardening, ongoing maintenance, and version management for production reliability.

---

**Made for developers, platform engineers, DevOps teams, and organizations building transparent command-line tooling.**  
Let's make Developer Tooling CLI more open, data-driven, and efficient.
