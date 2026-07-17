---
name: Automotive Precision System
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#44474d'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#75777e'
  outline-variant: '#c5c6cd'
  surface-tint: '#515f78'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#0d1c32'
  on-primary-container: '#76849f'
  inverse-primary: '#b9c7e4'
  secondary: '#505f76'
  on-secondary: '#ffffff'
  secondary-container: '#d0e1fb'
  on-secondary-container: '#54647a'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#341100'
  on-tertiary-container: '#d95f00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#b9c7e4'
  on-primary-fixed: '#0d1c32'
  on-primary-fixed-variant: '#39475f'
  secondary-fixed: '#d3e4fe'
  secondary-fixed-dim: '#b7c8e1'
  on-secondary-fixed: '#0b1c30'
  on-secondary-fixed-variant: '#38485d'
  tertiary-fixed: '#ffdbca'
  tertiary-fixed-dim: '#ffb690'
  on-tertiary-fixed: '#341100'
  on-tertiary-fixed-variant: '#783200'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  title-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 32px
  xl: 48px
  gutter: 20px
  margin-mobile: 16px
  margin-desktop: 40px
---

## Marca y Estilo

El sistema de diseño está orientado a la eficiencia operativa y la claridad visual dentro del entorno de alta exigencia de una agencia automotriz. La personalidad de la marca es **profesional, robusta y tecnológica**, transmitiendo confianza tanto al personal de almacén como a la gerencia administrativa.

El estilo visual combina el **minimalismo moderno** con toques de **glassmorphism funcional**. Se prioriza la legibilidad y la reducción de la fatiga cognitiva mediante el uso generoso de espacios en blanco (aire) y una jerarquía visual estricta. Los elementos de cristal se reservan para paneles laterales de navegación o filtros flotantes, permitiendo que la interfaz principal se mantenga sólida y confiable. El objetivo es evocar una sensación de orden sistemático y precisión mecánica.

## Colores

La paleta está diseñada para equilibrar la autoridad con la utilidad inmediata:

*   **Azul Medianoche Profundo (#0A192F):** Color primario. Se utiliza para la navegación principal, encabezados críticos y elementos de marca que requieren peso visual.
*   **Gris Acero (#64748B):** Color secundario. Aplicado en tipografía secundaria, iconos de estado neutro y bordes sutiles para definir la estructura sin sobrecargar.
*   **Naranja Vibrante (#F97316):** Color de acento y acción. Reservado exclusivamente para botones de "Call to Action" (CTA), alertas de stock bajo y estados que requieren atención inmediata del usuario.
*   **Fondo Neutro (#F8FAFC):** Un gris blanquecino ultra-claro que reduce el contraste agresivo y permite que las sombras sutiles generen profundidad de manera efectiva.

## Tipografía

Se utiliza **Inter** por su excepcional legibilidad en pantallas de alta densidad de datos, común en la gestión de inventarios.

*   **Jerarquía:** Los títulos utilizan pesos semibold (600) para destacar secciones de piezas o categorías de vehículos. 
*   **Legibilidad:** El cuerpo de texto mantiene un interlineado generoso para facilitar la lectura de códigos de partes (SKU) y descripciones técnicas.
*   **Micro-copia:** Las etiquetas (labels) utilizan un peso medium (500) y, en ocasiones, mayúsculas con espaciado ligero para diferenciar metadatos de los valores de entrada.

## Layout y Espaciado

El sistema emplea un modelo de **rejilla fluida** basado en una unidad base de 4px, optimizando la densidad de información sin sacrificar la claridad.

*   **Escritorio (Desktop):** Rejilla de 12 columnas con márgenes laterales de 40px. El contenido se organiza en tarjetas que agrupan información relacionada (ej. detalles de la refacción, compatibilidad de modelos).
*   **Móvil:** Rejilla de 4 columnas con márgenes de 16px. Se prioriza el escaneo vertical y el uso de gestos laterales para tablas de datos extensas.
*   **Ritmo Vertical:** Se aplica un espaciado de 24px entre bloques de contenido principales para mantener el "aire" solicitado y evitar la saturación visual.

## Elevación y Profundidad

La profundidad se comunica mediante una combinación de capas tonales y efectos de transparencia:

*   **Capas Base:** El fondo principal es plano. Las tarjetas de contenido utilizan un blanco puro (#FFFFFF) con un borde de 1px en gris acero muy suave (opacidad 10%).
*   **Sombras Ambientales:** Se aplican sombras muy difusas y de baja opacidad (Color: Azul Medianoche, Opacidad: 4%, Blur: 12px) para separar las tarjetas del fondo.
*   **Glassmorphism:** Los paneles de navegación lateral y los modales utilizan un desenfoque de fondo (backdrop-filter: blur(12px)) con un fondo blanco al 70% de opacidad. Esto permite mantener el contexto visual de la lista de refacciones mientras se interactúa con filtros o detalles.

## Formas

El lenguaje de formas es amigable pero estructurado, utilizando bordes redondeados suaves para suavizar la naturaleza técnica de la plataforma.

*   **Contenedores Estándar:** Radio de 0.5rem (8px) para tarjetas de inventario y cuadros de búsqueda.
*   **Elementos Grandes:** Las secciones de dashboard o paneles laterales utilizan un radio de 1rem (16px) para enfatizar la jerarquía de agrupación.
*   **Interactivos:** Los botones mantienen el estándar de 8px para proyectar una imagen de software moderno y profesional.

## Componentes

*   **Botones:** El botón primario es de color Naranja Vibrante con texto blanco. El estado *hover* oscurece ligeramente el naranja. Los botones secundarios usan Gris Acero con estilo "ghost" (borde y texto, sin fondo).
*   **Entradas de Datos (Inputs):** Bordes sutiles en Gris Acero. Al ganar el foco, el borde cambia a Azul Medianoche con un resplandor (glow) exterior muy suave de 2px.
*   **Chips de Estado:** Pequeñas píldoras redondeadas para indicar "En Stock" (verde suave), "Agotado" (rojo suave) o "Pedido en Camino" (azul suave), siempre con texto en alto contraste.
*   **Tarjetas de Producto:** Incluyen una imagen pequeña del componente, nombre de la refacción, SKU en negrita y el precio. El fondo es blanco puro con bordes redondeados de nivel 2.
*   **Tablas de Inventario:** Alternancia de filas con colores neutros muy tenues. El encabezado de la tabla es Azul Medianoche con texto blanco para anclar visualmente los datos.
*   **Buscador Global:** Situado en la parte superior, con glassmorphism ligero para sugerir que "flota" sobre el contenido principal.