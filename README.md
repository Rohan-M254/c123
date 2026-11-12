# Alphabet Recognition Experiment

A small machine-learning experiment using a saved NumPy dataset and CSV labels to train an alphabet classifier.

## Project structure

- `c123/alphabet_recognition.py` — model training and prediction workflow.
- `c123/image.npz` — image feature data.
- `c123/labels.csv` — corresponding labels.

## Status

This is an experimental coursework project, not a production-ready OCR system. The original training script needs dependency/import cleanup and validation of its data-loading and evaluation pipeline before its accuracy can be relied upon.

Inspect the script for the expected array keys and label format before running it. Dependencies include NumPy, pandas, scikit-learn, and Pillow.