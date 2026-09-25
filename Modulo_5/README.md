# Contenido del repositorio

En esta carpeta encontrarás dos subcarpetas: **Actividades 8 de agosto** y **Actividades 15 de agosto**. Dentro de cada una encontrarás los archivos `.ipynb` correspondientes a las actividades de esas fechas, además de subcarpetas adicionales con las actividades faltantes.

## Estructura de carpetas

### Actividades 8 de agosto

- **M5.1 Transfer Learning**: contiene los archivos con extensión `.pt`, que guardan el estado del entrenamiento.
- **M5.2 Autoencoders I**
- **M5.2 Autoencoders II**: requiere el archivo `Shapes.py`.

### Actividades 15 de agosto

- **M5.7 Lab Autoencoders**: contiene archivos `.pt` y el enlace al dataset.
- **M5.5 MAE**: contiene archivos `.pt` y el enlace al dataset.
- **M5.4 VAE**
- **M5.3 DAE**

## Archivos .pt

Los archivos con extensión `.pt` guardan el estado del entrenamiento. Son útiles si:

- la sesión se interrumpe,
- necesitas continuar el entrenamiento más tarde, o
- quieres comparar resultados entre distintas ejecuciones.

Si deseas comparar resultados, coloca estos archivos en la carpeta **Checkpoints** (creada automáticamente al ejecutar el notebook) dentro de la sección de archivos del entorno de Google Colab.

## Requisitos previos por notebook

Antes de ejecutar cualquier celda, agrega los siguientes archivos en la sección de archivos del entorno de Google Colab, según corresponda:

| Notebook | Archivo requerido |
|---|---|
| M5.5 MAE | `catsvsdogs.zip` |
| M5.7 Lab Autoencoders | `catsvsdogs.zip` |
| M5.2 Autoencoders II | `Shapes.py` |
