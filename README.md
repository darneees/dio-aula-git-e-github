# DIO | Resumos Git e GitHub :triangular_flag_on_post:

repositorio para armazenar resumos sobre Git e GitHub do curso Versionamento de Código com Git e Github da [Digital Innovation One](https://www.dio.me/).

## Documentação :books:

- [Documentação Git](https://git-scm.com/doc)
- [Documentação GitHub](https://docs.github.com/)

## Resumo das Aulas :memo:

| Modulos  | Resumos |
| ------------- | ------------- |
| 01 |  Visão geral do curso e ferramentas |
| 02 |  Instalação, configuração e autenticação |
| 03 |  Primeiros passos com GIT e GITHUB |
| 04 |  Dicas e materiais de apoio |
| 05 |  Questionário |


## Guia de comandos Git :mag:

```
$ git init
```
inicia um repositorio local.
#
```
$ git clone 'Url do arquivo'
```
clona um repositorio no github.
#
```
$ git remote add origin 'url'
```
adiciona o repositorio remoto ao repositorio local ( origin é o nome do repositorio remoto ).
#
```
$ git add .
```
adiciona todos os arquivos.
#
```
$ git add 'nome do arquivo'
```
adiciona um arquivo especifico.
#
```
$ git push -u origin main
```
envia o repositorio local para o remoto.
#
```
$ git pull
```
atualiza o repositorio local.
#
```
$ rm -rf .git
```
remove o repositorio.
#
```
$ git branch
```
mostra as branchs.
#
```
$ git branch 'nome da branch'
```
cria uma branch.
#
```
$ git checkout 'nome da branch'
```
altera a branch.
#
```
$ git branch -d 'nome da branch'
```
deleta uma branch.
#
```
$ git restore
```
remove as alterações feitas em um arquivo antes de ser adicionado na staged area ( antes do git add ).
#
```
$ git log --oneline
```
mostra o historico de alterações de forma resumida ( hash do commit e mensagem ).
#
```
$ git commit --amend -m "mensagem"
```
altera a mensagem do ultimo commit feito.
#
```
$ git reset --soft 'hash do commit'
```
volta para o commit especificado e mantem as alterações na staged area ( area de preparação ) para que possam ser adicionadas em um novo commit.
#
```
$ git reset --mixed 'hash do commit'
```
volta para o commit especificado e desfaz o commit, mas mantem as alterações no working directory e na staged area.
#
```
$ git reset --hard 'hash do commit'
```
volta para o commit especificado e desfaz o commit, e remove as alterações no working directory e na staged area (cuidado com esse comando).
#
```
$ git reflog
```
mostra o historico de commits e alterações do repositorio local ( utilizado para desfazer alterações ).
#
```
$ git revert 'hash do commit'
```
reverte o commit e cria um novo commit com a reversão do commit anterior.
#
```
$ git restore --staged 'nome do arquivo'
```
remove o arquivo do staged area e volta para o working directory.
#
```
$ git status
```
mostra o status do repositorio.
#
```
$ git log
```
exibe os commits realizados no repositorio local.
#
```
$ git commit -m "mensagem do commit"
```
cria um commit com uma mensagem de descrição do que foi feito.
#
```
$ git remote -v
```
exibe os repositorios remotos.
#
```
$ git clone 'url' --branch feature-1 --single-branch
```
clona um repositorio especifico de uma branch especifica e cria uma branch local com o mesmo nome da branch remota e faz o checkout automaticamente para a branch local criada.
#
```
$ git cat
```
mostra o repositorio remoto adicionado anteriormente.
#
```
$ mkdir .github
```
cria a pasta .github na raiz do projeto ( se não existir ).
#