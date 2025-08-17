# 📊 Análisis de Tarifas de Prepago - Megaline

[![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green?logo=pandas)](https://pandas.pydata.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)
[![Status](https://img.shields.io/badge/Project-Sprint%208-blueviolet)]()

---

## 🚀 Descripción

Este proyecto forma parte del **Sprint 8 del programa de Ciencia de Datos en TripleTen**.
El objetivo es realizar un **análisis preliminar de las tarifas de prepago "Surf" y "Ultimate" de la compañía Megaline**, con el fin de determinar cuál de los planes genera **mayores ingresos** y así optimizar la estrategia de marketing y publicidad.

Se trabaja con un conjunto de datos de **500 clientes** de 2018, incluyendo información sobre llamadas, SMS, tráfico de internet y el plan contratado.

---

## ✨ Objetivos principales

* 📈 Analizar el comportamiento de los clientes con base en llamadas, SMS y uso de datos.
* 💰 Calcular los ingresos mensuales de cada usuario según su tarifa.
* 🧮 Evaluar la rentabilidad de las tarifas **Surf** y **Ultimate**.
* 🧪 Aplicar **pruebas estadísticas** para comprobar si existen diferencias significativas en los ingresos medios:

  * Entre usuarios de Surf y Ultimate.
  * Entre clientes de Nueva York/Nueva Jersey y otras regiones.

---

## 📂 Diccionario de datos

El proyecto utiliza 5 tablas principales:

| Tabla        | Descripción                                                                      |
| ------------ | -------------------------------------------------------------------------------- |
| **users**    | Información general de los clientes (id, nombre, edad, ciudad, plan, etc.).      |
| **calls**    | Registro de llamadas: fecha, duración (en minutos).                              |
| **messages** | Registro de SMS enviados por cliente.                                            |
| **internet** | Sesiones web con volumen consumido (MB).                                         |
| **plans**    | Información de tarifas (precio mensual, minutos/SMS/GB incluidos, costos extra). |

---

## 🧰 Tecnologías utilizadas

* [Python 3](https://www.python.org/) – Lenguaje de programación principal
* [Pandas](https://pandas.pydata.org/) – Análisis y manipulación de datos
* [NumPy](https://numpy.org/) – Operaciones numéricas y estadísticas
* [Matplotlib](https://matplotlib.org/) – Visualización de datos
* [Seaborn](https://seaborn.pydata.org/) – Gráficos estadísticos
* [SciPy](https://scipy.org/) – Pruebas de hipótesis y estadística
* [Jupyter Notebook](https://jupyter.org/) – Entorno de desarrollo interactivo

---

## ⚙️ Estructura del proyecto

```bash
.
├── data/
│   ├── megaline_calls.csv
│   ├── megaline_internet.csv
│   ├── megaline_messages.csv
│   ├── megaline_plans.csv
│   └── megaline_users.csv
│   └── README.md
├── notebooks/
│   └── megaline_analysis.ipynb   # Notebook principal del proyecto
└── README.md
```

---

## ▶️ Ejecución

1. **Clonar repositorio**

   ```bash
   git clone https://github.com/cjhirashi/proyecto-sprint-5
   cd proyecto-sprint-5
   ```

2. **Abrir notebook en Jupyter**

   ```bash
   jupyter notebook notebooks/megaline_analysis.ipynb
   ```

---

## 📊 Resultados esperados

* Distribuciones de llamadas, SMS y consumo de datos por usuario.
* Cálculo de ingresos promedio por plan.
* Contraste estadístico de hipótesis para validar diferencias en ingresos.
* Conclusiones sobre la tarifa más rentable.

---

## 👨‍💻 Autor

**Carlos Jiménez Hirashi**
💼 Data Scientist Jr. | Python & Machine Learning

📧 [cjhirashi@gmail.com](mailto:cjhirashi@gmail.com) · 🌐 [LinkedIn](https://www.linkedin.com/in/cjhirashi)

---
