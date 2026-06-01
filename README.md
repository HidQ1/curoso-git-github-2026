# Curso TMW Git e GitHub



Um curso para iniciantes aprenderem a trabalhar com versionamento de código e repositório remotos com GitHub.

Além disso, vamos trabalhar com o GitFlow ao final do curso e VS Code.

## Fluxo de trabalho Git Local

01. git checkout -b <nova-branch>
02. cria ou atualiza arquivos
03. git status
04. git status
05. git add *arquivos*
06. git status
07. git commit -m "minha mensagem"
08. git checkout main
09. git merge nova-branch

## Fluxo de trabalho com Git Remote

01. git checkout -b <nova-branch>
02. cria ou atualiza arquivos
03. git add .
04. git commit -m "comentario de mudança"
05. git push origin <nova-branch>
06. abrir pull request no GitHub para main
07. excluir <nova-branch> origin
08. git checkout <nova-branch>
09. git branch -D <nova-branch>