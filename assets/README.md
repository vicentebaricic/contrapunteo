# Assets esperados por index.html

Si un archivo falta, la página muestra un recuadro punteado con la ruta exacta
("Subir: assets/…"), así que es fácil ver qué queda pendiente.

| Ruta | Uso | Recomendado |
|---|---|---|
| `assets/hero.mp4` | Video de fondo del hero (obligatorio) | 1920×1080, H.264, sin audio, 10–20 s en loop, < 8 MB |
| `assets/hero.webm` | Versión WebM del video (opcional, más liviana) | mismo contenido |
| `assets/hero-poster.jpg` | Imagen mientras carga el video / en modo "reducir movimiento" | 1920×1080, primer frame del video |
| `assets/logo.png` | Logo en el header (opcional: si no existe se usa el wordmark) | PNG transparente, claro, ~280×88 |
| `assets/favicon.png` | Ícono de la pestaña | 512×512 |
| `assets/og.jpg` | Imagen al compartir el link (WhatsApp, redes) | 1200×630 |
| `assets/nosotros/nosotros-1.jpg` | Collage "Quiénes somos": salón / ambiente (grande) | vertical 900×1100 |
| `assets/nosotros/nosotros-2.jpg` | Collage: arepas / comida | cuadrada 700×700 |
| `assets/nosotros/nosotros-3.jpg` | Collage: carne en vara al fuego | cuadrada 700×700 |
| `assets/fusion/fusion-1.jpg` | "La vara": carne ensartada junto a las brasas | 800×600 (4:3) |
| `assets/fusion/fusion-2.jpg` | "La sazón": aliños, guasacaca | 800×600 (4:3) |
| `assets/fusion/fusion-3.jpg` | "La mesa": plato servido con acompañamientos | 800×600 (4:3) |
| `assets/chef/chef.jpg` | Retrato del chef | vertical 800×1000 (4:5) |
| `assets/galeria/galeria-1.jpg` | Galería: foto principal (grande, horizontal) | 1200×800 |
| `assets/galeria/galeria-2.jpg` … `galeria-6.jpg` | Galería: ambiente, platos, barra, música, fachada | cuadradas 600×600 (la 4 funciona mejor vertical) |
| `assets/cta-fondo.jpg` | Fondo tenue de la sección final de reserva | 1600×900, oscura |

Tip: exporta las fotos en JPG calidad ~75–80 (o WebP) para que la página cargue rápido.
