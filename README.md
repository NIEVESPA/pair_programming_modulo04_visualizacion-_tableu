
## 📊 Dashboard Interactivo

!(Images\el_reparto_en_datos.png)

(https://public.tableau.com/views/Proyecto_Friends_17659698423520/Bienvenida?:language=es-ES&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)


# 📺 The One Where We Analyze Everything: El capítulo donde lo analizamos todo.

> "¿Alguna vez habéis estado en una terraza y todo el mundo empieza a hablar de Friends… y tú sonríes, asientes… pero en realidad no tienes ni idea de quién es Ross? Bueno, nosotras somos esas personas.
> Nunca habíamos visto Friends. Y este proyecto nace de ahí: queríamos dejar de sentirnos culturalmente excluidas. Pero en lugar de vernos las 10 temporadas en un fin de semana, decidimos hacer algo diferente: **usar los datos para entender por qué Friends es TAN importante.**"

Este proyecto, desarrollado bajo el marco de **Adalab**, es el resultado de una investigación colaborativa donde los datos y la IA sustituyen a los maratones de televisión para descubrir el fenómeno detrás de la sitcom más icónica de la historia.

---

## 🤝 Colaboración y Equipo

desarrollado de forma conjunta por:

* **Gisela Barroso** | **Nieves Pérez** | El Dashboard incluye acciones de URL dinámicas que permiten conectar directamente con nuestros perfiles profesionales.
---

## 📊 Estructura del Análisis

El dashboard ha sido diseñado como un viaje de descubrimiento estructurado en tres bloques clave:

### 1. "Una historia de popularidad"

Analizamos el impacto global y la evolución de la serie. Utilizamos los datasets `friends_info.csv` y `friends_episodes_v3` para visualizar audiencias millonarias y puntuaciones de IMDb, entendiendo qué episodios convirtieron a la serie en un hito histórico.

### 2. "Ellos son los verdaderos protagonistas"

Profundizamos en el reparto y su relevancia. A través de métricas comparativas y filtros dinámicos, exploramos la presencia de los personajes y cómo su peso en la trama evolucionó a lo largo de las 10 temporadas.

### 3. "¿Quién dijo qué? y ¿Cómo lo dijo?" (IA y Sentimientos)

Para una comprensión profunda de la psique de los personajes sin haber visto la serie, hemos integrado **Inteligencia Artificial**:

* **NLP con Hugging Face:** Aplicamos modelos de lenguaje avanzados como `sentiment_analyzer` para procesar el dataset `friends_quotes`.
* **Análisis de Emociones:** Clasificamos los diálogos para entender el tono emocional de cada protagonista.
* **Potencia de VizQL:** Utilizamos el motor **VizQL de Tableau** para realizar consultas visuales complejas sobre estas emociones, permitiendo identificar patrones afectivos y arcos de personalidad de forma dinámica.

---

## ☕ Entre Cafés y Frases: Seis voces, un juego

Como broche de oro, hemos creado un dashboard interactivo diseñado para que conectéis con los personajes de la misma forma que lo hicimos nosotras.
### ☕ [Haz clic aquí para abrir el Dashboard interactivo: "Entre cafés y frases"](https://public.tableau.com/views/Proyecto_Friends_17659698423520/Bienvenida?:language=es-ES&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

**OS ANIMAMOS A QUE LO PROBÉIS:**

> “Cada punto es una frase. Todas juntas dibujan la esencia de Friends: muchas voces, muchas personalidades, todo ocurriendo a la vez. Pasad el ratón por los puntos. Leed las frases. No busquéis contexto: solo sentid el tono. Después de escucharles hablar, ya no son seis desconocidos.”

---

## 🛠️ Ingeniería de Datos y Stack

* **Visualización:** Tableau Desktop / Public (Motor VizQL).
* **Inteligencia Artificial:** Modelos de **Hugging Face** (`sentiment_analyzer`).
* **Datasets:** `friends_episodes_v3`, `friends_info.csv` y `friends_quotes`.
* **Metodología:** Análisis Colaborativo / Pair Programming.

**NO VIMOS FRIENDS, PERO LOS DATOS SÍ.**

