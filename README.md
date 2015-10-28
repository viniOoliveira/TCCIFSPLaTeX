tugunisinos: Classes LaTeX para Monografias e Artigos no Padrão do IFSP VTP
==============================================================

Neste pacote você encontra os arquivos necessários para formatar sua
monografia ou artigo de TCC no padrão do IFSP VTP usando LaTeX.

Os arquivos necessários são:
- UNISINOSmonografia.cls: classe de documento LaTeX para monografias;
- UNISINOSartigo.cls: classe de documento LaTeX para artigos;
- unisinos.bst: estilo de referências bibliográficas.

Para usá-los, basta copiar os dois arquivos para a pasta onde se encontra
o documento .tex principal.

Dentro do pacote há também exemplos de uso, compostos pelos arquivos:
- exemplo-monografia.tex: arquivo do documento principal (que contém o texto), para o caso de monografias;
- exemplo-artigo.tex: arquivo do documento principal (que contém o texto), para o caso de artigos;
- exemplo.bib: base de referências bibliográficas;
- escrita.{eps,jpg}: exemplo de imagem inserida no documento. A versão .eps
  é usada quando se processa o documento usando o comando "latex".  A
  versão .jpg é usada com "pdflatex";
- exemplo.pdf: resultado final.

Para processar os documentos de exemplo (pegando o caso da monografia), basta fazer:
pdflatex exemplo-monografia
bibtex exemplo-monografia
pdflatex exemplo-monografia
pdflatex exemplo-monografia

Isso deve recriar o arquivo exemplo-monografia.pdf, que é o documento final.  Esteja
atento para mensagens de erro e avisos que possam aparecer.

É altamente importante ressaltar que este template foi baseado no template da UNISINOS

Link para o grupo autor do arquivo original http://groups.google.com/group/tugunisinos

