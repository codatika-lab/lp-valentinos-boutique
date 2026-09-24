# Avisos de dependencias de terceros

Este archivo registra las dependencias incorporadas por el generador en las landing pages publicadas.

El orquestador publica una copia de este archivo junto a cada `index.html` y también incorpora este contenido como comentario dentro del HTML. De esta forma, los avisos permanecen disponibles tanto en el repositorio generado como en una copia independiente de la landing.

## Lucide 1.38.0

- Paquete: `lucide`
- Uso: iconos de interfaz como teléfono, ubicación, horario, correo, menú, cierre, flechas y enlace externo.
- Licencia principal: ISC.
- Fuente: <https://lucide.dev>
- Cumplimiento en los artefactos: este aviso completo se publica como `THIRD_PARTY_NOTICES.md` y se incorpora como comentario en cada `index.html` generado.

### Aviso ISC de Lucide

```text
ISC License

Copyright (c) 2026 Lucide Icons and Contributors

Permission to use, copy, modify, and/or distribute this software for any
purpose with or without fee is hereby granted, provided that the above
copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR
ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN
ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF
OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
```

Algunos iconos incluidos por Lucide proceden del proyecto Feather y conservan además su licencia MIT:

```text
Copyright (c) 2013-present Cole Bemis

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## Simple Icons 16.29.0

- Paquete: `simple-icons`
- Uso: iconos de Facebook, Instagram, TikTok, WhatsApp, X y YouTube.
- Licencia: CC0 1.0 Universal.
- Condiciones: <https://creativecommons.org/publicdomain/zero/1.0/>
- Fuente: <https://simpleicons.org>
- Cumplimiento en los artefactos: la dependencia y su licencia se registran en el aviso publicado junto al HTML y dentro del comentario de licencias del propio HTML.

CC0 permite copiar, modificar, incorporar y redistribuir estos iconos, incluso con fines comerciales. La licencia no concede derechos sobre las marcas representadas; cada icono se utiliza exclusivamente para identificar su servicio correspondiente.

## Font Awesome Free Brands 7.3.1

- Paquete: `@fortawesome/free-brands-svg-icons`
- Uso: únicamente el icono de LinkedIn, como representación del servicio correspondiente.
- Licencia del icono SVG: Creative Commons Attribution 4.0 International (CC BY 4.0).
- Licencia del código del paquete: MIT.
- Fuente y condiciones: <https://fontawesome.com/license/free>
- Cumplimiento en los artefactos: el SVG generado incluye un comentario HTML que identifica Font Awesome Free, la licencia CC BY 4.0 y el enlace a sus condiciones.

Los iconos de marcas son marcas comerciales de sus respectivos propietarios y se utilizan únicamente para representar el servicio al que pertenecen.

## GSAP 3.15.0

- Paquete: `gsap`
- Componentes incorporados: GSAP Core y ScrollTrigger.
- Uso: animaciones programáticas de entrada y desplazamiento en las landing pages.
- Licencia: Standard "No Charge" GSAP License.
- Condiciones: <https://gsap.com/standard-license>
- Evaluación para este proyecto: el uso actual consiste en generar y mostrar animaciones dentro de sitios web, supuesto incluido entre los usos permitidos. El proyecto no ofrece una interfaz visual para crear animaciones ni pretende competir con las capacidades de animación visual de Webflow.
- Cumplimiento en los artefactos: el HTML generado incorpora GSAP y ScrollTrigger desde la dependencia fijada del paquete; este aviso acompaña al paquete fuente y documenta la licencia aplicable a los scripts embebidos.

Esta evaluación documenta el uso técnico actual. Cualquier cambio que convierta el producto en un constructor visual de animaciones requiere una nueva revisión de la licencia de GSAP.
