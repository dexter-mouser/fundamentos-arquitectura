# Fundamentos de arquitectura

Resumen propio, capítulo por capítulo, de *Fundamentals of Software Architecture* (2.ª edición, 2025), de Mark Richards y Neal Ford.

**Verlo en línea:** [dexter-mouser.github.io/fundamentos-arquitectura](https://dexter-mouser.github.io/fundamentos-arquitectura/)

## Qué incluye

- Los 27 capítulos agrupados en sus tres partes, cada uno con su idea central y el porqué de sus reglas.
- Ejemplos propios en JavaScript donde ayudan: connascencia, funciones de aptitud, capas, monolito modular, tubería, microkernel, eventos, microservicios y un registro de decisión (ADR).
- Una tabla para traducir preocupaciones del negocio a características y una matriz de riesgo.
- Una lista de chequeo para revisar un diseño.

## Cómo verlo

- **En línea:** se publica con GitHub Pages desde la rama `main`.
- **En local:** no necesita instalación. Abre `index.html` en cualquier navegador.

## Estructura

| Archivo | Qué es |
| --- | --- |
| `index.html` | El resumen completo, con el CSS y el JavaScript dentro. |
| `404.html` | Página de error de GitHub Pages, con enlace al resumen. |

## Cómo funciona

- Una sola página HTML, sin dependencias. Solo carga desde internet las fuentes de Google Fonts; sin conexión usa las del sistema.
- Se adapta al tema claro u oscuro del sistema y al ancho del móvil.
- Las marcas de la lista de chequeo se guardan en el `localStorage` del navegador y no salen de él.

## Aviso

El resumen y los ejemplos están escritos con palabras propias y no reproducen el texto del libro. Los capítulos nuevos de la 2.ª edición (11, 20 y 26) se resumen con lo que se sabe de ellos públicamente. Para el contenido completo, consulta la obra original.
