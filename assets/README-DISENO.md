# Guía breve de diseño · Rosewood Fantasy

Paleta: fondo `#171820`, panel `#22212B`, rosa `#C895A2`, ciruela `#775460`, dorado `#D5B58B`, salvia `#A6B5A4`, crema `#F1E7E2`.

- Cabecera: `rosewood-header.svg`.
- Títulos de sección: `section-*.svg`.
- Tarjetas de proyectos: `project-1.svg` a `project-4.svg`. Para añadir otra, duplica una tarjeta y edita los textos dentro del SVG, crea el enlace en `README.md` y actualiza su texto alternativo.
- Pie: `rosewood-footer.svg`.
- Todos los textos de los SVG locales utilizan Georgia (con alternativas serif), sin fuentes externas. Los párrafos Markdown siguen la tipografía impuesta por GitHub.
- Los badges de tecnologías son SVG locales. La tarjeta de estadísticas procede de un servicio externo y puede conservar una tipografía diferente; si falla, el resto del perfil sigue visible.
- Si cambias la paleta, actualiza los colores hexadecimales en los SVG y en las URL de los badges.
- Los enlaces de certificaciones apuntan a los PDF ya presentes en `assets/certificados`.
- No añadas botones con `#` o URL ficticias.


### Certificaciones (tarjetas SVG)
Las tres tarjetas están en `assets/certificados/tarjeta-*.svg`. Cada tarjeta enlaza directamente al PDF existente desde `README.md`. Para añadir una, crea una tarjeta SVG siguiendo la misma plantilla y enlázala al PDF real. No hay menú de navegación superior para evitar los enlaces azules predeterminados de GitHub.

- Los rótulos de tecnologías y el subtítulo de cabecera son SVG locales para mantener la coherencia tipográfica.
