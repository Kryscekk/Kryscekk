### Salut, moi c'est Driss 👋

Médecin urologue à **Fès, Maroc**. Architecte logiciel auto-formé.

Je code depuis quelques mois — du temps perdu pour vous, du temps gagné pour moi. Et beaucoup, beaucoup de questions à Claude.

---

#### ⚡ Démo méta : ce profil GitHub est géré par mon IA

Ce que vous lisez n'a pas été créé à la main.

À aucun moment je n'ai ouvert github.com pour cliquer sur *"New repository"*, ni tapé `git commit` dans un terminal. Ce profil, ce README, le repo de tutos lié plus bas, les commits, le push — tout a été fait **en live depuis une conversation chat avec Claude**.

**Mon rôle** : lui dire ce que je veux, en français.
**Son rôle** : tout le reste.

C'est rendu possible par les serveurs MCP que j'ai construits, qui exposent à Claude exactement les outils dont il a besoin pour piloter mon environnement. Ces serveurs ne sont pas publics — ils sont pensés pour mon usage.

Cette section a été ajoutée pendant que je relisais le rendu sur mon téléphone.

---

#### Ce qui tourne actuellement sur mon serveur

- **~104 000 lignes de Python** en production, ajoutées en quelques mois
- **4 systèmes métier** orchestrés par Claude, sur **un seul serveur à moins de 5 €/mois**
- **4 serveurs MCP** en parallèle qui exposent les outils de chaque projet à Claude.ai
- **Defense-in-depth** : 4 rôles Claude séparés avec garde-fous pour empêcher l'agent de toucher à la prod par accident
- **Charte méthodologique versionnée** sur 228 itérations, séparée du code, enforced par `AssertionError` citant les sections
- **Pipeline médical** PEC assurance : OCR, extraction patient, assemblage PDF, notifications WhatsApp
- **Plateforme de valuation fondamentale** boursière : 7 archétypes × 68 paramètres, 319 tests verts
- **30 crons orchestrés**, supervision auto, audit log médico-légal par domaine
- **claude-agent-sdk** avec `@tool` + `can_use_tool` callback pour validation humaine en boucle

Aucun de ces projets n'est open source — ils contiennent des données sensibles (patients, comptes).

#### Mes 4 projets

🏥 **Cabinet** — système qui gère mes patients, dossiers PEC assurance, scan CIN, notifications WhatsApp et planning
📈 **MASI** — plateforme de valuation fondamentale des sociétés cotées en Bourse
💰 **Finances** — dashboard perso qui agrège mes flux (cabinet + investissements + dépenses)
🔬 **R&D** — bac à sable infra et veille IA personnalisée

---

#### Ce que je publie ici

📚 [**agents-en-pratique**](https://github.com/Kryscekk/agents-en-pratique) — tutoriels en français pour les pros qui veulent comprendre les agents IA sans avoir fait d'informatique. Médecins, juristes, profs, comptables : si vous me suivez, c'est pour vous. Mais aussi pour les devs expérimentés qui veulent une référence FR concise à partager.

Les patterns architecturaux que j'utilise en prod finiront aussi ici, en tutoriels, au fil du temps — quand ils seront assez stables pour être pédagogiquement clairs.

Versions EN et AR prévues à partir des mois 3 et 5.

---

#### Pourquoi tout ça

Parce que j'ai compris en quelques semaines de Claude que la vraie question n'est plus *"est-ce que je sais coder ?"* mais *"est-ce que je sais expliquer ce que je veux ?"*. Et ça, comme médecin, je sais le faire depuis 20 ans.

Si vous êtes professionnel non-informaticien et que vous vous demandez si vous pouvez vous y mettre : oui. Suivez ce repo, on va le faire ensemble.

---

📧 **Contact** : LinkedIn (à venir), ou ouvrez une [issue](https://github.com/Kryscekk/agents-en-pratique/issues) sur le repo

⚠️ Pour toute question médicale, consultez un médecin en cabinet — ce profil est strictement dédié à mes activités tech.
