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

**Activate the virtual environment:**

Windows Git Bash:

```bash
source .venv/Scripts/activate
```
macOS/Linux:

```bash
source .venv/bin/activate
```
**Install the packages:**

```bash
pip install -r requirements.txt
```
Note: These Jupyter notebooks were tested and deployed using Python 3.10 in Google Colab and GitHub Codespaces. Adjustments may be needed for other environments.

** .gitignore**

This repository includes a `.gitignore` file to ensure that unnecessary files, for example within .venv/ are not tracked by Git.

## Performance Considerations for jupyter notebook utilizing Stanza

Stanza offers high accuracy for NLP tasks but can be resource-intensive and may run longer compared to other NLP tools. 

## Dataset

The MTS-Dialog Clinical Notes training and validation datasets contain short doctor-patient conversations. You can download the datasets from the following sources:
- [Hugging Face](https://huggingface.co/datasets/har1/MTS_Dialogue-Clinical_Note/tree/main)
- [Kaggle](https://www.kaggle.com/datasets/solomonamaningodum/mts-dataset-zip)


## License

This dataset is licensed under a creative commons Attribution 4.0 International (CC BY 4.0) license.  Original article: https://doi.org/10.18653/v1/2023.eacl-main.168
