# Student Performance Analysis

An exploratory machine learning project that analyzes student background and performance data using preprocessing, visualization, clustering, and classification. The goal is to understand how socioeconomic, demographic, and academic factors relate to student outcomes and to compare unsupervised and supervised machine learning approaches on the same dataset.

## Project Overview

This repository is centered on the notebook [Student_Performance_Analysis_Notebook.ipynb](Student_Performance_Analysis_Notebook.ipynb), which includes:

- Data loading and cleaning
- Exploratory data analysis and visualizations
- Feature encoding and scaling
- Clustering experiments with K-Means, K-Medoids-style assignment, and hierarchical clustering
- Cluster evaluation metrics
- A supervised Random Forest classifier for performance grouping

## Key Findings

- The clustering workflow compares K-Means, K-Medoids-style assignment, and hierarchical clustering on the same scaled feature set.
- The elbow analysis in the notebook suggests that 3 clusters is a reasonable choice for the dataset.
- The supervised section uses a Random Forest model to classify performance groups and review prediction quality with standard evaluation metrics.
- The notebook includes multiple visualizations to make the relationships between student attributes and performance easier to interpret.

## Repository Structure

- [Student_Performance_Analysis_Notebook.ipynb](Student_Performance_Analysis_Notebook.ipynb) - main analysis notebook
- [Student_Performance_Analysis_Report.pdf](Student_Performance_Analysis_Report.pdf) - project report
- [LICENSE](LICENSE) - MIT license
- [requirements.txt](requirements.txt) - Python dependencies

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- scikit-learn

## How to Run

1. Create and activate a Python environment.
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook in Jupyter, VS Code, or Google Colab.
4. Run the cells from top to bottom.

## Notes

- The notebook is the source of truth for the analysis.
- For a portfolio presentation, you can also export the notebook to HTML or PDF and link that output in the repo.
- If you later want a live demo, the notebook can be wrapped into a small Streamlit app.
