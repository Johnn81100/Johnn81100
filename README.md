# Jonathan GAU

**Développeur fullstack, en évolution vers l'architecture logicielle.**

J'interviens de l'analyse du besoin à la mise en production d'applications métier. Ma méthode de conception s'appuie sur les six piliers du **AWS Well-Architected Framework**  excellence opérationnelle, sécurité, fiabilité, performance, coûts, durabilité  appliqués quelle que soit la plateforme, et sur les recommandations **OWASP** pour tout ce qui touche à l'authentification et aux données utilisateur.

Mastère en développement d'applications mobiles, préparé en alternance chez **Collins Aerospace**, après plusieurs années d'études en développement web.

---

## Ce sur quoi je travaille

### [sauver-la-face/app](https://github.com/sauver-la-face/app)

Application de suivi post-opératoire pour les patients cambodgiens opérés lors de missions humanitaires de chirurgie maxillo-faciale.

Monorepo TypeScript, trois surfaces sur une base commune :

| Surface | Stack |
|---|---|
| API | Hono · Drizzle ORM · PostgreSQL |
| Web | Next.js · React · TanStack Query · Tailwind |
| Mobile | Expo · React Native |
| Infra | Bun workspaces · Docker Compose · Caddy · Biome |

---

## Comment je travaille

Les décisions structurantes sont écrites, pas transmises oralement. Le dépôt en porte la trace :

- **[24 ADR](https://github.com/sauver-la-face/app/tree/dev/docs/adr)** — chaque choix technique tranché, son contexte et ses conséquences
- **[Référentiel OWASP](https://github.com/sauver-la-face/app/tree/dev/docs/security)** — checklist tenue à jour, colonne « où c'est traité » renseignée avec le fichier réel
- **[Architecture système](https://github.com/sauver-la-face/app/blob/dev/docs/architecture-systeme.md)** · **[Schéma BDD](https://github.com/sauver-la-face/app/blob/dev/docs/schema.dbml)** · **[Accessibilité](https://github.com/sauver-la-face/app/blob/dev/docs/accessibilite.md)**
- **CI GitHub Actions** — lint, tests, contrôle du CHANGELOG à chaque PR
- **[Onboarding](https://github.com/sauver-la-face/app/blob/dev/docs/onboarding.md)** — un nouveau contributeur démarre sans me solliciter

Un projet doit rester lisible par quelqu'un qui n'était pas là quand les décisions ont été prises. C'est le fil qui relie l'ADR, la doc d'architecture et le refus explicite plutôt que le défaut implicite.

---

## Autres travaux publics

- **[capstone-cloud-2026](https://github.com/Johnn81100/capstone-cloud-2026)** — déploiement Kubernetes sur VPS d'une application web Coupe du Monde 2026
- **[TimeTravelAgency](https://github.com/Johnn81100/TimeTravelAgency)** — React 19, Tailwind v4, shadcn/ui, intégration Mistral AI
- **[studio-glossaires](https://github.com/Johnn81100/studio-glossaires)** — ressources design UI/UX

---

*Contact : via les issues de [sauver-la-face/app](https://github.com/sauver-la-face/app/issues).*
