<div align="center">

# TALLER PRÁCTICO DE PANDAS Y EXCEL EN PYTHON

![Logo Universidad](https://raw.githubusercontent.com/github/explore/main/topics/python/python.png)

## Análisis y Manipulación de Datos con Python y Pandas

---

### Universidad del Pacífico

### Integrantes

Anyela Katerine Rentería Cuama  
Kelly Jhoana Mosquera Urbano

---

### Ingeniería de Sistemas

### Desarrollado en Google Colab

![Colab](https://colab.research.google.com/img/colab_favicon_256px.png)

</div>

---

# INTRODUCCIÓN

Actualmente, el análisis de datos es una de las áreas más importantes dentro de la Ingeniería de Sistemas y la Ciencia de Datos.

Las empresas y organizaciones generan grandes cantidades de información que necesitan ser organizadas, procesadas y analizadas para facilitar la toma de decisiones.

Python es uno de los lenguajes de programación más utilizados en el mundo gracias a su facilidad, potencia y gran variedad de librerías. Entre estas herramientas destaca Pandas, una librería especializada en la manipulación y análisis de datos estructurados.

---

<div align="center">

![Pandas](https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg)

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

Pandas es una librería de Python diseñada para el análisis y manipulación de datos de manera rápida y eficiente.

Permite trabajar con:

- Tablas de datos
- Archivos Excel y CSV
- Estadísticas
- Bases de datos
- Grandes volúmenes de información

---

<div align="center">

![Python](https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg)

</div>

---

# GOOGLE COLAB

Google Colab es una plataforma gratuita basada en la nube que permite ejecutar código Python desde el navegador sin necesidad de instalar programas en el computador.

---

<div align="center">

![Colab](https://colab.research.google.com/img/colab_favicon_256px.png)

</div>

---

# IMPORTACIÓN DE LIBRERÍAS

```python
from google.colab import files
import pandas as pd
```

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

# ANÁLISIS DE DATOS CON PANDAS

Durante el desarrollo del notebook se realizaron diferentes procesos de análisis y manipulación de datos utilizando Pandas y archivos Excel.

Entre los procesos desarrollados se encuentran:

- Lectura de archivos Excel
- Creación de DataFrames
- Aplicación de filtros
- Operaciones matemáticas
- Estadísticas descriptivas
- Cálculo de porcentajes
- Organización de información

---

# EXPORTACIÓN DE RESULTADOS

```python
df.to_excel("resultados.xlsx")
```

Esto facilita el almacenamiento y generación de reportes automatizados.

---

# IMPORTANCIA DEL PROYECTO

El desarrollo de este taller fortalece habilidades relacionadas con:

- Ciencia de Datos
- Programación en Python
- Análisis estadístico
- Manipulación de archivos Excel
- Ingeniería de Sistemas

---

# CONCLUSIÓN

La librería Pandas representa una herramienta poderosa y eficiente para el análisis y manipulación de datos en Python.

Gracias a este taller fue posible comprender el funcionamiento de DataFrames, el manejo de archivos Excel y la aplicación de operaciones estadísticas y matemáticas.

---

<div align="center">

# DESARROLLADO POR

## Anyela Katerine Rentería Cuama  
## Kelly Jhoana Mosquera Urbano

</div>
