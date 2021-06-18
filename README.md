# Algunos datos de las Elecciones Generales 2021 del Perú

[![DOI](https://zenodo.org/badge/357629065.svg)](https://zenodo.org/badge/latestdoi/357629065)

Datos extraídos de la información presentada por ONPE en https://www.resultados.eleccionesgenerales2021.pe/

Ojalá ONPE libere esta información como datos abiertos, para no necesitar usar scraping.

## Contenido de los archvivos

- Participación en las elecciones
	- resultados-participacion-por-distrito.(csv|rds): Resultados de la participación a nivel distrital
- Elección presidencial (datos a nivel distrital)
	- presidencial-datos-generales.(csv|rds): Datos generales para el distrito
	- presidencial-datos-resumen.(csv|rds): Resúmen de actas, electores, etc. para el distrito
    - presidencial-datos-votos.(csv|rds): Votos totales, en blanco, nulos, etc para el distrito
	- presidencial-resultados-partidos.(csv|rds): Resultados por cada partido para el distrito

**Nota Importante**: El código de UBIGEO que usa ONPE en sus tablas es el de RENIEC, no el de INEI. Si necesitan hacer la conversión de uno a otro, pueden usar los datos que tengo publicados en: https://github.com/jmcastagnetto/ubigeo-peru-aumentado

**2021-06-17**: Añadiendo el archivo con información de actas de https://ronderos.pe (https://github.com/tabo/elecciones_peru_2021). El archivo `presidencial-actas_ronderos.pe.csv.gz` tiene sólo lo correspondiente a la primera vuelta.
