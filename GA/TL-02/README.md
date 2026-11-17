# GA-TL-02 FORM

Taller de entrevista estructurada y design thinking aplicados al PFC. Asignatura ISR-401, equipo ANY.

## Archivos

| Archivo | Contenido |
|---|---|
| `main.tex` | Fuente del informe |
| `main.pdf` | Informe compilado |
| `referencias.bib` | Referencias en formato IEEE |
| `manifiesto.md` | Manifiesto de evidencias (nombre, fecha, duración y SHA-256) |
| `figuras/` | Fuentes editables y figuras |

Los audios y consentimientos no están en este repositorio: se guardan en una carpeta institucional privada compartida con el docente.

## Compilación

- Archivo principal: `main.tex`
- Compilador: pdfLaTeX
- Bibliografía: Biber (biblatex, estilo IEEE)
- Paquetes: babel (español), biblatex, hyperref, longtable, booktabs, array, geometry, lmodern

```bash
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex
```

También puede abrirse en Overleaf con `main.tex` como documento principal.
