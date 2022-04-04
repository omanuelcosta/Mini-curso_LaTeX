[![YouTube Channel Views](https://img.shields.io/youtube/channel/views/UC7bMBdlD9U-qJD8q2tTgKVw?label=youtube&style=social)](https://www.youtube.com/channel/UC7bMBdlD9U-qJD8q2tTgKVw)  [![GitHub followers](https://img.shields.io/github/followers/omanuelcosta?style=social)](https://github.com/omanuelcosta/)   
<a href=https://github.com/omanuelcosta/Mini-curso_LaTeX>
  
 <a href=https://github.com/omanuelcosta/Mini-curso_LaTeX/archive/refs/heads/apresenta%C3%A7%C3%A3o.zip><img src="https://img.shields.io/github/downloads/omanuelcosta/Mini-curso_LaTeX/presentation/total"></a>

#  Apresentação do Mini-curso de _LaTeX_

## Arquivo fonte (.tex) e da build (figuras, pdfs e .tex de configurações)

Estes são os arquivos da apresentação feita no Mini-curso de LaTeX. 
Lembrando que a produção desta apresentação foi feita com recursos voltadas para usuários mais avançados, como animações, alteração de fontes _in-situ_
e outros recursos avançados.

### Pacotes utilizados
Os pacotes utilizados na produção são:

```
pdfbase, animate, multimedia, graphicx,xcolor, transparent, textpos, relsize, tikz, perpage, 
listings, amssymb, amsfonts, amsthm, bm, hyphenat, booktabs, multirow, siunitx, babel, caption, threeparttable
times, helvet, ebgaramond, lmodern, palatino # mudança in-situ de fontes
```

### Compilação
Os comandos utilizados para a compilação deste documento são (comando -- argumentos):

- pdflatex 
  - pdflatex -synctex=1 -interaction=nonstopmode -file-line-error %DOC%
- bibtex 
  - biber %DOCFILE%
- pdflatex(2x)

### Qualquer dúvida, envie-me um email: <a href="mailto:omanuelcosta@protonmail.com?subject=Mini-curso de LaTeX"><img src="https://img.shields.io/badge/ProtonMail-8B89CC?style=for-the-badge&logo=protonmail&logoColor=white"/></a>
