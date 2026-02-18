## Etapa 2: Refactorizacion y CSS Avansado

# Proyecto de Maquetación: Cozy Corner (Coworking)

Este proyecto forma parte de mi formación técnica en desarrollo web. No es solo una práctica visual, sino un ejercicio de resolución de problemas estructurales usando CSS moderno.

## 🚀 Evolución y Mejoras Técnicas

En esta etapa, decidí refactorizar la estructura inicial para lograr un código más limpio, escalable y profesional. Los cambios clave fueron:

* **Arquitectura con CSS Grid:** Implementé un sistema de rejilla para el Hero, permitiendo que la imagen y el bloque de contenido se solapen de forma elegante sin recurrir a posicionamientos forzados o "trucos" que rompen el flujo del documento.
* **Diseño Fluido con `clamp()`:** En lugar de tamaños fijos, utilicé funciones matemáticas de CSS para que la tipografía se adapte orgánicamente al tamaño de la pantalla, mejorando la experiencia de lectura sin saturar el código con reglas repetitivas.
* **Metodología BEM:** Organicé las clases siguiendo el estándar *Block-Element-Modifier*. Esto hace que el código sea fácil de leer para otros desarrolladores y mucho más sencillo de mantener a futuro.
* **Efectos Visuales Avanzados:** Apliqué *Glassmorphism* mediante `backdrop-filter` y fondos semi-transparentes, logrando una estética moderna y limpia en el bloque principal.
* **Optimización de Recursos:** Limpié el archivo HTML eliminando llamadas innecesarias a fuentes externas y optimicé el renderizado de imágenes mediante la propiedad `object-fit`.

## 🛠️ Tecnologías utilizadas

* HTML5 (Semántico)
* CSS3 (Custom Properties, Grid, Flexbox)
* Google Fonts

---
*Este repositorio refleja mi proceso de aprendizaje constante y mi compromiso con la creación de interfaces web sólidas y bien estructuradas.*

## Etapa 1: Estructura Inicial.

🏢 Cozy Corner - Coworking Landing Page

Landing page moderna para una agencia de Coworking. Este proyecto se enfoca en el uso de maquetación avanzada y diseño de interfaces limpias.

![Vista previa del Proyecto](../src/img/Previwe.png)

🚀 Conceptos Técnicos Aplicados
CSS Grid: Utilizado para la estructura global de la página, organizando el Nav, el Main y la Section en un sistema de filas y áreas.

Position Absolute: Implementado para lograr la superposición del cuadro de texto principal sobre la imagen del Hero, permitiendo un diseño dinámico.

Glassmorphism: Aplicado mediante filtros de desenfoque (blur) y transparencias en el contenedor central para lograr un efecto visual de "vidrio" moderno.

Layout Adaptativo: Uso de márgenes porcentuales negativos y unidades flexibles para posicionar elementos complejos sin romper el flujo de la página.

🛠️ Tecnologías y Recursos
HTML5: Estructura semántica.

CSS3: Grid, Flexbox y animaciones básicas.

Fuentes: Poppins y Playfair Display SC (Google Fonts).

✒️ Autor
Proyecto realizado como estudiante de Conquerblock, aplicando conocimientos de desarrollo web y automatización.