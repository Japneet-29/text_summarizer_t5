# Text Summarizer using T5 (FastAPI + Hugging Face)

## Overview

This project implements an **abstractive text summarization system** using the **T5 transformer model**.
It includes a FastAPI backend and a dataset-driven workflow for experimentation and evaluation.

---

## Tech Stack

* Python
* FastAPI
* Hugging Face Transformers (T5)
* Jupyter Notebook
* HTML

---

## Features

* Abstractive summarization using transformer-based models
* REST API for generating summaries
* Custom dataset integration (train, validation, test)
* End-to-end pipeline: preprocessing → model → summary generation
* Interactive frontend for testing

---

## Project Structure

```
Text-Summarizer/
│── app.py
│── index.html
│── text_summarizer.ipynb
│── README.md
│
├── data/
│   ├── samsum-train.csv
│   ├── samsum-validation.csv
│   └── samsum-test.csv
```

---

## Dataset

This project uses the **SAMSum dataset** for dialogue summarization.

* Train, validation, and test splits are included in the `data/` folder
* Used for experimentation and model evaluation

---

## How to Run

1. Clone the repository

```
git clone <your-repo-link>
cd text-summarizer
```

2. Install dependencies

```
pip install -r requirements.txt
```

3. Run the FastAPI server

```
python app.py
```

---

## Notebook

The `text_summarizer.ipynb` includes:

* Data preprocessing
* Model loading (T5)
* Summarization experiments
* Sample outputs

---

## Model

* Uses pretrained **T5 model** from Hugging Face
* Model weights are not included due to size constraints

---

## Notes

* This project is designed for **local execution**
* Dataset is included for experimentation
* Model is loaded dynamically using Hugging Face

---
