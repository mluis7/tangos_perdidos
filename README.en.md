# Tangos Perdidos

**Language:** [Español](README.md) | **English**

The goal of this project is to bring together and make more accessible tango sheet music scattered across the Internet, adding further information whenever possible.

- Title, composer/author, orchestra, singer, year (existing information).
- Scores collected in documents, books, or digital archives without an index, along with where to find them. Every record provides access to a score.
- Musical structure of tangos: sections and number of measures per section (additional processed data).
- Websites where scores can be found by title, author, or lyrics.

## Data sources
The data comes from public websites and/or documents and was processed using software developed for this purpose.

**Main sources**

- [Todo Tango](https://www.todotango.com/musica/obras/partituras/t/0/0/) - list of links to original scores.
- [tango-discographies.github.io](https://tango-discographies.github.io) - discography data.
- [Cancionero del Tango de Hugo Satorre](https://hugosatorre.com.ar/portfolio/cancionero/) - machine-readable digital format (MusicXML).

**Additional sources**

- [partiturastango.blogspot.com](https://partiturastango.blogspot.com) - original scores.
- [Internet Archive at archive.org](https://archive.org/search?query=collection%3A%28partituramagazine+OR+musicmagazines%29+AND+subject%3A%28partitura%29+AND+language%3A%28Spanish%29+) - original scores.
- [“Esteban Echeverría” Public Library](https://pergamo.legislatura.gob.ar/biblioteca/opac.php?a=bsqAv&c=&arMust1=MATERIAS.Materia&trMust1=tango&arMust2=MATERIAS.Materia&trMust2=partitura&o=&vm=ficha&p=1&i=100&flt=%5B%22tem%3APARTITURA%22%5D) - original scores.
- [National Library](https://catalogo.bn.gov.ar/F/1JYNTDLMAMQCJ5BN51FLLEPQY3AGNU54VLMPMDE8NDBUEQL9CT-22619?func=find-c&ccl_term=%28WSU+%3D+%28+tango+%29%29+and+%28WLN+%3D+%28+SPA+%29%29+and+%28WFM+%3D+%28+MU+%29%29+and+%28WFT+%3D+%28+VIEW+%29%29&local_base=GENER) - original scores.
- [Martín Benedetti, online bandoneon, guitar, and tango harmony teacher](https://martinbenedetti.com.ar/descargas) - modern transcriptions, both free and commercial.

## Websites with tango sheet music
These sites contain images or PDF documents of a significant number of tangos. The links below lead to their search pages or indexes.

- [Todo Tango](https://www.todotango.com/musica/obras/partituras/t/0/0/)
- [Cancionero del Tango de Hugo Satorre](https://hugosatorre.com.ar/portfolio/cancionero/)
- [partiturastango.blogspot.com](https://partiturastango.blogspot.com) - an old blog linking to an [extensive score repository](https://www.mediafire.com/folder/qxlnl1yw5ca5t/Partituras_Tango).
- [Internet Archive at archive.org](https://archive.org/search?query=collection%3A%28partituramagazine+OR+musicmagazines%29+AND+subject%3A%28partitura%29+AND+language%3A%28Spanish%29+)
- [“Esteban Echeverría” Public Library](https://pergamo.legislatura.gob.ar/biblioteca/opac.php?a=bsqAv&c=&arMust1=MATERIAS.Materia&trMust1=tango&arMust2=MATERIAS.Materia&trMust2=partitura&o=&vm=ficha&p=1&i=100&flt=%5B%22tem%3APARTITURA%22%5D)
- [National Library](https://catalogo.bn.gov.ar/F/1JYNTDLMAMQCJ5BN51FLLEPQY3AGNU54VLMPMDE8NDBUEQL9CT-22619?func=find-c&ccl_term=%28WSU+%3D+%28+tango+%29%29+and+%28WLN+%3D+%28+SPA+%29%29+and+%28WFM+%3D+%28+MU+%29%29+and+%28WFT+%3D+%28+VIEW+%29%29&local_base=GENER)
- [Martín Benedetti, online bandoneon, guitar, and tango harmony teacher](https://martinbenedetti.com.ar/descargas) - some scores are freely available.
- [Desgrabaciones de Tango para Todxs](https://lucascaceres.com.ar/dtt-ttfe)
- [superpartituras.com.br](https://www.superpartituras.com.br/genero/tango)
- [International Music Score Library Project](https://imslp.org/index.php?title=Category:Tangos&transclude=Template:Catintro)

## Books and commercial websites
The following resources are commercial, but their prices appear reasonable or affordable considering the number of tangos they provide or how difficult the material is to obtain.

- [Martín Benedetti, online bandoneon, guitar, and tango harmony teacher](https://martinbenedetti.com.ar/descargas) - transcriptions and orchestral arrangements.
- [Libro Real del tango Vol. 1](https://melos.com.ar/producto/el-libro-real-del-tango-volumen-1/)
- [Libro Real del tango Vol. 5](https://melos.com.ar/producto/el-libro-real-del-tango-vol-5-partituras-en-c/)
## How to use the data
**Download the spreadsheets to your computer**

- Download the compressed archive containing the spreadsheets [here](https://github.com/mluis7/tangos_perdidos/archive/refs/tags/release-0.1.zip).
- Extract the ZIP file and open `tango-fecha-orquesta-autores-partes-partitura-musicxml.csv` or `tangos-con-partitura-all.csv` with Excel or LibreOffice.

**Open the spreadsheets directly on the website**

- Click `tango-fecha-orquesta-autores-partes-partitura-musicxml.csv` or `tangos-con-partitura-all.csv` and use the site's built-in simple search feature.

## Methodology
The data is consolidated into two groups according to the information available:

- **Tangos with musical structure information**, plus date, orchestra, authors, and a link to the score.
- **Tangos with a link to the score**, page number where applicable, and author(s).

The structure of the tangos was obtained from machine-readable digital documents (MusicXML, rather than images or PDFs). A small number of records were manually corrected or added by reading the structure of scores in PDF or digital image form (e.g., “Emancipación”, “Una Fija”, “El Yaguarón”).
For tango albums or compilations in PDF format, the indexes were extracted as images and processed using optical character recognition (OCR).

## Scope
The **Tangos with musical structure information** list is based primarily on the *Cancionero del Tango de Hugo Satorre*, which covers approximately 400 tangos, expanding to nearly 700 records when the different orchestras that recorded the same tango are taken into account.  
The **Tangos with a link to the score** list contains approximately 800 records from PDF compilations or `partiturastango.blogspot.com`. These sources do not offer a search feature, so their contents were consolidated into a single list.  
This document also includes a list of search sites containing a large number of tangos, many of which are not included in this collection either to avoid duplication or, in the case of `archive.org`, because of the difficulty of extracting the information.

## Data format
Plain-text CSV files for applications such as Excel, Google Docs, or LibreOffice, allowing users to sort the data by multiple criteria or search for keywords.
The files contain NO text formatting or macros — they are plain text only.

## Notes on tango sections and structure
The sections were identified by reading MusicXML files downloaded from the [Cancionero del Tango de Hugo Satorre](https://hugosatorre.com.ar/portfolio/cancionero/) using Python code developed for this purpose. Musical notation marking section boundaries (double barlines, repeat barlines, etc.) was detected, and the measures between these markers were counted.
Some records were manually corrected — typically those showing 17 measures in the first section when there are actually 16.

- Some entries show more than three sections or a single section containing many measures. These require manual review of the original score, if available.
- The variety of section lengths is remarkable. Examples:
  * “Mañana zarpa un barco” - two sections of exactly 16 measures each.
  * “Fruta Amarga” - two sections of 23 and 20 measures.
  * “Tres amigos” - two sections of 13 and 20 measures.
  * “Después” - two sections of 22 and 16 measures.
- Sections can be subdivided into phrases of four or three measures that have meaningful connections to the lyrics. Example: “Amarras”, section A, 22 measures:

    _4 measures_  
    Vago como sombra atormentada  
    bajo el gris de la recova,  
    me contemplo y no soy nada...  

    _4 measures_  
    Soy como mi lancha carbonera  
    que ha quedado recalada,  
    bien atada a la ribera.  

    _3 measures_  
    Yo también atado a mi pasado  
    soy un barco que está anclado  
    (...)

## How to contribute to the project
The following contributions would help enrich the project collaboratively:

- Scores in machine-readable formats (MusicXML, Finale, MuseScore, or others).
- Structural analyses of tangos not included in these lists.
- Links to scores.
- Corrections to inaccurate or erroneous data.

**How to contribute:**  
Send an email with the information and/or attached files to `south.minds@gmail.com`, using “Partituras Perdidas” followed by the tango title as the subject line.

## About the editor
Luis Muñoz is a software developer and jazz musician living in Mendoza, Argentina. A milonguero since 2019, he is eager to understand and learn more about the wonderful world of tango.

P.S. I chose “Tangos Perdidos” (“Lost Tangos”) because it sounded more tango-like than “Tangos Encontrados” (“Found Tangos”) xD, and because it took me several years to gradually collect all this information and give it some shape. The most rewarding part has been finding scores of tangos I really like that were not available on todotango.com — “Una Fija”, “Emancipación”, “El yaguarón” :-)
