# Making presentations with Pandoc beamer


## Prerequisite
```bash 
# if you need latex install it with 
apt-get install texlive-latex-base texlive-fonts-recommended texlive-fonts-extra texlive-latex-extrasudo  

# clone the TU Dortmund theme
git clone https://github.com/maxnoe/tudobeamertheme $(kpsewhich --var-value TEXMFHOME)/tex/latex/tudobeamertheme

# and start compiling the presentation into a pdf 
pandoc presentation.md -t beamer  -o out.pdf

# (optional)
# to rebuild the presentation every time you save isntall entr and run 
echo  vorvortrag.md |entr  pandoc vorvortrag.md -t beamer  -o out.pdf


```

Built on top of: 
https://github.com/alexeygumirov/pandoc-beamer-how-to

