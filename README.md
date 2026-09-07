# Laboratorio de Matemáticas

Material docente de la asignatura **Laboratorio de Matemáticas**, orientada al aprendizaje práctico de herramientas de cálculo, programación, visualización y documentación científica.

La asignatura tiene una carga docente de **6 ECTS**, distribuida en:

- **15 horas de clases magistrales**.
- **45 horas de prácticas**.

## Contenidos

- Introducción al entorno de trabajo con R y RStudio/Posit.
- Variables, tipos de datos, funciones y estructuras de control.
- Vectores, matrices, listas y marcos de datos.
- Cálculo numérico y simulación.
- Análisis estadístico y modelización de datos.
- Visualización gráfica.
- Introducción a LaTeX.
- Markdown, R Markdown y Quarto.
- Elaboración de informes técnicos reproducibles.

## Materiales

- [Manual de la asignatura en PDF](manual_laboratorio_matematicas.pdf)
- [Fuente LaTeX del manual](manual_laboratorio_matematicas.tex)
- [Transparencias del curso](slides/)

El manual incluye una introducción conceptual y un itinerario de **15 prácticas**, cada una con una duración orientativa de 3 horas.

## Organización del repositorio

```text
.
├── manual_laboratorio_matematicas.pdf
├── manual_laboratorio_matematicas.tex
└── slides/
    └── README.md
```

Las transparencias se incorporarán progresivamente en `slides/`. Se recomienda nombrarlas con un prefijo numérico para conservar el orden del curso, por ejemplo:

```text
slides/
├── 01-introduccion.pdf
├── 02-r-y-rstudio.pdf
├── 03-estructuras-de-datos.pdf
└── ...
```

## Requisitos

Para trabajar con los materiales prácticos se recomienda instalar:

- [R](https://cran.r-project.org/)
- [RStudio Desktop](https://posit.co/download/rstudio-desktop/)
- Una distribución de LaTeX, como [TeX Live](https://www.tug.org/texlive/) o [MiKTeX](https://miktex.org/)
- [Quarto](https://quarto.org/), para los documentos reproducibles

Los paquetes de R utilizados en cada práctica se indican en el propio manual o en los materiales correspondientes.

## Compilar el manual

Desde la raíz del repositorio:

```bash
pdflatex manual_laboratorio_matematicas.tex
pdflatex manual_laboratorio_matematicas.tex
```

La segunda compilación permite actualizar correctamente el índice y las referencias internas.

## Licencia

La licencia del material se definirá al publicar el repositorio. Hasta entonces, el contenido se distribuye únicamente con fines docentes.

