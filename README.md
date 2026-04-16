# Análisis de Cobertura Móvil en Colombia

## Descripción

Este proyecto analiza la cobertura móvil por tecnología en Colombia, aplicando procesos de limpieza y análisis de datos para identificar brechas de conectividad.

## Dataset original

El dataset original se encuentra en: https://www.datos.gov.co/Ciencia-Tecnolog-a-e-Innovaci-n/Cobertura-m-vil-por-tecnolog-a-departamento-y-muni/9mey-c8s8/about_data

Debido a su tamaño, no se incluye en el repositorio. Se utilizan versiones reducidas para facilitar la ejecución del proyecto.

## Procesos realizados

* Limpieza de datos (valores nulos y duplicados)
* Estandarización de variables
* Análisis exploratorio (EDA)
* Visualización de datos

## Tecnologías

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

## Estructura

* `dataset_proyecto.py`: script principal
* `data/`: dataset utilizado

##  Ejecución

```bash
pip install -r requirements.txt
python dataset_proyecto.py
```

## Resultados

Se identificaron diferencias significativas en la cobertura móvil entre regiones del país, evidenciando desigualdad en conectividad.
