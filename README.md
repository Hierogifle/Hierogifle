<div align="center">

# 🧠 Romuald Courtois
### *De l'humain à l'IA — quand les sciences cognitives rencontrent le Machine Learning*

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=36BCF7&center=true&vCenter=true&multiline=true&width=650&height=80&lines=Alternant+Data+%26+IA+%40+Candide+%C3%97+Blue;M2+Expert+IA+%26+Data+%40+La+Plateforme_;Facteurs+humains+%C3%97+Machine+Learning)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/romuald-courtois-b71945231/)
[![Email](https://img.shields.io/badge/Contact-8B89CC?style=for-the-badge&logo=protonmail&logoColor=white)](mailto:romuald.courtois@proton.me)
[![Projet phare](https://img.shields.io/badge/Projet_phare-Terre_Vent_Feu_Eau_Data-e34948?style=for-the-badge&logo=streamlit&logoColor=white)](https://terre-vent-feu-eau-data.streamlit.app)

</div>

---

## 🎯 En une phrase

**Alternant Data & IA chez Candide × Blue** — une alternative domestique à l'eau en bouteille, pilotée par la qualité de l'eau locale — et en **M2 Expert IA & Data à [La Plateforme_](https://laplateforme.io)**, je construis des modèles dont on peut **vérifier les résultats** : protocole avant le code, validation sans fuite, incertitude chiffrée.

Mon atout : un background de chercheur en **STAPS – Facteurs Humains** (eye-tracking, modélisation du comportement). La démarche scientifique — hypothèse, biais, validation — appliquée au Machine Learning.

---

## 🛤️ Parcours

```mermaid
timeline
    title Du comportement humain à la data science
    2019-2024 : 🏃 Master STAPS — Facteurs Humains
              : Eye-tracking · recherche expérimentale · statistiques
    2024      : 🔄 Le pivot
              : Machine Learning appliqué aux sciences du comportement
    2025-2027 : 🎓 Master Expert IA & Data @ La Plateforme_
              : Deep Learning · Computer Vision · MLOps
    2025-2026 : 🤖 Lab IA @ La Plateforme_ (alternance)
              : RAG · LLMs · Vision médicale
    2026-2027 : 💧 Data & IA @ Candide × Blue (alternance)
              : Qualité de l'eau · SISE-Eaux · moteur de recommandation
```

---

## 🔭 En ce moment

```python
class Romuald:
    role     = "Alternant Data & IA @ Candide × Blue"
    school   = "M2 Expert IA & Data @ La Plateforme_"
    shipping = ["💧 Qualité de l'eau à l'adresse", "🔥 Terre-Vent-Feu-Eau-Data"]
    learning = ["Séries temporelles", "Statistiques bayésiennes", "MLOps"]
    method   = "Hypothèse → Données → Modèle → Validation → Déploiement"
    rule     = "Une métrique trop belle est une fuite jusqu'à preuve du contraire"
```

---

## 💧 Chez Candide × Blue

*Une station d'affinage de l'eau du robinet (filtration + pétillance) et des minéraux fonctionnels en sticks, recommandés à partir de la qualité de l'eau du foyer.*

Je porte le **volet data & IA** de l'entreprise. Le cœur : **croiser la qualité de l'eau à l'adresse avec le profil du foyer** pour recommander la bonne cartouche filtrante et le bon profil de reminéralisation.

<table>
<tr>
<td width="50%" valign="top">

**✅ Fait**
- Acquisition et structuration des données du contrôle sanitaire **SISE-Eaux** (~7 Go) et des contours des réseaux de distribution
- **18 notebooks d'analyse** de la qualité de l'eau du robinet en France, restitués à la direction
- Audit chiffré d'un POC de base de données livré par un prestataire
- **Explorateur eau** : outil web interne d'exploration des données

</td>
<td width="50%" valign="top">

**🛠️ En cours / à venir**
- Chaînage **adresse → UDI → derniers résultats d'analyse**, socle du moteur de recommandation
- Modélisation de la qualité de l'eau par territoire : nitrates, pesticides et métabolites, **PFAS**
- Extension à l'Europe et classement des pays par disponibilité des données
- Télémétrie de la station, indicateurs d'impact, outils IA internes et charte IA

</td>
</tr>
</table>

`SISE-Eaux` · `Hub'Eau` · `Géodonnées` · `SQL` · `Python` · `Recommandation`

---

## ⭐ Projet phare

### 🔥 [Terre, Vent, Feu, Eau, Data](https://github.com/Hierogifle/terre-vent-feu-eau-data) — risque de feu de forêt, commune × jour

[![Application](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://terre-vent-feu-eau-data.streamlit.app)
[![Présentation](https://img.shields.io/badge/vitrine-hierogifle.github.io-e34948)](https://hierogifle.github.io/terre-vent-feu-eau-data/)
[![CI](https://github.com/Hierogifle/terre-vent-feu-eau-data/actions/workflows/ci.yml/badge.svg)](https://github.com/Hierogifle/terre-vent-feu-eau-data/actions/workflows/ci.yml)

*Quel est le risque de feu de la commune X le jour J ?* Quatre sources publiques (Copernicus CEMS, BDIFF, CORINE, INSEE) croisées dans PostgreSQL/PostGIS, une grille de **253 M lignes** (2006-2025) et un événement à **0,019 %** de positifs.

<table>
<tr>
<td width="55%">

<a href="https://terre-vent-feu-eau-data.streamlit.app"><img src="https://raw.githubusercontent.com/Hierogifle/terre-vent-feu-eau-data/main/docs/img/carte.png" alt="Carte du risque de feu au 12 août 2024"></a>

</td>
<td width="45%">

- **Barrière temporelle** train 2006-19 / val 2020-22 / test 2023-25, garde-fous anti-fuite testés
- **5 modèles** comparés avec IC appariés — XGBoost, RF, DART, MLP, LSTM
- **×63,7 le hasard** sur le test, mesuré une seule fois
- **Explicabilité** : SHAP local, LIME, contrefactuels DiCE
- **Séries temporelles** : ADF, SARIMAX, tendance sur 53 ans de météo
- **Projections 2100** sous 3 scénarios GIEC
- Sans `lat`/`lon`, le modèle retrouve seul les Landes, la Méditerranée et la Corse

</td>
</tr>
</table>

`PostgreSQL/PostGIS` · `XGBoost` · `PyTorch` · `SHAP` · `statsmodels` · `Streamlit` · `pytest` · `GitHub Actions`

---

## 🧪 Autres projets

| Projet | Ce que ça fait | Stack |
|---|---|---|
| 🎬 [**Sparkle Movie**](https://github.com/Hierogifle/sparkle-movie) | Recommandation sur 87 000+ films : *« Fait pour vous »* (KNN + cosinus TF-IDF) et *« Changer d'air »* (hors de ses genres habituels) | `FastAPI` `scikit-learn` `React 19` `Docker` |
| ✍️ [**Handwritten Digits**](https://github.com/Hierogifle/Handwritten_Digits_Classification) | App web MNIST : dessin, upload ou caméra, prédictions MLP et CNN comparées en direct | `PyTorch` `Flask` `Canvas` `WebRTC` |
| 🎓 [**DropOutGuard**](https://github.com/Hierogifle/DropOutGuard) | Détection précoce du décrochage étudiant : AFDM sur données mixtes + MLP, dont un MLP NumPy from scratch | `PyTorch` `NumPy` `FAMD` |
| 🧩 [**ANN Playground**](https://github.com/Hierogifle/ANN-playground) · [**Perceptron**](https://github.com/Hierogifle/building-perceptron) | Fondamentaux : perceptron puis MLP codés à la main, comparés à Keras | `NumPy` `Keras` |
| 📚 [**L'Odyssée de l'IA**](https://github.com/Hierogifle/ai-odyssey) | Recueil documentaire sur l'histoire de l'IA, de la logique aux transformers, avec timeline interactive | `LaTeX` `HTML` |

<details>
<summary><b>🤖 Lab IA — La Plateforme_ (2025-2026)</b></summary>
<br>

- **RAG Teams Bot** — assistant RAG avec LLM local (Ollama / Qwen) intégré à Microsoft Teams, pensé pour les contraintes UX enterprise (latence, progressive disclosure)
- **Astrolabe / Nebula** — SaaS d'analyse du marché de l'emploi : scraping, enrichissement LLM, dashboard d'insights
- **Ruban Rose** — classification histopathologique Benign / Malignant (BreakHis), split sans fuite patient, Focal Loss

</details>

---

## 🛠️ Stack technique

### 💻 Langages
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/r-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white)
![Matlab](https://img.shields.io/badge/MATLAB-FF6600?style=for-the-badge&logo=matlab&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Bash](https://img.shields.io/badge/bash-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)
![LaTeX](https://img.shields.io/badge/latex-%23008080.svg?style=for-the-badge&logo=latex&logoColor=white)

### 📊 Data Science & ML
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=for-the-badge)
![statsmodels](https://img.shields.io/badge/statsmodels-4B8BBE?style=for-the-badge)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)
![Optuna](https://img.shields.io/badge/Optuna-1F5FDB?style=for-the-badge)
![SHAP](https://img.shields.io/badge/SHAP_·_LIME_·_DiCE-FF0D57?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

### 🧠 Deep Learning & Computer Vision
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![CUDA](https://img.shields.io/badge/cuda-000000.svg?style=for-the-badge&logo=nVIDIA&logoColor=76B900)
![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)
![HuggingFace](https://img.shields.io/badge/🤗%20Hugging%20Face-FFD21E?style=for-the-badge)

### 🚀 LLMs & IA générative
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-D4A27A?style=for-the-badge&logo=anthropic&logoColor=white)
![RAG](https://img.shields.io/badge/RAG_Pipelines-FF6F61?style=for-the-badge)

### 🗄️ Données & géospatial
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![PostGIS](https://img.shields.io/badge/PostGIS-2A5C8C?style=for-the-badge)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![GeoPandas](https://img.shields.io/badge/GeoPandas-139C5A?style=for-the-badge)
![xarray](https://img.shields.io/badge/xarray_·_NetCDF-0E4666?style=for-the-badge)
![Hub'Eau](https://img.shields.io/badge/API_Hub'Eau_·_open_data-0A6EBD?style=for-the-badge)
![Parquet](https://img.shields.io/badge/Parquet-50ABF1?style=for-the-badge&logo=apacheparquet&logoColor=white)

### 📈 Visualisation
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)
![Altair](https://img.shields.io/badge/Altair_·_Vega-1F77B4?style=for-the-badge)
![pydeck](https://img.shields.io/badge/pydeck_·_deck.gl-2C2C2C?style=for-the-badge)

### 🌐 Apps & API
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

### 🐳 DevOps & qualité
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![uv](https://img.shields.io/badge/uv-DE5FE9?style=for-the-badge&logo=uv&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![WSL](https://img.shields.io/badge/WSL2-4D4D4D?style=for-the-badge&logo=windows-terminal&logoColor=white)

### 🧩 Modèles & méthodes

<table>
<tr>
<td width="25%" align="center" valign="top">

#### 🔮 Neural Nets
`MLP` · `CNN`
`LSTM` · `Transformers`

</td>
<td width="25%" align="center" valign="top">

#### 🌳 Tree-Based
`XGBoost` · `DART`
`LightGBM`
`Random Forest`

</td>
<td width="25%" align="center" valign="top">

#### ⏱️ Séries temporelles
`SARIMAX`
`ACF` · `PACF` · `ADF`

</td>
<td width="25%" align="center" valign="top">

#### 📉 Réduction de dim.
`PCA` · `MCA` · `FAMD`
`t-SNE` · `UMAP`
`PaCMAP`

</td>
</tr>
<tr>
<td width="25%" align="center" valign="top">

#### 🔍 Explicabilité
`SHAP` · `LIME`
`DiCE` (contrefactuels)

</td>
<td width="25%" align="center" valign="top">

#### ✅ Évaluation
`Calibration`
`IC appariés`
`Split temporel / par groupe`

</td>
<td width="25%" align="center" valign="top">

#### ⚙️ Optimisation
`Optuna` · `Grid Search`
`Focal Loss`
`Rééchantillonnage`

</td>
<td width="25%" align="center" valign="top">

#### 💬 NLP & Reco
`RAG` · `TF-IDF`
`KNN` · `Cosine sim.`

</td>
</tr>
</table>

---

## 🎯 Vision

> *"Construire une IA qui décode le comportement humain — pour améliorer performance, santé et qualité des décisions."*

- Modélisation prédictive des intentions via **eye-tracking**
- IA appliquée au **sport, à l'esport et à la santé**
- Systèmes adaptatifs **human-centered**, évalués avec la rigueur d'un protocole expérimental

**Objectif long terme :** une carrière **R&D** à l'intersection de l'IA, des sciences cognitives et de la performance humaine.

---

## 🏃 Hors du code

| ⚽ **Football** <br> *lecture tactique* | 🏐 **Volley-ball** <br> *coordination collective* | ⛰️ **Trail running** <br> *endurance mentale* |
| 🎮 **Gaming** <br> *sujet de recherche ET passion* | 👨‍🍳 **Cuisine** <br> *expérimentation (résultats variables)* | 📖 **Lecture** <br> *IA, sciences, philo* |

---

<div align="center">

### 🤝 On en parle ?

**Data de l'eau ?** · **Data science appliquée à la santé ?** · **Eye-tracking ?** · **Projet R&D ?** · **Juste discuter ?**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/romuald-courtois-b71945231/)
[![Email](https://img.shields.io/badge/Email-8B89CC?style=for-the-badge&logo=protonmail&logoColor=white)](mailto:romuald.courtois@proton.me)

![Wave](https://capsule-render.vercel.app/api?type=waving&color=36BCF7&height=100&section=footer)

*« L'IA la plus sophistiquée reste l'intelligence humaine… pour l'instant 😉 »*

</div>
