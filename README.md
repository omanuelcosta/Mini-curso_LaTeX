[![YouTube Channel Views](https://img.shields.io/youtube/channel/subscribers/UC7bMBdlD9U-qJD8q2tTgKVw?style=social)](https://www.youtube.com/channel/UC7bMBdlD9U-qJD8q2tTgKVw)  [![GitHub followers](https://img.shields.io/github/followers/omanuelcosta?style=social)](https://github.com/omanuelcosta/) <a href=https://github.com/omanuelcosta/Mini-curso_LaTeX></a>

#  Artigo _fake_ do Mini-curso de _LaTeX_

## Arquivo fonte (.tex) e da build (figuras e _.bib_)

Estes são os arquivos do artigo _fake_ apresentado no Mini-curso de LaTeX. 
Este artigo foi feito com a classe _elsarticle_, feito para submeter artigos nos jornais científicos da editora Elsevier.
A documentação da classe _elsarticle_ está presente neste <<a href="https://www.elsevier.com/__data/assets/pdf_file/0008/56843/elsdoc-1.pdf">link</a>>

### Pacotes utilizados
Os pacotes utilizados na produção são:

```
hyperref, % links clicáveis
amsmath, amssymb, amsthm % ferramentas matemáticas
```

### Compilação
Os comandos utilizados para a compilação deste documento são (comando -- argumentos):

- pdflatex 
  - pdflatex -synctex=1 -interaction=nonstopmode -file-line-error %DOC%
- bibtex 
  - biber %DOCFILE%
- pdflatex(2x)

### Download:
 <a href=https://github.com/omanuelcosta/Mini-curso_LaTeX/archive/refs/heads/apresenta%C3%A7%C3%A3o.zip><img src="https://img.shields.io/badge/download%20.tex%20build-6%20mb-green"></a>

### Qualquer dúvida, envie-me um email: 
<a href="mailto:omanuelcosta@protonmail.com?subject=Mini-curso de LaTeX"><img src="https://img.shields.io/badge/ProtonMail-8B89CC?style=for-the-badge&logo=protonmail&logoColor=white"/></a>
