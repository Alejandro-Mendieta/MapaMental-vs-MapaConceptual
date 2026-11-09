# README.md

```markdown
# Mapa Conceptual vs. Mapa Mental

Presentación web interactiva que compara el **mapa conceptual** y el **mapa mental**: origen, características, similitudes, diferencias y aplicaciones prácticas.

**Autor:** Alejandro Mendieta

---

## Contenido

La presentación consta de **6 diapositivas**:

1. **Portada** — Título, subtítulo y autor.
2. **Mapa Conceptual** — Definición, origen (Novak, 1970s), características, ejemplo visual (el agua) y uso común.
3. **Mapa Mental** — Definición, origen (Buzan, 1974), características, ejemplo visual (proyecto final) y uso común.
4. **Similitudes** — Cuatro puntos en común entre ambas herramientas.
5. **Diferencias Clave** — Tabla comparativa con 5 criterios: enfoque, estructura, conexiones, verificabilidad y origen.
6. **Cuándo usar cada uno** — Aplicaciones prácticas de cada herramienta.

---

## Características técnicas

- **HTML + Tailwind CSS** (vía CDN) + **Lucide Icons**.
- **Modo oscuro / claro** con persistencia en `localStorage`.
- **Navegación** por botones, teclado, swipe táctil y vista general (grid).
- **Persistencia** de la diapositiva actual.
- **Exportación a PDF** mediante impresión (`Ctrl/Cmd + P`).
- **Pantalla completa**.
- **Diseño responsive** (móvil, tablet, escritorio).
- **Accesibilidad básica**: `aria-label`, `role`, focus visible.

---

## Atajos de teclado

| Tecla | Acción |
|-------|--------|
| `←` / `PageUp` | Diapositiva anterior |
| `→` / `Espacio` / `PageDown` | Diapositiva siguiente |
| `G` | Abrir vista general (grid) |
| `F` | Alternar pantalla completa |
| `Esc` | Cerrar vista general |

---

## Estructura del proyecto

```
.
└── index.html      # Archivo único autocontenido (HTML + CSS + JS)
```

No requiere instalación ni build. Solo abre `index.html` en un navegador moderno.

---

## Uso

1. Descarga o clona el archivo `index.html`.
2. Ábrelo en cualquier navegador (Chrome, Firefox, Edge, Safari).
3. Navega con los botones inferiores, el teclado o deslizando en móvil.

### Exportar a PDF

Haz clic en el botón de impresora (o `Ctrl/Cmd + P`) y selecciona **"Guardar como PDF"**. El modo de impresión está optimizado para orientación horizontal.

---

## Personalización

### Cambiar contenido
Edita directamente las secciones `<section class="slide">` dentro de `index.html`. Cada diapositiva es independiente.

### Añadir o quitar diapositivas
1. Duplica o elimina un `<section class="slide">`.
2. Actualiza el array `slideTitles` en el `<script>` con los títulos correspondientes.
3. El contador y la barra de progreso se ajustan automáticamente.

### Cambiar colores
Los colores principales se definen en `:root` y `.light-mode` dentro del `<style>`. Los acentos por diapositiva usan clases de Tailwind (`blue`, `purple`, `emerald`, `amber`, `rose`).

---

## Compatibilidad

- Chrome / Edge 90+
- Firefox 88+
- Safari 14+
- Navegadores móviles modernos

Requiere conexión a internet para cargar Tailwind, Lucide y la fuente Inter (vía CDN).

---

## Licencia

Uso educativo y libre. Créditos al autor si se reutiliza el contenido.
```