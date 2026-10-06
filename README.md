# Inteligencia Artificial y Aprendizaje Automático

Weekly assignments for the course **Inteligencia Artificial y Aprendizaje Automático**,
part of the Master in Applied Artificial Intelligence (MNA) at Tecnológico de Monterrey.

**Student:** Carlos Rodrigo Salguero Alcántara (A00833341)

## Assignments

Each assignment lives in its own folder as a Jupyter notebook.

| Activity | Folder | Topic |
| --- | --- | --- |
| Activity 2 | [`cali_housing/`](cali_housing/) | California Housing: data cleaning, Yeo-Johnson transformations and Pearson correlation analysis in preparation for multiple linear regression |
| Activity 3 | [`staff_rotation/`](staff_rotation/) | IBM Employee Attrition: EDA, ethical variable handling, scikit-learn pipelines, model selection and test-set evaluation for predicting staff turnover |

## Running the notebooks

The notebooks can run in [Google Colab](https://colab.research.google.com/) or locally.

| Activity | Dataset |
| --- | --- |
| Activity 2 | Colab's built-in `/content/sample_data/california_housing_train.csv` (no download needed in Colab) |
| Activity 3 | IBM HR Analytics CSV at [`staff_rotation/data/WA_Fn-UseC_-HR-Employee-Attrition.csv`](staff_rotation/data/WA_Fn-UseC_-HR-Employee-Attrition.csv) ([Kaggle source](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)) |

To run locally, install the dependencies:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

Then open the notebook from its folder (so relative paths resolve), for example:

```bash
cd staff_rotation
jupyter notebook employee_attrition.ipynb
```

For Activity 2 locally, point the notebook to your copy of `california_housing_train.csv`.

## License

This project is licensed under the [MIT License](LICENSE).
