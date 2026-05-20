# INST750LG

Welcome to the INST750LG repository.

## Overview

This project contains coursework and materials for INST750LG. The main notebook focuses on Amharic emotion classification using large language models (LLMs). It evaluates model performance on the original Amharic text and compares it with performance after augmenting the data by adding English translations.

The purpose of the project is to test whether English-translated Amharic data improves emotion classification performance. The initial assumption was that translated data may perform better because many LLMs are trained on much larger English datasets than Amharic or other African-language datasets. The project uses the `dev.csv` dataset, applies stratified sampling, runs LLM-based emotion classification, and analyzes the results using accuracy, F1 scores, confusion matrices, and prediction-change comparisons.

## Getting Started

To get started with this project, clone the repository and open the notebook in Google Colab or Jupyter Notebook.

Required files:
- `pipeline.ipynb`
- `dev.csv`

Basic steps:
1. Upload `dev.csv` to the notebook environment.
2. Install or import the required Python libraries.
3. Set up the required API key if using an LLM API.
4. Run the notebook cells in order.
5. Review the generated metrics, tables, and visualizations.

The notebook produces evaluation results for both the original Amharic dataset and the English-translated version, including classification metrics and confusion matrices.

## Contributing

Please follow the standard GitHub workflow for contributing to this project. Suggested improvements include testing additional LLMs, trying stronger emotion-preserving translation methods, adding bilingual prompting, and expanding the evaluation to more balanced or larger samples.

## License

This project is provided as-is for educational purposes.
