# Detección de SKUs en Imágenes de estantes del sector retail Usando YOLO

Este proyecto implementa un flujo completo para la detección de objetos (SKUs en estanterías) utilizando  YOLOv8. 
El proceso incluye la descarga de un dataset desde Kaggle, la preparación de datos, el entrenamiento del modelo y la realización de predicciones en nuevas imágenes.

## **Estructura del Proyecto**
El notebook está dividido en las siguientes secciones principales:

1. **Características del entorno**: Verifica la disponibilidad de la GPU y el entorno necesario para ejecutar el proyecto.
2. **Descarga del dataset desde Kaggle**: Obtiene los datos necesarios para el entrenamiento del modelo.
3. **Visualización de imágenes y bounding boxes**: Muestra cómo las imágenes del dataset están etiquetadas para el entrenamiento.
4. **Entrenamiento del modelo**: Configura y entrena el modelo YOLO usando el dataset descargado.
5. **Predicción en nuevas imágenes**: Aplica el modelo entrenado a nuevas imágenes y muestra y guarda los resultados.

## **Requisitos**
Para ejecutar este proyecto, se necesita lo siguiente:

- Python 3.8 o superior.
- GPU compatible con CUDA (recomendado para entrenamiento).
- Librerías de Python:
  - `opencv-python`
  - `matplotlib`
  - `numpy`
  - `pandas`
  - `kagglehub`

Puedes instalar estas librerías ejecutando:

```bash
pip install librteria  #-r requirements.txt
```
Además este proyecto descarga datos de Kaggle, por lo que se debe tener configurado correctamente la API de Kaggle, para no tener ningún inconveniente.