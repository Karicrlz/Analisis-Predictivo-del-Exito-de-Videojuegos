#  📈🎮Análisis Predictivo del éxito de Videojuegos 🎮🕹️
## Descripción del proyecto
En este proyecto, trabajé para la tienda online Ice, especializada en la venta de videojuegos a nivel mundial 🎮🌍. Mi tarea consistió en analizar datos de ventas históricas 📊, reseñas de usuarios y expertos 📝, géneros 🎯 y plataformas como Xbox y PlayStation 🖥️, con el fin de identificar patrones que ayudaran a predecir el éxito de un videojuego. Utilizando datos disponibles hasta 2016, me enfoqué en planificar una campaña publicitaria para 2017 📅. El análisis incluyó la clasificación ESRB de cada juego, un factor clave para determinar su éxito en función del público objetivo 🎯👾. Este proyecto me permitió adquirir experiencia práctica en el manejo de datos y en la detección de tendencias relevantes para estrategias comerciales 🚀

## Motivación 
Este proyecto es importante porque aborda la optimización de estrategias comerciales en la industria de los videojuegos, un mercado global altamente competitivo y dinámico. Al analizar datos de ventas históricas, reseñas de usuarios y expertos, y características clave de los videojuegos, como los géneros y plataformas, se pueden identificar patrones que permiten predecir qué juegos tienen más probabilidades de ser exitosos. Esta información es crucial para una tienda online como Ice, ya que ayuda a anticipar la demanda, maximizar las inversiones en publicidad y enfocar esfuerzos de marketing hacia títulos con mayor potencial. Además, considerar factores como la clasificación ESRB permite segmentar de manera más efectiva el público objetivo, garantizando que las campañas sean relevantes para los diferentes grupos de consumidores. Este tipo de análisis no solo optimiza el rendimiento comercial de la tienda, sino que también brinda una ventaja competitiva al tomar decisiones basadas en datos concretos. A nivel personal, el proyecto brindó valiosa experiencia práctica en la manipulación y análisis de datos, permitiendo desarrollar habilidades clave en el manejo de información relevante para la toma de decisiones estratégicas en el comercio digital.

## Características del Dataset

Name (Nombre)

— Platform (Plataforma)

— Year_of_Release (Año de lanzamiento)

— Genre (Género) 

— NA_sales (ventas en Norteamérica en millones de dólares estadounidenses) 

— EU_sales (ventas en Europa en millones de dólares estadounidenses) 

— JP_sales (ventas en Japón en millones de dólares estadounidenses) 

— Other_sales (ventas en otros países en millones de dólares estadounidenses) 

— Critic_Score (máximo de 100) 

— User_Score (máximo de 10) 

— Rating (ESRB)

## Herramientas Utilizadas
### Lenguaje: 
Python 
### Librerías:
Pandas 
numpy 
matplotlib
pyplot 
seaborn 
scipy.stats 

## Proceso del Proyecto

### Introducción
### Exploración y preprocesamiento de datos

El objetivo de este apartado es la exploración, modificación y corrección de los datos del data frame para posteriormente analizar los datos.

### Análisis de datos

Se realizaron los analisis generales de los datos presentados.Los juegos más vendidos, los mejor ranckeados, los más poluares, el genero más polar, etc.

### Análisis por región

Se realizaron los analisis generales de los datos presentados pero por región (Japón, Norte Ámerica y Europa) .Los juegos más vendidos, los mejor ranckeados, los más poluares, el genero más polar, etc.

### Prueba de hipotesis

H0 = Las calificaciones promedio de los usuarios para las plataformas Xbox One y PC son las mismas.

H1= Las calificaciones promedio de los usuarios para las plataformas Xbox One y PC son diferentes.

### Conclusiones

Se han detectado las platafomas y generos que más populares son y podemos saber a que lado de la moneda podemos apostarle. Se detectaron resultados que pueden generalizarse y tener buena ganancia, sin embargo para potencializarlo más, al hacer los análisis por región se logro entender el comportamiento de estas para evitar algunas perdidas.

En algunas regiones coiciden generos, plataformas y rating, pero en otras no. No es que el número sea extraodinariamente alejado, pero al tratarse de negocios, el tener esto en cuenta evita gasto;

Mientras que para Norteamérica y Europa, un juego de acción en xbox puede ser un gran lanzamiento, para Japón pasará desapercibido, ya que no tienen ventas significativas para esta plataforma y su género favorito no es de acción. De la misma manera un juego de Role_playing en 3DS puede ser un hit pero únicamente para Japón.

Por lo que es importante considerar la región en la que se quiere sacar un juego.
