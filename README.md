# Axel — Data Engineer

Data Engineer en fin de formation (parcours **Data Engineer d'OpenClassrooms**, titre RNCP *Expert en ingénierie et science des données*, niveau 7 / bac +5).
Je conçois et automatise des chaînes de données de bout en bout : collecte, stockage, transformation, orchestration, mise à disposition et supervision, jusqu'à l'intégration de modèles d'IA générative.

**Stack principale** : Python · SQL · PostgreSQL · MongoDB · dbt · Airbyte · Kestra · Spark · Redpanda (Kafka) · Docker · AWS · Google Cloud · LangChain · Mistral AI

---

## Projets

Huit projets professionnalisants, du stockage de données à l'IA générative. Chaque dépôt contient le code et sa documentation.

| # | Projet | Contexte et réalisation | Outils | Résultat |
|---|---|---|---|---|
| 5 | [**Stockage sécurisé de données médicales**](https://github.com/AxelFB1992/projet5) | Migration automatisée d'un fichier plat de dossiers patients vers une base NoSQL, avec gestion des droits d'accès | Python, pandas, MongoDB, Docker Compose | 55 500 patients migrés en documents structurés ; 3 rôles d'accès ; migration reproductible |
| 6 | [**Consommation énergétique des bâtiments**](https://github.com/AxelFB1992/projet6) | Prédiction de la consommation des bâtiments de Seattle pour l'objectif de neutralité carbone de la ville, exposée par une API | Python, scikit-learn, XGBoost, BentoML, Docker, Google Cloud Run | Modèle XGBoost (R² = 0,724) servi par une API déployée dans le cloud |
| 7 | [**Base NoSQL pour l'analyse de locations**](https://github.com/AxelFB1992/projet7) | Conception et analyse d'une base MongoDB sur les annonces Airbnb de Paris et Lyon | MongoDB (ReplicaSet, sharding), BI Connector, Tableau | Cluster répliqué et partitionné, connecté à un outil de visualisation |
| 8 | [**Pipeline ELT de données météorologiques**](https://github.com/AxelFB1992/projet8) | Ingestion des relevés de 6 stations météo, modélisation et déploiement sur AWS | Airbyte, PostgreSQL, dbt, AWS (RDS, ECR, ECS Fargate, Step Functions, EventBridge, CloudWatch, SNS, Secrets Manager) | Modèle dbt en 3 couches (staging, intermediate, marts) ; pipeline planifié et supervisé sur AWS |
| 9 | [**Architecture cloud hybride**](https://github.com/AxelFB1992/projet9) | Modélisation d'une infrastructure de données hybride et POC de traitement en flux de tickets clients | AWS (S3, Redshift, DMS, EC2, VPN, AD Connector), Redpanda, PySpark, Docker | Architecture cible documentée ; POC streaming entièrement conteneurisé |
| 10 | [**Orchestration d'un pipeline de ventes**](https://github.com/AxelFB1992/projet10) | Automatisation de l'analyse des ventes d'un marchand de vin à partir de son ERP et de sa boutique en ligne | Kestra, DuckDB, Python, pandas, Docker | Pipeline mensuel avec un test après chaque étape ; CA par produit et segmentation des vins premium (z-score) |
| 11 | [**Chatbot RAG d'événements culturels**](https://github.com/AxelFB1992/projet11) | POC d'assistant de recommandation d'événements culturels (Pays de la Loire) à partir des données OpenAgenda | Python, LangChain, Mistral AI (mistral-embed, Mistral Small), FAISS | Pipeline collecte → nettoyage → 9 tests de qualité → vectorisation ; chatbot avec filtrage par lieu et repli |
| 12 | [**Infrastructure de données automatisée**](https://github.com/AxelFB1992/projet12) | Automatisation de l'infrastructure de données d'une plateforme d'entraînement à la course à pied, en batch et en temps réel | Kestra, PostgreSQL, dbt, Redpanda, Debezium, Soda, Google Maps API | [Résultat à compléter] |

---

## Compétences démontrées

| Compétence | Projets |
|---|---|
| Concevoir et administrer des bases de données (SQL et NoSQL) | 5 · 7 · 8 · 12 |
| Construire des pipelines de données (ETL / ELT) | 8 · 10 · 11 · 12 |
| Orchestrer et planifier des flux | 8 · 10 · 12 |
| Traiter des données en temps réel (streaming) | 9 · 12 |
| Tester et contrôler la qualité des données | 10 · 11 · 12 |
| Concevoir et déployer une infrastructure cloud | 6 · 8 · 9 |
| Conteneuriser des applications | 5 · 6 · 9 · 10 |
| Sécuriser l'accès aux données | 5 · 8 · 9 |
| Intégrer des modèles de machine learning et d'IA générative | 6 · 11 |
| Documenter et présenter ses choix techniques | tous |

## Ce que j'apporte

- **Une vision de bout en bout** : de la source de données brute jusqu'au service exposé à l'utilisateur, en passant par le stockage, la transformation et la supervision.
- **Des pipelines fiables** : tests de qualité à chaque étape, automatisation et monitoring plutôt que traitements manuels.
- **Des choix techniques argumentés** : solutions adaptées au besoin, au budget et aux contraintes (simplicité, coût, souveraineté des données).
- **Une double compétence data et IA générative** : RAG, bases vectorielles et intégration de modèles de langage dans une architecture de données.

---

## Contact

[LinkedIn à compléter] · [Adresse e-mail à compléter]
