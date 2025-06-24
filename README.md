# data-engineering-bootcamp

## Description

Formation complète au Data Engineering en 5 modules (200h) couvrant les technologies et bonnes pratiques essentielles du Data Engineering moderne.

## Objectifs de la formation

- Maîtriser les outils et technologies du Data Engineering
- Concevoir et implémenter des pipelines ETL robustes
- Gérer des bases de données et data warehouses
- Orchestrer des workflows complexes avec Airflow
- Traiter de gros volumes de données avec Spark
- Appliquer les bonnes pratiques DevOps et CI/CD

## Programme de formation

### Module 1 : Fondamentaux du Data Engineering (40h)
*Semaines 1-2*

**Configuration et Python avancé**
- Setup environnement local (Python, VS Code, Git, Poetry)
- Configuration GitHub avec SSH et 2FA
- Python pour Data Engineering (classes, modules, gestion d'erreurs)
- Manipulation de données avec Pandas/NumPy
- Formats de fichiers (CSV, JSON, Parquet)

**CI/CD et Docker**
- Qualité de code (Ruff, Pylint, pre-commit hooks)
- Tests unitaires avec pytest
- GitHub Actions pour CI/CD
- Introduction Docker et containerisation

**Projet pratique :** Pipeline ETL simple avec validation automatique

---

### Module 2 : Gestion de Bases de Données (40h)
*Semaines 3-4*

**SQL et PostgreSQL**
- SQL avancé (jointures complexes, CTEs, window functions)
- PostgreSQL local (installation, administration, optimisation)
- Modélisation dimensionnelle et Data Warehouse

**Analytics et Docker Compose**
- DuckDB comme alternative locale à BigQuery
- Requêtes analytiques complexes
- Applications multi-containers avec Docker Compose

**Projet pratique :** Data Warehouse local avec PostgreSQL

---

### Module 3 : Pipelines et Orchestration (40h)
*Semaines 5-6*

**Apache Airflow**
- Installation et configuration Airflow local
- Création et gestion de DAGs
- Gestion des erreurs, monitoring et alerting

**dbt et Kubernetes**
- Transformations avec dbt (data build tool)
- Tests et documentation automatisés
- Introduction aux concepts Kubernetes avec Minikube

**Projet pratique :** Pipeline ETL complet avec Airflow + dbt

---

### Module 4 : Big Data et Streaming (40h)
*Semaines 7-8*

**PySpark**
- Installation PySpark local
- RDD et DataFrames, transformations et actions
- Optimisations et traitement de gros volumes

**Streaming et Monitoring**
- Apache Kafka local (producers, consumers)
- Stream processing en temps réel
- Monitoring avec logging et métriques

**Projet pratique :** Pipeline de streaming avec Kafka et PySpark

---

### Module 5 : Projet Final (40h)
*Semaines 9-10*

**Architecture complète**
- Conception d'architecture Data Engineering
- Infrastructure as Code avec Docker Compose
- Intégration de tous les outils appris

**Déploiement et documentation**
- Pipeline complet de A à Z
- Documentation technique et utilisateur
- Bonnes pratiques DevOps

**Projet final :** Architecture complète avec ingestion, transformation, stockage et visualisation

---

## Stack technique

### Langages et frameworks
- **Python 3.11+** : Langage principal
- **SQL** : PostgreSQL, DuckDB
- **Bash** : Scripts d'automatisation

### Data Engineering
- **Apache Airflow** : Orchestration de workflows
- **dbt** : Transformations de données
- **PySpark** : Traitement Big Data
- **Apache Kafka** : Streaming temps réel

### DevOps et Infrastructure
- **Docker & Docker Compose** : Containerisation
- **GitHub Actions** : CI/CD
- **Poetry** : Gestion des dépendances Python
- **pytest** : Tests unitaires

### Qualité de code
- **Ruff** : Linting rapide
- **Black** : Formatage automatique
- **pre-commit** : Hooks Git
- **Pylint** : Analyse statique

---

## Installation et démarrage rapide

### Prérequis
- Python 3.11+
- Git configuré
- Docker Desktop
- VS Code (recommandé)

### Setup initial
```bash
# Cloner le repository
git clone git@github.com:VOTRE_USERNAME/data-engineering-bootcamp.git
cd data-engineering-bootcamp

# Module 1 : Fondamentaux
cd module1
poetry install
poetry shell

# Lancer le cours interactif
jupyter notebook notebooks/cours-module1.ipynb
