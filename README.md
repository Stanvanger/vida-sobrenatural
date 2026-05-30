# 🏛️ Sitio Web Oficial - Iglesia Vida Sobrenatural Madrid

Este repositorio contiene el código fuente de la plataforma web oficial para la **Iglesia Vida Sobrenatural Madrid**. El proyecto ha sido diseñado específicamente para superar los desafíos técnicos y de comunicación que enfrentan las organizaciones comunitarias y religiosas en el entorno digital actual.

---

## 🧭 El Problema: Los Desafíos Digitales de las Iglesias

Muchas iglesias y comunidades locales sufren de "invisibilidad digital" debido a tres problemas críticos en sus sitios web:
1. **Falta de visibilidad local:** Las personas que buscan una iglesia o apoyo espiritual en su ciudad no los encuentran en Google porque las webs carecen de SEO técnico.
2. **Desconexión en buscadores de voz e Inteligencia Artificial:** Los asistentes de voz (Alexa, Google Assistant) y los nuevos buscadores de IA (ChatGPT, Perplexity) no logran leer ni interpretar correctamente los horarios de los cultos, eventos o preguntas frecuentes.
3. **Pérdida de interés al compartir enlaces:** Cuando los miembros comparten la web en redes sociales (WhatsApp, Instagram, Facebook), el enlace se ve vacío, sin imágenes atractivas ni descripciones claras, lo que reduce drásticamente los clics.

---

## 💡 La Solución: ¿Cómo lo resuelve este código?

Este proyecto soluciona estos problemas integrando una arquitectura de código moderna y optimizada en tres áreas clave:

### 📍 1. Posicionamiento Local e Inmediato (Local SEO)
*   **Implementación:** Se integraron etiquetas meta geográficas (`geo.region`, `geo.position`, `ICBM`) alineadas exactamente con la ubicación en la Calle Secoya 19, Madrid.
*   **Resultado:** Google indexa la iglesia de forma prioritaria para los usuarios que realizan búsquedas geolocalizadas en la Comunidad de Madrid.

### 🤖 2. Optimización para IA y Motores de Búsqueda (Gráfico de Conocimiento)
*   **Implementación:** Se estructuró todo el sitio utilizando **Schema JSON-LD** bajo el modelo `@graph`. Este unifica en un solo bloque de datos las entidades de *Church*, *FAQPage* y *Events*. Además, incluye la propiedad avanzada `speakable`.
*   **Resultado:** Los motores de búsqueda tradicionales e inteligencias artificiales entienden perfectamente qué es la iglesia, cuáles son sus horarios exactos (Domingos 10:00, Miércoles 19:30, Viernes 20:00) y pueden responder preguntas frecuentes directamente en los resultados de búsqueda por voz.

### 📱 3. Impacto Visual y Portabilidad (Open Graph & PWA)
*   **Implementación:** Configuración de protocolos `og:image` y `twitter:card` con dimensiones optimizadas (1200x800), junto con etiquetas de compatibilidad para Apple y aplicaciones web progresivas (PWA).
*   **Resultado:** Cada vez que alguien comparte el enlace en WhatsApp o redes sociales, se genera una tarjeta visual interactiva de alta conversión que invita a la comunidad a unirse.

---

## 🛠️ Tecnologías Clave Utilizadas

*   **HTML5 Semántico:** Para una accesibilidad e indexación óptimas.
*   **JSON-LD (Structured Data):** Estándar de la W3C para la comunicación con algoritmos e IA.
*   **Open Graph Protocol:** Para el control y optimización de contenido en redes sociales.
