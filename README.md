# {{cookiecutter.project_name}}

> {{cookiecutter.description}}

Creation of MLOps - Template with cookiecutter

## Table of Contents

- [Background & Purpose](#background--purpose)  
- [Features](#features)  
- [Prerequisites](#prerequisites)  
- [Installing the Template](#installing-the-template)  
- [Generating a New Project](#generating-a-new-project)  
- [License](#license)  

---

## Background & Purpose

This repository provides a **Cookiecutter template** to automate the creation of MLOps project skeletons. Its goals are to:

1. **Standardize** file and folder organization  
2. **Speed up** new project setup  
3. **Ensure** reproducibility and team collaboration  

---

## Features

- Generates a complete folder structure (`data/`, `models/`, `notebooks/`, `src/`, `tests/`, etc.)  
- Pre-filled base files:  
  - `README.md` (with Cookiecutter variables)  
  - `.gitignore`  
  - `requirements.txt`  
- Easy to extend with:  
  - CI/CD workflows (e.g. GitHub Actions)  
  - Git hooks (`pre-commit`)  
  - Data versioning (DVC)  
  - Documentation frameworks (MkDocs, Sphinx)  

---

## Prerequisites

- Python ≥ 3.7  
- [Cookiecutter](https://github.com/cookiecutter/cookiecutter) installed (`pip install cookiecutter`)  
- Git (for version control and publishing)  

---

## Installing the Template

Clone this repo locally or point Cookiecutter directly at GitHub:

# Option A: Clone and use locally
git clone https://github.com/thefranckt/mlops-project-template.git
cd mlops-project-template

# Option B: Use directly from GitHub
 cookiecutter https://github.com/thefranckt/mlops-project-template.git

---

## Generating a New Project

From the parent directory where you want your new project:


cookiecutter /path/to/mlops-project-template

Or, without cloning:

cookiecutter https://github.com/thefranckt/mlops-project-template.git

 

## License
This project is licensed under the MIT License. See the LICENSE file for details.

