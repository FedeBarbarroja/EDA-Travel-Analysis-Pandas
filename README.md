#  EDA Travel Analysis with Pandas

Federico Barbarroja  
Proyecto realizado en la Materia Fundamentos de ciencia de datos | Tecnicatura Universitaria en Inteligencia Artificial – FCEIA – UNR

---

## 📰 Descripción
Este proyecto realiza un análisis exploratorio de datos (EDA) a partir de un conjunto de datos sobre viajes realizados en el Gran Buenos Aires durante el año 2018. El dataset fue extraído de fuentes oficiales del Gobierno de la Ciudad de Buenos Aires.

Se analizaron distintos aspectos de la movilidad urbana en función del horario, medio de transporte, origen/destino, tiempo y distancia de los viajes.

---

## 📊 Variables Analizadas

- 🧭 Partido de origen y destino  
- 🧍‍♂️ Motivo del viaje  
- 🚍 Medio de transporte  
- ⏱️ Duración del viaje  
- 📏 Distancia del viaje  

---

## ⚡️ Hallazgos Principales

- La mayoría de los viajes se realizan en la franja horaria de la tarde, seguida por la mañana, coincidiendo con horarios laborales y escolares.
- Los viajes por motivos laborales y educativos utilizan principalmente transporte público, caminatas y automóviles.
- Los viajes por motivos recreativos muestran una mayor presencia de taxis, bicicleta y caminata.
- La mayoría de los viajes son internos (mismo partido de origen y destino), especialmente en los partidos con mayor volumen de viajes.
- El 90% de los viajes duran menos de 1 hora; la mediana es de 20 minutos, indicando fuerte presencia de outliers.
- La mediana de distancia es de 2,08 km, mientras que la media se ve afectada por valores extremos (5,23 km).

---

## 📁 Contenido del Repositorio

- `data/` → Conjunto de datos utilizado (si es público).
- `EDA_Travel_Analysis.ipynb` → Notebook de análisis en Python (usando Pandas).
- `EDA_Travel_Analysis.pdf` → Informe final del análisis.
- `README.md` → Este archivo.

---

## 🛠️ Herramientas utilizadas

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=seaborn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

---

## 📄 Informe
Podés ver el informe completo en el siguiente enlace:  
📎 [EDA_Travel_Analysis.pdf](informe/EDA_Travel_Analysis.pdf)

---

## ⚖️ Licencia
Este proyecto se encuentra bajo la licencia MIT.
