# Análisis de Cobertura Móvil en Colombia

## Descripción del proyecto
Este proyecto realiza un análisis de datos sobre la cobertura móvil por tecnología en Colombia, con el objetivo de identificar brechas de conectividad entre regiones y tecnologías.

Se aplican técnicas de limpieza, transformación y análisis exploratorio de datos (EDA) para generar insights relevantes sobre la distribución de cobertura.

---

## Objetivo
Analizar la cobertura móvil en Colombia para:

- Identificar desigualdades entre regiones
- Evaluar la disponibilidad de tecnologías (2G, 3G, 4G, LTE)
- Detectar zonas con baja o nula conectividad

---

## Preguntas de análisis
- ¿Qué departamentos tienen menor cobertura móvil?
- ¿Qué tecnologías están más distribuidas en el país?
- ¿Existen brechas entre regiones urbanas y rurales?
- ¿Qué tan extendida está la cobertura LTE y 4G?

---

## Procesamiento de datos

### Limpieza de datos
- Eliminación de valores nulos
- Detección y eliminación de duplicados
- Validación de consistencia

### Transformación
- Estandarización de variables de cobertura (S/N)
- Corrección de nombres de columnas
- Filtrado de datos relevantes

### Optimización
Se generaron datasets reducidos para facilitar pruebas y ejecución del proyecto.

---

## Análisis realizado

- Distribución de cobertura por departamento
- Comparación entre tecnologías móviles
- Identificación de regiones con menor conectividad
- Análisis geográfico de personas afectadas

---

## Hallazgos principales

- Existen diferencias significativas en cobertura entre regiones
- Tecnologías como LTE y 4G no están disponibles en todas las zonas
- Las regiones rurales presentan mayor desigualdad en conectividad

---

## Estructura del proyecto

analisis-cobertura-movil/
│
├── data/
├── dataset_proyecto_final.py
├── README.md
├── requirements.txt
└── .gitignore

---

## Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Cómo ejecutar el proyecto

pip install -r requirements.txt  
python dataset_proyecto_final.py  

---

## Nota sobre los datos

El dataset original no se incluye en este repositorio debido a su tamaño.  
Se utilizaron versiones reducidas para facilitar la ejecución del análisis.

---

## Fuente de datos

https://www.datos.gov.co/Ciencia-Tecnolog-a-e-Innovaci-n/Cobertura-m-vil-por-tecnolog-a-departamento-y-muni/9mey-c8s8/about_data

---

## Valor del proyecto

Este análisis permite identificar brechas digitales en Colombia y aporta información útil para estudios de conectividad.

---

## 🚀 Autor

Miguel Quintero  
Estudiante de Ciencia de Datos