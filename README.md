# 🌎 Análisis Sísmico de México — Servicio Sismológico Nacional (1925–2023)

> 98 años de sismos en México: ¿qué nos dicen los datos?
> Este proyecto analiza 98 años de registros sísmicos para responder esa pregunta con datos.

---

## 📌 Problemática

El territorio mexicano está atravesado por múltiples placas tectónicas, lo que lo convierte en una de las regiones con mayor actividad sísmica del continente. Analizar el catálogo histórico del SSN-UNAM permite identificar patrones de comportamiento que van más allá de los eventos aislados que llegan a los titulares. Este proyecto parte de una pregunta simple: ¿qué nos puede decir la historia sísmica de México?

---

## 🎯 Objetivo

Explorar el catálogo histórico del Servicio Sismológico Nacional (SSN-UNAM) 
para identificar patrones de actividad sísmica, zonas de mayor riesgo y 
tendencias a lo largo de 98 años de registros.

---

## 📊 Dataset

| Campo | Detalle |
|---|---|
| Fuente | Servicio Sismológico Nacional — UNAM |
| Período | 1925 – 2023 |
| Registros | 288,206 sismos |
| Variables | Fecha, Magnitud, Profundidad, Localización |

---

## 🔍 Preguntas de análisis

1. ¿Cómo ha evolucionado la actividad sísmica en México en 100 años?
2. ¿Qué zonas del país concentran los sismos más peligrosos?
3. ¿Existe relación entre la profundidad y la magnitud de un sismo?
4. ¿En qué épocas del año se registra mayor actividad sísmica?

---

## 🛠️ Tecnologías utilizadas

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.0-green)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12-9cf)
![Google Colab](https://img.shields.io/badge/Google%20Colab-notebook-yellow)

---

## 📂 Estructura del proyecto

📁 analisis-sismologico-mexico/

├── 📓 Sismológico_nacional.ipynb   # Notebook principal

├── 📄 README.md                    # Este archivo



---

## 💡 Hallazgos principales

- El **78.72%** de los sismos registrados son de baja magnitud (< 4) e imperceptibles.
- Las zonas de mayor actividad sísmica son **Oaxaca, Chiapas, Guerrero**.
- El **79.43%** de los sismos ocurre a menos de 50 km de profundidad.
- Solo **52 sismos** en 100 años han superado magnitud 7.

---
## Propuestas basadas en el análisis

**1. Reforzar los sistemas de alerta temprana en las zonas de mayor concentración sísmica**
El 85.6% de los sismos registrados entre 1925 y 2023 se concentra en Guerrero, Oaxaca 
y Chiapas. Esta concentración sugiere que los recursos de monitoreo, alerta temprana 
y respuesta de emergencia deberían priorizarse en estas entidades, garantizando que 
su infraestructura de protección civil esté a la altura del riesgo real que enfrentan.

**2. Revisar los códigos de construcción en regiones de sismicidad superficial**
El 75.81% de los sismos ocurre a menos de 40 km de profundidad. Los sismos 
superficiales liberan su energía más cerca de la superficie, lo que los hace 
potencialmente más destructivos. Esto representa un argumento sólido para revisar 
y actualizar los estándares de construcción en las zonas de mayor actividad, 
especialmente en zonas urbanas de Guerrero, Oaxaca y Chiapas.

**3. Comunicar el aumento en el registro sísmico de forma transparente a la población**
A partir de 2015 se observa un incremento significativo en el número de sismos 
registrados. Es importante que instituciones como el SSN comuniquen claramente 
que este aumento refleja en parte mejoras en la capacidad de detección tecnológica, 
y no necesariamente un incremento real en la actividad sísmica. Una comunicación 
transparente evita el pánico innecesario y fortalece la confianza pública en las 
instituciones científicas.
---


## 🚀 Siguientes pasos

- Incorporar datos geoespaciales para visualizar sismos en un mapa interactivo.
- Cruzar con datos socioeconómicos para estimar impacto potencial por región.

---

## 👤 Autor

**Fernando Teodoro Gabino**  
[LinkedIn](https://www.linkedin.com/in/fernandoteodorogabino/) • [GitHub](https://github.com/alfavinyl)


