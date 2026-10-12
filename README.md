<div align="center">

<img src="https://raw.githubusercontent.com/ishandutta2007/Awesome-Developer-Tooling-Cli/main/assets/banner.svg" alt="Awesome Developer Tooling CLI Banner" width="100%" />

# ⚡ Awesome Developer Tooling CLI 🛠️

**A Curated Directory of Command-Line Interfaces, Cloud SDKs, Developer TUIs, and Terminal Productivity Tools**

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Developer-Tooling-Cli/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Developer-Tooling-Cli?style=flat-square&logo=github&color=gold" alt="GitHub_Stars" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Developer-Tooling-Cli/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Developer-Tooling-Cli?style=flat-square&color=blue" alt="GitHub Forks" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Developer-Tooling-Cli/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-green.svg?style=flat-square" alt="License" /></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

<p align="center">
  <em>Supercharge your developer workflow, automate cloud deployments, manage container clusters, and elevate your terminal experience.</em>
</p>

</div>

---

## 📖 Table of Contents

- [🌟 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [🏢 SaaS & Hosted Platforms](#-saas--hosted-platforms)
- [💻 Open-Source GitHub Projects](#-open-source-github-projects)
  - [🧰 CLI Frameworks & Utilities](#-cli-frameworks--utilities)
- [📈 Star History](#-star-history)
- [💖 Support & Sponsorship](#-support--sponsorship)
- [🤝 How to Contribute](#-how-to-contribute)
- [⚖️ Disclaimer](#️-disclaimer)

---

## 🌟 Sector Overview & Market Dynamics

The global **Developer Tooling and DevOps Software Market** is estimated at **$13.5B – $16.2B in 2026** (projected to reach over $30B by 2030, registering a CAGR of ~18–22%). 

Market dynamics exhibit a **bifurcated, moderately fragmented ecosystem**:
- **Core Cloud Infrastructure & Platform CLIs** are concentrated around hyperscale cloud providers (*Amazon Web Services, Microsoft Azure, Google Cloud*) and dominant platforms (*Salesforce, GitHub, Stripe*), where high switching costs and ecosystem lock-in prevail.
- **Developer Productivity, Micro-Tooling, and CLI Utilities** remain **highly fragmented and decentralized**, driven by rapid open-source innovation, developer preference for lightweight modular Rust/Go utilities (*uv, fzf, lazygit, ripgrep*), and local-first open workflows.

---

## 🏢 SaaS & Hosted Platforms

The following table benchmarks category-leading hosted developer platforms and their official CLI tooling. Companies are sorted in descending order by **Company Size (Market Capitalization / Valuation)**.

| Company & CLI Tool | Company Size (Valuation / Revenue) | Starting Pricing (Paid Tiers) | Free Tier Limits / Free Trial | Key Capabilities |
| :--- | :--- | :--- | :--- | :--- |
| **[Microsoft Azure CLI](https://learn.microsoft.com/cli/azure/)** (`az`) | **$3.15 Trillion** Market Cap (~$245B Ann. Revenue) | $29.00/month (Developer Support Tier) + Pay-as-you-go resource consumption | **Free Forever**: 55+ services free (including Azure App Service 10 apps, 1M Azure Functions requests/mo, 100K Cognitive Services API calls/mo) + **$200 credit** for first 30 days. | Cross-platform CLI to provision, configure, and automate Azure infrastructure, Kubernetes clusters, and resource groups. |
| **[AWS CLI](https://aws.amazon.com/cli/)** (`aws`) | **$2.20 Trillion** Market Cap (~$105B AWS Ann. Revenue) | $29.00/month (AWS Developer Support) + Pay-as-you-go resource usage | **Free Forever**: 1M AWS Lambda requests/mo, 1M SNS requests/mo, 25 GB DynamoDB storage; **12-Month Free Tier**: 750 hours/mo EC2 t2.micro/t3.micro, 5 GB S3 standard storage. | Universal command-line interface to orchestrate, deploy, and script across 200+ AWS cloud services. |
| **[Google Cloud SDK](https://cloud.google.com/sdk)** (`gcloud`) | **$2.10 Trillion** Market Cap (~$38B GCP Ann. Revenue) | Pay-as-you-go resource pricing; Standard customer support starting at $29.00/user/month | **Free Forever**: 1 e2-micro VM instance/mo (US regions), 2M Cloud Functions invocations/mo, 5 GB Cloud Storage, 1 GB Firestore; **$300 free trial credits** valid for 90 days. | Unified SDK including `gcloud`, `gsutil`, and `bq` for Google Cloud resources, compute instances, BigQuery, and local service emulators. |
| **[Salesforce Platform CLI](https://developer.salesforce.com/tools/salesforcecli)** (`sf` / `sfdx`) | **$280 Billion** Market Cap (~$38B Ann. Revenue) | $25.00/user/month (Starter Suite billed annually) | **Free Developer Edition**: Lifetime free sandbox environment with 2 Salesforce standard user licenses, 5 MB data storage, and 20 MB file storage for custom app builds and testing. | Unified CLI for Salesforce DX, org authorizations, metadata deployments, packaging, and CI/CD pipelines. |
| **[Stripe CLI](https://stripe.com/docs/stripe-cli)** (`stripe`) | **$70 Billion** Valuation (~$16B Ann. Revenue) | 2.9% + 30¢ per successful card charge (Pay-as-you-go processing) | **Free Forever Sandbox**: Full developer testmode access with unlimited simulated API calls, real-time webhook event forwarding, fixture testing, and test clocks with $0 subscription fee. | Stream live webhook events to `localhost`, test payment flows, inspect API logs, and trigger test fixture payloads. |
| **[GitHub CLI](https://cli.github.com/)** (`gh`) | **$50 Billion+** Sub-Valuation (~$4B Ann. ARR / Owned by Microsoft) | $4.00/user/month (Team plan) | **Free Forever**: Unlimited public & private repositories, 2,000 GitHub Actions CI/CD minutes/month, 500 MB GitHub Packages storage, community issue/PR management. | Official GitHub CLI bringing pull request creation, issue tracking, GitHub Actions logs, and code reviews directly to the terminal. |
| **[HashiCorp Terraform CLI](https://developer.hashicorp.com/terraform/install)** (`terraform`) | **$6.4 Billion** Valuation (Acquired by IBM) | $0.00014/run-minute (~$20/month per active team workspace on HCP Terraform Standard) | **Free Forever HCP Tier**: Up to 500 managed resources/month with free state management, plan/apply runs, private module registry, and CLI integration. | Standard-bearer declarative Infrastructure as Code (IaC) tool for provisioning multi-cloud resources and orchestration. |
| **[Vercel CLI](https://vercel.com/docs/cli)** (`vercel`) | **$3.25 Billion** Valuation (~$100M+ Ann. ARR) | $20.00/member/month (Vercel Pro Tier) | **Free Hobby Plan Forever**: 100 GB monthly bandwidth, 300 serverless execution unit hours/month, unlimited personal preview deployments, and 1 concurrent build. | High-performance frontend cloud CLI for edge deployments, serverless functions, project linking, and environment variable management. |
| **[Supabase CLI](https://supabase.com/docs/guides/cli)** (`supabase`) | **$1.5 Billion** Valuation (Series C / Leading BaaS) | $25.00/project/month (Supabase Pro Tier) | **Free Forever Tier**: 2 active free projects, 500 MB Postgres database storage, 1 GB file storage, 50,000 monthly active users (MAU), and 500K Edge Function invocations/month. | Open-source Firebase alternative CLI for local Docker-based database stack, schema migrations, Edge Functions deploy, and TypeScript typegen. |
| **[Netlify CLI](https://docs.netlify.com/cli/get-started/)** (`netlify`) | **$750 Million** Valuation (~$60M Ann. ARR) | $19.00/member/month (Netlify Pro Tier) | **Free Starter Plan Forever**: 100 GB bandwidth/month, 300 build minutes/month, 100 concurrent form submissions, and instant branch deploy previews. | CLI tool to deploy modern web projects, test Netlify Functions locally, configure DNS/domains, and tail build logs. |

---

## 💻 Open-Source GitHub Projects

Curated list of developer tools, terminal companions, and API clients. Sorted in descending order by **GitHub_Stars_Count (⭐)**. Every Stars_Badge links directly to the project's stargazers community page.

| Repository | GitHub_Stars | License | Description |
| :--- | :--- | :--- | :--- |
| **[astral-sh/uv](https://github.com/astral-sh/uv)** | [![Stars](https://img.shields.io/github/stars/astral-sh/uv?style=social&color=white)](https://github.com/astral-sh/uv/stargazers) | Apache-2.0 / MIT | Blazing-fast Python package installer and resolver written in Rust. Drop-in replacement for `pip`, `pip-tools`, and `virtualenv`. |
| **[junegunn/fzf](https://github.com/junegunn/fzf)** | [![Stars](https://img.shields.io/github/stars/junegunn/fzf?style=social&color=white)](https://github.com/junegunn/fzf/stargazers) | MIT | General-purpose interactive command-line fuzzy finder with async search, preview windows, and shell bindings. |
| **[jesseduffield/lazygit](https://github.com/jesseduffield/lazygit)** | [![Stars](https://img.shields.io/github/stars/jesseduffield/lazygit?style=social&color=white)](https://github.com/jesseduffield/lazygit/stargazers) | MIT | Simple, intuitive terminal UI for Git commands to stage hunks, resolve conflicts, and navigate branches effortlessly. |
| **[hoppscotch/hoppscotch](https://github.com/hoppscotch/hoppscotch)** | [![Stars](https://img.shields.io/github/stars/hoppscotch/hoppscotch?style=social&color=white)](https://github.com/hoppscotch/hoppscotch/stargazers) | MIT | Lightweight open-source API development ecosystem, web client, desktop client, and CLI — alternative to Postman. |
| **[BurntSushi/ripgrep](https://github.com/BurntSushi/ripgrep)** | [![Stars](https://img.shields.io/github/stars/BurntSushi/ripgrep?style=social&color=white)](https://github.com/BurntSushi/ripgrep/stargazers) | MIT / Unlicense | Ultra-fast line-oriented search tool (`rg`) that recursively searches directories for regex patterns respecting `.gitignore`. |
| **[sharkdp/bat](https://github.com/sharkdp/bat)** | [![Stars](https://img.shields.io/github/stars/sharkdp/bat?style=social&color=white)](https://github.com/sharkdp/bat/stargazers) | MIT / Apache-2.0 | A `cat` clone with syntax highlighting, Git integration, automatic paging, and file concatenation support. |
| **[starship/starship](https://github.com/starship/starship)** | [![Stars](https://img.shields.io/github/stars/starship/starship?style=social&color=white)](https://github.com/starship/starship/stargazers) | ISC | Minimal, lightning-fast, and infinitely customizable cross-shell prompt for any shell (Bash, Zsh, Fish, PowerShell). |
| **[hashicorp/terraform](https://github.com/hashicorp/terraform)** | [![Stars](https://img.shields.io/github/stars/hashicorp/terraform?style=social&color=white)](https://github.com/hashicorp/terraform/stargazers) | MPL-2.0 / BSL | Industry-standard declarative Infrastructure as Code engine to codify multi-cloud APIs into versioned config files. |
| **[usebruno/bruno](https://github.com/usebruno/bruno)** | [![Stars](https://img.shields.io/github/stars/usebruno/bruno?style=social&color=white)](https://github.com/usebruno/bruno/stargazers) | MIT | Fast, Git-friendly offline API client storing collections directly in plain text files in your repository. |
| **[cli/cli](https://github.com/cli/cli)** | [![Stars](https://img.shields.io/github/stars/cli/cli?style=social&color=white)](https://github.com/cli/cli/stargazers) | MIT | GitHub's official command-line interface (`gh`) to manage pull requests, issues, releases, and CI/CD secrets. |
| **[spf13/cobra](https://github.com/spf13/cobra)** | [![Stars](https://img.shields.io/github/stars/spf13/cobra?style=social&color=white)](https://github.com/spf13/cobra/stargazers) | Apache-2.0 | Standard Go library for creating powerful modern CLI applications (powers `kubectl`, `hugo`, `gh`, and `docker`). |
| **[ajeetdsouza/zoxide](https://github.com/ajeetdsouza/zoxide)** | [![Stars](https://img.shields.io/github/stars/ajeetdsouza/zoxide?style=social&color=white)](https://github.com/ajeetdsouza/zoxide/stargazers) | MIT | Smarter `cd` command that remembers directories you use most frequently, navigating with minimal keystrokes. |
| **[Kong/insomnia](https://github.com/Kong/insomnia)** | [![Stars](https://img.shields.io/github/stars/Kong/insomnia?style=social&color=white)](https://github.com/Kong/insomnia/stargazers) | Apache-2.0 | Open-source API design and testing platform for REST, GraphQL, gRPC, WebSockets, and Server-Sent Events. |
| **[httpie/cli](https://github.com/httpie/cli)** | [![Stars](https://img.shields.io/github/stars/httpie/cli?style=social&color=white)](https://github.com/httpie/cli/stargazers) | BSD-3-Clause | User-friendly HTTP client CLI with JSON formatting, syntax coloring, persistent sessions, and auth workflows. |
| **[jdx/mise](https://github.com/jdx/mise)** | [![Stars](https://img.shields.io/github/stars/jdx/mise?style=social&color=white)](https://github.com/jdx/mise/stargazers) | MIT | Polyglot runtime version manager, task runner, and environment variable manager (replacement for `asdf` & `direnv`). |
| **[derailed/k9s](https://github.com/derailed/k9s)** | [![Stars](https://img.shields.io/github/stars/derailed/k9s?style=social&color=white)](https://github.com/derailed/k9s/stargazers) | Apache-2.0 | Terminal-based UI to interact with your Kubernetes clusters, inspect pods, stream logs, and manage resources. |
| **[dandavison/delta](https://github.com/dandavison/delta)** | [![Stars](https://img.shields.io/github/stars/dandavison/delta?style=social&color=white)](https://github.com/dandavison/delta/stargazers) | MIT | Syntax-highlighting and side-by-side diff viewer and pager for Git, diff, and grep output. |
| **[helm/helm](https://github.com/helm/helm)** | [![Stars](https://img.shields.io/github/stars/helm/helm?style=social&color=white)](https://github.com/helm/helm/stargazers) | Apache-2.0 | The Kubernetes package manager for defining, installing, upgrading, and managing complex K8s applications. |
| **[Schniz/fnm](https://github.com/Schniz/fnm)** | [![Stars](https://img.shields.io/github/stars/Schniz/fnm?style=social&color=white)](https://github.com/Schniz/fnm/stargazers) | GPL-3.0 | Fast, zero-dependency Node.js version manager built in Rust with auto-switching via `.nvmrc` files. |
| **[charmbracelet/gum](https://github.com/charmbracelet/gum)** | [![Stars](https://img.shields.io/github/stars/charmbracelet/gum?style=social&color=white)](https://github.com/charmbracelet/gum/stargazers) | MIT | Tool for glamorous shell scripts. Provides beautiful TUI inputs, selects, spinners, confirmations, and tables. |
| **[ogham/exa](https://github.com/ogham/exa)** | [![Stars](https://img.shields.io/github/stars/ogham/exa?style=social&color=white)](https://github.com/ogham/exa/stargazers) | MIT | Modern replacement for `ls` featuring color schemes, metadata columns, and Git status visualization. |
| **[eza-community/eza](https://github.com/eza-community/eza)** | [![Stars](https://img.shields.io/github/stars/eza-community/eza?style=social&color=white)](https://github.com/eza-community/eza/stargazers) | EUPL-1.2 | Maintained, modern, feature-rich replacement for `ls` and community successor to `exa` with icon support. |
| **[fastapi/typer](https://github.com/fastapi/typer)** | [![Stars](https://img.shields.io/github/stars/fastapi/typer?style=social&color=white)](https://github.com/fastapi/typer/stargazers) | MIT | Modern Python library for building intuitive CLI applications based on standard Python type hints. |
| **[aws/aws-cli](https://github.com/aws/aws-cli)** | [![Stars](https://img.shields.io/github/stars/aws/aws-cli?style=social&color=white)](https://github.com/aws/aws-cli/stargazers) | Apache-2.0 | Official universal Command Line Interface repository for Amazon Web Services. |
| **[docker/cli](https://github.com/docker/cli)** | [![Stars](https://img.shields.io/github/stars/docker/cli?style=social&color=white)](https://github.com/docker/cli/stargazers) | Apache-2.0 | Official Docker command-line interface to build, containerize, run, and share container applications. |
| **[Azure/azure-cli](https://github.com/Azure/azure-cli)** | [![Stars](https://img.shields.io/github/stars/Azure/azure-cli?style=social&color=white)](https://github.com/Azure/azure-cli/stargazers) | MIT | Microsoft's open-source cross-platform command-line client repository for Azure management. |
| **[kubernetes/kubectl](https://github.com/kubernetes/kubectl)** | [![Stars](https://img.shields.io/github/stars/kubernetes/kubectl?style=social&color=white)](https://github.com/kubernetes/kubectl/stargazers) | Apache-2.0 | Official command line tool and codebase for communicating with Kubernetes cluster control planes. |
| **[azlanabdulla/dev-kit](https://github.com/azlanabdulla/dev-kit)** | [![Stars](https://img.shields.io/github/stars/azlanabdulla/dev-kit?style=social&color=white)](https://github.com/azlanabdulla/dev-kit/stargazers) | MIT | Developer toolbox CLI equipped with 17 utility plugins for hashing, encoding, encryption, formatting, and conversion. |

---

### 🧰 CLI Frameworks & Utilities

Frameworks and developer utilities for engineering custom terminal tools:

- **[Cobra](https://github.com/spf13/cobra)** (Go) & **[Typer](https://github.com/fastapi/typer)** (Python): Leading CLI architecture engines.
- **[Bubble Tea](https://github.com/charmbracelet/bubbletea)** & **[Gum](https://github.com/charmbracelet/gum)** (Go): The Elm architecture for interactive terminal user interfaces (TUIs).
- **[Ratatui](https://github.com/ratatui/ratatui)** (Rust): Terminal UI library for creating rich text-based interfaces.
- **[DevKit](https://github.com/azlanabdulla/dev-kit)**: Ready-to-use extensible Swiss Army Knife toolkit.

---

## 📈 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Developer-Tooling-Cli&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Developer-Tooling-Cli&type=date&legend=top-left)

---

## 💖 Support & Sponsorship

If you find this curated collection useful for your daily developer workflows, infrastructure orchestration, or terminal setup, please consider supporting the project:

- ⭐ **Star this repository** to help others discover it!
- 🍴 **Fork and contribute** your favorite CLIs and tools.
- 📢 **Share with your colleagues** on developer communities and social networks.
- ☕ **Buy me a coffee / Sponsor the project**: Support ongoing maintenance via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

---

## 🤝 How to Contribute

Contributions are warmly welcomed! Help keep this ecosystem up-to-date:

1. **Fork** this repository.
2. Add your tool to the corresponding table in `README.md` keeping the sorting criteria intact.
3. Ensure the project is active, well-documented, and includes factual pricing/open-source metadata.
4. Submit a **Pull Request** with a descriptive summary of the change.

---

## ⚖️ Disclaimer

- This list is **community-curated** for educational and reference purposes; inclusion does not constitute an endorsement.
- All brand names, product trademarks, and logos are property of their respective owners.
- CLIs handling credentials, API tokens, and cloud infrastructure must adhere to security best practices (such as token rotation and least-privilege scoping).
