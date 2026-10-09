# Skill Issue — la formation

Le site de la formation « Skill Issue » : construire son propre skill de code review (cas Angular 22), le mesurer sur une vraie PR, le partager à toute l'équipe quel que soit son harness, puis le faire tourner dans le cloud.

En ligne : https://princyexaltit.github.io/skill-issue-site/

Ce dépôt ne contient que le site généré (`index.html` et ses vidéos). Il est produit par `node site/build.mjs` dans le dépôt du kit `PrincyExaltIT/skill-issue`.

Le package de Princy (angular-review, review-fix, pr-handoff, skill-smith) s'installe depuis le registre public [agent-skill](https://github.com/PrincyExaltIT/agent-skill) avec [forgent](https://github.com/PrincyExaltIT/forgent) :

```bash
npx forgent add --provider agents,claude --project angular-review review-fix pr-handoff skill-smith
```
