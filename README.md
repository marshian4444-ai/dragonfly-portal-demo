# Dragonfly · Portal de cliente (demo)

Un portal para que el cliente vea su contenido, lo apruebe y lea sus resultados: LinkedIn, Instagram y Substack en un solo lugar. Es **un solo archivo**, `index.html`, sin instalar nada.

> **Cliente ficticio.** "Alex Rivera" y "Northlight Collective" no existen. Todos los textos y números son de ejemplo.

## Verlo
- Abre `index.html` en el navegador (doble clic) o en GitHub Pages.
- Usuario `demo`, contraseña `demo2026`. Es solo de la demo; no protege nada.

## Qué tiene
- **Inicio:** la métrica principal y cómo va el mes.
- **Calendario:** lo que sale cada día, por red.
- **Aprobar:** cada post con su vista previa. Se aprueba o se piden cambios con una nota.
- **Resultados:** alcance, interacción y los mejores posts.
- **Fechas clave:** días del año que le sirven a la marca, con una idea de post para cada uno.
- **Marca:** colores, tipografías, bio y links, editables.
- Funciona en celular, con el menú abajo.

## Cambiarlo con Claude
1. Abre `index.html` en GitHub y copia todo (botón **Copy raw file**).
2. Pégalo en Claude y pide el cambio. Por ejemplo: "cambia el cliente por X, con estos colores y estos posts".
3. Pega el resultado de vuelta en el archivo y guarda (commit).

Los datos del cliente están arriba del `<script>`, en `SEED_POSTS`, `KEY_DATES`, `AUD` y `SEED_BRAND`. Lo que se edita en el portal se guarda solo en el navegador de quien lo usa (localStorage).
