# Números Reales — Presentación Web

Presentación interactiva de **Matemática · Unidad 01: Números Reales** (estructura, orden y completitud de la recta), con estética clásica inspirada en el *Álgebra de Baldor*: pergamino, tinta sepia, dorado envejecido, rojo carmesí y ornamentos tipográficos de libro académico.

## Contenido (13 láminas)

1. Portada
2. Frontispicio ornamental (Álgebra · Números Reales)
3. La Recta Real
4. Taxonomía de los Números (ℕ ⊂ ℤ ⊂ ℚ ⊂ ℝ)
5. Análisis Decimal y Fraccionario
6. Construcción Geométrica de √2
7. Orden Denso
8. Un Cuerpo Ordenado
9. Tramos Continuos (intervalos)
10. El Valor Absoluto Mide Distancia
11. Radicales y Notación Científica
12. Completitud
13. Síntesis

## Controles

| Acción | Tecla / botón |
|---|---|
| Siguiente / anterior | → / ← (o barra espaciadora) |
| Primera / última | Inicio / Fin |
| Pantalla completa | F |
| Índice de láminas | Botón **MENÚ** |
| Reproducción automática | Botón **AUTO** |

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `numeros-reales`).
2. Sube `index.html`, `baldor.css` y `README.md` a la raíz del repositorio (botón **Add file → Upload files**).
3. Ve a **Settings → Pages**.
4. En **Source** elige **Deploy from a branch**, rama `main`, carpeta `/ (root)` y pulsa **Save**.
5. En uno o dos minutos la presentación estará en:
   `https://<tu-usuario>.github.io/numeros-reales/`

## Notas técnicas

## Estructura de archivos

| Archivo | Descripción |
|---|---|
| `index.html` | Estructura, contenido de las 13 láminas y JavaScript de navegación. |
| `baldor.css` | Sistema de estilos "Álgebra de Baldor": variables de paleta (pergamino, sepia, dorado, carmesí), tipografía, marcos ornamentales, tablas, fórmulas y diseño responsivo. |
| `README.md` | Este documento. |

## Notas técnicas

- `index.html` enlaza la hoja de estilos externa con `<link rel="stylesheet" href="baldor.css">`; ambos archivos deben estar en la misma carpeta.
- Para cambiar la paleta basta con editar las variables de `:root` en `baldor.css`.
- Dependencias externas por CDN (importadas desde `baldor.css`): Google Fonts (EB Garamond, JetBrains Mono) y Material Symbols.
- No requiere compilación; también funciona abriendo `index.html` directamente en el navegador.
