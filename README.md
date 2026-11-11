1. Estructura
	Análisis de la desigualdad de España. Informe que recoge los datos calculados así como su interpretación.
	Dashboard de desigualdad. Visualción de los datos calculados de una forma resumida y visual.
	EDA. Fichero jupyter donde aparece el código utilizado para limpiar las bases de datos así como calcular los datos.
	BBDD Capreta donde se enceuntra la descarga de la ECV en csv
	Readme


2. Descripción del proyecto

Este proyecto tiene como objetivo analizar las condiciones de desigualdad de la población de los hogares en España a partir de los microdatos de la Encuesta de Condiciones de Vida (ECV) de 2025, elaborada por el Instituto Nacional de Estadística (INE).

El estudio se centra principalmente en el análisis de la renta, la desigualdad económica y el riesgo de pobreza, prestando especial atención a las diferencias existentes entre comunidades autónomas y distintos grupos de población.

Para ello, se han utilizado técnicas de estadística descriptiva y análisis distributivo, incorporando los factores de elevación de la encuesta para obtener estimaciones representativas de la población española.

3. Herramientas utilizadas

El tratamiento y análisis de los datos se ha realizado principalmente mediante:

Python 3.13
Jupyter y visual studio code
Pandas
Seaborn
pyplot
numpy
Power BI

4. Metodología y análisis realizados

El estudio se estructura en diferentes bloques de análisis:


4.1. Análisis demográfico


Se analiza la distribución de la población española atendiendo a distintas características sociodemográficas:

Distribución de la población por comunidades autónomas.

Distribución según el grado de urbanización.

Composición de la población por género.

Distribución por nacionalidad.

Estructura de edades de la población.


4.2. Análisis de la renta


Se estudia el nivel de ingresos de los hogares y de la población mediante diferentes indicadores:

Renta media per cápita.

Renta media equivalente, utilizando la escala de equivalencia modificada de la OCDE.

Mediana de la renta.

Desviación típica y coeficiente de variación.

Cuartiles y rango intercuartílico (IQR).

Distribución de la renta mediante deciles.

Estos indicadores permiten estudiar tanto el nivel de renta como su dispersión y las diferencias existentes entre distintos grupos de población.


4.3. Análisis de la desigualdad económica


Se analiza cómo se distribuye la renta entre la población y las diferencias existentes entre territorios.

Para ello, se utilizan los siguientes indicadores y herramientas:

Curvas de Lorenz para representar gráficamente la distribución de la renta.

Índice de Gini para cuantificar el grado de desigualdad económica.

Participación del percentil 90 (P90) en la renta total.

Comparación de la dispersión de la renta mediante el rango intercuartílico y su relación con la mediana.

El análisis se realiza tanto a escala nacional como por comunidades autónomas.


4.4. Análisis de la pobreza


Se estudia la incidencia del riesgo de pobreza en España utilizando el umbral de pobreza y los factores de elevación de la encuesta.

Se distinguen dos perspectivas:

Tasa de riesgo de pobreza: porcentaje de población que se encuentra por debajo del umbral de pobreza.

Distribución de la población en riesgo de pobreza: contribución de cada comunidad autónoma al total nacional de personas en riesgo de pobreza.

Esto permite diferenciar entre los territorios con mayores tasas de pobreza y aquellos que concentran un mayor número de personas en esta situación.

5. Visualización de los datos 

Se representa de una forma interactiva y resumida los datos sobre demografía y desigualdad en un Power BI.
