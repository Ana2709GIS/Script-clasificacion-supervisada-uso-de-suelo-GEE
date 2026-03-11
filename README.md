# Clasificación de Uso del Suelo con Google Earth Engine

Este repositorio contiene el script utilizado para la validación semiautomática de un mapa de uso del suelo mediante imágenes Sentinel-2 y un algoritmo de clasificación Random Forest en Google Earth Engine.

## Metodología

1. Selección de imágenes Sentinel-2 (COPERNICUS/S2_HARMONIZED)
2. Enmascaramiento de nubes
3. Cálculo de índices espectrales:
   - NDVI
   - NDBI
   - MNDWI
   - NDSLI
4. Entrenamiento de modelo Random Forest
5. Clasificación supervisada
6. Evaluación mediante matriz de confusión
7. Vectorización de resultados

## Clases clasificadas

1. Cobertura boscosa  
2. Infraestructura  
3. Agropecuario  
4. Agua  

## Plataforma

Google Earth Engine (JavaScript API)

## AutorAS

Ana María López y Natalia Martinez
2026
