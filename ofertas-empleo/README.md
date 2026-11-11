# Radar de Prácticas

Página estática (un solo `index.html`, sin dependencias) para seguir becas y prácticas de
Ingeniería Electrónica y Automática Industrial:

- **Ofertas interesantes**: ofertas recibidas por correo (alertas de LinkedIn, ARQUIMEA, Sener…) a las que aún no has aplicado. Filtros por área y tipo (beca / empleo junior).
- **Mis candidaturas**: candidaturas enviadas con su estado (pendiente, pendiente sin noticias >45 días, descartada, cancelada).
- **Mi CV y matching**: sube tu CV (PDF o texto) y cada oferta y candidatura muestra el % de requisitos que cumples, con los que tienes y los que te faltan.
- **Empresas objetivo**: empresas del sector con tus candidaturas en cada una y enlace a sus ofertas.

Abre `index.html` en el navegador. Los botones "Ya la he solicitado" / "Descartar" guardan el
estado solo en tu navegador (localStorage).

Para actualizar los datos, edita los arrays `OFERTAS`, `CANDIDATURAS` y `EMPRESAS` al principio
del `<script>` (o pide a Claude que vuelva a revisar el Gmail).
