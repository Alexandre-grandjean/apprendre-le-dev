# Apprendre le dev

> Un parcours d'apprentissage du développement web en six modules : de la requête HTTP
> jusqu'à l'authentification JWT.

**En ligne :** https://alexandre-grandjean.github.io/apprendre-le-dev/

## Ce que c'est

Un site de cours progressif, écrit pour comprendre ce qu'on fait quand on branche une
application — pas pour réciter une syntaxe. Chaque module traite un palier, et chaque
leçon part d'un problème concret avant de nommer la notion.

Les leçons sont écrites en **MDX** et rendues par Next.js ; certaines embarquent des
schémas interactifs.

## Les six modules

| Module | Sujet |
| :----- | :---- |
| **m0** | HTTP — requêtes et réponses, méthodes, statuts, URL |
| **m1** | Premiers pas — inscription, connexion, lire une liste, créer une entité, DevTools |
| **m2** | Architecture serveur — contrôleur, service, repository, ORM, DTO, injection de dépendances |
| **m3** | Architecture client — composants, état, contexte, routage, intercepteurs |
| **m4** | Sécurité — session ou jeton, JWT, stockage, XSS, validation serveur |
| **m5** | Qualité — conventions, séparation des responsabilités, tests, hygiène de codebase |

## Stack

Next.js · MDX · React · TypeScript · React Flow (schémas) · Framer Motion · Zod

## Lancer en local

| Commande            | Action                              |
| :------------------ | :---------------------------------- |
| `npm install`       | Installe les dépendances            |
| `npm run dev`       | Serveur local (port 3000)           |
| `npm run build`     | Build de production                 |
| `npm run test`      | Tests (Vitest)                      |
| `npm run typecheck` | Vérification des types (tsc --noEmit) |

## Ajouter une leçon

Les leçons vivent dans `content/`, nommées `mX-sujet.mdx`. Le préfixe `mX` détermine le
module d'appartenance ; aucun autre enregistrement n'est nécessaire.

## Licence

MIT — voir [LICENSE](LICENSE).
