# 📊 Analyse du Churn Client

Solution de Business Intelligence dédiée à l'analyse du churn client dans le secteur des télécommunications.

## 📌 Présentation du projet

Ce projet consiste à mettre en place une solution complète de Business Intelligence permettant d'analyser le comportement des clients et d'identifier les profils présentant un risque élevé de churn.

La solution combine un processus ETL, un Data Warehouse, une analyse multidimensionnelle avec SSAS ainsi qu'un dashboard interactif pour faciliter l'analyse et la prise de décision.

## 🎯 Objectifs

- Analyser le comportement des clients
- Identifier les clients présentant un risque de churn
- Segmenter les clients selon leurs caractéristiques
- Construire un Data Warehouse centralisé
- Analyser les principaux indicateurs de churn
- Faciliter la prise de décision et les stratégies de fidélisation

## 🛠️ Technologies utilisées

### Business Intelligence
- SQL Server
- SSIS
- SSAS
- Data Warehouse
- Cube OLAP

### Analyse de données
- Python
- Pandas

### Visualisation
- Dash
- Plotly

## 🔄 Processus ETL

Le processus ETL est organisé en plusieurs étapes :

1. Chargement des données dans la zone de staging
2. Nettoyage et transformation des données
3. Chargement des tables de dimensions
4. Chargement de la table de faits
5. Création et alimentation du cube SSAS
6. Analyse des indicateurs liés au churn

## 📁 Structure du projet

```text
Projet_ETL_Telco_Churn/
│
├── Projet_ETL_Telco_Churn/
│   ├── 01_Load_Staging.dtsx
│   ├── 02_Load_Clean.dtsx
│   ├── 03_Load_Dimensions.dtsx
│   └── 04_Load_Fact.dtsx
│
├── Projet_SSAS_Telco_Churn/
│   ├── Cube_Telco_Churn.cube
│   ├── Dim_Customer.dim
│   ├── Dim_Contract.dim
│   ├── Dim_Service.dim
│   └── ...
│
└── Projet_ETL_Telco_Churn.sln
