# Fluxo Básico
## Clonando o Projeto
Faça uma cópia local do projeto utilizando a seguinte instrução:

`git clone https://github.com/coronagis/site.git`

## Atualizando o Repositório Local
Sempre, antes de iniciar alguma nova atividade, garanta que o código local está sincronizado com o repositório remoto. Para isso, utilizamos o seguinte:

`git pull origin master`

Precisamos lembrar que, caso você tenha uma versão antiga do código, o comando acima apenas fará o download da mais atual. Do contrário, teremos como retorno o seguinte:

```
From https://github.com/coronagis/site
* branch            master     -> FETCH_HEAD
Already up to date.
```
Isso nos indica que estamos com a versão mais recente do código.

## Criando e Acessando uma nova [branch](https://receitasdecodigo.com.br/devops/git-o-que-e-um-branch)

Criamos uma nova **branch**, ou uma ramificação no GIT, a partir do ramo **master** para fazer alterações que não impactem diretamente o ramo principal. Para isso, utilizamos o seguinte comando:

`git checkout -b [NomeDaSuaBranch]`

O comando acima cria e já acessa nossa branch.

## Salvar e Enviar suas Alterações

Adicionando todas as alterações:

`git add .` 

Fazendo o [commit](https://pt.wikipedia.org/wiki/Commit)

`git commit -m "Mensagem do commit"`

Enviando suas atualizações para o repositório remoto:

`git push origin [NomeDaSuaBranch]`

## Etapa Final

Depois disso, consulte nosso repositório e faça um [Pull Request](https://help.github.com/pt/github/collaborating-with-issues-and-pull-requests/about-pull-requests) da sua atualização. Depois de encaminhado o Pull Requests, caso você não tenha permissões para prosseguir, aguarde até que algum dos administradores faça um [merge](https://developers.sap.com/tutorials/webide-github-merge-pull-request.html) do seu Pull Resquest e atualize o ramo principal com as suas atualizações.

## Referências
1. [Git](https://git-scm.com/)
2. [git - guia prático](https://rogerdudler.github.io/git-guide/index.pt_BR.html)
3. [GIT - Avançado](https://gist.github.com/leocomelli/2545add34e4fec21ec16)
