# 📚 Learning Journey — Monorepo d'Apprentissage

> **Parcours d'apprentissage** : De mes premiers pas en Python aux projets Data Science & ML concrets.  
> Historique Git préservé pour suivre la progression réelle.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?logo=python)](https://python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)](https://jupyter.org)
[![Streamlit](https://img.shields.io/badge/Streamlit-Apps-FF4B4B?logo=streamlit)](https://streamlit.io)
[![Pandas](https://img.shields.io/badge/Pandas-Data-150458?logo=pandas)](https://pandas.pydata.org)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-F7931E?logo=scikitlearn)](https://scikit-learn.org)

---

## 🗂 Structure du Monorepo

```
learning-journey/
├── python-fundamentals/      # 🐍 Bases Python & setup environnement
│   └── README.md             #   Installation, syntaxe, structures, fonctions, modules
│
├── data-science-labs/        # 📊 Introduction aux Applications Data
│   └── README.md             #   Pandas, NumPy, Visualisation, Nettoyage, EDA
│
└── ml-projects/              # 🤖 Projets pratiques ML & Data
    ├── web-scraping/         #   Selenium + BeautifulSoup (automatisation)
    ├── streamlit-apps/       #   Apps interactives (dashboard, NLP)
    ├── nlp-experiments/      #   Analyse sentiments, classification, embeddings
    ├── experiments/          #   Notebooks Jupyter d'exploration
    ├── first_web_scraping_1A_BI&A.ipynb
    ├── stremlit_apps.py
    ├── my_streamlit_app/     #   Multi-page Streamlit app
    └── scratch/              #   Scripts de test rapides
```

---

## 🎯 Modules & Progression

| Module | Période | Compétences Clés | Projets |
|--------|---------|------------------|---------|
| **python-fundamentals** | Avril 2026 | Python 3, VS Code, venv, pip, syntaxe, contrôle de flux, fonctions | Setup environnement, premiers scripts |
| **data-science-labs** | Avril 2026 | Pandas, NumPy, Matplotlib/Seaborn, Nettoyage, EDA, Jupyter | Manipulation datasets, visualisation |
| **ml-projects** | Avril-Juin 2026 | Selenium, Streamlit, Transformers, NLP, Scraping, ML | Web scraping, Dashboard santé mentale, Sentiment Analysis |

---

## 🚀 Projets Phares (dans `ml-projects/`)

### 🕷️ Web Scraping & Automatisation
- **Selenium Scrapers** : Extraction sites dynamiques (JS, pagination, formulaires) → Export CSV/JSON
- **BeautifulSoup** : Parsing HTML statique rapide
- **Gestion** : Rate limiting, retries, headers rotatifs, Cloudflare bypass basique

### 📱 Streamlit Apps
| App | Fonctionnalités |
|-----|-----------------|
| **Mental Health AI Dashboard** | Analyse sentiments temps réel, visualisations interactives, multi-pages (Tables, Graphiques, NLP) |
| **Scrapers UI** | Interface pour configurer/lancer scrapers, logs temps réel, téléchargement résultats |

### 🧠 NLP & ML Experiments
- **Sentiment Analysis** : Few-shot / fine-tuning avec Transformers (Hugging Face)
- **Text Classification** : Catégorisation documents, détection sujets
- **Embeddings** : Similarité sémantique, clustering, recherche vectorielle

---

## 🛠 Stack Technique

| Domaine | Outils |
|---------|--------|
| **Core** | Python 3.10+, Jupyter, VS Code |
| **Data** | Pandas, NumPy, JSON, CSV, Parquet |
| **Visualisation** | Matplotlib, Seaborn, Plotly, Altair |
| **Web/Scraping** | Selenium, BeautifulSoup, Requests, Playwright |
| **Apps** | Streamlit, Plotly Express |
| **NLP/ML** | Transformers, Scikit-learn, Sentence-Transformers, Torch |
| **Env** | venv, pip, requirements.txt |

---

## 📦 Installation

```bash
# Cloner
git clone https://github.com/amassalabi-spec/learning-journey.git
cd learning-journey

# Environnement global (optionnel)
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate

# Dépendances par projet
cd ml-projects/my_streamlit_app && pip install -r requirements.txt
cd ../../ml-projects/web-scraping && pip install -r requirements.txt  # si existe
```

---

## 📈 Philosophie d'Apprentissage

> **Apprendre en construisant** — Chaque dossier = un projet réel, pas juste des exercices.

1. **Fondations solides** → `python-fundamentals/`
2. **Data literacy** → `data-science-labs/`
3. **Projets end-to-end** → `ml-projects/` (data → model → app)

**Pourquoi un monorepo ?**
- 📜 Historique unique = progression visible
- 🔗 Réutilisation code entre modules
- 📦 Portfolio cohérent pour recruteurs
- 🧹 Nettoyage centralisé (`.gitignore`, `LICENSE`, `README`)

---

## 🤝 Contribuer (à soi-même)

- ✅ Un commit = une étape d'apprentissage claire
- ✅ Messages Conventional Commits (`feat:`, `fix:`, `docs:`, `refactor:`)
- ✅ Nettoyer les données lourdes (`.gitignore` : `*.csv`, `*.json`, `*.pkl`, `__pycache__/`)
- ✅ Documenter dans `README.md` de chaque module

---

## 📄 License

MIT License — Voir `LICENSE`

---

## 👤 Auteur

**MASSALABI OUMAROU Almajir**  
🇲🇦 Maroc | Data Science & AI Engineer  
🔗 [GitHub](https://github.com/amassalabi-spec) | 📧 amassalabi@gmail.com

---

> *"Le code qu'on écrit en apprenant devient la fondation de ce qu'on construit en pro."*