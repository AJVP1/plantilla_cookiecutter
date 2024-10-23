# {{ cookiecutter.project_name }}


Plantilla para proyectos de machine learning creada a traves de cookie cutter y hecha por {{cookiecutter.author_name}}

## Descripción

Este proyecto contiene el flujo completo para entrenar y evaluar un modelo de machine learning. Está organizado en las siguientes secciones:

- **data/**: Contiene los datos sin procesar y los datos procesados.
- **notebooks/**: Jupyter Notebooks para análisis exploratorio y modelado.
- **src/**: Código fuente que contiene scripts para procesamiento de datos y modelos.
- **tests/**: Pruebas unitarias para asegurar la calidad del código.

## Requisitos

- Python {{cookiecutter.python_version}}
- Dependencias: Ver `environment.yml` o `requirements.txt` para instalar todas las bibliotecas necesarias.

## Instalación

Para configurar el entorno, ejecuta el siguiente comando:

```bash
conda env create -f environment.yml
```

## Project organization

    {{ cookiecutter.project_name }}
        ├── data
        │   ├── processed              <- The final, canonical data sets for modeling.
        │   └── raw                    <- The original, immutable data dump.
        │
        ├── notebooks          
        │   ├── exploration.ipynb      <- for exploring the data.
        │   └── modeling.ipynb         <- models created.
        │
        ├── .gitignore         <- Files to ignore by `git`.
        │
        ├── environment.yml    <- The requirements file for reproducing the analysis environment.
        │
        └── README.md          <- The top-level README for developers using this project.

---