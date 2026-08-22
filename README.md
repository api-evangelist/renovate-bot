# Renovate (renovate-bot)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Renovate is an open source automated dependency update bot maintained by Mend. It scans repositories for references to dependencies across 100+ package managers — npm, pip, poetry, Maven, Gradle, NuGet, Go modules, Cargo, Bundler, Docker, Helm, Kubernetes, Terraform, GitHub Actions and many more — and opens pull/merge requests that update versions, lockfiles, and digests. Renovate runs as a CLI, Docker container, GitHub App, GitLab Runner, Bitbucket Cloud app, or Azure DevOps integration, supports GitHub, GitLab, Bitbucket, Azure DevOps, Gitea, Forgejo, AWS CodeCommit, and Gerrit, and is configured via a `renovate.json` file with shareable presets, `packageRules`, automerge, grouping, scheduling, and a Dependency Dashboard. Mend provides a free Community Cloud hosted tier for unlimited public and private repositories and a paid Enterprise Cloud tier with higher concurrency, Merge Confidence Workflows, and support.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/renovate-bot/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=opensource-api-evangelist&utm_content=repo)

## Tags

 - DependencyUpdates, DeveloperTools, Bots, Automation, SoftwareSupplyChain, OpenSource, Mend, AGPLv3, Node.js, TypeScript

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## At a Glance

| Field | Value |
|---|---|
| Project | Renovate |
| Steward | Mend.io |
| License | AGPL-3.0-only |
| Primary Language | TypeScript |
| Distribution | npm (`renovate`), Docker (`renovate/renovate`, `ghcr.io/renovatebot/renovate`), GitHub Action, pre-commit hook, Mend-hosted SaaS |
| Source Code | https://github.com/renovatebot/renovate |
| Documentation | https://docs.renovatebot.com/ |
| Hosted Portal | https://developer.mend.io/ |
| Supported Platforms | GitHub, GitLab, Bitbucket Cloud, Bitbucket DC/Server, Azure DevOps, Gitea, Forgejo, AWS CodeCommit (experimental), Gerrit (experimental), SCM-Manager (experimental) |
| Package Managers | 100+ across npm, Python, Java/JVM, .NET, Go, Rust, Ruby, Docker, Kubernetes, Terraform, CI systems, Bazel, Ansible, Homebrew, asdf, mise, nix, proto |
| Hosted Tiers | Community Cloud (free), Community OSS Cloud (free for OSI projects), Enterprise Cloud (paid) |

## APIs

### Renovate CLI
The open source Renovate CLI is a Node.js application distributed via npm and as Docker images on Docker Hub and GitHub Container Registry. It can be run locally, in CI, or as a long-lived self-hosted bot to scan repositories, detect dependency files for 100+ package managers, and open pull requests that update outdated versions, lockfiles, and digests.

**Human URL:** [https://docs.renovatebot.com/usage/](https://docs.renovatebot.com/usage/)

- [Documentation](https://docs.renovatebot.com/)
- [Source Code](https://github.com/renovatebot/renovate)
- [npm package](https://www.npmjs.com/package/renovate)
- [Docker Hub](https://hub.docker.com/r/renovate/renovate)
- [GHCR](https://ghcr.io/renovatebot/renovate)

### Renovate Configuration
Renovate's behavior is driven by repository-level configuration files (`renovate.json`, `renovate.json5`, `.github/renovate.json`, `.gitlab/renovate.json`, `.renovaterc`, or a deprecated `renovate` key in `package.json`). Configuration supports presets (`extends`), `packageRules` for conditional behavior, schedules, automerge policies, base branch patterns, the Dependency Dashboard, grouping, and per-manager overrides.

**Human URL:** [https://docs.renovatebot.com/configuration-options/](https://docs.renovatebot.com/configuration-options/)

- [Configuration options](https://docs.renovatebot.com/configuration-options/)
- [Config presets](https://docs.renovatebot.com/config-presets/)
- [Dependency Dashboard](https://docs.renovatebot.com/key-concepts/dependency-dashboard/)
- [Configuration templates](https://docs.renovatebot.com/configuration-templates/)
- [JSON Schema (renovate-schema.json)](https://docs.renovatebot.com/renovate-schema.json)

### Renovate Package Managers
Renovate ships 100+ package manager modules covering JavaScript (npm, bun, deno, nvm, nodenv), Python (poetry, pipenv, pip-compile, pep621, pyenv), Java/JVM (maven, gradle, sbt, ant), .NET (nuget, cake), Go (gomod), Rust (cargo), Ruby (bundler), Docker (dockerfile, docker-compose, devcontainer), Kubernetes (kubernetes, kustomize, helmfile, helmsman, flux, argocd), Terraform (terraform, terragrunt), CI systems (github-actions, gitlabci, circleci, jenkins, azure-pipelines, bitbucket-pipelines, buildkite, droneci, tekton, woodpecker), Bazel, Ansible, Homebrew, asdf, mise, nix, proto, and many more.

**Human URL:** [https://docs.renovatebot.com/modules/manager/](https://docs.renovatebot.com/modules/manager/)

- [Manager modules](https://docs.renovatebot.com/modules/manager/)
- [Datasource modules](https://docs.renovatebot.com/modules/datasource/)
- [Versioning modules](https://docs.renovatebot.com/modules/versioning/)

### Renovate Git Platforms
Renovate has pluggable platform adapters for GitHub (cloud and Enterprise Server), GitLab (SaaS and CE/EE), Bitbucket Cloud, Bitbucket Data Center / Server, Azure DevOps, Gitea, Forgejo, AWS CodeCommit (experimental), Gerrit (experimental), and SCM-Manager (experimental).

**Human URL:** [https://docs.renovatebot.com/modules/platform/](https://docs.renovatebot.com/modules/platform/)

- [GitHub](https://docs.renovatebot.com/modules/platform/github/)
- [GitLab](https://docs.renovatebot.com/modules/platform/gitlab/)
- [Bitbucket Cloud](https://docs.renovatebot.com/modules/platform/bitbucket/)
- [Bitbucket Server](https://docs.renovatebot.com/modules/platform/bitbucket-server/)
- [Azure DevOps](https://docs.renovatebot.com/modules/platform/azure/)
- [Gitea](https://docs.renovatebot.com/modules/platform/gitea/)
- [Forgejo](https://docs.renovatebot.com/modules/platform/forgejo/)
- [AWS CodeCommit](https://docs.renovatebot.com/modules/platform/codecommit/)
- [Gerrit](https://docs.renovatebot.com/modules/platform/gerrit/)

### Mend Hosted Renovate
Mend operates a hosted Renovate service that runs Renovate as a GitHub App, Bitbucket Cloud app, and Azure DevOps integration on Mend infrastructure. A generous Community Cloud free tier covers unlimited public and private repositories.

**Human URL:** [https://docs.renovatebot.com/mend-hosted/overview/](https://docs.renovatebot.com/mend-hosted/overview/)

- [Mend-hosted overview](https://docs.renovatebot.com/mend-hosted/overview/)
- [Mend Developer Portal](https://developer.mend.io/)
- [Renovate GitHub App](https://github.com/apps/renovate)
- [mend.io/renovate](https://www.mend.io/renovate/)

### Renovate Merge Confidence
Merge Confidence is a Mend-operated data service that classifies each candidate update (Low / Neutral / High / Very High) using package age, adoption, test pass rates, and known vulnerabilities. Renovate consumes the Merge Confidence API to attach a confidence badge and reason to each PR.

**Human URL:** [https://docs.renovatebot.com/merge-confidence/](https://docs.renovatebot.com/merge-confidence/)

- [Merge Confidence documentation](https://docs.renovatebot.com/merge-confidence/)
- [Merge Confidence API](https://developer.mend.io/api/mc/)

## Plans

### Community Cloud (Free)
Free hosted Renovate on Mend infrastructure for any GitHub, Bitbucket Cloud, or Azure DevOps org. Unlimited public and private repositories.

- 1 concurrent job per organization
- 4-hour job scheduling
- 1 vCPU, 3 GB memory, 15 GB disk
- 30-minute job timeout
- No Merge Confidence Workflows

### Community OSS Cloud (Free for OSI projects)
Enhanced free tier for OSI-licensed open source projects on request.

- 2 concurrent jobs per organization
- 4-hour job scheduling
- 2 vCPU, 6 GB memory, 25 GB disk
- 60-minute job timeout
- Merge Confidence Workflows included

### Enterprise Cloud (Paid — contact sales)
Commercial managed Renovate offering from Mend with higher concurrency and support.

- 16 concurrent jobs per organization
- Hourly job scheduling (every 4 hours on Bitbucket)
- 2 vCPU, 8 GB memory, 40 GB disk
- 60-minute job timeout
- Merge Confidence Workflows
- Mend.io helpdesk support

## Key Features

- Open source dependency update bot written in TypeScript and distributed under AGPL-3.0-only
- 100+ package manager modules across the major language and infrastructure ecosystems
- Pluggable Git platform adapters for GitHub, GitLab, Bitbucket, Azure DevOps, Gitea, Forgejo, AWS CodeCommit, Gerrit, SCM-Manager
- Repository configuration via `renovate.json` / `renovate.json5` / `.github/renovate.json` / `.gitlab/renovate.json` / `.renovaterc` with a canonical JSON Schema
- Shareable config presets (`extends`) including the curated `config:recommended` preset
- `packageRules` for conditional behaviour by package, depType, manager, or file pattern
- Dependency Dashboard issue summarising every open and pending update
- Automerge with PR, branch, or PR-comment strategies and a separate `automergeSchedule`
- Grouping of related updates (`group`, `group:allNonMajor`, `group:monorepos`, etc.)
- Lock file maintenance and digest pinning for Docker, GitHub Actions, and Helm
- Custom (regex) manager for updating versions in arbitrary file formats
- Private package and registry support (npmrc, hostRules, Vault / cloud secrets)
- Self-hosted execution as Node.js CLI, Docker container (Docker Hub + GHCR), GitHub Action, or pre-commit hook
- Mend-hosted Renovate as a GitHub App, Bitbucket Cloud app, and Azure DevOps integration
- Merge Confidence ratings (Low / Neutral / High / Very High) per update from `developer.mend.io/api/mc/`
- Vulnerability alerts integration (GitHub Dependabot alerts, OSV)
- Configurable schedules to limit when PRs are opened or merged
- `baseBranchPatterns` to run Renovate across multiple branches in a single repo
- Deprecation handling with migration PRs for replacement packages
- 90+ versioning modules so version comparisons match the upstream ecosystem
- Multiple-times-per-day release cadence (43,000+ versions on npm, 5,000+ GitHub releases)
- Datasource modules covering npm, PyPI, Docker, Maven, NuGet, GitHub releases/tags, Helm, crate, Go proxy, Conan, RubyGems, packagist, Terraform Registry, and more
- Pre-commit hook support
- JSON Schema (`renovate-schema.json`) for IDE validation of every configuration option

## Common Links

- [Portal](https://www.mend.io/renovate/)
- [Documentation](https://docs.renovatebot.com/)
- [Getting Started](https://docs.renovatebot.com/getting-started/installing-onboarding/)
- [Source Code](https://github.com/renovatebot/renovate)
- [GitHub Organization](https://github.com/renovatebot)
- [Renovate GitHub App](https://github.com/apps/renovate)
- [Mend Developer Portal](https://developer.mend.io/)
- [Release Notes](https://github.com/renovatebot/renovate/releases)
- [Issues](https://github.com/renovatebot/renovate/issues)
- [Discussions](https://github.com/renovatebot/renovate/discussions)
- [License (AGPL-3.0-only)](https://github.com/renovatebot/renovate/blob/main/license)
- [npm package](https://www.npmjs.com/package/renovate)
- [Docker Hub](https://hub.docker.com/r/renovate/renovate)
- [GHCR](https://github.com/renovatebot/renovate/pkgs/container/renovate)
- [GitHub Action](https://github.com/renovatebot/github-action)
- [pre-commit hooks](https://github.com/renovatebot/pre-commit-hooks)
- [Self-hosted configuration](https://docs.renovatebot.com/self-hosted-configuration/)
- [Configuration options](https://docs.renovatebot.com/configuration-options/)
- [Config presets](https://docs.renovatebot.com/config-presets/)
- [Dependency Dashboard](https://docs.renovatebot.com/key-concepts/dependency-dashboard/)
- [Automerge](https://docs.renovatebot.com/key-concepts/automerge/)
- [Package Manager Modules](https://docs.renovatebot.com/modules/manager/)
- [Datasource Modules](https://docs.renovatebot.com/modules/datasource/)
- [Versioning Modules](https://docs.renovatebot.com/modules/versioning/)
- [Platform Modules](https://docs.renovatebot.com/modules/platform/)
- [Custom (regex) Manager](https://docs.renovatebot.com/modules/manager/regex/)
- [Merge Confidence](https://docs.renovatebot.com/merge-confidence/)
- [Troubleshooting](https://docs.renovatebot.com/troubleshooting/)
- [Security and permissions](https://docs.renovatebot.com/security-and-permissions/)
- [Private packages](https://docs.renovatebot.com/getting-started/private-packages/)
- [Mend-hosted Renovate](https://docs.renovatebot.com/mend-hosted/overview/)
- [Mend Privacy Policy](https://www.mend.io/privacy-policy/)
- [Mend Terms of Service](https://www.mend.io/terms-of-service/)
- [Mend Trust Center](https://www.mend.io/security-and-compliance/)
- [Mend Blog](https://www.mend.io/blog/)
- [LinkedIn](https://www.linkedin.com/company/mend-io/)
- [Twitter](https://twitter.com/mend_io)

## Maintainers

| FN | Email |
|---|---|
| Kin Lane | info@apievangelist.com |
