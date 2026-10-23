# Tangos Perdidos

**Idioma:** **Español** | [English](README.en.md)

El objetivo del proyecto es consolidar y visibilizar partituras de tango dispersas por Internet y agregar si es posible datos adicionales.

- Título, autor, orquesta, cantor, año (dato existente).
- Partituras agrupadas en documentos, libros o archivos digitales sin índice y donde obtenerlas. Todos los registros proveen acceso a una partitura.
- Estructura musical de los tangos: partes y cantidad de compases por parte (dato adicional procesado).
- Sitios de Internet que permiten encontrar partituras por títulos, autores o letras.

## Fuentes de datos
Los datos provienen de sitios y/o documentos públicos y fueron procesados con software desarrollado al efecto.

**Principales**  

- [Todo Tango](https://www.todotango.com/musica/obras/partituras/t/0/0/) - lista con links a partituras originales.
- [tango-discographies.github.io](https://tango-discographies.github.io) - datos de la discografía.
- [Cancionero del Tango de Hugo Satorre](https://hugosatorre.com.ar/portfolio/cancionero/) - formato digital procesable (musicxml).

**Auxiliares**  

- [partiturastango.blogspot.com](https://partiturastango.blogspot.com) - partituras originales.
- [Archivo de Internet en archive.org](https://archive.org/search?query=collection%3A%28partituramagazine+OR+musicmagazines%29+AND+subject%3A%28partitura%29+AND+language%3A%28Spanish%29+) - partituras originales.
- [Biblioteca Pública "Esteban Echeverría"](https://pergamo.legislatura.gob.ar/biblioteca/opac.php?a=bsqAv&c=&arMust1=MATERIAS.Materia&trMust1=tango&arMust2=MATERIAS.Materia&trMust2=partitura&o=&vm=ficha&p=1&i=100&flt=%5B%22tem%3APARTITURA%22%5D)  - partituras originales.
- [Biblioteca Nacional](https://catalogo.bn.gov.ar/F/1JYNTDLMAMQCJ5BN51FLLEPQY3AGNU54VLMPMDE8NDBUEQL9CT-22619?func=find-c&ccl_term=%28WSU+%3D+%28+tango+%29%29+and+%28WLN+%3D+%28+SPA+%29%29+and+%28WFM+%3D+%28+MU+%29%29+and+%28WFT+%3D+%28+VIEW+%29%29&local_base=GENER)  - partituras originales.
- [Martín Benedetti, profesor de bandoneón, guitarra y armonía de tango online](https://martinbenedetti.com.ar/descargas-2/) - desgrabaciones modernas, gratis y comerciales.

## Sitios de Internet con partituras de tango
Esto sitios contienen imágenes o documentos pdf de un número significativo de tangos. Los links más abajo llevan al buscador o a los índices de los mismos.

- [Todo Tango](https://www.todotango.com/musica/obras/partituras/t/0/0/)
- [Cancionero del Tango de Hugo Satorre](https://hugosatorre.com.ar/portfolio/cancionero/)
- [partiturastango.blogspot.com](https://partiturastango.blogspot.com) - blog antiguo pero con link a un [respositorio extenso de partituras](https://www.mediafire.com/folder/qxlnl1yw5ca5t/Partituras_Tango).
- [Archivo de Internet en archive.org](https://archive.org/search?query=collection%3A%28partituramagazine+OR+musicmagazines%29+AND+subject%3A%28partitura%29+AND+language%3A%28Spanish%29+)
- [Biblioteca Pública "Esteban Echeverría"](https://pergamo.legislatura.gob.ar/biblioteca/opac.php?a=bsqAv&c=&arMust1=MATERIAS.Materia&trMust1=tango&arMust2=MATERIAS.Materia&trMust2=partitura&o=&vm=ficha&p=1&i=100&flt=%5B%22tem%3APARTITURA%22%5D)
- [Biblioteca Nacional](https://catalogo.bn.gov.ar/F/1JYNTDLMAMQCJ5BN51FLLEPQY3AGNU54VLMPMDE8NDBUEQL9CT-22619?func=find-c&ccl_term=%28WSU+%3D+%28+tango+%29%29+and+%28WLN+%3D+%28+SPA+%29%29+and+%28WFM+%3D+%28+MU+%29%29+and+%28WFT+%3D+%28+VIEW+%29%29&local_base=GENER)
- [Martín , profesor de bandoneón, guitarra y armonía de tango online](https://martinbenedetti.com.ar/descargas) - algunas partituras son de libre acceso.
- [Desgrabaciones de Tango para Todxs](https://lucascaceres.com.ar/dtt-ttfe)
- [superpartituras.com.br](https://www.superpartituras.com.br/genero/tango)
- [International Music Score Library Project](https://imslp.org/index.php?title=Category:Tangos&transclude=Template:Catintro)

## Libros y sitios comerciales
Las siguientes referencias son comerciales pero al parecer a precios razonables o accesibles dado la cantidad de tangos que proveen o la dificultad de conseguir el material.

- [Martín Benedetti, profesor de bandoneón, guitarra y armonía de tango online](https://martinbenedetti.com.ar/descargas) - transcripciones y arreglos de orquestas.
- [Libro Real del tango Vol. 1](https://melos.com.ar/producto/el-libro-real-del-tango-volumen-1/)
- [Libro Real del tango Vol. 5](https://melos.com.ar/producto/el-libro-real-del-tango-vol-5-partituras-en-c/)

## Cómo usar los datos
**Descargar las planillas a la computadora**  

- Descargar el archivo comprimido con las planillas [aquí](https://github.com/mluis7/tangos_perdidos/archive/refs/tags/release-0.1.zip).
- Descomprimir el zip y abrir `tango-fecha-orquesta-autores-partes-partitura-musicxml.csv` o `tangos-con-partitura-all.csv` con Excel o LibreOffice.


**Abrir las planillas en el mismo sitio**  
- Hacer click en `tango-fecha-orquesta-autores-partes-partitura-musicxml.csv` o `tangos-con-partitura-all.csv` y usar el buscador simple que ofrece el sitio.

## Metodología
Los datos se consolidan en dos grupos de acuerdo a la información que contienen

- **Tangos con información de estructura musical** más fecha, orquesta, autores y link a la partitura.
- **Tangos con link a la partitura**, número de página si aplica y autor(es).

La estructura de los tangos se obtuvo de documentos en formato digital procesable (musicxml, no imágenes o pdf) y algunos pocos registros se corrigieron o agregaron en forma manual leyendo la estructura de la partitura en pdf o imagen digital (e.g.: "Emancipación", "Una Fija", "El Yaguarón").
En el caso de álbumes o recopilaciones de tango en pdf se extrajeron los índices a imágenes y se procesaron las mismas para extraer el texto de las mismas (OCR).

## Alcance
La lista de **Tangos con información de estructura musical** se basa principalmente en el "Cancionero del Tango de Hugo Satorre" que abarca unos 400 tangos que se extienden a cerca de 700 registros considerando las distintas orquestas que grabaron el mismo tango.  
La lista **Tangos con link a la partitura** contiene cerca de 800 registros provenientes de compilaciones en PDF o del sitio `partiturastango.blogspot.com`. Estas fuentes no proveen un buscador por eso fueron consolidadas en una lista única.  
Se incluye en este documento una lista de buscadores con una gran cantidad de tangos muchos de ellos no presentes en esta recopilación porque sería información duplicada o por la dificultad de extraer la misma en el caso de `archive.org`.

## Formato de la información
Archivos de texto para aplicaciones como Excel, Google Docs o LibreOffice (CSV) que permiten ordenar los datos de acuerdo a múltiples criterios o buscar en los mismos por palabras claves.
Los archivos NO contienen formato de texto ni macros - son solo texto.

## Notas sobre las partes o estructura de los tangos
Las partes se obtuvieron leyendo los archivos musicxml descargados del [Cancionero del Tango de Hugo Satorre](https://hugosatorre.com.ar/portfolio/cancionero/) por medio de código python desarrollado al efecto. Se detectaron notaciones musicales indicadoras de principio a fin de parte (barras dobles, barras de repetición, etc.) y se contaron los compases entre ellas.
Algunos registros fueron corregidos a mano - típicamente los que muestran 17 compases en la primera parte pero en realidad son 16.

- Hay entradas que muestran más de 3 partes o una sola parte de muchos compases. Requieren revisión manual leyendo la partitura original si existe.
- La diversidad de métricas en las partes es notable. Ejemplos:
  * "Mañana zarpa un barco" - 2 partes de exactamente 16 compases cada una.
  * "Fruta Amarga"          - dos partes de 23 y 20 compases.
  * "Tres amigos"           - dos partes de 13 y 20 compases.
  * "Después"               - dos partes de 22 y 16 compases.
- Las partes se pueden subdividir en sub-frases de 4 o 3 compases que se conectan significativamente con la letra de los mismos. Ejemplo: "Amarras", parte A de 22 compases

    _4 compases_  
    Vago como sombra atormentada  
    bajo el gris de la recova,  
    me contemplo y no soy nada...  
      
    _4 compases_  
    Soy como mi lancha carbonera  
    que ha quedado recalada,  
    bien atada a la ribera.  
      
    _3 compases_  
    Yo también atado a mi pasado  
    soy un barco que está anclado  
    (...)  

## Cómo colaborar con el proyecto
Las siguientes contribuciones ayudarían a enriquecer el proyecto de forma colaborativa:

- Partituras en formato procesable (musicxml, finale, musescore u otros).
- Análisis de estructuras de tangos no incluidos en estas listas.
- Links a partituras.
- Corrección de datos imprecisos u erróneos.

**Cómo colaborar**:  
Enviando un email con la información aportada y/o los archivos adjuntos a `south.minds@gmail.com` con el asunto "Partituras Perdidas" más el título del tango.

## Acerca del editor
Luis Muñoz es desarrollador de software y músico de jazz viviendo en Mendoza, Argentina. Milonguero desde 2019 y con gran avidez por entender y aprender más sobre el maravilloso tango.

P.D.: Elegí "Tangos Perdidos" porque sonaba más tanguero que "Tangos Encontrados" xD y porque me llevó varios años recopilar de a poco toda esta info y darle algo de forma. Lo más significativo ha sido encontrar partituras de tangos que me gustan mucho y no estaban en todotango.com - "Una Fija", "Emancipación", "El yaguarón" :-)


