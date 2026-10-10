# Skill Issue — la formation

Le site de la formation « Skill Issue », pour les développeurs et les consultants placés chez de grands comptes : une mission en jeu de rôle, puis quatre modules pour construire son propre skill de code review (cas Angular 22), le mesurer sur une vraie PR, le partager à toute l'équipe quel que soit son outil et l'installer chez le client (proxy, CI sans internet, dossier RSSI, pilote). En bonus : le cloud et le package de Princy.

En ligne : https://princyexaltit.github.io/skill-issue-site/

Ce dépôt ne contient que le site généré (`index.html` et ses vidéos). Il est produit par `node site/build.mjs` dans le dépôt du kit `PrincyExaltIT/skill-issue`.

Le package de Princy (angular-review, review-fix, pr-handoff, skill-smith) s'installe depuis le registre public [agent-skill](https://github.com/PrincyExaltIT/agent-skill) avec [forgent](https://github.com/PrincyExaltIT/forgent) :

```bash
npx forgent add --provider agents,claude --project angular-review review-fix pr-handoff skill-smith
```
