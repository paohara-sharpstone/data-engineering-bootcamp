


# Plan de Formation Data Engineering

Un programme complet de 200 heures structuré en 5 modules pour maîtriser le Data Engineering avec un apprentissage pratique et des projets concrets.

## Vue d'ensemble

Cette formation vous permettra d'acquérir toutes les compétences essentielles du Data Engineering, de la programmation Python aux architectures Big Data, en passant par l'orchestration de pipelines et le streaming de données.

**Durée totale :** 200 heures  
**Structure :** 5 modules de 40 heures chacun  
**Approche :** Apprentissage pratique avec projets GitHub

---

## Module 1 : Fondamentaux du Data Engineering (40h)

### Semaines 1-2

**Objectifs :**
- Maîtriser Python pour le Data Engineering
- Comprendre CI/CD et les bonnes pratiques
- Découvrir Docker et les concepts serverless
- Créer un Data Lake basique

### Programme détaillé

#### Semaine 1 : Setup et Python
- **Jour 1-2 :** Configuration environnement local
  - Installation Python, VS Code, Git
  - Configuration GitHub et création repo personnel
  - Setup environnement virtuel avec Poetry

- **Jour 3-5 :** Python pour Data Engineering
  - Révision Python avancé (classes, modules, gestion erreurs)
  - Manipulation de données avec Pandas/NumPy
  - Lecture/écriture fichiers (CSV, JSON, Parquet)

#### Semaine 2 : CI/CD et Docker
- **Jour 1-2 :** Qualité de code
  - Configuration Ruff et Pylint
  - Pre-commit hooks avec GitHub
  - Tests unitaires avec pytest

- **Jour 3-4 :** CI/CD avec GitHub Actions
  - Workflows automatisés
  - Tests et déploiement continu

- **Jour 5 :** Introduction Docker
  - Concepts de base, Dockerfile
  - Containerisation d'une app Python simple

**Projet pratique :** Pipeline ETL simple avec validation automatique via GitHub Actions

---

## Module 2 : Gestion de Bases de Données (40h)

### Semaines 3-4

**Objectifs :**
- Maîtriser SQL avancé
- Comprendre PostgreSQL et BigQuery
- Découvrir Docker Compose

### Programme détaillé

#### Semaine 3 : SQL et PostgreSQL
- **Jour 1-2 :** SQL avancé
  - Jointures complexes, CTEs, window functions
  - Optimisation de requêtes

- **Jour 3-5 :** PostgreSQL en local
  - Installation et configuration PostgreSQL
  - Administration de base (users, permissions)
  - Backup/restore, monitoring

#### Semaine 4 : Data Warehouse et Docker Compose
- **Jour 1-2 :** Concepts Data Warehouse
  - Modélisation dimensionnelle
  - Star schema vs Snowflake

- **Jour 3-4 :** BigQuery (simulation locale)
  - Utilisation de DuckDB comme alternative locale
  - Requêtes analytiques complexes

- **Jour 5 :** Docker Compose
  - Multi-containers applications
  - PostgreSQL + application Python

**Projet pratique :** Data Warehouse local avec PostgreSQL et interface Python

---

## Module 3 : Pipelines et Orchestration (40h)

### Semaines 5-6

**Objectifs :**
- Maîtriser Airflow pour l'orchestration
- Comprendre dbt pour la transformation
- Découvrir Kubernetes (concepts)

### Programme détaillé

#### Semaine 5 : Airflow
- **Jour 1-2 :** Installation Airflow local
  - Configuration et premiers DAGs
  - Concepts : tasks, dependencies, scheduling

- **Jour 3-5 :** DAGs avancés
  - Gestion des erreurs et retry
  - Monitoring et alerting
  - Intégration avec bases de données

#### Semaine 6 : dbt et Kubernetes
- **Jour 1-3 :** dbt (data build tool)
  - Installation et configuration locale
  - Modèles, tests, documentation
  - Intégration avec PostgreSQL

- **Jour 4-5 :** Introduction Kubernetes
  - Concepts théoriques (pods, services, deployments)
  - Minikube pour tests locaux

**Projet pratique :** Pipeline ETL complet avec Airflow + dbt

---

## Module 4 : Big Data et Streaming (40h)

### Semaines 7-8

**Objectifs :**
- Comprendre PySpark
- Découvrir le streaming avec Kafka
- Monitoring et alerting

### Programme détaillé

#### Semaine 7 : PySpark
- **Jour 1-2 :** Installation PySpark local
  - Concepts RDD et DataFrames
  - Transformations et actions

- **Jour 3-5 :** Traitement de gros volumes
  - Optimisations et partitioning
  - Intégration avec différents formats

#### Semaine 8 : Streaming et Monitoring
- **Jour 1-3 :** Kafka local
  - Installation et configuration
  - Producers et consumers Python
  - Stream processing basique

- **Jour 4-5 :** Monitoring
  - Logging avec Python
  - Métriques et alerting
  - Grafana + Prometheus (optionnel)

**Projet pratique :** Pipeline de streaming avec Kafka et PySpark

---

## Module 5 : Projet Final (40h)

### Semaines 9-10

**Objectifs :**
- Intégrer tous les concepts appris
- Créer un projet complet de A à Z
- Bonnes pratiques DevOps

### Programme détaillé

#### Semaine 9 : Architecture et Infrastructure
- **Jour 1-2 :** Conception architecture
  - Choix technologiques
  - Documentation technique

- **Jour 3-5 :** Infrastructure as Code
  - Docker Compose avancé
  - Scripts d'automatisation

#### Semaine 10 : Finalisation et Déploiement
- **Jour 1-3 :** Développement projet
  - Implémentation pipeline complet
  - Tests et validation

- **Jour 4-5 :** Documentation et présentation
  - README détaillé
  - Déploiement local optimisé

**Projet final :** Architecture complète avec ingestion, transformation, stockage et visualisation

---

## Ressources et Outils

### Outils principaux
- **Python** : pandas, numpy, sqlalchemy, psycopg2
- **Bases de données** : PostgreSQL, DuckDB (alternative BigQuery)
- **Orchestration** : Apache Airflow
- **Transformation** : dbt-core
- **Big Data** : PySpark
- **Streaming** : Apache Kafka
- **Containerisation** : Docker, Docker Compose
- **CI/CD** : GitHub Actions, pre-commit
- **Qualité code** : Ruff, Pylint, pytest

### Alternatives locales pour services cloud
- **BigQuery** → DuckDB ou PostgreSQL
- **Google Cloud Storage** → MinIO (S3-compatible)
- **Dataflow** → PySpark local
- **Pub/Sub** → Apache Kafka

## Planning suggéré

- **20h/semaine** : Formation complète en 10 semaines
- **10h/semaine** : Formation étalée sur 20 semaines
- **40h/semaine** : Formation intensive en 5 semaines

## Prérequis

- Connaissances de base en Python
- Familiarité avec Git et GitHub
- Notions de base en SQL
- Environnement de développement configuré

## Structure des projets

Chaque module comprend :
- Des exercices pratiques quotidiens
- Un projet de fin de module
- Une documentation complète sur GitHub
- Des tests automatisés
- Une présentation des résultats

---

*Ce plan de formation est conçu pour un apprentissage autonome avec un focus sur la pratique et les projets concrets. Tous les outils utilisés peuvent être installés et utilisés localement.*