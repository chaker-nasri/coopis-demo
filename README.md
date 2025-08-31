# coopis-demo

This repository contains all materials for the CoopIS 2025 demo paper: a prototype integrating NuSMV with an LSTM-based intelligent filtering system for model checking.

## Repository Structure

coopis-demo/
│── notebook.ipynb       # Main Jupyter Notebook with the demo code
│── data/
│     └── dataset.csv    # Dataset used for experiments
│── requirements.txt     # Python dependencies
│── report.pdf           # Demo paper / report (optional)
│── README.md            # Project description (this file)


## Description

This demo system includes:

- Automatic extraction of valid and invalid paths from SMV models.
- Encoding of traces into sequences compatible with an LSTM network.
- Training of the LSTM to predict path validity.
- Generation of a PDF report with metrics and filtered paths.
- A minimal, reproducible workflow for testing the pipeline on a landing gear model.

## Requirements

Install Python 3.9+ and the dependencies using:

```bash
pip install -r requirements.txt
```
