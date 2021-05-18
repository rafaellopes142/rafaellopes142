# Desafio Front-End-Fpass Marvel

### Conforme foi passado, criei um pequeno sistema utilizando a API da Marvel para fazer uma pesquisa dos heróis pelo nome.

Menu.html
No “menu.html” nessa tela vai ser mostrada para fazermos todas as ações . 
1. Ao clicar no botão “Marvel” aparecera uma imagem com vários heróis da Marvel.
2. Ao clicar no botão “Pesquisar Herói” vai abrir uma tela abaixo para digitar o nome do herói, assim que digitar o nome clicar em Enviar vai aparecer o ‘Nome do herói, descrição e uma foto’.
3.  Ao clicar no botão “Cadastrar Herói” vai abrir uma tela abaixo para digitar o nome do herói, a descrição e escolher um foto do herói e quando clicar em cadastrar ele pega os dados e salva no banco de dados.

## Tecnologias usadas para fazer o desafio

1. Utilizei o HTML para fazer o front-end do “menu” e  o CSS para  personalizar deixá-lo mas bonito.
2. Para fazer a tela de pesquisar  utilizei o HTML e junto  o método POST que chama pesquisar.php que é feita em PHP, nele é feito  toda a configuração para fazer a busca no banco de dados e informar o que foi pesquisado.
3. Para fazer a tela de cadastrar utilizei o HTML e junto  o método POST que chama pesquisar.php que é feita em PHP, nele é feito  toda a configuração para fazer o cadastro do herói aonde informa seu nome a descrição e uma foto e todas essas informações são salvas no banco de dados.
4. No banco de dados foi criado 4 tabelas uma para cada funcionalidade uma para guardar a id, outra o nome, outra a descrição e a outra a imagem. Todas essas irformações apareceram no junto com o html.
