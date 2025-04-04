# Collection Categories Section

Una sección dinámica y moderna para mostrar categorías de colección con efectos visuales atractivos y alta personalización.

## Características

### Diseño
- Grid responsive de 3 columnas (se adapta a 2 y 1 columna en tablets y móviles)
- Imágenes en formato 9:16 para una presentación visual consistente
- Overlay con gradiente para mejor legibilidad del texto
- Espaciado optimizado entre elementos

### Efectos de Hover
- Animación suave del título y subtítulo
- El título se desplaza hacia arriba al hacer hover
- El subtítulo aparece con fade in
- Ambos elementos quedan centrados verticalmente
- Transiciones suaves de 0.3s

### Personalización del Encabezado
- Título principal configurable
- Subtítulo opcional
- Opciones de alineación (izquierda, centro, derecha)
- Tamaños de título (pequeño, mediano, grande)
- Estilos de texto:
  - Normal
  - Mayúsculas
  - Negrita
  - Negrita + Mayúsculas
- Línea divisoria que se extiende de borde a borde

### Efectos de Texto
- Sombra de texto opcional para mejor legibilidad
- Intensidad de sombra optimizada para fondos claros y oscuros
- Se aplica tanto al título como al subtítulo

## Uso

1. Agregar la sección al tema:
```liquid
{% section 'collection-categories' %}
```

2. Configurar en el customizer de Shopify:
   - Establecer título y subtítulo de la sección
   - Ajustar estilo y formato del texto
   - Activar/desactivar sombras de texto
   - Agregar bloques para cada categoría

3. Para cada bloque de categoría:
   - Seleccionar una colección
   - Opcionalmente subir una imagen personalizada
   - Si no se sube imagen, se usa la imagen destacada de la colección
   - Configurar título y subtítulo de la categoría

## Estructura de Archivos

- `sections/collection-categories.liquid`: Template principal y schema
- `assets/section-collection-categories.css`: Estilos y animaciones

## Personalización Avanzada

Los siguientes elementos son personalizables a través del código:

### CSS
- Tamaños de fuente
- Velocidad de las animaciones
- Intensidad del gradiente
- Espaciado entre elementos
- Intensidad de la sombra de texto

### Liquid
- Formato de las imágenes
- Estructura del grid
- Comportamiento responsive

## Ejemplo de Configuración

```json
{
  "title": "SHOP BY CATEGORY",
  "subtitle": "Discover our collections",
  "text_align": "left",
  "title_size": "medium",
  "title_style": "uppercase",
  "enable_text_shadow": true
}
```

## Compatibilidad

- Shopify 2.0+
- Navegadores modernos con soporte para:
  - CSS Grid
  - Flexbox
  - Transitions
  - Transform
  - Opacity

## Mejores Prácticas

1. Imágenes:
   - Usar imágenes de alta calidad
   - Mantener la relación de aspecto 9:16
   - Optimizar el peso de las imágenes

2. Texto:
   - Mantener títulos concisos
   - Usar subtítulos descriptivos pero breves
   - Asegurar buen contraste con el fondo

3. Rendimiento:
   - Las imágenes se cargan de forma lazy
   - Las transiciones están optimizadas
   - El código está minificado

## Soporte

Para preguntas o personalización adicional, contactar a:
[daniel@section.store](mailto:daniel@section.store) 