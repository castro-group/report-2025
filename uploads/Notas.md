# Castro Group — RS2025 Web · Brief de ajustes

**Fecha:** 15 mayo 2026
**Para:** Claude Code
**De:** MFZ
**Proyecto:** Página web Relatório de Sustentabilidade Castro Group 2025
**Referencia visual:** Página web RS2025 NEXA (versión actual, ya aprobada) + `/referencias/01` (carpeta del repo)

---

## 1. Apertura del reporte

### 1.1 Retirar quote duplicada de Peter
En la parte inicial hay una quote de Peter que se repite más abajo. **Eliminar la primera** — dejar solo la siguiente, que ya está en el flujo.

### 1.2 Reducir el círculo interactivo giratorio
El círculo animado que rueda con la frase de Peter + el texto "Report de 2025" está demasiado grande. **Hacerlo más chico** sin romper la vista mobile.

---

## 2. Spacing general — comprimir verticalidades

Hay demasiado aire entre bloques. **Comprimir el spacing vertical** en toda la página, manteniendo la legibilidad y la vista mobile.

Casos concretos:
- Espacio **encima** de la quote del CEO → reducir
- Espacio **entre** quote del CEO y quote de Fernanda → reducir
- Espacio **debajo** de la quote de Fernanda → reducir

Regla general: revisar todos los márgenes/paddings verticales entre secciones y reducir ~20–30%. No tocar mobile breakpoints más allá de lo necesario para mantener la legibilidad.

---

## 3. Botón "Ir para arriba"

Mover **ligeramente a la izquierda** para que no se solape con el lateral vertical "Creating Tomorrow" del capítulo 3.

---

## 4. Páginas de pausa interactivas

### 4.1 Retirar la pausa con varias bolitas "Castro Group"
Eliminar por completo la página de pausa interactiva con múltiples bolitas que dice "Castro Group" — no suma en términos de diseño.

---

## 5. Gráfico de doble materialidad

Rehacerlo **inspirado en el de NEXA** (ese quedó muy bien). Mismo lenguaje visual, adaptado a los datos de Castro Group.

---

## 6. Pilar 2 — Social

### 6.1 Bolitas interactivas de colaboradores
Actualmente las bolitas que muestran la cantidad de colaboradores femeninos y masculinos están dispuestas en **2 líneas**. Cambiar a **una sola línea** — queda más impactante.

---

## 7. Cuadros con valores macro — restaurar gráficos al hacer clic

Cuando el usuario hace clic en un cuadro con un KPI macro, debe abrirse el **gráfico tal cual aparece en el PDF final del reporte**. Estaba antes así y se perdió.

Ejemplo claro: al hacer clic en "horas de formación" → debe aparecer el **gráfico de barras comparando 2024 vs 2025**, idéntico al del PDF.

**Aplicar este comportamiento a TODOS los cuadros macro**, no solo al de formación.

---

## 8. Retirar Pilar 4 — Económico

Eliminar el Pilar 4 (Económico) completo de la web. **Pedido de administración.**

---

## 9. Plan de Transición Climática — mejorar gráfico

El gráfico actual del plan de transición climática hay que **mejorarlo gráficamente**.

Referencias:
- El de **NEXA** (ya quedó muy bien) — usar como base
- La carpeta `/referencias/01` del repo — animaciones de este estilo me gustan, ser más creativo en esa línea

---

## 10. Paleta de grises — simplificar

Actualmente hay **3 grises** en la página. El gris de fondo se ve "sucio".

Simplificar a **2 grises**:
- **Gris medio-claro** (el segundo más claro de la paleta actual) → fondo de la página
- **Gris más claro** → botones

Eliminar el gris oscuro/sucio del fondo. Aplicar el cambio en toda la página de forma consistente.

---

## 11. Página de agradecimientos

Los círculos con los nombres están demasiado grandes. **Reducir el tamaño del círculo** pero **mantener el tamaño de la letra** como está ahora — solo achicar el círculo que rodea cada nombre.

---

## Checklist final antes de commit

- [ ] Quote duplicada de Peter retirada
- [ ] Círculo giratorio inicial reducido
- [ ] Spacing vertical comprimido (CEO/Fernanda y resto)
- [ ] Botón "Ir para arriba" movido a la izquierda
- [ ] Pausa "Castro Group" con bolitas retirada
- [ ] Doble materialidad rehecho estilo NEXA
- [ ] Bolitas H/M Pilar 2 en una sola línea
- [ ] Cuadros macro abren gráficos del PDF (todos)
- [ ] Pilar 4 Económico eliminado
- [ ] Gráfico Plan Transición Climática mejorado (ref NEXA + /referencias/01)
- [ ] Grises reducidos de 3 → 2 (fondo más claro)
- [ ] Círculos de agradecimientos reducidos (letra igual)

---

**Notas finales:**
- No romper responsive mobile.
- Mantener consistencia con la web de NEXA cuando sea posible.
- Si algo no queda claro, preguntar antes de implementar.
