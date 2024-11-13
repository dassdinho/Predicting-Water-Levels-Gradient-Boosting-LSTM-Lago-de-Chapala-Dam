# Predicting Water Levels Using Gradient Boosting Regressor and LSTM Models: A Case Study of Lago de Chapala Dam

This repository contains the full implementation of the research paper *Predicting Water Levels Using Gradient Boosting Regressor and LSTM Models: A Case Study of Lago de Chapala Dam*, presented at MICAI 2024. The project explores time-series modeling techniques, using both Gradient Boosting and LSTM models to predict water levels at the Lago de Chapala Dam, based on environmental and temporal factors.

## Citation

**Paper Link**: https://link.springer.com/chapter/10.1007/978-3-031-75540-8_8

```
@InProceedings{10.1007/978-3-031-75540-8_8,
  author="L{\'o}pez-Barrios, Jesus Dassaef
  and de Anda-Garc{\'i}a, Ilse Karena
  and Jimenez-Cruz, Raul
  and Trejo, Luis A.
  and Ochoa-Ruiz, Gilberto
  and Gonzalez-Mendoza, Miguel",
  title="Predicting Water Levels Using Gradient Boosting Regressor and LSTM Models: A Case Study of Lago de Chapala Dam",
  booktitle="Advances in Computational Intelligence",
  year="2025",
  publisher="Springer Nature Switzerland",
}
```

## Repository Structure
- **code/**: Contains the primary scripts for data processing, model training, and evaluation, implemented in Jupyter Notebooks on Google Drive for reproducibility.
- **data/**: Includes links to necessary datasets (not included directly) for water levels and climate information:
  - `original_presa_chapala_since_1991.csv`
  - `temp_diaria_chapala.txt`

## Project Highlights
- **Data Preparation**: Feature engineering, time-series preprocessing, and handling missing values.
- **Models**: Implementation of Gradient Boosting and LSTM models with and without a 1-day lag feature for `almacenamiento_hm3` (water storage).
- **Evaluation**: RMSE, MAE, and R² metrics to assess model performance, along with comprehensive visualization of results and residual analysis.
- **Visualization**: Side-by-side comparison of actual vs. predicted values, residual distributions, and feature correlations for interpretability.

## Getting Started
To replicate this project, clone this repository and follow the Jupyter Notebooks in the `code/` directory to set up data processing and model training.

## Reference
- **Authors**: Jesús Dassaef López-Barrios, Ilse Karena de Anda-García, Raul Jimenez-Cruz, Luis A. Trejo, Gilberto Ochoa-Ruiz, Miguel Gonzalez-Mendoza
- **Conference**: MICAI 2024
- **Paper Link**: [Springer DOI](https://doi.org/10.1007/978-3-031-75540-8)
