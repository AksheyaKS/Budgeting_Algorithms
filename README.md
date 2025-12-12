Budgeting Algorithms – Interactive Finance Management App

This project implements and compares two budgeting algorithms for personal finance management and exposes them through an interactive Gradio web app.

The goal is to let a user upload their transaction data, select an algorithm, set a target budget, and immediately see suggested cuts plus visual summaries.

For grading: you only need to open and run the Finance_Management_GradioApp.ipynb notebook.
The other notebooks contain the backend logic, data model, and test cases.

1. Computing Environment / Architecture
The notebooks are standard CPU-only Python code; no GPU is required.

The project was developed and tested on:
OS: Windows 11 (x86_64), also runs on Linux / macOS
Python: 3.10+ (3.9–3.11 should work)
Hardware: ≥ 8 GB RAM CPU laptop

Any machine with a recent Python 3 and the packages below should be able to run the Gradio app.

Required Python Packages
Install these into a virtual environment or your base environment:
pandas
numpy
matplotlib
gradio
scikit-learn

Single command:

pip install pandas numpy matplotlib gradio scikit-learn
