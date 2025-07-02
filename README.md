
<div style="display: flex; align-items: center;">
    <div style="flex: 1;">
        <a href="https://isel.pt" target="_blank">
            <img src="./img/isel_logo.png" alt="ISEL logo" style="width: 400px; height: auto;">
        </a>
    </div>
    <div style="flex: 1;">
        <a href="https://womencourage2025.org" target="_blank">
            <img src="./img/womencourage_logo.png" alt="womENcourage 2025 logo" style="width: 300px; height: auto;">
        </a>
    </div>
    <div style="flex: 3; text-align: left; padding-left: 20px;">
        <h3>From Messy Data to Medical Insights: Creating Knowledge Graphs for Drug Repurposing</h3>
        <p><em>Tutorial presented at womENcourage 2025</em></p>
    </div>
</div>

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
[![Docker](https://img.shields.io/badge/Docker-Available-blue.svg)](https://www.docker.com/)
[![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?logo=neo4j&logoColor=white)](https://neo4j.com/)
[![NLTK](https://img.shields.io/badge/NLTK-3776AB?logo=python&logoColor=fff)](https://www.nltk.org)
[![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=fff)](https://pandas.pydata.org)
[![Website](https://img.shields.io/website-up-down-green-red/http/shields.io.svg)](https://shields.io/)

This repository supports the tutorial presented at [womENcourage 2025], focused on biomedical data wrangling and the construction of knowledge graphs (KGs) for **drug repurposing**. 

Participants will learn practical techniques using Python, public drug databases, and the Neo4j graph database — all within Google Colab.

---

## 📚 Tutorial Overview

- **Objective**: Learn to extract, clean, integrate, and visualize pharmaceutical data as Knowledge Graphs.
- **Main Tooling**: Python, Neo4j, MedJsonify (custom methodology), Google Colab
- **Key Concepts**:
  - Named Entity Recognition (NER)
  - Relationship extraction
  - Biomedical ontologies and sources (DrugBank, DO, ChEBI, etc.)
  - Cypher queries and graph visualization

---

## 📁 Repository Structure

| Folder/File      | Description |
|------------------|-------------|
| `notebooks/`     | Step-by-step Colab notebooks |
| `data/`          | Sample datasets (with metadata) |
| `scripts/`       | Python scripts (e.g., MedJsonify utilities) |
| `assets/`        | Images or diagrams for the tutorial |
| `requirements.txt` | Python dependencies |
| `.gitignore`     | Files and folders excluded from versioning |
| `LICENSE`        | License information |

---

## ▶️ How to Run (Google Colab)

All notebooks are Colab-ready. Click the badge below to launch the main tutorial:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

---

## 🔗 Data Sources

We use data from:
- [DailyMed](https://dailymed.nlm.nih.gov/)
- [DrugBank](https://go.drugbank.com/)
- [ChEBI](https://www.ebi.ac.uk/chebi/)
- [Orphanet](https://www.orpha.net/)
- [Purple Book](https://purplebooksearch.fda.gov/)
- [Orange Book](https://www.accessdata.fda.gov/scripts/cder/ob/)

See the `data/README.md` for usage and licensing info.

---

## 🤝 Acknowledgments
Supported by:
- LASIGE
- IBEB  
- NOVA LINCS
- [womENcourage 2025](https://womencourage2025.org) <img src="./img/womencourage_logo.png" alt="womENcourage 2025" height="30">

---

## 📜 License

This project is licensed under the MIT License. See `LICENSE` for details.
