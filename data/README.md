# 📂 Diccionario de Datos - Megaline

Este directorio contiene los archivos de datos utilizados en el proyecto de análisis de tarifas de prepago de **Megaline**. A continuación, se describen las tablas y el significado de cada columna.

---

## 👤 Tabla: Usuarios (`users`)

* `user_id`: Identificador único del usuario.
* `first_name`: Nombre del usuario.
* `last_name`: Apellido del usuario.
* `age`: Edad del usuario.
* `reg_date`: Fecha de registro del usuario.
* `churn_date`: Fecha de baja del servicio (si aplica).
* `city`: Ciudad de residencia del usuario.
* `plan`: Nombre de la tarifa contratada.

---

## 📑 Tabla: Planes (`plans`)

* `plan_name`: Nombre de la tarifa contratada.
* `usd_monthly_fee`: Cuota mensual en dólares estadounidenses.
* `minutes_included`: Minutos incluidos al mes.
* `messages_included`: SMS incluidos al mes.
* `mb_per_month_included`: Datos incluidos al mes (en megabytes).
* `usd_per_minute`: Costo por minuto adicional.
* `usd_per_message`: Costo por SMS adicional.
* `usd_per_gb`: Costo por gigabyte adicional (1 GB = 1024 MB).

---

## ☎️ Tabla: Llamadas (`calls`)

* `id`: Identificador único de la llamada.
* `call_date`: Fecha de la llamada.
* `duration`: Duración de la llamada en minutos.
* `user_id`: Identificador del usuario que realizó la llamada.

---

## 💬 Tabla: Mensajes (`messages`)

* `id`: Identificador único del mensaje de texto.
* `message_date`: Fecha del mensaje.
* `user_id`: Identificador del usuario que envió el mensaje.

---

## 🌐 Tabla: Internet (`internet`)

* `id`: Identificador único de la sesión web.
* `mb_used`: Volumen de datos utilizados durante la sesión (en megabytes).
* `session_date`: Fecha de la sesión web.
* `user_id`: Identificador del usuario que realizó la sesión.

---
