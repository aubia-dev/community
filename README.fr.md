# Communauté Aubia

[English](README.md) | **Français**

**Aubia fait se relire vos agents IA.**

Espace public pour les utilisateurs, beta testeurs et premiers soutiens d'Aubia. Les discussions, les retours et la visibilité de la feuille de route vivent ici.

[Rejoindre la liste d'attente sur aubia.dev](https://aubia.dev) | [Journal de bord](https://aubia.dev/fr/blog) | [@aubia_dev sur X](https://x.com/aubia_dev) | [Aubia sur LinkedIn](https://www.linkedin.com/company/aubia-dev)

![Phase 0 liste d'attente](https://img.shields.io/badge/Phase%200-Liste%20d%27attente-8839ef?style=flat-square&labelColor=1e1e2e)
![Beta 0.1 troisième trimestre 2026](https://img.shields.io/badge/Beta%200.1-T3%202026-1e66f5?style=flat-square&labelColor=1e1e2e&logo=apple&logoColor=cdd6f4)
![Conçu à Paris](https://img.shields.io/badge/Con%C3%A7u%20%C3%A0-Paris%20FR-45475a?style=flat-square&labelColor=1e1e2e)
[![X @aubia_dev](https://img.shields.io/badge/%40aubia__dev-1e1e2e?style=flat-square&logo=x&logoColor=cdd6f4)](https://x.com/aubia_dev)

## Sommaire

- [Qu'est-ce qu'Aubia](#quest-ce-quaubia)
- [Comment contribuer](#comment-contribuer)
- [Roadmap publique](#roadmap-publique)
- [Contact](#contact)
- [Code de conduite](#code-de-conduite)

## Qu'est-ce qu'Aubia

Aubia est un cockpit desktop posé au-dessus de Claude Code, Codex CLI et Mistral. Un agent implémente, un agent d'une autre famille de modèles relit, et ils se repassent le diff jusqu'à l'accord. Vous arbitrez.

- **Cross-review automatique** : ils s'échangent le diff jusqu'à convergence, sur le nombre d'itérations que vous fixez.
- **Mode Opinions vers Plan exécutable** : soumettez une décision technique à plusieurs modèles simultanément. Chacun argumente sa position, Aubia synthétise les convergences, isole les désaccords, et génère un plan arbitré que vous éditez et exécutez.
- **BYOK** : vos contrats Anthropic, OpenAI et Mistral restent les vôtres. Clés chiffrées dans le keychain de votre OS, aucune revente de tokens, aucune dépendance vendor.
- **Desktop local-first** : les agents tournent en local, chacun dans son propre git worktree isolé. Vos sources ne quittent jamais votre machine.

## Comment contribuer

Cet espace communautaire est l'endroit où Aubia prend forme, avant et pendant la beta. Choisissez la bonne catégorie de discussion :

| Vous voulez | Allez sur |
|---|---|
| Poser une question, obtenir de l'aide, trouver un contournement | [Q&A](https://github.com/aubia-dev/community/discussions/categories/q-a) |
| Suggérer une fonctionnalité, une intégration, un workflow | [Ideas](https://github.com/aubia-dev/community/discussions/categories/ideas) |
| Partager ce que vous construisez avec Aubia | [Show and tell](https://github.com/aubia-dev/community/discussions/categories/show-and-tell) |
| Discuter de tout autre sujet pertinent | [General](https://github.com/aubia-dev/community/discussions/categories/general) |
| Lire les annonces produit, les sorties, les jalons | [Announcements](https://github.com/aubia-dev/community/discussions/categories/announcements) |

Je réponds aux nouvelles discussions sous 24 à 48 heures, en jours ouvrés.

## Roadmap publique

- **Phase 0** (en cours) : liste d'attente publique, profil d'organisation, cet espace communautaire, le journal de bord sur aubia.dev.
- **Beta 0.1** (troisième trimestre 2026) : macOS Apple Silicon. Cross-review, Mode Opinions vers Plan exécutable, cockpit local. Premières invitations de la liste d'attente.
- **Beta 0.2 et suivantes** : Gemini via Antigravity CLI, inférence locale Ollama, cross-review en DAG multi-étapes, CI auto-fix, companion mobile.
- **1.0** : support Linux et Windows, sortie de beta.

## Contact

| Sujet | Où |
|---|---|
| Questions produit | Ouvrir une discussion Q&A ci-dessus |
| Presse, partenariats, business | `contact@aubia.dev` |
| Vie privée, RGPD, protection des données | `dpo@aubia.dev` |
| Divulgation sécurité | `contact@aubia.dev` |

## Code de conduite

Soyez respectueux, constructifs et dans le sujet. Aubia est construit par une seule personne : les discussions qui violent le respect basique ou qui spamment le repo sont supprimées sans préavis. Voir [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) (Contributor Covenant 2.1).

Aubia est conçu et écrit par Mike EL GHALI, depuis Paris.
