# Galería Geométrica con Three.js

Una galería interactiva que muestra figuras geométricas 3D animadas con colores pastel. El proyecto presenta tres formas geométricas principales (prisma, tubo y orbe) tanto en una escena principal como en tarjetas informativas individuales.

## Descripción

Formas en Movimiento es una experiencia visual que combina gráficos 3D con diseño web moderno. Las figuras geométricas rotan suavemente en el espacio, creando una presentación elegante y minimalista con una paleta de colores pastel relajante.

## Características

- Tres figuras geométricas 3D animadas simultáneamente
- Escena principal con las tres formas en rotación continua
- Tarjetas individuales con vistas miniatura de cada figura
- Diseño responsive que se adapta a diferentes tamaños de pantalla
- Paleta de colores pastel suave y moderna
- Efectos hover en las tarjetas
- Animaciones fluidas a 60 FPS
- Descripciones informativas de cada figura

## Tecnologías

- HTML5 - Estructura
- CSS3 - Estilos y animaciones
- JavaScript (ES6) - Lógica y control de animaciones
- Three.js (r128) - Renderizado 3D
- Bootstrap 5.3.0 - Framework CSS

## Instalación

Clona este repositorio y abre el archivo index.html en tu navegador web.

No requiere instalación de dependencias. Three.js y Bootstrap se cargan desde CDN.

## Estructura de archivos

El proyecto contiene:
- index.html - Estructura HTML principal
- main.js - Lógica de renderizado y animaciones 3D
- style.css - Estilos y diseño visual
- README.md - Este archivo

## Figuras incluidas

### Prisma
Figura cúbica que representa equilibrio y orden. Color: Azul pastel.

### Tubo
Cilindro con estructura suave y continua. Color: Rosa suave.

### Orbe
Esfera que simboliza perfección y fluidez. Color: Celeste pastel.

## Características técnicas

### Sistema de renderizado múltiple
- Un renderizador principal para la escena superior
- Tres renderizadores individuales para las tarjetas
- Cuatro escenas Three.js independientes operando simultáneamente

### Animación
- Rotación continua en los ejes X e Y para todas las figuras
- Sincronización perfecta entre las vistas principal y miniatura
- RequestAnimationFrame para animaciones suaves

### Layout
- Sección superior ocupa el 60% del viewport
- Sección de tarjetas adaptable con flexbox
- Diseño responsive con redimensionamiento automático

## Paleta de colores

- Fondo principal: Rosa muy claro (#FDF1F1)
- Fondo tarjetas: Lavanda suave (#E8DFF5)
- Título: Púrpura (#7A5C99)
- Prisma: Azul pastel (#A7C7E7)
- Tubo: Rosa pastel (#F9C5D5)
- Orbe: Celeste pastel (#B9F3FC)
- Imagen tarjeta: Lila medio (#C8A2C8)
- Contenido tarjeta: Rosa claro (#F2BED1)
- Texto tarjeta: Púrpura oscuro (#4B296B)

## Geometrías utilizadas

- BoxGeometry (1x1x1) para el prisma
- CylinderGeometry (radio 0.5, altura 1, 32 segmentos) para el tubo
- SphereGeometry (radio 0.7, 32x16 segmentos) para el orbe

## Futuras mejoras

- Controles interactivos para rotar las figuras manualmente
- Más figuras geométricas (pirámide, toro, cono)
- Opciones para cambiar colores dinámicamente
- Información detallada expandible en cada tarjeta
- Animaciones personalizadas para cada figura
- Efectos de iluminación avanzados
- Texturas y materiales más complejos
- Modo oscuro alternativo

## Contribuciones

Las contribuciones son bienvenidas. Si deseas mejorar este proyecto:

1. Fork el repositorio
2. Crea una rama para tu feature
3. Commit tus cambios
4. Push a la rama
5. Abre un Pull Request


## Autor

Claudia Lorena Cerquera Gonzalez

