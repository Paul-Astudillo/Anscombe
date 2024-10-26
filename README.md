# UNIVERSIDAD POLITÉCNICA SALESIANA
![Universidad Politécnica Salesiana](https://github.com/vlarobbyk/fundamentos-vision-artificial-doctoradoCC/blob/main/images/Logo-UPS-30-Años.png?raw=true)

**Carrera**: Computación  
**Período**: 65  
**Estudiante**: Paul Astudillo 

## El Cuarteto de Anscombe

El **Cuarteto de Anscombe** es un conjunto de datos compuesto por cuatro grupos, ideados en 1973 por el estadístico británico Francis Anscombe, con el objetivo de demostrar la importancia de la **visualización** en el análisis de datos. Los cuatro grupos (I, II, III, IV) tienen propiedades estadísticas muy similares, pero con patrones gráficos radicalmente distintos. A nivel numérico, los cuatro conjuntos comparten:

- Media de `x` e `y` prácticamente iguales.
- Varianza similar en ambos ejes.
- Una correlación entre las variables `x` e `y` que es prácticamente idéntica en los cuatro casos.
- La misma ecuación de la línea de regresión lineal.

Sin embargo, al graficar estos conjuntos de datos, se revelan patrones completamente diferentes. Este fenómeno destaca la importancia de la visualización para evitar interpretaciones engañosas basadas únicamente en los valores estadísticos, mostrando que los números por sí solos no cuentan toda la historia.

## Dataset Datasaurus

El **Datasaurus**, creado por Alberto Cairo y popularizado en 2017 por Justin Matejka y George Fitzmaurice, es otro ejemplo que resalta la importancia de visualizar los datos. Aunque las estadísticas descriptivas del Datasaurus (como la media y la varianza) son similares a otros conjuntos de datos, al graficarlo se revela una imagen inesperada: un dinosaurio. Esto demuestra cómo diferentes distribuciones de puntos pueden dar lugar a formas visuales únicas que las estadísticas numéricas no pueden captar.

### Datasaurus Dozen

El **Datasaurus Dozen** es una extensión de este concepto. Consiste en una serie de 13 conjuntos de datos que, a pesar de tener estadísticas descriptivas casi idénticas, generan formas visualmente distintas cuando se grafican, como círculos, estrellas, líneas o figuras abstractas. Este conjunto de datos refuerza la lección de que las estadísticas no son suficientes y que la visualización es una herramienta esencial para un análisis exhaustivo y preciso de los datos.

---

### Estructura del Repositorio:

1. **README.md**: Este archivo con la explicación de los conceptos clave.
2. **data/**: Directorio que contiene todos los conjuntos de datos utilizados en la práctica, incluyendo los del cuarteto de Anscombe y el Datasaurus Dozen.
3. **anscombe/**: Contiene el código fuente del cuaderno de Jupyter con las siguientes secciones:
   - Carga de los datasets.
   - Resúmenes estadísticos.
   - Gráficos de los cuatro conjuntos de datos.
   - Box plots correspondientes a cada grupo.
   - Código documentado en Markdown o comentarios.
4. **DataSaurus/**: Contiene el archivo `.rmd` con el análisis del dataset Datasaurus Dozen y el resultado en formato HTML.
5. **Herramienta de Regresión**: Directorio que incluye el código y la gráfica de la regresión lineal sobre el dataset seleccionado del Datasaurus.

---

