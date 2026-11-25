# Números Reales — Presentación Web

Presentación interactiva de **Matemática · Unidad 01: Números Reales**  
(estructura, orden y completitud de la recta), con estética inspirada en el clásico *Álgebra de Baldor*:  
tipografía monoespaciada, fondo hueso, texto negro y títulos en rojo carmesí.

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

## Estructura de archivos

| Archivo | Descripción |
|---|---|
| `index.html` | Estructura HTML, contenido de las 13 láminas y JavaScript de navegación. |
| `baldor.css` | Hoja de estilos: fondo hueso (`#EDE8DC`), tipografía monoespaciada (JetBrains Mono), texto negro (`#1A1A1A`), títulos en carmesí (`#CC0000`), ornamentos dorados en header/footer. |
| `README.md` | Este documento. |

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub (p. ej. `numeros-reales`).
2. Sube los tres archivos (`index.html`, `baldor.css`, `README.md`) a la raíz.
3. Ve a **Settings → Pages → Source**: rama `main`, carpeta `/ (root)`, pulsa **Save**.
4. En uno o dos minutos estará disponible en:
   `https://<tu-usuario>.github.io/numeros-reales/`

## Notas técnicas

- `index.html` carga los estilos con `<link rel="stylesheet" href="baldor.css">`.
- Ambos archivos deben estar en la misma carpeta.
- Dependencias externas (CDN, en `baldor.css`): JetBrains Mono (Google Fonts) y Material Symbols.
- No requiere compilación; funciona abriendo `index.html` directamente en el navegador.
