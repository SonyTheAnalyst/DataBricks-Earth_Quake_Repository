# 🌍 Earthquake Data Engineering Project  
### Medallion Architecture — Bronze • Silver • Gold

---

## 🇬🇧 English Version

## 📌 Overview
This project implements a complete **Medallion Architecture** (Bronze → Silver → Gold) to process, clean, and enrich **earthquake data**.  
The goal is to build a scalable, modular, and analytics‑ready data pipeline suitable for BI dashboards, machine learning models, or real‑time monitoring.

The repository contains Jupyter notebooks for each transformation layer and a visual pipeline diagram.

---

## 🏗️ Architecture (Medallion Model)

### 🥉 Bronze Layer — Raw Data
**Notebook:** `broze_notebook.ipynb`  
- Ingests raw earthquake data from the source.  
- Stores it in a structured but uncleaned format.  
- Preserves original schema and data fidelity.

### 🥈 Silver Layer — Cleaned Data
**Notebook:** `silver_notebook.ipynb`  
- Cleans and standardizes the Bronze dataset.  
- Handles missing values, type casting, and schema normalization.  
- Produces a reliable dataset ready for enrichment.

### 🥇 Gold Layer — Enriched Data
**Notebook:** `Gold_layer.ipynb`  
- Enriches the Silver dataset with additional features.  
- Applies business logic and joins with lookup tables (if applicable).  
- Produces analytics‑ready tables for dashboards or ML.

---

## 🔄 Pipeline Workflow
The pipeline follows this sequence:

1. Raw ingestion (Bronze)  
2. Cleaning & standardization (Silver)  
3. Enrichment & feature engineering (Gold)  
4. Final dataset ready for analysis  

A visual representation of the pipeline is included:  
`pipeline_earthquake.png`

---

## 🧰 Technologies Used
- Python  
- Jupyter Notebooks  
- Medallion Architecture  
- Data transformation & cleaning techniques  
- Spark / Pandas / Delta Lake  

---

## 🎯 Objectives
- Build a reproducible and modular data pipeline  
- Apply the Medallion Architecture to real‑world seismic data  
- Ensure data quality and consistency  
- Enable analytics and machine learning use cases  

---

---

---

## 🇫🇷 Version Française

## 📌 Aperçu
Ce projet met en place une **architecture Medallion** complète (Bronze → Silver → Gold) pour traiter, nettoyer et enrichir des **données sismiques**.  
L’objectif est de construire un pipeline modulaire, évolutif et prêt pour l’analyse, la BI ou le machine learning.

Le dépôt contient des notebooks Jupyter pour chaque couche de transformation ainsi qu’un schéma du pipeline.

---

## 🏗️ Architecture (Modèle Medallion)

### 🥉 Couche Bronze — Données Brutes
**Notebook :** `broze_notebook.ipynb`  
- Ingestion des données sismiques brutes.  
- Stockage structuré mais non nettoyé.  
- Conservation du schéma original.

### 🥈 Couche Silver — Données Nettoyées
**Notebook :** `silver_notebook.ipynb`  
- Nettoyage et standardisation du dataset Bronze.  
- Gestion des valeurs manquantes, typage, normalisation.  
- Production d’un dataset fiable prêt pour l’enrichissement.

### 🥇 Couche Gold — Données Enrichies
**Notebook :** `Gold_layer.ipynb`  
- Enrichissement des données Silver.  
- Application de la logique métier et jointures éventuelles.  
- Production de tables prêtes pour l’analyse ou le ML.

---

## 🔄 Flux du Pipeline
Le pipeline suit les étapes suivantes :

1. Ingestion brute (Bronze)  
2. Nettoyage et standardisation (Silver)  
3. Enrichissement et création de features (Gold)  
4. Dataset final prêt pour l’analyse  

Le schéma du pipeline est disponible :  
`pipeline_earthquake.png`

---

## 🧰 Technologies Utilisées
- Python  
- Jupyter Notebooks  
- Architecture Medallion  
- Techniques de transformation et nettoyage  
- (Optionnel) Spark / Pandas / Delta Lake  

---

## 🎯 Objectifs
- Construire un pipeline modulaire et reproductible  
- Appliquer l’architecture Medallion à des données sismiques réelles  
- Garantir la qualité et la cohérence des données  
- Permettre l’analyse et le machine learning  

---

## 📁 Structure du Dépôt
