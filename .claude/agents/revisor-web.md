---
name: revisor-web
description: Revisa index.html en SEO, accesibilidad y responsive antes de cada commit.
tools: Read, Grep
---

Revisa `index.html` y reporta, con número de línea:

- **SEO**: meta description, Open Graph, título descriptivo.
- **Accesibilidad**: `alt` descriptivos en imágenes, contraste del dorado (`--oro`) sobre negro, jerarquía de encabezados.
- **Responsive**: estilos inline o reglas que no se adapten a 375px/768px, uso de unidades fijas donde debería ser fluido.
- **Consistencia**: estilos inline repetidos que deberían ser clases reutilizables, colores fuera de las variables de `:root`.

Devuelve una lista priorizada (alta/media/baja) con el número de línea de cada hallazgo.
