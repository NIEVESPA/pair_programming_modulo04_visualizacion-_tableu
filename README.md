📊 Práctica de Importación y Gestión de Datos en Tableau (Serie Friends)

🎯 Objetivo General

El objetivo de estas sesiones es practicar la importación y gestión de datos en Tableau, utilizando varias fuentes de datos relacionadas con la icónica serie Friends. Aplicaremos habilidades clave como la inspección de columnas, el ajuste de formatos, la combinación de fuentes y la exploración de datos.

🛠️ Pair 1: Preparación de Datos y EDA

Objetivo

El objetivo de esta sesión es tener los datos preparados para poder hacer las visualizaciones. Para ello necesitamos hacer una serie de transformaciones.
Para realizar las transformaciones necesarias, lo primero que necesitamos es conocer nuestros datos correctamente. El primer paso debería ser hacer un pequeño EDA (Análisis Exploratorio de Datos).

📈 Pair 2: Creación de Visualizaciones Básicas
1. Big Numbers (Indicadores Clave)
Objetivo: Familiarizarse con métricas clave y funciones de agregación.

Indicador	Función de Agregación
Número de episodios	Conteo total
Número de temporadas	Valores únicos
Puntuación media en IMDb	Promedio
Millones de visualizaciones	Suma

Exportar a Hojas de cálculo:

2. Gráfico de Barras
Objetivo: Comparar categorías usando codificación visual dual (altura + color).

3. Gráfico de Líneas
Objetivo: Analizar tendencias temporales.

4. Histograma
Objetivo: Entender la distribución de audiencia.

5. Gráfico Circular (Quotes por Author)
Objetivo: Identificar proporciones en una variable categórica.

🎨 Pair 3: Personalización, Filtros y Formato del Dashboard

personalizar nuestras gráficas y a dar formato a nuestro Dashboard.

1. Filtro Top N
Objetivo: En alguna de nuestras visualizaciones tenemos demasiadas categorías y eso nos crea una gráfica con demasiados datos que es difícil de leer. En este caso vamos a aplicar un filtro Top N para que se muestren las categorías principales.

2. Mostrar Filtro (por Temporadas)
Objetivo: Para poder analizar y entender correctamente los datos y poder encontrar patrones, necesitamos poder filtrar por alguna categoría. Para este ejercicio vamos a añadir un filtro por temporadas al gráfico anterior. Esto nos permite poder ver la evolución de los protagonistas a lo largo de las distintas temporadas y saber si ha cambiado su presencia.

3. Descripciones Emergentes (Tooltips)
Objetivo: Las descripciones emergentes nos pueden mostrar más variables y ofrecer más información sobre los datos que estamos visualizando. Para poder hacer esto de forma correcta, deben tener un diseño claro y unos nombres descriptivos de las variables.

4. Añadir Imagen
Objetivo: Uno de los elementos para personalizar nuestro trabajo es la inserción de imágenes. En este caso, aprovecharemos la estética conocida de la serie.

5. Contenedores
Objetivo: En el primer boceto del Dashboard, los Big Numbers que habíamos añadido no estaban cuadrados y la estética no era la adecuada. Utilizaremos contenedores para organizar y alinear estos elementos.

🧼 Pair 4: Limpieza de Datos y Campos Calculados
Al ir realizando este proyecto, hemos podido detectar que hay alguna incostistencia en los datos. Vamos a ver cómo podemos corregir esto usando campos calculados.

1. Limpieza columna Author
Objetivo: Los datos que hemos mostrado en nuestro gráfico de Donut no son del todo correctos, algunos nombres están escritos de distintas maneras (ej: "Rachel" y "RACHEL"). Necesitamos un campo calculado para unificar los nombres de los autores en el archivo quotes.csv.

2. Buscando la frase mítica
Objetivo: Una de las frases más repetidas e importantes de la serie es: "oh my god". Vamos a utilizar nuestros conocimientos de campos calculados para contar o destacar esta frase.

3. Crear campo de Capítulo y Temporada
Objetivo: Queremos ver el detalle de visualizaciones por temporada y capítulo. Para poder visualizar esto de la forma correcta, tenemos que crear un campo calculado que una en una misma cadena de texto el número de temporada y el número de capítulo (ej: "T01-E05").