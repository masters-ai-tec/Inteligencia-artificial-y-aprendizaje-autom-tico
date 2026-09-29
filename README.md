# Inteligencia Artificial y Aprendizaje Automático

Weekly assignments for the course **Inteligencia Artificial y Aprendizaje Automático**,
part of the Master in Applied Artificial Intelligence (MNA) at Tecnológico de Monterrey.

**Student:** Carlos Rodrigo Salguero Alcántara (A00833341)

## Assignments

Each assignment lives in its own folder as a Jupyter notebook.

| Activity | Folder | Topic |
| --- | --- | --- |
| Activity 2 | [`cali_housing/`](cali_housing/) | California Housing: data cleaning, Yeo-Johnson transformations and Pearson correlation analysis in preparation for multiple linear regression |

## Running the notebooks

The notebooks are written to run in [Google Colab](https://colab.research.google.com/).
Activity 2 uses Colab's built-in dataset at `/content/sample_data/california_housing_train.csv`,
so no download is needed there.

To run locally instead, install the dependencies:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

and update the dataset path in the notebook to point to your local copy of
`california_housing_train.csv`.

## License

This project is licensed under the [MIT License](LICENSE).
