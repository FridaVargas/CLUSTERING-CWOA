# 🐋 CLUSTERING CON WOA

Este repositorio presenta un proyecto de clustering utilizando el **Whale Optimization Algorithm (WOA)**, aplicado a conjuntos de datos reales, incluyendo uno enfocado en la detección de cáncer de mama.

El trabajo fue desarrollado por **Frida Michelle Vargas Bautista** como proyecto final en la materia de **Cómputo Evolutivo** impartida por **Oscar Hernández Constantino**.

---

## 🔎 Descripción general

El algoritmo de optimización por ballena jorobada (WOA) es una metaheurística bioinspirada que simula el comportamiento de caza de las ballenas jorobadas al rodear a sus presas. En este proyecto, se adapta para resolver problemas de clustering, donde cada “ballena” representa una posible solución (asignación de centros) y se evalúa con una función de aptitud basada en la distancia de cada punto a su centro más cercano.

Se probaron diferentes funciones de aptitud y métricas de evaluación sobre conjuntos de datos reales, destacando su aplicación a datos del *Wisconsin Breast Cancer Dataset*.

> *Este proyecto nace de la curiosidad por ver cómo un algoritmo inspirado en ballenas puede aprender a agrupar datos médicos con sentido.*

---

## 📁 Archivos incluidos

- `Clustering_con_WOA.pdf` – Documento completo con explicaciones teóricas, pseudocódigo, pruebas experimentales y resultados.

> El código fue implementado y probado, pero no se comparte en esta versión para preservar su desarrollo original.

---

## 📊 Datasets utilizados

- Iris Dataset (clásico)
- Seeds Dataset
- Wine Dataset
- **Breast Cancer Wisconsin (Diagnostic) Dataset**

---

## 🖼️ Resultados visuales

A continuación se muestran algunos de los agrupamientos obtenidos con el algoritmo en distintos conjuntos de datos:

### 🌸 Iris Dataset

![imagen](https://github.com/user-attachments/assets/df3914c4-66d6-4d84-9e83-5705c7f0bd21) ![imagen](https://github.com/user-attachments/assets/6ae1f3bf-9159-49bc-89a2-561b18f1e81a)

---

### 🍇 Wine Dataset

<p align="center">
  <img src="img/wine_resultado.png" width="500"/>
</p>

---

### 🌾 Seeds Dataset

<p align="center">
  <img src="img/seeds_resultado.png" width="500"/>
</p>

---

### 🧬 Cáncer de mama (Wisconsin Diagnostic)

<p align="center">
  <img src="img/cancer_resultado.png" width="500"/>
</p>

---

## 📚 Referencias clave

- Mirjalili, S., & Lewis, A. (2016). The whale optimization algorithm. *Advances in Engineering Software*, 95, 51–67.
- UCI Machine Learning Repository

---

## 💬 Nota personal

Este proyecto fue una oportunidad para explorar la belleza de los algoritmos inspirados en la naturaleza y su potencial para resolver problemas del mundo real. Aunque no comparto el código, cada línea fue pensada, probada y entendida a fondo. Lo que comparto aquí es la estructura, el proceso y el aprendizaje.

> *A veces una ballena también sabe agrupar cosas que parecen imposibles.*
