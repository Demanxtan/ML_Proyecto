## Dataset

-  Nombre: [`Fresh and Stale Images of Fruits and Vegetables`](https://www.kaggle.com/datasets/raghavrpotdar/fresh-and-stale-images-of-fruits-and-vegetables)
- Contiene imágenes en carpetas separadas por clase, como:
  - `fresh_apple`, `stale_banana`, y muchaos otros tipos de frutas y verduras tanto frescas como en descomposición.

## Modelos implementados

- **MobileNetV2 (Transfer Learning)**
- **CNN personalizada desde cero**
- Comparados en términos de precisión, arquitectura y desempeño.

## Requisitos

bash

pip install -r requirements.txt


> Se uso Python 3.11.x(probado con la version 3.11.9)

## Cómo ejecutar la app

bash

streamlit run app_streamlit.py

## Interfaz gráfica

- Permite subir una imagen y clasificarla como:
  -  **Fresh**
  -  **Stale**
- Muestra la probabilidad de predicción y la imagen cargada.
- Selector interactivo para elegir entre MobileNetV2 y CNN.
