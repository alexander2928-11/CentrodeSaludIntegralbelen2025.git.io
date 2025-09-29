# Instrucciones para agentes AI en CentrodeSaludIntegralbelen2025.git.io

## Descripción general
Este proyecto es un sitio web estático para el Centro de Salud Integral "BELÉN". El código fuente principal se encuentra en `mi proyecto/Untitled-1.html` y los estilos en `mi proyecto/styles.css`. El sitio utiliza una imagen de fondo (`AdobeStock_512307383_Preview.jpeg`) y fuentes de Google Fonts.

## Estructura y convenciones
- **HTML principal:** Todo el contenido y la estructura de la página están en `Untitled-1.html`. El archivo es extenso y contiene navegación fija, secciones informativas y estilos embebidos.
- **Estilos:** Se usan tanto estilos embebidos en el HTML como un archivo CSS externo. El CSS externo define el fondo y tipografía global.
- **Imágenes:** Las imágenes se almacenan localmente en la carpeta raíz del proyecto (`mi proyecto/`).
- **Fuentes:** Se utiliza la fuente 'Inter' desde Google Fonts.
- **Idioma:** Todo el contenido está en español.

## Patrones y recomendaciones
- **Diseño:** El sitio emplea una paleta de colores definida en variables CSS (`:root`). Mantén la coherencia usando estas variables para nuevos estilos.
- **Navegación:** La barra de navegación es fija y utiliza `backdrop-filter` para desenfoque. Si agregas nuevas secciones, enlázalas desde la navegación.
- **Responsive:** El diseño usa `meta viewport` y estilos flexibles. Asegúrate de que cualquier cambio preserve la adaptabilidad móvil.
- **Imágenes:** Usa rutas relativas para imágenes y recursos.
- **Accesibilidad:** Mantén etiquetas semánticas y atributos `alt` en imágenes.

## Flujos de trabajo
- **No hay scripts de build ni pruebas automáticas.**
- **Desarrollo:** Edita directamente los archivos HTML y CSS. Visualiza los cambios en un navegador local.
- **No hay dependencias externas aparte de Google Fonts.**

## Ejemplo de patrón
```html
<!-- Ejemplo de sección con variable de color -->
<section style="background: var(--color-gray-100);">
  <h2>Servicios</h2>
  <!-- ... -->
</section>
```

## Archivos clave
- `mi proyecto/Untitled-1.html`: Estructura y contenido principal.
- `mi proyecto/styles.css`: Estilos globales y fondo.
- `mi proyecto/README.md`: Breve descripción del proyecto.

## Recomendaciones para agentes AI
- Mantén la coherencia visual y semántica.
- Usa las variables CSS existentes.
- Documenta cambios relevantes en el README si modificas la estructura.
- No agregues frameworks ni dependencias externas sin consulta.

---
¿Falta información sobre flujos, convenciones o patrones? Indica qué aspectos necesitas aclarar para mejorar estas instrucciones.