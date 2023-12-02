# Sarcasm Detection in E-commerce Reviews

This repository contains the resources and source code used for the project "Unmasking Sarcasm: Enhancing Sentiment Analysis in E-commerce Reviews and Questions." It aims to explore and compare different deep learning strategies for detecting sarcasm in user-generated product reviews, with a special focus on Amazon as the e-commerce platform.

## Project Structure

The repository is organized into multiple directories, containing datasets, code notebooks, model checkpoints, and documentation that cover various stages of the project.

### Directories

- `code/`: Contains Jupyter notebooks for different models, experiments, and tests.
  - `bert_model.ipynb`: The notebook detailing our main BERT-based model implementation.
  - `basic_model_1/`: Early experiments with LSTM and SVM on individual datasets.
  - `feature_basic_model/`: SVM models with a focus on using feature engineering to improve sarcasm detection.
  - `ColBERT.ipynb`: Our attempt at implementing and adapting the ColBERT model architecture for sarcasm detection.
  - `amazon_dataset.ipynb`: Preprocessing and fine-tuning associated with the Amazon reviews dataset.
  - `combine_datasets.ipynb`: Initial preprocessing combining datasets from various sources.
- `datasets/`: Contains the raw and processed datasets used for model training and evaluation.
- `doc/`: Project documentation, including proposals, reports, and resource references.
  - `Final_project_report/`: LaTeX source files and related resources for the final project report.
  - `Intermediate Project report/`: Materials related to interim reporting stages.
- `*.pth`: Model checkpoint files storing the weights of our trained models.

### Navigating the Codebase

- Start with the `code/` directory to get an understanding of the models and experiments conducted. Specific notebooks are named according to their purpose and contents.
- View training and evaluation results directly within the `*.ipynb` notebooks, which include commentary and analysis.
- Refer to the `doc/` directory for comprehensive project documentation, including the final report which summarizes our findings and methodology.

### Running the Notebooks

To replicate our experiments or conduct your own, ensure that you have Jupyter Notebook or JupyterLab installed, along with necessary dependencies such as `transformers`, `torch`, and `pandas`. Notebooks can be run in sequence, starting with dataset preparation and culminating in model training and evaluation.

## Authors

- Hugo Bouy - `hbouy@hawk.iit.edu`
- Rémi Kalbe - `rkalbe@hawk.iit.edu`
- Mathias Roumane - `mroumane@hawk.iit.edu`
