# Evaluacion_Unidad_IV_Practica

Evaluación Práctica de la Unidad IV de la asignatura Ingeniería de Requisitos.

## Datos

**Estudiante:** Zambrano Moya Angelo Paul  
**Asignatura:** Ingeniería de Requisitos - ISR-401  
**Paralelo:** B  
**Caso:** Sistema de Reserva de Citas Médicas  

## Repositorio

https://github.com/AngeloP2114/Evaluacion_Unidad_IV_Practica

## Archivo principal

El archivo principal de LaTeX es:

`Prueba IV_Practica_Angelo_Zambrano.tex`

## Compilador

El documento debe compilarse utilizando:

`pdflatex`

## Orden de compilación

Desde la raíz del repositorio ejecutar los siguientes comandos en este orden:

```bash
pdflatex "Prueba IV_Practica_Angelo_Zambrano.tex"
bibtex "Prueba IV_Practica_Angelo_Zambrano"
pdflatex "Prueba IV_Practica_Angelo_Zambrano.tex"
pdflatex "Prueba IV_Practica_Angelo_Zambrano.tex"
```

## Dependencias

Para la compilación se requiere una distribución de LaTeX con soporte para los siguientes paquetes:

- inputenc
- fontenc
- helvet
- textcomp
- geometry
- amsmath
- amssymb
- graphicx
- tikz
- xcolor
- array
- tabularx
- multirow
- colortbl
- booktabs
- enumitem
- microtype
- parskip
- titlesec
- fancyhdr
- caption
- pdflscape
- natbib
- hyperref
- tcolorbox

## Archivos del repositorio

El repositorio contiene los siguientes archivos principales:

- `Prueba IV_Practica_Angelo_Zambrano.tex` — archivo fuente principal de LaTeX.
- `Prueba IV_Angelo_Zambrano.pdf` — documento PDF compilado.
- `referencias (1).bib` — archivo de referencias bibliográficas.
- `Resumen_Cuestionario.jpeg` — captura del resumen del cuestionario realizado en el SGA.
- `Revision_Intento.jpeg` — captura de la revisión del intento realizado en el SGA.
- `README.md` — instrucciones de compilación y descripción del repositorio.

## Figuras

La carpeta `figuras/` contiene los diagramas utilizados como evidencias del desarrollo:

- `figuras/Diagrama_Actividades.jpeg`
- `figuras/Diagrama_Corregido.jpeg`
- `figuras/Diagrama_Maquinas_Estado.jpeg`
- `figuras/Diagrama_clases_uml.jpeg`

## Evidencias del SGA

Las evidencias del cuestionario se encuentran en la raíz del repositorio:

- `Resumen_Cuestionario.jpeg`
- `Revision_Intento.jpeg`

Estas capturas son incorporadas en el documento LaTeX y forman parte del PDF final.

## PDF compilado

El documento PDF entregable es:

`Prueba IV_Angelo_Zambrano.pdf`

## Reproducibilidad

El repositorio contiene el archivo fuente LaTeX, las evidencias, las figuras y las referencias necesarias para reproducir el documento.

Después de clonar o descargar el repositorio, se debe ejecutar el orden de compilación indicado anteriormente desde la raíz del proyecto para generar nuevamente el PDF.
