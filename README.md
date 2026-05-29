````markdown id="u4w7y2"
<div align="center">

<img src="https://upload.wikimedia.org/wikipedia/commons/5/5d/Universidad_del_Pacifico_Colombia_logo.png" width="220">

# TALLER PRÁCTICO DE PANDAS Y EXCEL EN PYTHON

<br>

<img src="https://pandas.pydata.org/static/img/pandas_mark.svg" width="220">

## Análisis y Manipulación de Datos con Python y Pandas

---

### Universidad del Pacífico

### Integrantes

### Anyela Katerine Rentería Cuama  
### Kelly Jhoana Mosquera Urbano  

---

### Ingeniería de Sistemas

### Desarrollado en Google Colab

<br>

<img src="https://colab.research.google.com/img/colab_favicon_256px.png" width="90">

</div>

---

# INTRODUCCIÓN

Actualmente, el análisis de datos es una de las áreas más importantes dentro de la Ingeniería de Sistemas y la Ciencia de Datos. Las empresas y organizaciones generan grandes cantidades de información que necesitan ser organizadas, procesadas y analizadas para facilitar la toma de decisiones.

Python es uno de los lenguajes de programación más utilizados en el mundo gracias a su facilidad, potencia y gran variedad de librerías. Entre estas herramientas destaca Pandas, una librería especializada en la manipulación y análisis de datos estructurados.

En este notebook se desarrolla un taller práctico utilizando Pandas y archivos Excel en Google Colab. Durante el desarrollo se realizan operaciones matemáticas, análisis estadísticos, filtros, cálculos de porcentajes y exportación de resultados a Excel.

Además, cada sección contiene explicaciones detalladas sobre el funcionamiento del código, la utilidad de cada función y la interpretación de los resultados obtenidos.

---

<div align="center">

<img src="https://miro.medium.com/v2/resize:fit:1400/1*5JxdL6P1M5yP4mM4Ww0r2Q.png" width="750">

</div>

---

# OBJETIVOS

## Objetivo General

Aplicar la librería Pandas en Python para realizar análisis y manipulación de datos contenidos en archivos Excel utilizando Google Colab.

---

## Objetivos Específicos

- Importar y manipular archivos Excel utilizando Pandas.
- Crear y analizar DataFrames.
- Realizar operaciones matemáticas entre columnas.
- Aplicar estadísticas descriptivas.
- Filtrar y ordenar información.
- Exportar resultados finales a Excel.
- Interpretar los resultados obtenidos.

---

# ¿QUÉ ES PANDAS?

<div align="center">

<img src="https://upload.wikimedia.org/wikipedia/commons/e/ed/Pandas_logo.svg" width="280">

</div>

Pandas es una librería de Python diseñada para el análisis y manipulación de datos de manera rápida y eficiente.

Esta herramienta permite trabajar con:

- Tablas de datos
- Archivos Excel y CSV
- Estadísticas
- Bases de datos
- Grandes volúmenes de información

Actualmente es utilizada en áreas como:

- Ciencia de Datos
- Inteligencia Artificial
- Machine Learning
- Ingeniería de Sistemas
- Big Data

---

<div align="center">

<img src="https://www.simplilearn.com/ice9/free_resources_article_thumb/Python_Pandas.png" width="720">

</div>

---

# GOOGLE COLAB

<div align="center">

<img src="https://miro.medium.com/v2/resize:fit:1200/1*iNPHcCxIvcm7RwkRaMTx5Q.png" width="720">

</div>

Google Colab es una plataforma gratuita basada en la nube que permite ejecutar código Python desde el navegador sin necesidad de instalar programas en el computador.

Gracias a Colab es posible:

- Ejecutar notebooks interactivos.
- Trabajar con Pandas y Python.
- Subir archivos Excel.
- Compartir proyectos fácilmente.
- Guardar proyectos en Google Drive.

---

# IMPORTACIÓN DE LIBRERÍAS

```python
from google.colab import files
import pandas as pd
````

Estas librerías permiten subir archivos Excel a Google Colab y trabajar con estructuras de datos organizadas mediante DataFrames.

---

# EJEMPLO DE CÓDIGO

```python
import pandas as pd

datos = {
    "Producto": ["Mouse", "Teclado", "Monitor"],
    "Precio": [50000, 80000, 700000]
}

df = pd.DataFrame(datos)

print(df)
```

---

<div align="center">

<img src="https://media.geeksforgeeks.org/wp-content/uploads/20230706144311/Python-Pandas-Tutorial.webp" width="720">

</div>

---

# ANÁLISIS DE DATOS CON PANDAS

Durante el desarrollo del notebook se realizaron diferentes procesos de análisis y manipulación de datos utilizando Pandas y archivos Excel.

Entre los procesos desarrollados se encuentran:

* Lectura de archivos Excel.
* Creación de DataFrames.
* Aplicación de filtros.
* Operaciones matemáticas.
* Estadísticas descriptivas.
* Cálculo de porcentajes.
* Organización de información.

---

# EXPORTACIÓN DE RESULTADOS

Pandas también permite exportar información procesada nuevamente a archivos Excel.

```python
df.to_excel("resultados.xlsx")
```

Esto facilita el almacenamiento, organización y generación de reportes automatizados.

---

<div align="center">

<img src="https://datascientest.com/es/wp-content/uploads/sites/7/2021/08/pandas-python-1.png" width="720">

</div>

---

# IMPORTANCIA DEL PROYECTO

El desarrollo de este taller fortalece habilidades fundamentales relacionadas con:

* Ciencia de Datos
* Programación en Python
* Análisis estadístico
* Manipulación de archivos Excel
* Ingeniería de Sistemas

El uso de Pandas representa una herramienta esencial para el manejo eficiente de grandes cantidades de información.

---

# CONCLUSIÓN

La librería Pandas representa una herramienta poderosa y eficiente para el análisis y manipulación de datos en Python.

Gracias a este taller fue posible comprender el funcionamiento de DataFrames, el manejo de archivos Excel y la aplicación de operaciones estadísticas y matemáticas para interpretar información de manera organizada y profesional.

Además, el uso de Google Colab permitió desarrollar el proyecto de forma interactiva y accesible desde la nube.

---

<div align="center">

# DESARROLLADO POR

## Anyela Katerine Rentería Cuama

## Kelly Jhoana Mosquera Urbano

<br>

<img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg" width="80">

### Proyecto Académico

</div>
```
