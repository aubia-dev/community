# Aubia community

**English** | [Français](README.fr.md)

**Aubia makes your AI agents review each other.**

Public space for Aubia users, beta testers and early supporters. Discussions, feedback and roadmap visibility live here.

[Join the waitlist on aubia.dev](https://aubia.dev) | [Devlog](https://aubia.dev/en/blog) | [@aubia_dev on X](https://x.com/aubia_dev) | [Aubia on LinkedIn](https://www.linkedin.com/company/aubia-dev)

![Phase 0 Waitlist](https://img.shields.io/badge/Phase%200-Waitlist-8839ef?style=flat-square&labelColor=1e1e2e)
![Beta 0.1 Q3 2026](https://img.shields.io/badge/Beta%200.1-Q3%202026-1e66f5?style=flat-square&labelColor=1e1e2e&logo=apple&logoColor=cdd6f4)
![Made in Paris FR](https://img.shields.io/badge/Made%20in-Paris%20FR-45475a?style=flat-square&labelColor=1e1e2e)
[![X @aubia_dev](https://img.shields.io/badge/%40aubia__dev-1e1e2e?style=flat-square&logo=x&logoColor=cdd6f4)](https://x.com/aubia_dev)

## Table of contents

- [What is Aubia](#what-is-aubia)
- [How to contribute](#how-to-contribute)
- [Public roadmap](#public-roadmap)
- [Contact](#contact)
- [Code of conduct](#code-of-conduct)

## What is Aubia

Aubia is a desktop cockpit sitting above Claude Code, Codex CLI and Mistral. One agent implements, an agent from another model family reviews, and they hand the diff back and forth until they agree. You arbitrate.

- **Automatic cross-review**: they exchange the diff until convergence, over the number of iterations you set.
- **Opinions to Executable Plan Mode**: submit a technical decision to several models at once. Each argues its position, Aubia synthesizes the convergences, isolates the disagreements, and generates an arbitrated plan you can edit and run.
- **BYOK**: your contracts with Anthropic, OpenAI and Mistral stay yours. Keys encrypted in your OS keychain, no token reselling, no vendor lock-in.
- **Local-first desktop**: agents run locally, each in its own isolated git worktree. Your code never leaves your machine.

## How to contribute

This community space is where Aubia takes shape, before and during the beta. Pick the right discussion category:

| Want to | Go to |
|---|---|
| Ask a question, get help, find a workaround | [Q&A](https://github.com/aubia-dev/community/discussions/categories/q-a) |
| Suggest a feature, an integration, a workflow | [Ideas](https://github.com/aubia-dev/community/discussions/categories/ideas) |
| Share something you built with Aubia | [Show and tell](https://github.com/aubia-dev/community/discussions/categories/show-and-tell) |
| Discuss anything else relevant to the community | [General](https://github.com/aubia-dev/community/discussions/categories/general) |
| Read product updates, releases, milestones | [Announcements](https://github.com/aubia-dev/community/discussions/categories/announcements) |

I answer new discussions within 24 to 48 hours on business days.

## Public roadmap

- **Phase 0** (current): public waitlist, the organization profile, this community space, the devlog on aubia.dev.
- **Beta 0.1** (third quarter of 2026): macOS Apple Silicon. Cross-review, Opinions to Executable Plan Mode, local cockpit. First waitlist invites go out.
- **Beta 0.2 and beyond**: Gemini via Antigravity CLI, local Ollama inference, multi-step DAG cross-review, CI auto-fix, mobile companion.
- **1.0**: Linux and Windows support, out of beta.

## Contact

| Topic | Where |
|---|---|
| Product questions | Open a Q&A discussion above |
| Press, partnerships, business | `contact@aubia.dev` |
| Privacy, GDPR, data protection | `dpo@aubia.dev` |
| Security disclosure | `contact@aubia.dev` |

## Code of conduct

Be respectful, constructive and on topic. Aubia is built by one person: discussions that break basic respect or spam the repo are removed without notice. See [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) (Contributor Covenant 2.1).

Aubia is designed and written by Mike EL GHALI, from Paris.
