
![Tutorial Banner](./img/banner.png)


[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
[![Docker](https://img.shields.io/badge/Docker-Available-blue.svg)](https://www.docker.com/)
[![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?logo=neo4j&logoColor=white)](https://neo4j.com/)
[![NLTK](https://img.shields.io/badge/NLTK-3776AB?logo=python&logoColor=fff)](https://www.nltk.org)
[![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=fff)](https://pandas.pydata.org)
[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)
[![Website](https://img.shields.io/website-up-down-green-red/http/shields.io.svg)](https://shields.io/)


This repository supports the tutorial presented at [womENcourage 2025](https://womencourage.acm.org/2025/), focused on biomedical data wrangling and the construction of knowledge graphs (KGs) for **drug repurposing**. 

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
| Folder/File | Description |
|------------------|-------------|
| `notebooks/` | Step-by-step Colab notebooks |
| `data/` | Sample datasets (with metadata) |
| `scripts/` | Python scripts (e.g., MedJsonify utilities) |
| `docs/` | Tutorial webpage files (HTML, CSS, assets) |
| `requirements.txt` | Python dependencies |
| `.gitignore` | Files and folders excluded from versioning |
| `LICENSE` | License information |

---

## 🌐 Tutorial Website
Visit our tutorial webpage: [https://yourusername.github.io/repository-name](https://yourusername.github.io/repository-name)

The website source code is located in the `docs/` folder.

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
- [IBEB](https://ibeb.ciencias.ulisboa.pt/en/home-2/)  
- [LASIGE](https://lasige.pt)
- [NOVA LINCS](https://nova-lincs.di.fct.unl.pt)
- [womENcourage 2025](https://womencourage.acm.org/2025/)

---

## 📜 License

This project is licensed under the MIT License. See `LICENSE` for details.
