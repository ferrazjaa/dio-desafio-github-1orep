## Alguns comandos usado no git bash

- Link com documentação sobre o git: https://git-scm.com/docs
  - Pode-se escolher a língua ao clicar no tema
- git init => inicia um repositório Git vazio
- ls -a => mostra arquivos ocultos
- git config --global user.email "meuEmail" => quando usar a primeira vez
- git config --global user.name COLOCA NOME DO USER
  - é bom deixar e-mail e user igual do github
- git commit -m "mensagem sobre o commit" => cria commit
- git add deixa o arquivo/código no stage
  - git add -a => adiciona todos os arquivos (novos, modificados e deletados)
  - git add . => adiciona os arquivos novos e modificados, mas não os deletados
  - git add * => usado para adicionar arquivos novos e modificados do diretório atual
- git restore --staged "<nomeArquivo>" => restaura os caminhos definidos na working tree
- git config --list =>Trazer uma lista com todas configurações do meu git
- git remote add origin link_do_repositorio_github => adiciona repositório local no repositório remoto
- git remote -v => Mostrará as listas de repositórios remotos que tenho cadastrado
- git push origin master => levar o local para o remoto