# Meta_Lab
Proyecto en Python que convierte pixel art creado en Excel en una matriz de códigos RGB, extrayendo los colores de cada celda mediante openpyxl.
# Extractor de RGB para Pixel Art en Excel

Este proyecto permite convertir pixel art creado en Excel (usando celdas coloreadas) en una matriz de códigos RGB.

El script lee el color de fondo de cada celda en un archivo de Excel y reemplaza ese color por su código RGB correspondiente en una nueva hoja. Esto es útil cuando se trabaja con pixel art almacenado como celdas coloreadas en una hoja de cálculo.

## Características

- Lee archivos de Excel que contienen pixel art hecho con celdas coloreadas
- Extrae los valores RGB de cada celda
- Escribe los códigos RGB en una nueva hoja
- Elimina el color original de las celdas
- Puede ejecutarse en Google Colab o en cualquier entorno de Python

## Tecnologías utilizadas

- Python
- openpyxl
- Google Colab

## Cómo funciona

1. Se carga el archivo de Excel que contiene el pixel art.
2. El programa recorre cada celda de la hoja.
3. Extrae el valor RGB del color de fondo de la celda.
4. Escribe el código RGB en una nueva hoja.
5. Guarda un nuevo archivo de Excel con los resultados.

## Ejemplo

Pixel art original en Excel:

⬛🟩🟩🟩  
🟩⬛⬛🟩  
🟩🟩⬛⬛  

Resultado generado:
4CAF50 4CAF50 4CAF50
4CAF50 000000 000000
4CAF50 4CAF50 000000

## Uso

1. Coloca tu archivo de Excel en Google Drive o en tu directorio de trabajo.
2. Ejecuta el script en Google Colab.
3. Se generará un nuevo archivo de Excel con los códigos RGB.

## Salida

El script genera un nuevo archivo de Excel donde cada celda contiene el código RGB correspondiente en lugar del color original.

## Autor

David Cardenas
