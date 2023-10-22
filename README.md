# Práctica Big Data Arquitectura

"TCG Price Insight" es un proyecto diseñado para proporcionar información actualizada, análisis y proyecciones sobre los precios de Trading Card Games (TCG) coleccionables. Esta plataforma se basa en el concepto de "Data as a Service" (DAaaS), brindando a los usuarios suscritos acceso a datos valiosos y oportunidades de inversión en el mundo de los coleccionables.

## Objetivos del Proyecto 🎯

- 📊 Recopilar datos precisos y oportunos de diversas fuentes de TCG coleccionables.
- 📈 Ofrecer análisis basados en datos históricos para tomar decisiones informadas.
- 🕒 Proporcionar información actualizada en tiempo real a través de una plataforma web.
- 🌐 Desarrollar una interfaz de usuario amigable para una experiencia de usuario sin problemas.

## Modelo de Negocio 💼

El modelo de negocio se basa en las suscripciones de los usuarios. Los suscriptores tendrán acceso a datos actualizados y análisis detallados sobre precios de coleccionables. Además, se puede explorar oportunidades de ingresos adicionales a través de publicidad dirigida y la venta de datos agregados.

- 💰 Tarifas de suscripción recurrentes mensuales o anuales con diferentes niveles de acceso.
- 🎯 Exploración de oportunidades de publicidad dirigida y colaboraciones con socios del mercado de cartas coleccionables.

## Oportunidades de Crecimiento 🚀

- 📚 Ampliación de la base de datos para incluir más tarjetas y fuentes de datos.
- 🧮 Desarrollo de algoritmos avanzados para análisis de datos más precisos.
- 🌍 Exploración de otros mercados de coleccionables además de TCG.
- 🤝 Colaboraciones estratégicas con tiendas en línea y sitios de subastas.
- 🏆 Oferta de suscripciones premium con características exclusivas.
- 📱 Desarrollo de aplicaciones móviles para acceder a la información sobre la marcha.

## Definición DAaaS

La estrategia para el Data Analytics as a Service (DAaaS) se centra en proporcionar una plataforma robusta y completa para el análisis de cartas coleccionables. El catálogo de servicios incluye:

- 📊 **Incorporación de Datos**
- 🔄 **Transformación de Datos**
- 🧰 **Bibliotecas de Herramientas Analíticas**
- 🚀 **Administración y actualización continua de crawlers y scrapers**
- 🛡️ **Mantenimiento y escalabilidad de la infraestructura en la nube**
- 🔒 **Políticas de seguridad para proteger los datos**
- 📊 **Monitoreo constante para identificar y resolver problemas**
- 💰 **Gestión de costos eficiente**

## Arquitectura DAaaS 🏗️

La arquitectura del DAaaS se basa en componentes clave:

- 🌐 **Página Web Interactiva:** Una interfaz de usuario intuitiva que permite a los usuarios explorar cartas, ver precios y estadísticas, y acceder a información valiosa.
- ☁️ **Google Cloud Platform (GCP):** La plataforma se aloja en GCP, lo que garantiza escalabilidad, seguridad y confiabilidad.
- 🕒 **Datos en Tiempo Real:** Ofrecer datos actualizados al instante, incluyendo análisis de precios, comentarios de usuarios y proyecciones.
- 🔍 **Fuentes de Datos Confiables:** Utilizar web crawlers y algoritmos de recopilación de datos para mantener la información precisa y actualizada.
- 📊 **Incorporación de Datos:** Recopilación automática de información de cartas, precios y comentarios de usuarios desde fuentes en línea, utilizando web scrapers y crawlers programados.
- 🧹 **Limpieza de Datos:** Procesamiento y transformación de datos para garantizar la calidad y precisión de la información recopilada.
- 🔄 **Transformación de Datos:** Preparación de datos para su análisis, incluyendo la estructuración de la información y la creación de conjuntos de datos coherentes.
- 📚 **Datapedias:** Creación de repositorios de datos y metadatos para facilitar la comprensión de los datos recopilados.
- 🧰 **Bibliotecas de Herramientas Analíticas:** Proporcionar acceso a herramientas de análisis de datos, visualización y generación de proyecciones de precios.

## DAaaS Operating Model Design 🛠️

🕷️ **Crawlers y Scrapers:** Se utiliza crawlers y scrapers para recopilar información de sitios de subastas y comentarios. Esta recopilación de datos es fundamental para proporcionar información precisa y actualizada.

📋 **Almacenamiento en Elasticsearch:** Toda la información recopilada se almacena y se busca eficientemente en Elasticsearch. Esto garantiza una búsqueda y recuperación de datos rápida y precisa.

💌 **Transmisión en Tiempo Real con Kafka:** Se utiliza Kafka para transmitir datos en tiempo real, lo que nos permite mantener a nuestros usuarios constantemente actualizados con información en tiempo real.

🧹 **Limpieza y Conversión de Datos:** Se realiza la limpieza y conversión de datos para garantizar la calidad y consistencia de la información. Además, convertimos los datos en formato CSV para facilitar su análisis.

☁️ **Almacenamiento en Cloud Storage:** Los datos procesados se almacenan en Cloud Storage, una solución escalable que garantiza la disponibilidad y durabilidad de los datos.

📊 **Visualización de Datos en la Página Web:** Se presentan los datos de manera efectiva a los usuarios a través de una página web interactiva. Se aplican herramientas de visualización de datos efectivas y amigables para proporcionar a los usuarios una experiencia de usuario sin problemas.

Este flujo de trabajo permite ofrecer a los usuarios información precisa, actualizada y visualmente atractiva sobre los precios y tendencias de los TCG coleccionables.






## Diagrama

![image](https://github.com/Robertogag/Big-Data-Arquitectura-KeepCoding/assets/137840110/afac598f-4fc4-4a09-9319-ac059efa57bb)





