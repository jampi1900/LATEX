# LATEX
Proyecto Látex de Dr. Oscar J. Jiménez Flores

Este es un proyecto en LaTeX destinado a la creación de documentos académicos relacionados con el programa de Ingeniería de Sistemas .

# Descripción
Este repositorio contiene plantillas, configuraciones y generados en LaTeX para facilitar la creación de documentos de tesis, artículos, informes y otros documentos académicos conforme a los lineamientos establecidos por la Facultad de la universidad.
# Estructura del proyecto Latex
El proyecto está organizado de la siguiente manera:

- main.tex : Este archivo .tex, es el principal para compilar.
- /Preliminares : Contiene los archivos .texde la caratula
- /Capítulos : Contiene los archivos .texde los capítulos de forma individual
- /Anexos : Contiene los archivos .texde los anexos (si hubieran)
- /Bibliografía : Contiene los archivos .texde la bibliografía en formato.bib

# Requisitos

Para compilar el proyecto, asegúrese de tener instalado:

- LaTeX (TeX Live, MiKTeX, o cualquier distribución compatible).
- Un editor de texto compatible con LaTeX, como Overleaf , TeXShop (macOS), TeXworks (Windows)
- En VS Code instala la extensión:
Taller de LaTeX.
  - Previsualizador de LaTeX
  - Utilidades de LaTeX
  - PDF de Markdown

# Limpiar archivos auxiliares Latex
1. Darle permisos a clean.sh
```
chmod +x clean.sh  
```
2. ejecutar clean.sh
```
./clean.sh
```
