![Poster Taller](https://raw.githubusercontent.com/santisoler/taller-latex/master/poster/poster-taller-latex.png)

## Si tenés intenciones de participar del Taller, ingresá tus datos [acá](https://docs.google.com/forms/d/e/1FAIpQLSeSHYbCO4y1PWeqs_dhnhWpDhGIMngRbVLaX2Xg48lGQwnnFA/viewform?usp=sf_link)

Tus datos no serán publicados en ningún sitio, solo los recopilamos para tener una lista de contactos y conocer las necesidades para cada área del conocimiento.

## Sobre el Taller...
### Objetivos

El taller posee como objetivo introducir a los interesados y las interesadas en el sistema de composición de textos LaTeX y la final elaboración de un documento propio, en el cual se utilicen las herramientas descriptas a lo largo del mismo. Se otorgará especial énfasis a la producción de artı́culos cientı́ficos, informes de laboratorio y redacción de Tesis. Es nuestra intención que cada participante pueda utilizar las horas de taller tanto para incorporar los conocimientos básicos de LaTeX, ası́ como también producir un documento que le sea útil en su presente trabajo, estudio, investigación, etc. Además se introducirán conocimientos sobre el uso de software afines a LaTeX, tal como la construcción de base de datos bibliográficas a través de la herramienta BibTeX.

### Duración y Lugar

El Taller se llevará a cabo los días 7, 9, 21, 23, 28 y 30 de Junio del 2017, en el horario de 14:00 a 18:00, en el Aula de Posgrado de la Facultad de Ciencias Exactas, Físicas y Naturales de la UNSJ.

### Requisitos

Se solicita a los participantes traer su notebook con sistema operativo a elección (recomendamos utilizar Software Libre como GNU/Linux) y el software que utilizaremos ya instalados.

No se requieren conocimientos previos.

## Software Necesario para el Taller

### GNU/Linux
#### Para Debian/Ubuntu y derivados:

Instalamos la distribución de LaTeX texlive junto con paquetes extra, de idiomas para español e inglés y un paquete adicional para clases de documentos adicionales utilizados por diversos journals científicos:
```
sudo apt-get install texlive texlive-latex-extra texlive-lang-spanish texlive-lang-english texlive-publishers
```

Instalamos un editor para LaTeX, podemos optar por TexMaker o Kile:
```
sudo apt-get install texmaker

sudo apt-get install kile kile-l10n
```

Vamos a instalar JabRef, un gestor de referencias y bibliografía:
```
sudo apt-get install jabref
```

**Observación**: Estas instrucciones también sirven para Huayra, la distribución de GNU/Linux que viene instalada en las netbooks de Conectar Igualdad.

### Windows

Vamos a instalar una distribución de LaTeX (MikTex), el editor (TexMaker) y el gestor de referencias (JabRef):

* [MikTex](https://miktex.org/download) - Descargar el Basic Installer en la arquitectura de tu compu (32 o 64bits)
* [TexMaker](http://www.xm1math.net/texmaker/download.html)
* [JabRef](http://www.jabref.org/#downloads)

## Dudas y consultas

Escribinos a santiago.r.soler@gmail.com y pesce.agustina@gmail.com


## Recursos y Referencias

### Presentaciones de las Clases

* [Clase 1: Introducción](https://github.com/santisoler/taller-latex/raw/master/beamer-clase1/beamer-clase1.pdf)
* [Clase 2: Artículo Científico](https://github.com/santisoler/taller-latex/raw/master/beamer-clase2/beamer-clase2.pdf)
* [Clase 3: Bibliografía](https://github.com/santisoler/taller-latex/raw/master/beamer-clase3/beamer-clase3.pdf)
* [Clase 4: Libro](https://github.com/santisoler/taller-latex/raw/master/beamer-clase4/beamer-clase4.pdf)

### Respuestas a dudas en las Clases

* [Ejemplos de cómo resolver algunas de las dudas que surgieron en clase](https://github.com/santisoler/taller-latex/tree/master/examples)
* Algunas respuestas a dudas que surgieron en clase: [aquí](https://github.com/santisoler/taller-latex/raw/master/respuestas-dudas/respuestas-dudas.pdf)
* Cómo cambiar la fuente de todo el documento: vean [este ejemplo](https://github.com/santisoler/taller-latex/blob/master/examples/fonts/fonts.tex).
* Tablas apaisadas: [leer esto](https://tex.stackexchange.com/questions/3930/how-to-rotate-landscape-table-page-in-pdf#123330).
* Listas horizontales: Leer la respuesta de [este post](https://tex.stackexchange.com/questions/146306/how-to-make-horizontal-lists/324740#324740) que hace uso del paquete **tasks**.
* Afiliaciones de autores en maketitle: [post](https://tex.stackexchange.com/questions/107739/authors-with-multiple-affiliations/370813#370813) y [ejemplo](https://github.com/santisoler/taller-latex/blob/master/examples/affiliations/affiliations.tex)
* Crear dos abstract: uno en español y otro en inglés. [Aquí](https://github.com/santisoler/taller-latex/blob/master/examples/two_abstracts/two_abstracts.tex) hay un ejemplo.


### Otros Recursos 

* [The No So Short Introduction to LaTeX](http://ftp.inf.utfsm.cl/pub/tex-archive/info/lshort/english/lshort.pdf)
* [Introducción a LaTeX. Carlos M. Silva (2009)](https://github.com/santisoler/taller-latex/raw/master/documentos/Silva2009.pdf)
* [Wikibook de LaTeX](https://en.wikibooks.org/wiki/LaTeX)
* The LaTeX Companion: Libro muy completo. [Aquí](http://ptgmedia.pearsoncmg.com/images/9780201362992/samplepages/0201362996.pdf) se puede leer un capítulo de muestra.
* [Writing a Thesis with LaTeX](https://tug.org/pracjourn/2008-1/mori/mori.pdf)
* [OverLeaf](https://www.overleaf.com/): Plataforma online para escribir en colaboración
* [SciWeavers](http://www.sciweavers.org/free-online-latex-equation-editor) y [CodeCogs](http://www.codecogs.com/latex/eqneditor.php): editores de ecuaciones online

## Licencia
Copyright (c) 2017 Santiago R. Soler and Agustina Pesce. Todos los derechos reservados.

Los templates, documentos, códigos y todo el material restante presente en este repositorio se encuentran disponibles bajo la licencia [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

![CreativeCommons](https://licensebuttons.net/l/by-sa/4.0/88x31.png)

A excepción de [documentos/Silva2009](https://github.com/santisoler/taller-latex/raw/master/documentos/Silva2009.pdf), Copyright (c) 2009 Carlos M. Silva. Todos los derechos reservados.
