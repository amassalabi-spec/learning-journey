# 🤖 ML Projects — Projets Pratiques

> **Projets concrets** : Web scraping, apps Streamlit, NLP, expériences ML.

## 🗂 Structure

```
ml-projects/
├── web-scraping/          # 🕷️ Selenium + BeautifulSoup
│   ├── scrapers/          #   Scripts d'extraction (Selenium, requests, bs4)
│   ├── data/              #   Données brutes exportées (CSV, JSON) — *gitignored*
│   └── results/           #   Résultats nettoyés — *gitignored*
│
├── streamlit-apps/        # 📱 Applications interactives
│   ├── mental-health/     #   Dashboard analyse sentiments + NLP
│   └── scrapers-ui/       #   Interface pour scrapers
│
├── nlp-experiments/       # 🧠 Traitement langage naturel
│   ├── sentiment-analysis/ #   Classification sentiments (transformers)
│   └── text-classification/ #   Autres tâches NLP
│
└── experiments/           # 🧪 Notebooks d'exploration
    ├── first_web_scraping_1A_BI&A.ipynb
    └── ...
```

## 🚀 Projets Détaillés

### 🕷️ Web Scraping (`web-scraping/`)
| Script | Description | Stack |
|--------|-------------|-------|
| `scrapers/selenium_scraper.py` | Extraction sites dynamiques (JS, pagination, formulaires) | Selenium, ChromeDriver |
| `scrapers/beautifulsoup_scraper.py` | Parsing HTML statique rapide | requests, BeautifulSoup |
| `data/` | Exports bruts (CSV/JSON) | — |

### 📱 Streamlit Apps (`streamlit-apps/`)
| App | Description | Fonctionnalités |
|-----|-------------|-----------------|
| `mental-health/` | Dashboard santé mentale | Analyse sentiments, visualisations temps réel, multi-pages |
| `scrapers-ui/` | UI pour lancer scrapers | Config paramètres, logs temps réel, download résultats |

### 🧠 NLP Experiments (`nlp-experiments/`)
- **Sentiment Analysis** : Fine-tuning / few-shot avec transformers (Hugging Face)
- **Text Classification** : Catégorisation documents, détection sujets
- **Embeddings** : Similarité sémantique, clustering

## 🛠 Stack Technique

| Domaine | Outils |
|---------|--------|
| **Scraping** | Selenium, BeautifulSoup, requests, lxml, playwright |
| **Web Apps** | Streamlit, Plotly, Altair, pandas |
| **NLP/ML** | transformers, scikit-learn, torch, sentence-transformers |
| **Data** | pandas, numpy, json, csv |
| **Env** | Jupyter, VS Code, venv |

## 🎯 Objectifs d'apprentissage

- [x] Automatiser l'extraction de données web (statique + dynamique)
- [x] Construire des apps data interactives avec Streamlit
- [x] Appliquer des modèles NLP pré-entraînés (transformers)
- [x] Expérimenter dans Jupyter, documenter le processus
- [x] Gérer des projets end-to-end : data → model → app

## 📚 Ressources

- [Streamlit Docs](https://docs.streamlit.io/)
- [Hugging Face Transformers](https://huggingface.co/docs/transformers/)
- [Selenium Python](https://selenium-python.readthedocs.io/)
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)

---

*Historique importé depuis `First_lab1` (avril-juin 2026)*