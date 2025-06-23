# PRÁCTICA DE DEEP LEARNING

Este repositorio contiene la implementación y los recursos de la práctica de Deep Learning.

## Contenido Adicional Incluido:

* **Visualización del Modelo:**
    * Imágenes de la arquitectura del modelo final (`engagement_model.onnx.png` y `model_graph_final.png`).
    * **Modelo ONNX** (`engagement_model.onnx`) para una exploración interactiva en Netron.
        * **Instrucciones para visualizar en Netron:**
            1.  Visita la página oficial de Netron: [https://netron.app/](https://netron.app/)
            2.  Haz clic en el botón "Open Model..." y selecciona el archivo `engagement_model.onnx` desde tu equipo.
* **Documentación Detallada:**
    * Memoria técnica exhaustiva en formato PDF: `Proyecto Deep Learning - Sofia Gabian.pdf`.
* **Código Fuente:**
    * Notebook de Jupyter con todo el código: `Practica_Deep_Learning_Sofia_Gabian.ipynb`.
* **Modelos Optimizados:**
    * Los mejores modelos obtenidos a través de la optimización con Optuna.

## Instrucciones para la Ejecución:

1.  **Datos:**
    * Descomprime el archivo `data_main.zip` ubicado dentro de la carpeta `datos`.
    * **Estructura de Carpetas Requerida:** Asegúrate de que la estructura de los datos sea: `\datos\data_main\` y, dentro de `data_main`, todas las carpetas que contienen las imágenes.
    * El archivo `poi_dataset.csv` debe estar dentro de la carpeta `datos`.

2.  **Requisitos:**
    * Se incluye un archivo `requirements.txt` con todas las dependencias necesarias para ejecutar el código. Puedes instalarlas usando `pip install -r requirements.txt`.

3.  **Configuración de Ruta de Datos:**
    * Dentro del notebook `Practica_Deep_Learning_Sofia_Gabian.ipynb`, localiza la variable `ruta_imgs` y actualízala con la ruta absoluta donde se encuentran tus datos.
    * **Ejemplo:** `ruta_imgs = "/tu/ruta/a/la/carpeta/datos/"`
  
