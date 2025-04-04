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

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue primero para discutir los cambios que te gustaría hacer.

## Licencia

Este proyecto está bajo la Licencia MIT. 