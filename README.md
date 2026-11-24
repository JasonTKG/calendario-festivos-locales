# Fiestas laborales locales, autonómicas y nacionales de España, 2026 y 2027

Fiestas laborales locales de 2027 de los 1.167 municipios de Andalucía, Galicia y Canarias que figuran en las relaciones publicadas por sus comunidades, una fila por municipio y fecha, y las fiestas nacionales y autonómicas de 2026 y 2027 de cada comunidad según las relaciones del BOE. (Local, regional and national public holidays in Spain, read from the official bulletins.)

Site: https://festivos.govsimple.org/

## Files

| File | Rows |
|---|---|
| `fiestas_locales_2027.csv` | 2,334 |
| `fiestas_nacionales_autonomicas.csv` | 454 |

## Columns

**`fiestas_locales_2027.csv`**

- `comunidad`: comunidad autónoma
- `provincia`: provincia
- `municipio`: municipio
- `fecha`: fecha de la fiesta local (AAAA-MM-DD)
- `denominacion`: nombre de la fiesta si el boletín lo da; «Fiesta local» si solo da la fecha
- `boletin`: boletín oficial del que se ha leído
- `url_boletin`: dirección del boletín
- `pagina`: página del municipio en el sitio, si la tiene

**`fiestas_nacionales_autonomicas.csv`**

- `anio`: año
- `comunidad`: comunidad o ciudad autónoma
- `fecha`: fecha (AAAA-MM-DD)
- `denominacion`: nombre de la fiesta
- `tipo`: nacional o autonómica, según la relación del BOE
- `boletin`: boletín
- `url_boletin`: dirección del boletín

## Sources

| Source | URL | Terms | Retrieved |
|---|---|---|---|
| Resolución de 8 de octubre de 2026, de la Dirección General de Trabajo, por la que se publica la relación de fiestas laborales para el año 2027 (BOE núm. 254, de 13/10/2026) | https://www.boe.es/diario_boe/txt.php?id=BOE-A-2026-21254 | Disposición oficial (art. 13 de la Ley de Propiedad Intelectual); reutilización con cita de la fuente | 2026-11-23 |
| Resolución de 17 de octubre de 2025, de la Dirección General de Trabajo, por la que se publica la relación de fiestas laborales para el año 2026 (BOE de 28/10/2025) | https://www.boe.es/diario_boe/txt.php?id=BOE-A-2025-21667 | Igual | 2026-11-23 |
| Andalucía: Resolución de 23 de octubre de 2026 de la Dirección General de Trabajo, Seguridad y Salud Laboral (BOJA núm. 210, 29/10/2026) | https://www.juntadeandalucia.es/boja/2026/210/25.html | Igual | 2026-11-23 |
| Galicia: Resolución de 15 de octubre de 2026 de la Secretaría General de Empleo y Relaciones Laborales (DOG núm. 204, 26/10/2026) | https://www.xunta.gal/dog/Publicados/2026/20261026/AnuncioG0767-161026-0001_es.html | Igual | 2026-11-23 |
| Canarias: Orden de 7 de agosto de 2026 de la Consejería de Turismo y Empleo (BOC núm. 168, 21/08/2026) | https://www.gobiernodecanarias.org/boc/2026/168/3035.html | Igual | 2026-11-23 |
| Canarias: Orden de 11 de noviembre de 2026 (BOC núm. 234, 20/11/2026), que modifica la anterior | https://www.gobiernodecanarias.org/boc/2026/234/4068.html | Igual | 2026-11-23 |

## How it was checked

Las fechas se leen por programa de la copia guardada de cada boletín. Un segundo programa comprueba, para cada municipio, que la línea del boletín citada está en la copia guardada y que las fechas de la página coinciden con ella; las tablas nacionales se comparan celda a celda con la relación del BOE. La Orden de Canarias de 11 de noviembre de 2026, que modifica cuatro municipios, está aplicada. Si una fecha no coincide con el boletín, vale el boletín.

## Left out

Solo están las tres comunidades cuyas relaciones locales de 2027 se habían publicado y leído al exportar. No se incluyen las cifras de población del INE que el sitio usa para ordenar los municipios.

## Licence

Las disposiciones y actos de los organismos públicos no son objeto de propiedad intelectual (art. 13 del texto refundido de la Ley de Propiedad Intelectual) y su reutilización pide citar la fuente: cite el boletín de cada fila. La ordenación de estos ficheros se dedica al dominio público con CC0 1.0 (véase `LICENSE`).

## Maintainer

Built and maintained by [JasonTKG](https://github.com/JasonTKG); corrections and questions: open an issue.

Exported 2026-11-24 from the data the site's pages are generated from.
