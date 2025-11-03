# Pandoc

## Što je Pandoc?

Pandoc je alat za konverziju dokumenata između različitih formata.
Primjerice, možeš pretvoriti tekst iz Markdowna u PDF, Word u HTML, LaTeX u DOCX, HTML u EPUB, itd.
Vrlo je popularan među programerima, piscima i akademicima jer podržava stotine formata i omogućuje automatizirane konverzije putem naredbenog retka.

## Primjeri konverzija

### Markdown -> PDF
``` bash
pandoc dokument.md -o dokument.pdf
```

### Word(DOCX) -> Markdown 
```bash
pandoc tekst.docx -o tekst.md
```

### Markdown -> HTML
```bash
pandoc dokument.md -o dokument.html
```

## Naredbe u Pandocu

Ovo su neki primjeri naredba u pandocu

```bash
-s, --standalone
```
 ```bash
-o, -output
```
