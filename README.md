# Titanic Dataset Analysis

Este proyecto contiene un cuaderno Jupyter (`titanic.ipynb`) que realiza un análisis exploratorio de datos sobre el famoso conjunto de datos del Titanic. El objetivo es mostrar técnicas básicas de manipulación, filtrado y visualización de datos usando pandas y seaborn.

## Archivos

- `titanic.ipynb`: Cuaderno principal con el análisis y visualizaciones.
- `titanic.csv`: Archivo de datos con información de los pasajeros.

## Instalación

Instala las dependencias necesarias ejecutando:

```bash
pip install pandas numpy matplotlib seaborn kagglehub
```

## Estructura del análisis

1. **Carga de datos**  
   Se utiliza pandas para leer el archivo `titanic.csv` y cargarlo en un DataFrame.

2. **Exploración inicial**  
   - Visualización de las primeras filas (`head`)
   - Revisión de la forma del DataFrame (`shape`)
   - Información de columnas y tipos de datos (`info`)

3. **Selección y filtrado de columnas**  
   - Extracción de columnas relevantes: Edad, Sexo y Clase (`Age`, `Sex`, `Pclass`)
   - Filtrado de pasajeros por edad y sexo (ejemplo: mayores de 30 años, mujeres mayores de 30)

4. **Estadísticas descriptivas**  
   - Uso de `describe()` para obtener estadísticas de las columnas numéricas y categóricas
