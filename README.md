# Bonjour, moi c'est Eya 👋

**Ingénieure IA générative à Toulouse.** Je construis des assistants IA pour des équipes qui
surveillent des satellites, et je passe autant de temps à vérifier qu'ils disent vrai qu'à les
construire.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Eya%20Weslati-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/eya-ouesleti-840597160)
[![Email](https://img.shields.io/badge/Email-eyaweslatii12%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:eyaweslatii12@gmail.com)
![Disponible](https://img.shields.io/badge/Disponible-imm%C3%A9diatement-2EA44F)

---

### Ce qui me fait avancer

Un LLM qui répond avec assurance n'est pas un LLM qui a raison.

Chez **CLS** (filiale du CNES), les opérateurs mettaient une dizaine de minutes à retrouver une
information dispersée entre Jira, Confluence et plusieurs bases de données. L'assistant RAG que
j'ai construit leur répond en quelques minutes, pour une centaine d'utilisateurs. Mais la partie
dont je suis la plus fière, c'est l'autre moitié du travail : savoir **quand** il se trompe,
mesurer ses hallucinations et prouver qu'une nouvelle version de prompt fait mieux que la
précédente avant de la mettre en production.

C'est devenu ma façon de travailler : **construire, mesurer, puis seulement affirmer.**

---

### Ce que je construis en dehors du travail

#### 🗄️ [Agent Text-to-SQL sur Lakehouse](https://github.com/wesletieya/text-to-sql-agent)

*Et si on pouvait poser une question à sa base de données comme à un collègue, sans craindre
qu'il casse quelque chose ?*

J'ai construit un agent qui transforme une question en SQL, le vérifie, l'exécute en lecture
seule et se corrige seul quand il se trompe. Le tout tourne en local, gratuitement, avec un modèle
de 7 milliards de paramètres.

- **81,3 % de réponses exactes** sur 91 questions, jugées sur le résultat obtenu et non sur le SQL écrit
- un lakehouse DuckDB (100 000 commandes) qui corrige les pièges des données **avant** qu'ils ne trompent le modèle
- **42 attaques** testées contre le SQL généré, et **182 tests** en CI

`Qwen 2.5 Coder` `DuckDB` `sqlglot` `FastAPI` `Streamlit` `Docker`

#### 🛡️ [MCP Red-Team Lab](https://github.com/wesletieya/mcp-redteam-lab)

*Que se passe-t-il quand un document lu par un agent IA contient une instruction cachée ?*

J'ai monté un laboratoire pour attaquer mon propre agent, puis le défendre couche par couche.
Ce que j'en retiens : aucune défense ne suffit seule, et une attaque un peu maligne peut inverser
le classement des défenses qui semblaient les meilleures.

- **6 défenses en couches** comparées sur 11 configurations, scénarios alignés sur l'OWASP LLM Top 10
- des mesures déterministes (canary tokens, journaux d'audit) plutôt qu'un LLM qui juge un autre LLM
- sur agent simulé, le taux d'attaques réussies passe de **100 % à 0 %**, sans perte d'utilité

`Python` `pandas` `pytest` `GitHub Actions` `Streamlit`

---

### Comment je travaille

**Je mesure avant d'affirmer.** RAGAS, LLM-as-a-judge, MLflow : si je ne peux pas montrer qu'une
amélioration en est une, je ne la livre pas.

**Je pense la sécurité dès le départ.** Un agent qui a accès à des outils doit être limité par
conception, pas par espoir.

**J'explique simplement.** J'ai été formatrice en data science pendant un an et demi : rendre un
sujet technique clair pour quelqu'un qui découvre le sujet, c'est un plaisir, pas une corvée.

---

### Mon parcours, en bref

De **Tunis** à **Toulouse**. Diplômée ingénieure en Systèmes Intelligents (INSAT), j'ai touché à
la vision par ordinateur, à la segmentation d'images médicales, à la prédiction du churn et même à
un petit robot compagnon, avant de me spécialiser dans l'IA générative. Aujourd'hui : plus de
3 ans en data et IA, dont 19 mois sur des LLM en production dans le secteur spatial, et un Master
Cloud Data Engineering en alternance.

<details>
<summary><b>Ma boîte à outils</b></summary>
<br>

| | |
|---|---|
| **LLM & agents** | LangChain, LangGraph, MCP, Ollama, AWS Bedrock, prompt engineering |
| **RAG** | pgvector, FAISS, ChromaDB, Supabase, recherche hybride, re-ranking |
| **Évaluation** | RAGAS, LLM-as-a-judge, MLflow, pytest |
| **Data** | Python, SQL, PostgreSQL, DuckDB, pandas, Spark, Kafka |
| **ML** | PyTorch, TensorFlow, XGBoost |
| **Mise en production** | Docker, Kubernetes, FastAPI, Streamlit, GitHub Actions |

</details>

---

### On en parle ?

Je cherche mon prochain poste d'**ingénieure IA générative / data**, à Toulouse ou sur site
client. Et si vous voulez simplement échanger sur le RAG, les agents ou l'évaluation des LLM,
écrivez-moi : c'est mon sujet préféré.

📫 [eyaweslatii12@gmail.com](mailto:eyaweslatii12@gmail.com) · [LinkedIn](https://www.linkedin.com/in/eya-ouesleti-840597160)
