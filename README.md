# 📊 Análisis de Tarifas de Prepago (Megaline) -Sprint 5

[![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green?logo=pandas)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-Numerical-lightblue?logo=numpy)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?logo=plotly)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-Stats%20Plots-teal?logo=python)](https://seaborn.pydata.org/)
[![SciPy](https://img.shields.io/badge/SciPy-Statistics-purple?logo=scipy)](https://scipy.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)
[![Pipenv](https://img.shields.io/badge/Pipenv-Environment-lightgrey?logo=pypi)](https://pipenv.pypa.io/en/latest/)
[![Status](https://img.shields.io/badge/Project-Sprint%205-blueviolet)]()
[![GitHub](https://img.shields.io/badge/Repo-GitHub-black?logo=github)](https://github.com/cjhirashi/proyecto-sprint-5)

---

## 🚀 Descripción

Este proyecto corresponde al **Sprint 5** del programa de Ciencia de Datos en **TripleTen**.
El objetivo es analizar datos de los clientes del operador **Megaline**, con el fin de determinar cuál de las tarifas de prepago (**Surf** o **Ultimate**) genera mayores ingresos y así optimizar la estrategia de marketing y publicidad.

Se trabaja con datos de **500 clientes durante 2018**, incluyendo llamadas, SMS, tráfico de internet y plan contratado.

Acceso al Notebook: [notebooks/megaline\_analysis.ipynb](https://github.com/cjhirashi/proyecto-sprint-5/blob/main/notebooks/megaline_analysis.ipynb)

---

## ✨ Objetivos principales

* Preparar y limpiar los datos 📊
* Analizar comportamiento de clientes en llamadas, SMS y uso de datos 📱
* Calcular ingresos mensuales por usuario y plan 💰
* Visualizar distribuciones y patrones de uso 📈
* Probar hipótesis estadísticas sobre ingresos medios entre planes y regiones 🧪

---

## 🧰 Tecnologías utilizadas

* [Python 3](https://www.python.org/)
* [Pandas](https://pandas.pydata.org/)
* [NumPy](https://numpy.org/)
* [Matplotlib](https://matplotlib.org/)
* [Seaborn](https://seaborn.pydata.org/)
* [SciPy](https://scipy.org/)
* [Jupyter Notebook](https://jupyter.org/)
* [Pipenv](https://pipenv.pypa.io/en/latest/) – gestión de entornos y dependencias

---

## ⚙️ Estructura del proyecto

```bash
.
├── data/
│   ├── megaline_calls.csv
│   ├── megaline_internet.csv
│   ├── megaline_messages.csv
│   ├── megaline_plans.csv
│   ├── megaline_users.csv
│   └── README.md               # Diccionario de datos
├── notebooks/
│   └── megaline_analysis.ipynb # Notebook principal del proyecto
├── Pipfile
├── Pipfile.lock
└── README.md
```

---

## ▶️ Instalación y uso

1. **Clonar repositorio**

   ```bash
   git clone https://github.com/cjhirashi/proyecto-sprint-5.git
   cd proyecto-sprint-5
   ```

2. **Crear entorno e instalar dependencias con Pipenv**

   ```bash
   pipenv install
   pipenv shell
   ```

3. **Abrir notebook en Jupyter**

   ```bash
   jupyter notebook notebooks/megaline_analysis.ipynb
   ```

---

## 📑 Dataset

Los datos provienen de **Megaline** y se encuentran en la carpeta `/data`.

**Tablas principales:**

* **users** → Información de usuarios (id, nombre, edad, ciudad, plan).
* **calls** → Llamadas realizadas (fecha, duración, usuario).
* **messages** → SMS enviados por usuario (fecha, id).
* **internet** → Sesiones web y volumen de datos consumidos (MB).
* **plans** → Información de tarifas (cuota mensual, minutos/SMS/datos incluidos y costos adicionales).

Más detalle en [`/data/README.md`](https://github.com/cjhirashi/proyecto-sprint-5/blob/main/data/README.md).

---

## 📊 Resultados esperados

* Distribuciones de llamadas, SMS y datos por usuario.
* Ingresos promedio por plan y región.
* Verificación de hipótesis estadísticas entre planes y áreas geográficas.
* Conclusiones sobre la tarifa más rentable para la compañía.

---

## ✅ Conclusiones

El análisis permitió obtener hallazgos clave:

1. **Consumo promedio:** los usuarios de **Ultimate** suelen consumir más minutos y datos, mientras que los de **Surf** tienden a enviar más SMS.
2. **Ingresos:** en promedio, **Ultimate** genera ingresos más altos y estables, mientras que **Surf** depende de pagos extra por excedentes.
3. **Hipótesis:** se confirmó que existen diferencias significativas en ingresos promedio entre **Surf** y **Ultimate**. Asimismo, los usuarios del área de **NY/NJ** generan más ingresos que los de otras regiones.
4. **Distribuciones:** los ingresos muestran colas largas (usuarios con consumos atípicos), lo que evidencia la importancia de controlar outliers en el análisis.

---

## 📌 Recomendaciones

1. **Estrategia publicitaria:** orientar mayores esfuerzos de marketing hacia el plan **Ultimate**, dado que asegura ingresos más estables.
2. **Plan Surf:** promoverlo como opción inicial, pero resaltar costos extra para incentivar la migración a **Ultimate**.
3. **Segmentación regional:** invertir en campañas específicas en **NY/NJ**, donde los ingresos por usuario son más altos.
4. **Gestión de datos:** mantener monitoreo constante de clientes con consumos atípicos para identificar oportunidades o riesgos.

---

## 👨‍💻 Autor

**Carlos Jiménez Hirashi**
💼 Data Scientist Jr. | Python & Machine Learning

📧 [cjhirashi@gmail.com](mailto:cjhirashi@gmail.com) · 🌐 [LinkedIn](https://www.linkedin.com/in/cjhirashi)

---
