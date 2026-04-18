# ML Cookiecutter Template

A Cookiecutter template designed to generate structured, modular, and reproducible Machine Learning projects.

---

## 📌 Purpose

This template standardizes ML project creation by providing:

* a clear and modular architecture
* a ready-to-use environment
* integrated testing and formatting tools
* a reproducible project structure

---

## 🧱 Template Structure

```text
cookiecutter-ml-project/
├── cookiecutter.json
├── hooks/
│   ├── pre_gen_project.py
│   └── post_gen_project.py
└── {{cookiecutter.project_slug}}/
    ├── .github/workflows/
    ├── data/
    ├── output/
    ├── src/
    │   ├── loaders/
    │   ├── processors/
    │   ├── translators/
    │   ├── evaluators/
    │   └── orchestrator/
    ├── tests/
    ├── .gitignore
    ├── pyproject.toml
    └── README.md
```

---

## ⚙️ Features

* automated ML project generation
* modular pipeline architecture
* unit testing with `pytest`
* code formatting with `black`
* centralized configuration via `pyproject.toml`
* CI/CD with GitHub Actions

---

## ▶️ Usage

### 1. Install Cookiecutter

```bash
pip install cookiecutter
```

### 2. Generate a project

```bash
python -m cookiecutter path/to/cookiecutter-ml-project
```

### 3. Set up the generated project

```bash
cd your_project_name
python -m venv .venv
.venv\Scripts\activate
pip install black pytest
```

---

## 🧠 Architecture

Generated projects follow a modular pipeline design:

* **loaders** → data ingestion
* **processors** → preprocessing
* **translators** → model execution
* **evaluators** → performance metrics
* **orchestrator** → pipeline coordination

This separation ensures maintainability and extensibility.

---

## 🔁 Example project generated from this template:

👉 https://github.com/your-username/ml-translation-pipeline

---

## 🎯 Academic Context

Developed as part of a Big Data and Machine Learning Infrastructure course, focusing on:

* architecture standardization
* workflow automation
* reproducibility
* modular pipeline design

---

## 👤 Author

Salma ALAOUI MRANI
Master Big Data, Analysis, Business Intelligence
Sorbonne Paris Nord University

