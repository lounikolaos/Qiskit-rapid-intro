# Qiskit Rapid Intro

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lounikolaos/Qiskit-rapid-intro/blob/main/Qiskit_Introduction.ipynb)

A rapid introduction for students who are already comfortable with quantum computing and want to learn how to use Qiskit. The examples assume basic Python knowledge.

[Read the notebook on GitHub](Qiskit_Introduction.ipynb) to see the explanations, code, and saved outputs. Exercise cells are intentionally left blank.

## Topics

- Bell states, registers, measurement, and simulation.
- Qiskit bit ordering and the Deutsch–Jozsa algorithm.
- Order finding, small-number factorization, and noisy simulations.

The Shor demonstration constructs dense matrices and is practical only for small values of N. The full decomposed-circuit drawing is optional: set `SHOW_FULL_CIRCUIT = True` in the notebook to display it.

## Run in Colab

Use the badge above, run the installation cell, restart the runtime, then run the cells from the imports onward. Colab is a convenient launch option; the validation below was performed locally.

## Run locally

Use Python 3.12, matching the tested environment. Download or clone the repository, create and activate a virtual environment, then run from the repository folder:

```bash
python -m pip install -r requirements.txt
python -m pip install jupyterlab
python -m jupyter lab Qiskit_Introduction.ipynb
```

Select the environment's Python kernel. Start with the imports after the installation cell and run the examples in order. Restart the kernel after package changes.

## Validation

The examples were validated on 28 October 2026 with Python 3.12.14, Qiskit 2.6.1, and Qiskit Aer 0.18.2: all 31 runnable example cells and nine correctness checks passed. The installation cell and blank exercises were excluded. Sampling-based results may vary when rerun.
