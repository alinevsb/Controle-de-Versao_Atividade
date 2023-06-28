# Controle-de-Versao_Atividade

Passos:
   - 1- Iniciar repositório com git init
   - 2- Criar um arquivo novo (no caso, criei o primeiro_arquivo.py)
   - 3- Podemos usar o git status para verificar as mudanças que foram feitas (até então, não houveram mudanças já que não inserimos o arquivo criado no versionamento)
   - 4- Podemos inserir um git add . (que vai adicionar todos os arquivos)
      - Agora, se colocamos um git satus novamente, vamos ver que há um "new file" porém não existem commits ainda, ou seja, o arquivo passou a ser tracked mas não foi commitado ainda, pois não informamos ao git ainda que queremos salvar o arquivo em certo ponto
   - 5- Para informar ao git as mudanças desejadas, podemos usar o comando git commit -a -m (o -a serve pra que sejam adicionados todos os tipos de arquivos) (o -m adicionará uma mensagem, pra que qualquer pessoa que leia o histórico de commits consiga compreender o que foi feito)
   - 6- Podemos usar o git status novamente, para ter certeza que o commit deu certo
   - 7- Agora usamos o repositório que foi criado no github, adicionando o comando git remote add origin <link do repositório>


Comandos importantes para versionamento:
   - Inicialização:
      -> git init: Inicializa repositório
      -> git clone: Clona um repositório


- Alterações:
-> git status: Verifica se alguma mudança foi feita no branch atual   
-> git add: Adiciona arquivos ao versionamento
-> git commit: Salva as alterações de código

- Reversão:
-> git reset: Volta o código a algum ponto específico
-> git checkout <arquivo>: Descarta mudanças em algum arquivo específico

- Branches:
-> git branch: Listagem de branches
-> git checkout <branch>: Altera o branch

- Publicação e atualização:
-> git pull: Recebe atualizações do repositório remoto   
-> git push: Envia atualizações para o repositório remoto
-> git fetch: Recebe branches remotos que não estão mapeados

  
