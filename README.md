# Práctica Big Data Arquitectura

## Objetivos del Proyecto
🌟 Dado el gran número de coleccionistas y entusiastas en todo el mundo, la plataforma de análisis de cartas coleccionables Pokémon y Yu-Gi-Oh tiene un amplio público objetivo.

📈 Ofrecer datos en tiempo real, análisis precisos y proyecciones de precios como diferenciador clave.

🌐 Potencial de expansión a otros juegos de cartas coleccionables.

💼 Transformar el acceso a la información en una fuente de ingresos a través de suscripciones.

## Modelo de Negocio
💰 Tarifas de suscripción recurrentes mensuales o anuales con diferentes niveles de acceso.

🎯 Exploración de oportunidades de publicidad dirigida y colaboraciones con socios del mercado de cartas coleccionables.

## Oportunidades de Crecimiento
🔍 **Ampliación de Contenido:** Añadir más juegos de cartas coleccionables a la plataforma.

🌎 **Expansión Global:** Llegar a audiencias internacionales y localizadas.

🔌 **Integración de API:** Ampliar servicios a través de integraciones con otras plataformas y servicios.

📱 **Desarrollo de Aplicaciones Móviles:** Lanzar aplicaciones móviles para un acceso más conveniente.

## Definición DAaaS
La estrategia para el Data Analytics as a Service (DAaaS) se centra en proporcionar una plataforma robusta y completa para el análisis de cartas coleccionables. El catálogo de servicios incluye:

1. 📊 **Incorporación de Datos:** Recopilación automática de información de cartas, precios y comentarios de usuarios desde fuentes en línea, utilizando web scrapers y crawlers programados.
2. 🧹 **Limpieza de Datos:** Procesamiento y transformación de datos para garantizar la calidad y precisión de la información recopilada.
3. 🔄 **Transformación de Datos:** Preparación de datos para su análisis, incluyendo la estructuración de la información y la creación de conjuntos de datos coherentes.
4. 📚 **Datapedias:** Creación de repositorios de datos y metadatos para facilitar la comprensión de los datos recopilados.
5. 🧰 **Bibliotecas de Herramientas Analíticas:** Proporcionar acceso a herramientas de análisis de datos, visualización y generación de proyecciones de precios.

## Arquitectura DAaaS
La arquitectura del DAaaS se basa en componentes clave:

1. 🌐 **Página Web Interactiva:** Una interfaz de usuario intuitiva que permite a los usuarios explorar cartas, ver precios y estadísticas, y acceder a información valiosa.
2. ☁️ **Google Cloud Platform (GCP):** La plataforma se aloja en GCP, lo que garantiza escalabilidad, seguridad y confiabilidad.
3. 🕒 **Datos en Tiempo Real:** Ofrecer datos actualizados al instante, incluyendo análisis de precios, comentarios de usuarios y proyecciones.
4. 🔍 **Fuentes de Datos Confiables:** Utilizar web crawlers y algoritmos de recopilación de datos para mantener la información precisa y actualizada.

## DAaaS Operating Model Design
### Recopilación de Datos y Actualización
#### Web Scraper y Crawler:
- 🐍 Implementa web scrapers y crawlers programados con Python.
- 📌 Extraen información desde fuentes en línea como sitios web de subastas y foros de discusión.
- 🔄 Programados para ejecutarse automáticamente cada 12 horas utilizando Cloud Functions y un Scheduler.

### Almacenamiento de Datos y Procesamiento
#### Google Cloud Storage:
- 📂 Los datos recopilados por los crawlers se almacenan en Google Cloud Storage, actuando como una ubicación centralizada y escalable.

### Análisis de Sentimientos y Comentarios
#### Web Scraper para Comentarios:
- 🔍 Se utiliza un web scraper adicional para recopilar comentarios de usuarios desde foros y redes sociales.
#### Elasticsearch:
- 📋 Los comentarios y opiniones de usuarios se almacenan en Elasticsearch.

### Interacción con Usuarios y Actualización en Tiempo Real
#### Página Web:
- 🌐 La página web interactúa con BigQuery, Google Cloud Storage para proporcionar a los usuarios acceso a datos, análisis y proyecciones en tiempo real.
#### Kafka:
- 💌 Kafka se encarga de transmitir datos en tiempo real entre los diferentes componentes de la arquitectura, asegurando información actualizada al instante.

### Programación y Automatización
#### Scheduler:
- 🕒 Se programa un Scheduler para ejecutar tareas periódicas, como la actualización de datos de los crawlers desde fuentes en línea cada 12 horas y el análisis de sentimientos en los comentarios de usuarios diariamente.




## Diagrama

![image](https://github.com/Robertogag/Big-Data-Arquitectura-KeepCoding/assets/137840110/ba6c1321-432d-48bf-84c4-c0bdc3cb0d37)




