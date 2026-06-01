# Practica_visualización_datos
## Descripción

Proyecto de visualización de datos desarrollado para la asignatura de Fundamentos de Modelado Orientado a Datos.

El objetivo es analizar la relación entre variables clínicas y moleculares del cáncer de mama utilizando el conjunto de datos METABRIC, prestando especial atención a la supervivencia global, la recaída y la identificación de perfiles de pacientes.

## Dataset

Se utiliza el dataset METABRIC (Molecular Taxonomy of Breast Cancer International Consortium), que contiene información clínica y molecular de 2509 pacientes diagnosticadas de cáncer de mama.

Las variables estudiadas incluyen:

- Edad al diagnóstico

- Estadio tumoral

- Tamaño tumoral

- Estado de los receptores ER, PR y HER2

- Subtipo molecular PAM50

- Mutation Count

- Nottingham Prognostic Index

- Supervivencia global

- Estado de recaída

## Preguntas analizadas
1. ¿Cuál es el perfil general de las pacientes?

2. ¿Influye el estadio tumoral en la supervivencia?

3. ¿Influye el estadio tumoral en la recaída?

4. ¿Existen diferencias entre subtipos moleculares?

5. ¿Aporta información pronóstica la información molecular?

6. ¿Pueden identificarse perfiles diferenciados de pacientes?

## Herramientas utilizadas
- Python

- Pandas

- NumPy

- Matplotlib

- Seaborn

- Plotly

- Lifelines

- Scikit-Learn


## Estructura del proyecto

data/

graficas/

README.md

requirements.txt

LICENSE


## Ejecución

Instalar dependencias:

pip install -r requirements.txt


## Ejecutar:

python visualizacion.py


## Visualización web

La página web integra visualizaciones estáticas e interactivas desarrolladas en Python mediante Matplotlib, Seaborn y Plotly, permitiendo la exploración de los principales hallazgos obtenidos a partir del dataset METABRIC.

La visualización puede consultarse públicamente en:

https://franciscomorao.github.io/Practica_visualizacion_datos/

La página principal se encuentra en el archivo:

```text
index.html
```


## Licencia

MIT License.
