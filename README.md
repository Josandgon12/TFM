# TFM - Explicabilidad en sistemas de inteligencia artificial para la detección de tumores

Este repositorio contiene el código y la documentación correspondiente al Trabajo de Fin de Máster (TFM) sobre el análisis y clasificación de imágenes médicas utilizando arquitecturas de Deep Learning.

## Estructura del Proyecto

- `notebooks/`: Cuadernos Jupyter con el flujo completo de entrenamiento y evaluación.
  - `TFM.ipynb`: Implementación de modelos de clasificación (VGG16, Xception).
  - `YOLO.ipynb`: Implementación de detección de objetos con la arquitectura YOLO.
- `docs/`: Documentación oficial, incluyendo la memoria del TFM y presentaciones.
- `requirements.txt`: Lista de dependencias de Python necesarias para ejecutar el proyecto.

## Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/[TU_USUARIO]/TFM-Code.git
   cd TFM-Code
   ```

2. Crea un entorno virtual e instala las dependencias:
   ```bash
   python -m venv venv
   source venv/bin/activate  # En Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```

## Modelos y Datasets

Debido al tamaño de los archivos, los pesos de los modelos (.keras) y los datasets no se encuentran incluidos en este repositorio.

> [!NOTE]
> Puedes descargar los modelos y el dataset desde los siguientes enlaces:
> - [Enlace al Dataset] (Añadir enlace aquí)
> - [Enlace a Modelos Entrenados] (Añadir enlace aquí)

## Licencia

Este proyecto está bajo la licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.
