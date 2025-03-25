# 🏪 Data Pipeline Retail

Projet personnel de data engineering simulant un pipeline de données retail en environnement moderne (ELT) avec ingestion, transformation, tests et orchestration.

---

## 📌 Objectifs pédagogiques

- Comprendre et implémenter un pipeline ELT complet
- Utiliser les outils modernes de la data stack : Airflow, DBT, SQL, Python
- Appliquer les bonnes pratiques de structuration, tests et documentation
- Simuler une stack cloud (Snowflake, etc.) en environnement local

---

## ⚙️ Outils utilisés

| Outil        | Rôle                                               |
|--------------|----------------------------------------------------|
| Python       | Scripts d'ingestion et manipulation de données     |
| Pandas       | Nettoyage et transformation initiale               |
| SQLite / PostgreSQL | Stockage local simulant Snowflake           |
| SQLAlchemy   | Connexion et insertion dans la base                |
| DBT          | Transformations SQL + tests + documentation        |
| Airflow      | Orchestration du pipeline (DAG)                    |
| GitHub       | Versionnage et publication                         |

---

## 📁 Structure du projet

data-pipeline-retail/ ├── airflow/ ← DAG Airflow ├── dbt/ ← Projet DBT (modèles SQL, tests…) ├── data/ ← Données brutes (CSV) ├── notebooks/ ← Analyses exploratoires ou KPIs ├── etl/ ← Scripts Python (extraction, chargement) ├── README.md ├── requirements.txt └── docker-compose.yml ← (optionnel) Setup local


---

## 🚀 À venir

- Ajout d’un DAG Airflow pour orchestrer le pipeline
- Création de modèles DBT : staging, marts, KPIs
- Documentation automatique avec DBT docs
- Test de qualité sur les données

---

## 📸 Captures (à venir)

- Aperçu du DAG Airflow
- Résultats de tests DBT
- Extraits de données transformées
