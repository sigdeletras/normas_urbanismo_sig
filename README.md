# Normas y especificaciones técnicas sobre planeamiento urbanístico en España

Recopilación y análisis normativas técnicas españolas que regulen la presentación digital de los instrumentos de planificación urbanística y territorial en formato #GIS.

- [2º Entrada. Publicación del repositorio](https://www.linkedin.com/posts/patriciosorianocastro_github-sigdeletrasnormasurbanismosig-activity-7006570086958264320-oXw-/)
- [1º Entrada. Propuesta y enlaces](https://www.linkedin.com/feed/update/urn:li:activity:6979697381382479872/)


## ¿Cómo colaborar?

Para colaborar complemtando o mejorando este repositorio público existen varias vías. Por orden de preferencia:

1. Añadir un [issue](https://github.com/sigdeletras/normas_urbanismo_sig/issues) a este reposotorio indicando un nuevo recurso o enlace de interés.
2. Clonando el respositorio y realizando Pull Request. [¿Breve guía para principiantes de como contribuir a un repositorio en GitHub?](https://www.freecodecamp.org/espanol/news/como-hacer-tu-primer-pull-request-en-github/)
3. Entrando en el hilo creado en [Linkedin](https://www.linkedin.com/posts/patriciosorianocastro_github-sigdeletrasnormasurbanismosig-activity-7006570086958264320-oXw-/) y hacer un comentario.
4. Compartiendo este enlace en Linkedin o en Twitter haciendo referencia al perfil [@sigdeletras](https://twitter.com/sigdeletras)

## Características a evaluar

- Cartografía: Relación de cartografías de referencia.
- Capas: Incorporación de relación de capas a utilizar. Se suele incorporar tablas donde se presentan una codificación de las capas.
- Modelos: Se incluye relación de campos a cumplimentar, incluyendo su tipo (texto, entero, decimal, booleano) y diccionarios (tablas de dominio a aplicar a campos)
- Topología: Guías para la representación de entidades gráficas (geográficas), escalas de representación.
- Simbología: Gamas de colores, etiquetas
- Fichas: Normalización de formato y campos para la presentación de fichas
- Aplicaciones: Se suministra archivos, ficheros o herramientas informáticas para aplicar la norma.
- Metadatos: Metadatos de referencia
- Documentación: Manuales de ayuda, guías, video tutoriales...

## Normas

### 01	Andalucía

- Ley 7/2021, de 1 de diciembre, de impulso para la sostenibilidad del territorio de Andalucía (LISTA). [Enlace](https://www.juntadeandalucia.es/eboja/2021/233/BOJA21-233-00135-19403-01_00251661.pdf)
  - Artículo 62. Contenido documental de los instrumentos de ordenación urbanística. Respecto a la cartografía, sólo referencia a los conjuntos de datos de Información y Ordenación.
- Decreto 550/2022, de 29 de noviembre, por el que se aprueba el Reglamento General de la Ley 7/2021, de 1 de diciembre, de impulso  para la sostenibilidad del territorio de Andalucía. [Enlace](https://www.juntadeandalucia.es/sites/default/files/inline-files/2022/12/Decreto%20550_2022_REGLAMENTO%20LISTA.pdf)
  - Artículo 2.2 El derecho de acceso a la información territorial y urbanística
  - Artículo 5. Registros administrativos de instrumentos de ordenación urbanística y convenios. 
  - Artículo 6. Sistema de información territorial y urbanística

| Característica | Incluido | Observaciones |
| ----------- | ----------- | ----------- |
| Cartografía | No | |
| Capas | No |  |
| Modelos | No | |
| Topología |  No | |
| Simbología | No |  |
| Fichas | No | |
| Aplicaciones | No| |
| Metadatos | No | |
| Documentación | No | |

**De interés**

- Documento de la Diputación de Sevilla. Pliego de Prescripciones técnicas para la contratación de servicios de redación del Plan General/Básico de Ordenación municipal. [PDF](https://www.dipusevilla.es/export/sites/diputacion-sevilla-corporativo/.galleries/DOCUMENTOS-descarga/DOCUMENTOS-Cohesion-territorial/subvenciones-planeamiento-urbanistico/2-PPT.pdf). ANEXO II Hace referencia a las carecterísticas de la entrega de documentación en sorporte digital, añadiendo un partado breve sobre Modelo de datos SIG indicando una Estructura de las capas de información urbanística general (Estructura de las capas de información urbanística general,  Estructura de las capas de ordenación urbanística general

### 02	Aragón

**Proyecto NOTEPA. Normalización del planeamiento urbanístico en Aragón. [Enlace](http://notepa.aragon.es/)** . DECRETO 78/2017, de 23 de mayo, del Gobierno de Aragón, por el que se aprueba la Norma Técnica de Planeamiento (NOTEPA)

Dirección General de Urbanismo del Gobierno de Aragón

| Característica | Incluido | Observaciones |
| ----------- | ----------- | ----------- |
| Cartografía | Sí | Proporcionada por el IGEAR |
| Capas | Sí | ANEXO IV |
| Modelos | No | La referencia a los modelos es exlusiva a al anexo ANEXO VI - Geodatabase. No se ha localizado dicha Geodatabase|
| Topología | ¿? | No se ha encontrado una referencia clara. Puede que se encuentre en las aplicaciones CAD y GIS . En la norma se hace referencia a Geodatabases|
| Simbología | Sí | ANEXO III |
| Fichas | Sí | Excel |
| Aplicaciones | Sí | NOTEPACAD (AutoCAD / Autocad Map) y NOTEPAGIS (ArcGIS 9)|
| Metadatos | Sí | Basados en la ISO 19115. Entrega en [hoja de cálculo](http://notepa.aragon.es/images/stories/201609_otros/Excel%20de%20Metadatos.xls) |
| Documentación | Sí| |

### 03	Asturias, Principado de

**Normalización urbanística. [Enlace](https://www.asturias.es/detalle/-/categories/612963?p_r_p_categoryId=612963&_com_liferay_asset_categories_navigation_web_portlet_AssetCategoriesNavigationPortlet_articleId=2535583&articleId=2535583&title=Normalizaci%C3%B3n%20urban%C3%ADstica&redirect=https%3A%2F%2Fwww.asturias.es%2Fast%2Fgeneral%2F-%2Fcategories%2F572499%3Fp_r_p_categoryId%3D572499)**

[Registro de planeamiento y gestión urbanística y su integración en el Sistema de Información Territorial del Principado de Asturias, dictada mediante Resolución de 2 de septiembre de 2014, (BOPA de 25 de septiembre de 2014)](https://www.asturias.es/bopa/2014/09/25/2014-15826.pdf)

[Introducción a la instrucción (pdf: 48 Kb)](https://www.asturias.es/documents/217090/1854024/Introduccion-instruccion-normalizacion-instrumentos-planeamiento-gestion-urbanistica-revisada.pdf/29982aa5-1f2c-9ecd-58e7-4ce45aaead2b?t=1667208894454)

| Característica | Incluido | Observaciones |
| ----------- | ----------- | ----------- |
| Cartografía | Sí | cartografía básica oficial disponible en la Consejería competente en la materia y la cartografía básica que disponga el promotor del instrumento urbanístico.|
| Capas | Sí | |
| Modelos | Sí | Base de Datos Espacial (estructura, los campos y los dominios) anexo III|
| Topología | Sí | |
| Simbología | Sí | Artículo 9.—Documentación gráfica. artículo 4. 4 de la Instrucción |
| Fichas | ¿? | No localizadas|
| Aplicaciones | Sí | 3 formatos vectoriales (ArcView, AutoCAD Map y GeoMedia) . Archivos shp, ndb (geomedia) y dwg|
| Metadatos | No | |
| Documentación | Sí | Tutoriales para AutocadMap |

**De interés**:
- Lista de escalas. Artículo 5.—Escalas.
- Instrucciones topológicas:  
  - Todas las clases de entidad o capas que formen parte del Sistema de Información Geográfica estarán formadas por geometrías de tipo área, línea o punto, no permitiéndose geometrías mixtas o combinadas dentro de la misma capa de información.
  - Las líneas estarán compuestas por tramos rectos, no admitiéndose geometrías curvas, como pueden ser arcos circulares, elípticos, parabólicos, etc.; así como tampoco líneas B-splines (curvas de Bézier u otro tipo de curvas similares).


### 04	Balears, Illes

**Normas Técnicas de Planeamiento (NTP) [Enlace](https://www.caib.es/sites/muib/es/ntp_normas_tecnicas_de_planeamiento/)**

Dirección General de Territorio y Paisaje. 

| Característica | Incluido | Observaciones |
| ----------- | ----------- | ----------- |
| Cartografía | Sí | mapa  topogràfic de les Illes Balears MTIB 1:5000 per al sòl rústic i 1:1000 per al sòl urbà i urbanitzable. ETRS89 (EPSG:25831) |
| Capas | Sí | ANNEX 3: CODIS ENTITATS (QUALIFICACIONS AL SÒL URBÀ I URBANITZABLE DIRECTAMENT ORDENAT, SÒL URBANITZABLE I CATEGORIES DEL SÒL RÚSTIC). ANNEX 4: CODIS CLASSIFICACIÓ|
| Modelos | Sí | ANNEX 1D - CONJUNTS D'ARXIUS SHAPEFILES I FULLS DE CÀLCUL |
| Topología | Sí  | ANNEX 2: NORMES DE DIGITALITZACIÓ I ATRIBUTS DE LA CAPA D'ENTITATS |
| Símbología | Sí | ANNEX 3: CODIS ENTITATS (QUALIFICACIONS AL SÒL URBÀ I URBANITZABLE DIRECTAMENT ORDENAT, SÒL URBANITZABLE I CATEGORIES DEL SÒL RÚSTIC). ANNEX 4: CODIS CLASSIFICACIÓ|
| Fichas | Sí| |
| Aplicaciones | No | |
| Metadatos | No | |
| Documentación | No | |

**De interés:**
- Topología:
  - Les línees que delimiten els polígons de les diferents capes han de ser coincidents amb les línees de la base cartogràfica, sempre que tingui un sentit lògic i coherent amb la realitat física. 
  - Els elements gràfics de planejament, tals com límits de classificació, categories, sectors o alineacions, s’hauran de representar als plànols de forma inequívoca. En cas de solapament de vàries línees sobre un mateix punt, línea o traçat, l’escala del tipus de línea o el color hauran de permetre la diferenciació entre elles.
  - Ha d'estar format únicament per elements gràfics de tipus POLIGONAL
  - Els polígons gràfics no es poden solapar, o, el que és el mateix, cap polígon gràfic es pot superposar a un altre.
  -La unió dels polígonsgràfics ocuparà tot l’àmbit sense deixar cap forat(aquesta unió de polígons defineix l’àmbit).Allà on els polígons gràfics siguin adjacents,cal que la línia que comparteixen ambdós polígons estigui formada per exactament els mateixos nodes. Això implica que cal que el viari i el sòlrústic siguin poligonitzats.
- Formatos: digital en formats Shapefile i fulles de càlcul.


### 05	Canarias
### 06	Cantabria
### 07	Castilla y León

**ORDEN FOM/1572/2006, de 27 de septiembre, por la que se aprueba la Instrucción Técnica Urbanística 2/2006, sobre normalización de los Instrumentos de Planeamiento Urbanístico (ITPLAN). [Enlace])(https://bocyl.jcyl.es/boletines/2006/10/10/pdf/BOCYL-D-10102006-10.pdf)**

Consejería de Fomento

| Característica | Incluido | Observaciones |
| ----------- | ----------- | ----------- |
| Cartografía | Sí | Centro de Información Territorial (CIT) de la Consejería de Fomento |
| Capas | ¿? | No me queda claro |
| Modelos | ¿? | Geodatabase o Shapefile, según plantilla. No localizada. DISPOSICIÓN ADICIONAL 1. TABLA SÍNTESIS DE USOS  y Tablas de Tipologías|
| Topología | ¿? | artículo 2 |
| Simbología | Sí | Publicada en el BOP en escala de grises|
| Fichas | Sí | Fichas de síntesis ¿Digitales? |
| Aplicaciones | Sí | PLURCAD, que consisten en personalizaciones de los productos CAD|
| Metadatos | Sí | ficha síntesis con los datos clave del planeamiento (metadatos), conforme al modelo reproducido en la Disposición Adicional|
| Documentación | | |


### 08	Castilla - La Mancha

- ANEXO 1_SIU INSTRUCCIÓN 20170720_DEFINITIVA INSTRUCCIONES PARA GENERAR EL ARCHIVO DE PLANEAMIENTO URBANÍSTICO EN 
FORMATO SHAPEFILE (shp) [Enlace](https://urbanismo.castillalamancha.es/sites/urbanismo.castillalamancha.es/files/documentos/pdf/20191022/instrucciones_para_generar_el_archivo_de_planeamiento_urbanistico_en_formato_shp.pdf)

### 09	Cataluña

- Mapa urbanístic de Catalunya sintètic v1.2. Especificacions per al format “Shapefile” Implementació 1 Revisió del document 19/02/2016 [Enlace PDF](https://territori.gencat.cat/web/.content/home/06_territori_i_urbanisme/07_observatori_territori/mapa_urbanistic_de_catalunya/estandard/documents/especificacions_shp_mucs.pdf)

### 10	Comunitat Valenciana.

**Decreto 65/2021, de 14 de mayo, del Consell, de regulación de la Plataforma Urbanística Digital y de la presentación de los instrumentos de planificación urbanística y territorial. [Enlace](https://dogv.gva.es/portal/ficha_disposicion_pc.jsp?sig=005292/2021&L=1)**

- Artículo 6. Norma técnica relativa a la referenciación cartográfica y formatos de presentación de instrumentos de planificación urbanística y territorial y de las declaraciones de interés comunitario
- Anexo I. Norma técnica: Referenciación cartográfica y formatos de presentación de los instrumentos de planificación urbanística y territorial y de las declaraciones de interés comunitario.
- Anexo II. Nomenclatura de términos urbanísticos
- Anexo III. Estructura de los archivos shape
- Anexo IV. Estructura de capas, códigos de color, línea y símbolo

Conselleria de Política Territorial, Obras Públicas y Movilidad

| Característica | Incluido | Observaciones |
| ----------- | ----------- | ----------- |
| Cartografía |  Sí | base topográfica, las series cartográficas del Instituto Cartográfico Valenciano y como cartografía temática la de la Infraestructura Verde y Paisaje, así como la cartografía de afecciones territoriales. EPSG: 25830|
| Capas | Sí |  Anexo IV.|
| Modelos | Sí | Anexo III |
| Topología | Sí | Anexo I . ) Los recintos representados gráficamente vendrán definidos siempre por entidades poligonales cerradas, perfectamente solidarias entre
sí, sin huecos y sin solapas, y serán recintos planos, con altura cero en la coordenada “z”. |
| Simbología | Sí | Anexo IV|
| Fichas | ¿? | No localizadas|
| Aplicaciones | Sí | Descarga http://politicaterritorial.gva.es/va/web/urbanismo/sistema-de-informacion-urbanistic Descarga shp [Enlace](https://politicaterritorial.gva.es/es/web/urbanismo/models-arxius-shp-descargables) |
| Metadatos | Sí |  estándar ISO19115|
| Documentación | | |

### 11	Extremadura

### 12	Galicia

**ORDEN de 8 de abril de 2022 por la que se modifica la Orden de 10 de octubre de 2019 de aprobación de las normas técnicas de planeamiento urbanístico de Galicia. [Enlace](https://www.xunta.gal/dog/Publicados/2022/20220425/AnuncioG0532-080422-0005_es.pdf)** 

Consellería de Medio Ambiente, Territorio y Vivienda

| Característica | Incluido | Observaciones |
| ----------- | ----------- | ----------- |
| Cartografía |  | |
| Capas | Sí | Anexo 2 |
| Modelos | Sí | Anexo 3: Modelo de datos de los archivos vectoriales |
| Topología | Sí  | Anexo 2 |
| Simbología | Sí | Anexo 2: Simbología gráfica y parámetros de etiquetado |
| Fichas |  | |
| Aplicaciones | | |
| Metadatos | | |
| Documentación | | |

**De interés**
- Anexo 4: Estructura y codificación de carpetas y archivos de las figuras de planeamiento
- Anexo 8: Catálogo mínimo de objetos geográficos de la base topográfica del planeamiento urbanístico

### 13	Madrid, Comunidad de

### 14	Murcia, Región de

### 15	Navarra, Comunidad Foral de

**Decreto Foral 253/2019 de 16 Oct. CF Navarra. Registro de Planeamiento de Navarra y el formato de presentación de los instrumentos de planificación urbanística y territorial de Navarra [Enlace](http://www.lexnavarra.navarra.es/detalle.asp?r=52066)**

| Característica | Incluido | Observaciones |
| ----------- | ----------- | ----------- |
| Cartografía |  | |
| Capas | Sí | ANEXO: Formatos de archivo La información geográfica vectorial señalada en el artículo 10 se entregará en formato shapefile. EPSG: 25830 |
| Modelos | Sí | TÍTULO IV |
| Topología | Sí  | La geometría será de tipo poligonal aceptando elementos multiparte y polígonos|
| Simbología | No | |
| Fichas | No | |
| Aplicaciones | No | |
| Metadatos | No | |
| Documentación | No | |

**De interés**
- Cuando el ámbito del instrumento tenga establecida una delimitación gráfica oficial (municipio, con-cejo, polígono o parcelas catastrales...), o dichas referencias gráficas sean necesarias para ajustar el límite del ámbito, se utilizará la delimitación oficial que para esa fecha tenga establecido el Departa-mento del Gobierno de Navarra competente.
- El planeamiento a desarrollar deberá ajustarse a la delimitación del ámbito oficial. Sólo podrá haber desajuste en caso de que la nueva ordenación requiera la modificación del ámbito, y sólo en las parce-las que requieran ser segregadas o anexionadas.
- Coherencia entre el contenido de la documentación escrita y los planos
- Coherencia topológica con los recintos definidos en planeamiento de nivel superior
- Coherencia topológica con las líneas de catastro:
- Coherencia topológica de cada conjunto de datos consigo mismo
- Coherencia topológica de cada conjunto de datos con los demás
- Coherencia topológica entre recintos de conjuntos de datos con contenidos complementarios

### 16	País Vasco

### 17	Rioja, La

** Documento de recomendaciones técnicas para la interpretación y aplicación de la Ley 5/2006, de 2 de mayo, de Ordenación del Territorio y Urbanismo de La Rioja y otras normativas sectoriales con incidencia en la materia, para coordinar y agilizar el procedimiento de redacción y aprobación del planeamiento urbanístico. [Enlace](https://www.larioja.org/territorio/es/ordenacion-territorio-urbanismo/documento-recomendaciones-tecnicas)**

### 18	Ceuta

### 19	Melilla
