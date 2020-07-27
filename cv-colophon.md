
The CV is exported to PDF using pandoc:

```bash
pandoc '/path/to/PaulMcKenzie.md' \
  --output Paul-McKenzie-CV-$(date "+%Y-%m-%d").pdf \
  --pdf-engine=/Library/TeX/texbin/pdflatex
 ```
