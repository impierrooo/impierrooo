# Pierre Montaret

Développeur full-stack en alternance. Je construis des systèmes complets et
je les mène jusqu'en production : PHP, Python, TypeScript, et je passe du
serveur à l'interface sans me cantonner à une case. Ce qui revient partout,
c'est le soin porté à ce qui rend un système fiable. L'IA a élargi ce que je
peux construire seul, et la finance et la sécurité reviennent dans presque
tout ce que je touche.

---

## En alternance

Je travaille surtout sur NSICA, un ERP pour établissements d'enseignement
qui remplace un système historique devenu impraticable. Il équipe les écoles
du groupe Adonis comme des écoles externes. J'y touche au front comme au
back, une API REST en PHP et une interface React. Je vais du ticket Jira à la
merge request, conception, code, tests et relecture.

J'y ai conçu et développé toute la brique de visioconférence, adossée à
BigBlueButton, ainsi que le moteur qui génère les emplois du temps et les
répartit. C'est le projet dont je suis le plus fier.

Chez Adonis, je développe aussi de mon côté, surtout des automatisations.
Mais NSICA prend le plus clair de mon temps.

L'équipe technique compte 19 personnes. Le DSI me délègue directement une
part des sujets, et j'encadre jusqu'à 5 stagiaires en parallèle. Pour la
suite, j'ai autant envie de faire avancer un projet et une équipe que
d'écrire du code.

---

## Mes projets perso

Ils sont privés. Je peux en parler, pas encore montrer le code.

**Dora** - une chaîne d'agents que j'ai bâtie au-dessus de Claude Code. Elle
prend un ticket en charge de bout en bout. Elle part d'un ticket Jira ou
d'une demande brute reçue sur Discord ou par mail, et va jusqu'à la merge
request prête à relire. Quand il le faut, elle enquête sur les serveurs, lit
la base et les fichiers pour comprendre un bug avant de le corriger. Un
orchestrateur répartit le travail entre 7 sous-agents spécialisés : un pour
trouver le bon dépôt, un pour développer, d'autres pour tout vérifier avant
le push. Un mode question affine le plan avec moi avant la première ligne de
code. Sept garde-fous par hooks bloquent ce qui ne passe pas les contrôles,
et une suite de tests se rejoue à chaque installation d'un poste. Elle
tourne pour deux organisations sans que j'aie à reprendre la main.

**Financial** - un cockpit patrimonial avec un journal de trading analysé
par IA. Multi-devises, simulateur fiscal, un LLM qui coache mes trades.
FastAPI et SQLAlchemy derrière, React et TypeScript devant, Docker autour.
Auth Argon2id et une CI qui bloque le code non typé ou vulnérable. Le projet
où je soigne le plus la sécurité.

**Bot-trading** - un moteur qui cherche des stratégies crypto, construit
pour ne pas me mentir. Il teste sur 686 000 bougies, compte les vrais coûts,
frais, slippage et funding, et valide chaque résultat au bootstrap. La
stratégie retenue bat son univers de référence sur près de neuf ans, avec le
plus faible drawdown de tout ce que j'ai testé. Rien n'est laissé à
l'intuition.

**Simulation ransomware** - un projet annuel d'école où j'ai reconstruit une
chaîne d'attaque ransomware complète, pour en comprendre les mécanismes du
côté de la défense. Le chiffrement et le déchiffrement des fichiers sont
écrits en assembleur x86-64 (NASM), avec un module de détection d'entropie.
Un serveur de commande et contrôle en Node.js distribue les clés et reçoit
les fichiers, avec deux interfaces : un tableau de bord de supervision et la
page de rançon côté victime. L'ensemble tourne dans Docker, en environnement
isolé. C'est le projet qui m'a le plus appris sur ce qui se passe réellement
sous le langage - registres, appels système, entropie d'un fichier chiffré.
Il n'a jamais été diffusé et ne le sera pas.

**Setup-wsl** - mon poste de dev tient dans un dépôt. Un script Bash
idempotent réinstalle tout d'un coup, paquets, git, SSH, secrets chiffrés,
que la machine soit neuve ou vieille de trois semaines. C'est aussi lui qui
déploie Dora et toute sa configuration. Pas glamour, mais je ne refais plus
jamais ça à la main.

---

## Ma stack

| Domaine | Outils |
| --- | --- |
| Backend | PHP (Laravel, Slim), Python (FastAPI), Node.js, Java 21 (Spring Boot 3) |
| Frontend | React, TypeScript, JavaScript |
| Données | PostgreSQL, SQLite, SQL |
| Infra & CI | Docker, Linux, Git, GitLab CI, GitHub Actions, Maven |
| Qualité | Pest, PHPStan, pytest, ruff, mypy, JUnit 5, Mockito |
| Autres | C/C++, assembleur x86-64, Python embarqué, API REST, Swagger, UML, BigBlueButton |

---

## Me contacter

- [LinkedIn](https://www.linkedin.com/in/pierre-montaret)
- [pierre.montaret@gmail.com](mailto:pierre.montaret@gmail.com)
