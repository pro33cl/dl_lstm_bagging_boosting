# 📘 Deep Learning & NLP: LSTM + Word Embeddings + Bagging & Boosting

Notebook: dl_lstm_bagging_boosting.ipynb

🧠 Descripción General

Este repositorio contiene un notebook que desarrolla un flujo completo de Procesamiento de Lenguaje Natural (NLP) aplicando técnicas modernas de Deep Learning y Machine Learning sobre un dataset de noticias. El objetivo es predecir el nivel de viralidad de cada artículo mediante modelos tanto tradicionales como basados en redes neuronales.
El proyecto integra procesamiento de texto, embeddings, redes LSTM, técnicas de ensamble y análisis de métricas, ofreciendo una visión práctica del pipeline típico utilizado en problemas reales de clasificación de texto.

📂 Contenidos del Notebook

El notebook se organiza en actividades que abarcan todo el ciclo de modelamiento:

1️⃣ Exploración de Datos (EDA)

Carga del dataset news1.csv.

División en training y test.

Exploración de palabras, conteos y patrones.

Identificación del objetivo: número de veces que el artículo fue compartido.

2️⃣ Word Embeddings

Uso de un modelo Word2Vec preentrenado.

Generación de las secuencias de texto.

Construcción de la matriz de embeddings para alimentar los modelos.

3️⃣ Modelo LSTM (Deep Learning)

Implementación de una red neuronal recurrente (LSTM).

Preparación del pipeline de tokenización y padding.

Evaluación del modelo mediante:

Accuracy

Matriz de confusión

Curva ROC y AUC

4️⃣ Predicciones y Análisis de Errores

Predicción de nuevas observaciones del conjunto de noticias.

Análisis de casos correctamente clasificados.

Comentarios sobre errores y desafíos del modelo.

5️⃣ Técnicas de Ensamble

Bagging

Boosting

Comparación conceptual entre técnicas tradicionales y Deep Learning.

🛠️ Tecnologías Utilizadas

- Python 3

- NumPy

- Pandas

- Matplotlib / Seaborn

- TensorFlow / Keras

- Gensim (Word2Vec)

- Scikit-learn
