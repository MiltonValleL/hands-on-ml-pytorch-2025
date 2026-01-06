# 🔭 Capítulo 1: El Panorama del Machine Learning

<br>

> *"Antes de tocar una sola línea de código, debemos entender la arquitectura mental del ingeniero de ML."*

<br>
<br>

## 🎯 Objetivo del Capítulo
Este módulo establece los fundamentos teóricos críticos para distinguir entre la simple memorización de datos y el verdadero aprendizaje automático generalizable. Aquí diseccionamos los componentes que hacen que un sistema de ML sea robusto en producción.

<br>
<br>

## 🔑 Conceptos Clave (Golden Nuggets)

<br>

### 1. Generalización: ¿Memorizar o Entender?
Exploramos la diferencia fundamental entre:
* **Aprendizaje Basado en Instancias:** El modelo memoriza ejemplos (ej. k-NN).
* **Aprendizaje Basado en Modelos:** El modelo detecta patrones y construye una función matemática (ej. Regresión Lineal, Redes Neuronales).

<br>

### 2. Los "Asesinos Silenciosos" del Modelo
No basta con elegir un buen algoritmo; los datos suelen ser el culpable de los fallos.
* **Sampling Bias (Sesgo de Muestreo):** Cómo datos no representativos pueden destruir la credibilidad de un modelo (Caso: Encuestas electorales fallidas).
* **Data Mismatch:** El peligro de entrenar con datos de alta calidad para un entorno de producción de baja calidad.

<br>

### 3. Diseño Experimental Riguroso
La disciplina científica para evitar el auto-engaño.
* **Train / Validation / Test:** Por qué dividir en dos partes no es suficiente.
* **Data Snooping:** Cómo evitar "hacer trampa" inconscientemente al mirar demasiado el set de prueba.

---

<br>
<br>

## 📂 Contenido Técnico

| Archivo | Descripción |
| :--- | :--- |
| [**01_panorama_general.ipynb**](./01_panorama_general.ipynb) | **Notebook Principal.** Implementación de ejemplos de generalización, visualización de sesgos y configuración del entorno. |

---

## 📺 Video Explicativo

Profundizo en estos conceptos y explico el código paso a paso en mi canal:

[🔴 **Ver Video: Fundamentos de ML y el Arte de la Generalización**](LINK_A_TU_VIDEO_AQUI)
