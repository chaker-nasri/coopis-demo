# coopis-demo

This repository contains all materials for the CoopIS 2025 demo paper: a prototype integrating NuSMV with an LSTM-based intelligent filtering system for model checking.

## Repository Structure

coopis-demo/
│── notebook.ipynb       # Main Jupyter Notebook with the demo code
│── data/
│     └── dataset.csv    # Dataset used for experiments
│── requirements.txt     # Python dependencies
│── report.pdf           # Demo paper / report (optional)
│── coopis-demo-paper.pdf # Submitted CoopIS 2025 paper
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

## Usage

Open the Jupyter Notebook with:

```bash
jupyter notebook notebook.ipynb
```

Run the cells step by step to reproduce the demo, generate predictions, reports, and metrics.

## Report

- A PDF version of the demo results is provided in **report.pdf**.  
- The submitted CoopIS 2025 demo paper is included as **coopis-demo-paper.pdf**.

## Citation

If you use this repository, dataset, or code in your research, please cite our CoopIS 2025 demo paper:

```bibtex
@inproceedings{nasri2025coopis,
  author    = {Chaker Nasri and Leila Ben Ayed},
  title     = {Enhancing Model Checking with LSTM-based Intelligent Filtering},
  booktitle = {Cooperative Information Systems (CoopIS 2025) -- Demo Track},
  year      = {2025},
  note      = {Demo Paper},
}
```

