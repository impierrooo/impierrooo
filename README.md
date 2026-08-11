# Pierre Montaret

Développeur full-stack en alternance. Je fais du PHP, du Python et du TypeScript, et je passe du serveur à l'interface sans me cantonner à une case. L'IA a élargi ce que je peux construire seul. La finance et la sécurité reviennent dans presque tout ce que je touche.

---

## En alternance

Je développe le backend de NSICA, l'ERP du groupe d'écoles Adonis. C'est une API REST en PHP qui gère des établissements scolaires. Je vais du ticket Jira à la merge request, conception, code, tests et relecture.

J'encadre aussi des stagiaires et je relis leur travail au quotidien. Je porte une part de gestion de projet et j'avance avec beaucoup d'autonomie. Pour la suite, j'ai autant envie de faire avancer un projet et une équipe que d'écrire du code.

---

## Mes projets perso

Ils sont privés. Je peux en parler, pas encore montrer le code.

**Dora** - une chaîne d'agents que j'ai bâtie au-dessus de Claude Code. Elle prend un ticket en charge de bout en bout. Elle part d'un ticket Jira ou d'une demande brute reçue sur Discord ou par mail, et va jusqu'à la merge request prête à relire. Quand il le faut, elle enquête sur les serveurs, lit la base et les fichiers pour comprendre un bug avant de le corriger. Un orchestrateur répartit le travail entre des sous-agents spécialisés, un pour trouver le bon dépôt, un pour développer, d'autres pour tout vérifier avant le push. Un mode question affine le plan avec moi avant la première ligne de code. Des garde-fous par hooks bloquent ce qui ne passe pas les contrôles. Elle tourne pour deux organisations sans que j'aie à reprendre la main.

**Financial** - un cockpit patrimonial avec un journal de trading analysé par IA. Multi-devises, simulateur fiscal, un LLM qui coache mes trades. FastAPI et SQLAlchemy derrière, React et TypeScript devant, Docker autour. Auth Argon2id et une CI qui bloque le code non typé ou vulnérable. Le projet où je soigne le plus la sécurité.

**Bot-trading** - un moteur qui cherche des stratégies crypto, construit pour ne pas me mentir. Il teste sur 686 000 bougies, compte les vrais coûts, frais, slippage et funding, et valide chaque résultat au bootstrap. La stratégie retenue bat son univers de référence sur près de neuf ans, avec le plus faible drawdown de tout ce que j'ai testé. Rien n'est laissé à l'intuition.

**Setup-wsl** - mon poste de dev tient dans un dépôt. Un script Bash idempotent réinstalle tout d'un coup, paquets, git, SSH, secrets chiffrés, que la machine soit neuve ou vieille de trois semaines. C'est aussi lui qui déploie Dora et toute sa configuration. Pas glamour, mais je ne refais plus jamais ça à la main.

---

## Ma stack

| Domaine | Outils |
| --- | --- |
| Backend | PHP (Laravel, Slim), Python (FastAPI), Node.js |
| Frontend | React, TypeScript, JavaScript |
| Données | PostgreSQL, SQLite |
| Infra & CI | Docker, Linux, Git, GitLab CI, GitHub Actions |
| Qualité | Pest, PHPStan, pytest, ruff, mypy |

---

## Me contacter

- [LinkedIn](https://www.linkedin.com/in/pierre-montaret)
- [pierre.montaret@gmail.com](mailto:pierre.montaret@gmail.com)
