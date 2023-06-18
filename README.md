# Análisis Geoespacial con Geohash

Este repositorio contiene un análisis geoespacial que utiliza Geohash, un sistema de geocodificación de dominio público, para simplificar y acelerar las operaciones espaciales, como la clasificación y búsqueda. El caso de uso que se explora en este proyecto se basa en las geometrías de las unidades educativas en Guayaquil. Utilizamos los [datos públicos](https://geoportal-guayaquil.opendata.arcgis.com/datasets/219588488dca4a40be9bf9afae22cb82_0/explore?location=-2.198659%2C-79.881801%2C14.92) disponibles en el portal de datos geoespaciales de la Municipalidad. [Accede al Notebook de Análisis aquí](./Geohash_Instituciones_Educativas_Guayaquil.ipynb).

## Contenido
El repositorio incluye un Jupyter Notebook *(GeohashSpatialAnalysis.ipynb)* que realiza los siguientes pasos:

1. Carga los datos geoespaciales de las unidades educativas en Guayaquil y los transforma al Sistema de Referencia de Coordenadas (CRS) correcto (EPSG:4326).
2. Extrae la latitud y la longitud de los puntos de geometría.
3. Genera códigos de Geohash a partir de la latitud y la longitud utilizando una precisión de 7.
4. Crea polígonos a partir de los códigos Geohash.
5. Visualiza los datos geoespaciales en un mapa con un mapa base.
6. Crea un mapa interactivo con marcadores para cada punto de nuestro GeoDataFrame.

## Prerrequisitos
Para ejecutar el notebook, necesitarás tener instaladas las siguientes bibliotecas de Python:
 
- pandas
- geopandas
- python-geohash
- tqdm
- shapely
- contextily
- matplotlib
- folium

Puedes instalar todas estas bibliotecas utilizando pip:

```python

pip install pandas geopandas python-geohash tqdm shapely contextily matplotlib folium
```

## Ejecución
Para ejecutar el notebook, simplemente navega hasta el directorio que contiene GeohashSpatialAnalysis.ipynb y ejecuta jupyter notebook desde la línea de comandos. Luego, en la interfaz de Jupyter que se abre en tu navegador web, abre GeohashSpatialAnalysis.ipynb.

Para más detalles y una explicación detallada del código y los resultados, consulta [este artículo en Medium](https://medium.com/@xavier.jacome.p/aprovechando-el-poder-de-geohash-para-un-an%C3%A1lisis-geoespacial-innovador-y-pr%C3%A1ctico-f3db82051b48?source=friends_link&sk=9dcfc4c48e930a7a073e1502a1f9a5a0).

# <a name="connect"></a> 🔗 Conecta conmigo

<a href="https://medium.com/@xavier.jacome.p" target="_blank"><img alt="Medium" src="https://img.shields.io/badge/medium-%2312100E.svg?&style=for-the-badge&logo=medium&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/xavierjacomep/" target="_blank"><img alt="LinkedIn" src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>
