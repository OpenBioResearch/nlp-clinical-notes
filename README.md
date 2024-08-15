# nlp-clinical-notes

## Project Overview

This repository explores NLP techniques (entity recognition, relation extraction, topic modeling) applied to clinical notes using domain-specific models (BioBert, ClinicalBert, Medacy). The goal is to extract valuable insights and potentially predict conditions like sepsis.

## Setup

**Clone the repository:**

```bash
git clone https://github.com/OpenBioResearch/nlp-clinical-notes.git
cd nlp-clinical-notes
```

**Create a virtual environment:**
```bash
python -m venv .venv 
```

**Activate the virtual environment (git bash):**



```bash
source .venv/Scripts/activate
source .venv/bin/activate
```
* You should see the virtual environment name (`.venv`) appear near your terminal prompt, indicating it's active.

**Install the packages:**

```bash
pip install -r requirements.txt
```
These Jupyter notebooks were tested and dployed using Python 3.10.

## Performance Considerations

Stanza offers high accuracy for NLP tasks, but this comes with a trade-off in running time. The library uses deep learning models, which can be resource-intensive and may run longer compared to other NLP tools, especially when processing large datasets or performing complex tasks. For better performance, particularly when dealing with substantial data, consider utilizing GPU acceleration.

## Dataset

The MTS-Dialog Clinical Notes training and validation datasets are included in this repo.

## License

This dataset is licensed under a creative commons Attribution 4.0 International (CC BY 4.0) license.  Original article: https://doi.org/10.18653/v1/2023.eacl-main.168
