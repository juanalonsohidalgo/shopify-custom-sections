# Shopify Custom Sections

Colección de secciones personalizadas para temas de Shopify, diseñadas para mejorar la experiencia de usuario y la presentación de productos.

## Technical Highlights Section

Una sección dinámica y moderna para mostrar características técnicas o beneficios de productos con un diseño limpio y funcional.

### Características

- **Diseño Responsive**: Se adapta perfectamente a todos los dispositivos
- **Visualización Grid**: Layout de 3 columnas en desktop, 2 en tablet y 1 en móvil
- **Expansión de Contenido**: 
  - Muestra 3 líneas de texto inicialmente
  - Botón "Leer más" para expandir el contenido
  - Botón global "Ver menos" para colapsar todo
- **Iconos Personalizables**: Soporte para imágenes de 60x60px
- **Títulos en Bold**: Destacan las características principales
- **Línea Divisoria**: Separa elegantemente el título de la sección del contenido

### Uso

1. Agregar la sección a tu tema:
   ```liquid
   {% section 'technical-highlights' %}
   ```

2. Configurar en el customizer de Shopify:
   - Título de la sección (opcional)
   - Agregar bloques para cada highlight
   - Configurar imagen, título y descripción para cada bloque

### Estructura de Archivos

- `sections/technical-highlights.liquid`: Template principal
- `assets/section-technical-highlights.css`: Estilos de la sección

### Personalización

Los siguientes elementos son personalizables:
- Número de columnas
- Altura del contenido colapsado
- Colores y tipografía
- Espaciado entre elementos
- Estilo de los botones

### Preview

[Vista previa de la sección Technical Highlights]

### Requisitos

- Tema de Shopify 2.0+
- Soporte para secciones dinámicas

---

## Hero Banner Section

Una potente sección de banner principal con múltiples opciones de personalización para crear impactantes héroes visuales.

### Características

- **Posicionamiento Flexible**: 
  - Control de posición vertical (arriba, centro, abajo)
  - Control de posición horizontal (izquierda, centro, derecha)
  - Alineación de texto personalizable
- **Personalización Visual Completa**:
  - Tamaño, color y sombra para títulos y subtítulos
  - Múltiples estilos de botón (sólido, contorno, transparente)
  - Control de opacidad para contenido y overlay
- **Soporte para Media**:
  - Imágenes de fondo de alta resolución
  - Videos de YouTube y Vimeo
  - Integración de logo con separador vertical
- **Diseño Responsive**:
  - Optimizado para todos los dispositivos
  - Ajuste automático de tamaños y espaciados

### Uso

1. Agregar la sección a tu tema:
   ```liquid
   {% section 'hero-banner' %}
   ```

2. Configurar en el customizer de Shopify:
   - Fondo (imagen o video)
   - Posición y alineación del contenido
   - Textos, colores y estilos
   - Opciones de botón

### Estructura de Archivos

- `sections/hero-banner.liquid`: Template principal
- `assets/section-hero-banner.css`: Estilos de la sección

### Personalización

Opciones de personalización incluyen:
- Colores de texto, botones y overlay
- Tamaños de fuente para encabezados
- Efectos de sombra para mejor legibilidad
- Estilos de botón
- Ancho del área de contenido
- Opacidad de elementos

### Preview

[Vista previa de la sección Hero Banner]

---

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue primero para discutir los cambios que te gustaría hacer.

## Licencia

Este proyecto está bajo la Licencia MIT. 