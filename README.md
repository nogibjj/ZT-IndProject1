[![Code Formatting](https://github.com/JTuratkhan/ZT-IndProject1/actions/workflows/format.yml/badge.svg?branch=main)](https://github.com/JTuratkhan/ZT-IndProject1/actions/workflows/format.yml)
[![Code Linting](https://github.com/JTuratkhan/ZT-IndProject1/actions/workflows/lint.yml/badge.svg?branch=main)](https://github.com/JTuratkhan/ZT-IndProject1/actions/workflows/lint.yml)
[![Install Dependencies](https://github.com/JTuratkhan/ZT-IndProject1/actions/workflows/install.yml/badge.svg?branch=main)](https://github.com/JTuratkhan/ZT-IndProject1/actions/workflows/install.yml)
[![Run Tests](https://github.com/JTuratkhan/ZT-IndProject1/actions/workflows/tests.yml/badge.svg?branch=main)](https://github.com/JTuratkhan/ZT-IndProject1/actions/workflows/tests.yml)

# ZT-IndProject1🍎

# # Continuous Integration using GitHub Actions of Python Data Science Project
Hey, there! Welcome to my Individual project 1

# Goal🚀
The goal of thus project is to establish a CodeSpace environment that automates the process of loading a dataset, generating descriptive statistics on the dataset, and creating data visualizations of the dataset using Pandas and matplotlib, utilizing GitHub Actions.

# Preparation🌱
Configured GitHub codespaces with .devcontainer, GitHub Actions, Readme.md
Created scaffold for structure of project: 'Makefile', 'requirements.txt'
Included csv dataset to perform descriptive statistics using polars in jupyter notebook and main.py python script

# Instructions for further local development🔧
1. Install **Docker** to your local PC
2. Install **Remote - containers**
3. Clone repository to your local PC
4. Open the repo in local codespace like VS Code
5. Press "Reopen Folder in Container" when notifications appear at your local codespace
6. So **Dockerfile** is provided and you have ready-to-use Python environment

# File Structure📝
* polars.ipynb: A Jupyter notebook includes cells that perform descriptive statistics using Polars
* lib.py: A file that shares common code between the script and notebook
* Makefile: Contains commands to run tests, format code, lint code, and install necessary Python packages
* test_polars.py: includes unit tests for the script
* test_lib.py: includes unit tests for the lib file
* requirements.txt: includes codes, basically the dependencies required for the project
* .devcontainer: Configurations for the VS Code remote container development environment
* .github/workflows: Workflow definitions for Continuous Integration using GitHub Actions

  # Demo video link
***

# The end
