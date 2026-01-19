# 📊 Clustering de Docentes mediante Técnicas de Aprendizaje No Supervisado

Este repositorio contiene el desarrollo de un análisis de **clustering a nivel de docente**, realizado como parte de un trabajo de investigación académica. El objetivo principal es identificar **perfiles de docentes** a partir de información institucional, utilizando técnicas de **aprendizaje no supervisado** en Python.

El análisis se implementa en un *Jupyter Notebook* y sigue un flujo metodológico estructurado que incluye limpieza de datos, agregaciones, reducción de dimensionalidad y aplicación de algoritmos de clustering.

---

## 🎯 Objetivo del proyecto

Identificar y caracterizar grupos homogéneos de docentes a partir de variables relacionadas con:

- Evaluación docente  
- Carga académica y distributivos  
- Formación y características profesionales  

Los resultados buscan apoyar procesos de **toma de decisiones institucionales**, planificación académica y análisis exploratorio en contextos educativos.

---

## 🗂️ Estructura del repositorio

```
├── Clustering docentes.ipynb   # Notebook principal con todo el análisis
├── README.md                  # Descripción general del proyecto
└── Datos/                      # Carpeta con los conjuntos de datos
```

---

## 🧾 Descripción de los datos

El análisis parte de la integración de **múltiples fuentes de datos institucionales**, entre ellas:

- Resultados de heteroevaluación docente por asignatura
- Resultados de coevaluación docente por pares y autoridades
- Información de distributivos académicos
- Datos de formación docente
- Análisis de sentimiento sobre comentarios de estudiantes

Uno de los archivos contiene más de **70.000 registros**, por lo que se realiza inicialmente un proceso de:
- Limpieza de datos
- Normalización y tipificación de variables
- Agregación a nivel de docente

Posteriormente, estos datos se integran con otras las otras fuentes de menor tamaño.

---

## 🔄 Metodología aplicada

El flujo de trabajo seguido en el notebook es el siguiente:

1. Carga y exploración inicial de los datos  
2. Limpieza y preprocesamiento  
3. Agregación de información a nivel de docente  
4. Selección y transformación de variables  
5. Reducción de dimensionalidad mediante PCA  
6. Aplicación de algoritmos de clustering (*K-means*)  
7. Análisis y caracterización de los clusters obtenidos  

---

## 🛠️ Tecnologías y librerías utilizadas

- Python 3.x  
- pandas  
- numpy  
- scikit-learn  
- matplotlib  
- seaborn  

---

## ▶️ Ejecución del proyecto

1. Clona este repositorio:
   ```bash
   git clone <url-del-repositorio>
   ```

2. Abre el notebook:
   ```bash
   jupyter notebook "Clustering docentes.ipynb"
   ```

3. Ejecuta las celdas en orden para reproducir el análisis.

---

## 📌 Notas adicionales

- El proyecto está orientado a un contexto académico.
- Los datos utilizados están anonimizados por motivos de confidencialidad.

---

## 👩‍🎓 Autora

**Karina Abad**  
Maestría en Inteligencia de Negocios y Ciencia de Datos

---

✨ Este proyecto forma parte de un proceso de investigación y puede seguir evolucionando con nuevas variables, algoritmos y análisis.
