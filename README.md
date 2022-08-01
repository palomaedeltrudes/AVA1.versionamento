# AVA1.versionamento
Repositorio da Avaliacao 1 do modulo PBE10 - UC7 - VERSIONAMENTO - Senai

Os principais comandos utilizados para gerenciar o versionamento deste arquivo, foram:

$ git init = cria um novo repositório do Git. 
  Foi usado para inicializar um novo repositório vazio no meu desktop.

$ git status = fornece todas as informacoes sobre a branch atual.
  Aqui podemos ver que um arquivo de texto foi criado, mas ainda nao foi atualizado na branch.
  
$ git add . = inclui as alterações de um ou vários arquivos em nosso próximo commit.
  O arquivo txt foi incluido na fase de stage. Aguardando o commit.
  
$ git commit -m "mensagem do commit" = salva as alterações no espaço de trabalho local, com comentario.

Depois de criar o repositório remoto, fizemos a ligação com o repositório local usando os seguintes comandos:

$ git remote add origin <url-repositório-remoto> = informar a pasta remota.

$ git remote -v = visualizar o repositório remoto.

$ git push -u origin main = publicar as alterações no repositório remoto.

Criei este README.md para simular uma alteracao feita por outro desenvolvedor. Apos isso, voltando para o repositorio local, os seguntes comandos foram usados:

$ git pull = puxar as alterações feitas no repositorio remoto para o repositorio local.

$ git checkout -b <nome-da-branch> = criar uma nova branch.

Criei um novo arquivo dentro desta nova branch e usei os comandos:

$ git status

$ git add .

$ git commit -m "mensagem do commit"

$ git push -u origin <nome-da-branch>

$ git checkout main 

$ git checkout -b <nome-da-branch>

Readme atualizado no repositorio local com essas informacoes. 

Para atualizar o repositorio remoto usei os mesmos comandos acima, porem em uma nova branch. 

$ git status

$ git add .

$ git commit -m "mensagem do commit"

$ git push -u origin <nome-da-branch>

 



