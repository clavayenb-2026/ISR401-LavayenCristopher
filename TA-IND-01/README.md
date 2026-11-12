
# TA-IND-01

## Trabajo individual: IEEE 29148 y tipos de requisitos de un sistema conocido

**Asignatura:** Ingeniería de Requisitos (ISR-401)

**Estudiante:** Cristopher Lavayen

**Tipo de actividad:** Sumativa individual

**Sistema seleccionado:** Mi Claro Ecuador

## Archivos

| Archivo | Descripción |
|---|---|
| `main.tex` | Código fuente del informe en LaTeX. |
| `main.pdf` | Documento académico compilado. |
| `referencias.bib` | Referencias bibliográficas. |
| `evidencias/` | Capturas propias de Mi Claro. |
| `README.md` | Información e instrucciones de compilación. |

## Requisitos para compilar

- pdfLaTeX.
- Biber.
- biblatex.
- babel con soporte para español.
- Paquetes utilizados en `main.tex`.

**Archivo principal:** `main.tex`

**Compilador:** pdfLaTeX

**Gestor bibliográfico:** Biber

**Secuencia de compilación:**

```bash
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex
```

## Referencias

- ISO/IEC/IEEE 29148:2018.
- ISO/IEC 25010:2023.
