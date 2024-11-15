# Movie Recommender System 🎥

Este es un proyecto básico de un **Sistema Recomendador de Películas** desarrollado en Python. Utiliza la técnica de **TF-IDF (Term Frequency-Inverse Document Frequency)** y **Similitud del Coseno** para recomendar películas basadas en sus descripciones.

---

## 📋 Características

- Basado en **descripciones de películas** del dataset TMDb 5000 Movies.
- Recomendaciones generadas utilizando la **Similitud del Coseno**.
- Fácil de entender y extender para proyectos más avanzados.

---

## 📂 Dataset

El proyecto utiliza el dataset **TMDb 5000 Movies Dataset**, disponible en [Kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata).

---

## ⚙️ Requisitos

Antes de ejecutar el proyecto, asegúrate de instalar las siguientes bibliotecas de Python:

```bash
pip install pandas numpy scikit-learn
```
---

## 🚀 Cómo usarlo
Clona este repositorio:

```bash
git clone https://github.com/fenyx144/movie-recommender-AI.git
```

Descarga el dataset de Kaggle y colócalo en el mismo directorio del archivo movie_recommender.ipynb.
Abre y ejecuta el archivo Jupyter Notebook:

```bash
jupyter notebook movie_recommender.ipynb
```

Cambia el título de la película en la función recommend_movies() para obtener recomendaciones.

---

## 🛠️ Estructura del proyecto

```
📂 Movie Recommender
├── movie_recommender.ipynb  # Notebook con el código
├── tmdb_5000_movies.csv     # Dataset (descargar manualmente)
└── README.md                # Documentación
```
---

## 📜 Ejemplo de uso
Entrada:

```python
recommend_movies("The Godfather")
```

Salida:

```
Películas recomendadas para 'The Godfather':

1. The Godfather: Part II
2. Scarface
3. Goodfellas
4. Casino
5. Heat
...
```

---

## 🤔 ¿Cómo funciona?
### 1. Preprocesamiento del Dataset:
Limpieza de valores nulos en las sinopsis.
### 2. Vectorización TF-IDF:
Convierte las sinopsis en vectores numéricos.
### 3. Similitud del Coseno:
Calcula la similitud entre todas las películas.
### 4. Recomendaciones:
Devuelve las películas más similares basadas en la sinopsis de la película seleccionada.

---

## 🌟 Próximas mejoras
Incorporar información adicional como géneros, elenco o calificaciones.
Crear una interfaz gráfica (GUI) para facilitar el uso.
Implementar un modelo basado en aprendizaje profundo para recomendaciones.

---

## 🤝 Contribuciones
¡Las contribuciones son bienvenidas! Si tienes ideas para mejorar este proyecto, no dudes en enviar un pull request.