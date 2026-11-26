# FORM-IC-01

## Generar el PDF

Usa una distribución de LaTeX con `pdflatex`, `biber` y los paquetes
`babel` con soporte para español, `newtx`, `geometry`, `graphicx`,
`csquotes`, `biblatex`, `biblatex-ieee` y `hyperref`.

Desde la raíz del repositorio, compila el archivo principal `analisis.tex`
en este orden:

```sh
pdflatex analisis.tex
biber analisis
pdflatex analisis.tex
pdflatex analisis.tex
```

El PDF generado es `analisis.pdf`.
