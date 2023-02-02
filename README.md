# Making presentations with Pandoc beamer


## Prerequisite
if you need latex install it with 
```apt-get install texlive-latex-base texlive-fonts-recommended texlive-fonts-extra texlive-latex-extrasudo  ```

clone the TU Dortmund theme
```bash git clone https://github.com/maxnoe/tudobeamertheme $(kpsewhich --var-value TEXMFHOME)/tex/latex/tudobeamertheme```

compiling works with 
```bash pandoc presentation.md -t beamer  -o out.pdf```

Built on top of: 
https://github.com/alexeygumirov/pandoc-beamer-how-to

