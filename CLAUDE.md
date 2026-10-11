# BarberKing

Landing estática en un solo `index.html` (CSS y HTML inline, sin build, sin dependencias).

## Reglas de estilo
- Colores: usar solo las variables definidas en `:root` (`--oro`, `--negro`, `--blanco`, etc.). Nunca hex sueltos fuera de `:root`.
- Fuentes: Playfair Display (títulos), Cormorant Garamond (acentos), Montserrat (texto general).
- Textos en español, tono elegante/premium.
- Las secciones usan `id` para los anclas del nav (`#servicios`, `#galeria`, `#contacto`). Mantener esos ids si se reordena contenido.
- Mobile-first: probar siempre a 375px y 768px antes de dar algo por terminado (el layout actual solo tiene un `@media`).

## Estructura
- Todo vive en `index.html`: `<style>` en el `<head>`, markup en `<body>`.
- No introducir frameworks ni build tools salvo que el usuario lo pida explícitamente.
