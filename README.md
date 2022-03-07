# EDA_Palmer_Pinguins_ES
EDA - Análisis exploratorio de datos siguiendo la metodología de Google

# Objetivo
El objetivo de este análisis exploratorío de datos es el de aplicar la metodología demarcada por Google, en un set de datos conocido con el fin de realizar ejercicios de aprendizaje en Python.

## Contexto de los datos
Estos datos pertenecen al estadista y biólogo británico Ronald Fisher, en los cuales se describen características de tres diferentes especies de pingüinos, Adelié, Gentoo y Chinstrap; encontrados en el archipiélago Palmer.

Link to Dataset: https://www.kaggle.com/parulpandey/palmer-archipelago-antarctica-penguin-data


# Metodología aplicada.

Se hace uso del método de análisis de datos utilizado por Google, el cual se compone de seis distintas fases:

1. **Preguntar:** Establecer el problema a resolver.

2. **Preparar:** Establecer las necesidades de datos y almacenarlos.

3. **Procesar:** Limpiar los datos, establecer si los datos son suficientes.

4. **Analizar:** Organizar los datos y utilizar métodos analíticos para extraer información que resuelve el problema.

5. **Compartir:** Generar visualizaciones y presentaciones que permitan entender el proceso y solución.

6. **Actuar:** Tomar decisiones basadas en el análisis de los datos.

# Desarrollo

En el documento adjunto de  Jupyter Notebooks se ejecuta paso a paso en análisis exploratorio de datos, siguiendo la metología ya mencionada, ejecutando:

- Gestión de archivos en Python con la librería Pandas.
- Visualizaciones preliminares de información para comprender los datos, ayudado de librerías como Seaborn y Matplotlib.
- Limpieza de datos utilizando Pandas.
- Análisis exploratorio de datos usando gráficos de densidades de distribuciones, gráficos de puntos y boxplots, que permiten comparar los atributos fisícos de los pinguinos, así como entender las diferencias entre estas tres especíes.
- Ejecutar validaciones estadísticas para determinar si los parecidos encontrados son significativos.
- LLegar a conclusiones preliminares acerca de las diferencias y similitudes fisícas de las razas de pingüinos estudiadas.

# Conclusiones del análisis exploratorio de datos

Según el análisis exploratorio de datos, para las observaciones brindadas de diferentes especíes de pingüinos en el archipielago Palmer, se puede concluir que se puede dar una clasificación para cada especíe según las carácteristicas físicas muestreadas en el estudio. Es decir, existen diferencias físicas entre las especíes estudiadas de la siguiente manera:

**Adelie Penguin (Pygoscelis adeliae)**

- Los Adelie parecen tener una profundidad de culmen similar a los Chinstrap
- Entre las tres especíes son los que poseen una menor longitud de culmen.
- Poseen un peso estadísticamente similar a los de los Chinstrap, siendo pingüinos de un peso menor a los Gentoo.
- Son los de ala mas corta entre las tres especíes.
- En cuanto a la medida del delta 15 N estos destacan por tener una alta variabilidad y valores estadísticos intermedios al compararlos con las otras dos especíes.
- Los valores de delta 13 C nos muestran comportamientos similares entre las especíes Adelie y Gentoo

**Chinstrap penguin (Pygoscelis antarctica)**
- Los Chinstrap son similares a los Adelie en cuanto a la profundidad del culmen y el peso corporal.
- Tienen un largo de culmen un poco mayor a las otras dos especíes.
- Su longitud de ala es un poco mayor a la de los Adelie pero menor a los Gentoo.
- Presentan los mayores valores en cuanto al 15N y 13C, separandose por bastante en esta última medida de los otros dos grupos.

**Gentoo penguin (Pygoscelis papua)**
- Los Gentoo destacan por ser de ala larga y mayor peso. Podrìamos decir que son los más grandes de los tres.
- Aunque tienen la menor profundidad de culmen de los tres.
- Presentan los menores valores en cuanto a 15N y están un poco por debajo de los Adelie en 13C.
