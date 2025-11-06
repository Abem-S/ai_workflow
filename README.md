# AI Hospital Readmission Risk Model

This repository contains the sample code for the "Applying the AI Development Workflow" assignment. It demonstrates a simplified, end-to-end machine learning pipeline for the **Part 2 Case Study: Predicting Patient Readmission**.

## Project Overview

The goal of this project is to build a model that can predict a patient's risk of being readmitted to the hospital within 30 days of discharge. This file demonstrates:
1.  **Data Creation:** A small, hypothetical dataset is created using `pandas`.
2.  **Preprocessing:** Data is cleaned, encoded, and scaled using `scikit-learn`.
3.  **Model Training:** A `RandomForestClassifier` is trained on the data.
4.  **Evaluation:** The model is evaluated using a confusion matrix, precision, and recall.
5.  **Interpretability:** Feature importance is extracted from the model.

## Files
* `workflow_case_analysis.ipynb`: A Jupyter Notebook containing all the Python code and explanations.
* `ai_workflow.pdf`: A PDF document answering all case_analysics, short answer questions and diagrams

## How to Run
1.  Clone this repository.
2.  Ensure you have `pandas`, `scikit-learn`, and `jupyter` installed:
    ```bash
    pip install pandas scikit-learn jupyter
    ```
3.  Run `jupyter notebook` and open the `.ipynb` file.
