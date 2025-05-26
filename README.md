# 📊 Curso de Analítica de Datos con Python

Este repositorio contiene una colección de notebooks interactivos 🧠 diseñados para enseñar los fundamentos de la **analítica de datos con Python**, incluyendo manipulación de datos, visualización y análisis exploratorio. Está orientado tanto a principiantes como a personas con conocimientos básicos que desean profundizar sus habilidades en ciencia de datos.

---

## 🧠 Módulos Incluidos

| 📘 Módulo | Archivo | Descripción |
|----------|---------|-------------|
| 1️⃣ | pandas_module.ipynb | Introducción a **Pandas** para la manipulación y análisis de datos tabulares. |
| 2️⃣ | numpy_module.ipynb | Fundamentos de **NumPy** para operaciones vectorizadas y manejo eficiente de arreglos. |
| 3️⃣ | numpy_pandas.ipynb | Comparación e integración entre **NumPy** y **Pandas**. |
| 4️⃣ | matplotlib_module.ipynb | Gráficos básicos y personalizados con **Matplotlib**. |
| 5️⃣ | seaborn_module.ipynb | Visualización estadística avanzada con **Seaborn**. |
| 6️⃣ | data_analisys.ipynb | Técnicas de análisis exploratorio (EDA) con datasets como Titanic, Penguins y Diamonds. |
| 7️⃣ | data_mining.ipynb | Introducción a **minería de datos**: clasificación, regresión y modelos básicos con `scikit-learn`. |

---

## 📁 Archivos de Datos

Este repositorio incluye algunos datasets y salidas que se utilizan en los notebooks:

- `data/Country-data.csv`
- `data/data-dictionary.csv`
- `data/data.csv`
- `data/diamonds.csv`
- `data/penguins.csv`
- `data/titanic.csv`
- `out/registro_de_pago.csv`
- `out/registro_de_pago.xlsx`

---

## 📷 Visualizaciones Exportadas

- `img/penguins_scatterplot.png`

---

📦 Principales librerías utilizadas

| Librería          | Propósito                                      |
| ----------------- | ---------------------------------------------- |
| `pandas` 🐼       | Manipulación y análisis de datos estructurados |
| `numpy` 🔢        | Cálculo numérico eficiente con arrays          |
| `matplotlib` 📈   | Creación de gráficos básicos                   |
| `seaborn` 🎨      | Visualización estadística de alto nivel        |
| `scikit-learn` 🤖 | Algoritmos de machine learning                 |
| `jupyterlab` 🧪   | Entorno interactivo para ejecutar notebooks    |


## 🛠️🚀 Requisitos de instalación

En una terminal ejecuta:
```bash
git clone https://github.com/jcm78411/data-analisys.git
cd data-analisys
```
Despues abre la carpeta con tu editor de codigo favorito
```bash
code . #Si tienes el IDE de Visual Studio Code
```
Asegúrate de tener instalado Python 3.8 o superior. 

Ejecuta el siguiente comando para crear y activar el entorno virtual:
```bash
py.exe -m venv .venv #o tambien python -m venv .venv
.\.venv\Scripts\Activate.ps1
```
O si estas en Linux/MacOS
```bash
source venv/bin/activate
```

Si al activar el entorno virtual te da error de politica de ejecucion de scripts:
```bash
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
```

Luego ejcuta el siguiente comando para instalar los paquetes necesarios:

```bash
pip install -r requirements.txt
```

📚 Recursos adicionales:

📖 **[Documentación oficial de Pandas](https://pandas.pydata.org/docs/)**

📖 **[Guía de NumPy](https://numpy.org/)**

📖 **[Documentación de Matplotlib](https://matplotlib.org/)**

📖 **[Tutorial oficial de Seaborn](https://seaborn.pydata.org/)**

📖 **[Mapa de aprendizaje de Scikit-learn](https://scikit-learn.org/)**

