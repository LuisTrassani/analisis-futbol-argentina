# analisis-futbol-argentina
Analisis de partidos a lo largo de los años, contiene un análisis exploratorio de datos (EDA) sobre los partidos de la Selección Argentina.

**Fuente:**  
[Kaggle - International Football Results from 1872 to 2023](https://www.kaggle.com/martj42/international-football-results-from-1872-to-2017)

**Pasos realizados:**
1. **Extracción:** Se importó el dataset desde una fuente pública kaggle.  
2. **Transformación:**  
   - Eliminación de nulos y duplicados.  
   - Conversión de la columna de fecha a tipo datetime.  
   - Renombre de columnas para facilitar el acceso.
   - Creación de nuevas variables:
     -'DifGoles': diferencia de goles.
     - 'Resultado': resultado del local (gana, empata o pierde).
3. **Carga:** Se generó un archivo limpio (ResultadosFulbo.csv) listo para análisis.

**Analisis**
- Partidos Selección Argentina.  
- Total partidos Selección Argentina.  
- Tabla pivote 

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ltrassani/analisis-futbol-argentina/blob/main/Resultados.ipynb)
