# Mapa Conceptual vs. Mapa Mental

Presentación web interactiva que compara el **mapa conceptual** y el **mapa mental**: características, similitudes, diferencias y aplicaciones prácticas.

**Autor:** Alejandro Mendieta

---

## 📌 Contenido de la presentación

La presentación consta de **6 diapositivas**:

1. **Portada** — Título, subtítulo y autor.
2. **Mapa Conceptual** — Definición, origen, características, ejemplo visual y uso común.
3. **Mapa Mental** — Definición, origen, características, ejemplo visual y uso común.
4. **Similitudes** — Puntos en común clave entre ambas herramientas.
5. **Diferencias Clave** — Tabla comparativa (en enfoque, estructura, conexiones, verificabilidad y origen).
6. **Cuándo usar cada uno** — Guía de aplicación práctica.

---

## 🛠️ Características técnicas

* **HTML único** (Tailwind CSS vía CDN + Lucide Icons).
* **Modo oscuro / claro** con persistencia en `localStorage`.
* **Navegación avanzada**: Botones, teclado, *swipe* táctil y vista general en cuadrícula (grid).
* **Pantalla completa** integrada.
* **Optimizado para impresión / Exportación a PDF**.
* **Diseño responsive** (móvil, tablet, escritorio).
* **Accesibilidad**: Atributos `aria-label`, roles y enfoque visible.

---

## ⌨️ Atajos de teclado

| Tecla | Acción |
|-------|--------|
| `←` / `PageUp` | Diapositiva anterior |
| `→` / `Espacio` / `PageDown` | Diapositiva siguiente |
| `G` | Abrir vista general (grid de miniaturas) |
| `F` | Alternar pantalla completa |
| `Esc` | Cerrar vista general / salir de modales |

---

## 📂 Estructura del proyecto

```text
.
└── Mapas.html      # Archivo único autocontenido (HTML + CSS + JS)