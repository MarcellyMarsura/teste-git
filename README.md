# teste-git
Documentação para orientação de boas práticas no uso e versionamento de código via Git e GitHub

## Carregar o repositório Localmente
1. Abrindo o terminal Git Bash no diretório desejado, realiza-se uma "clonagem" do repositório remoto, utilizando o comando `git clone` passando por parametro a url do projeto.

`git clone https://github.com/MarcellyMarsura/teste-git.git`

> Obtendo link do repositório

> ![image](https://github.com/MarcellyMarsura/teste-git/assets/89610420/14a6bec8-1ed2-4e35-8026-e94f556d9fde)

> Abrindo o git bash

> ![image](https://github.com/MarcellyMarsura/teste-git/assets/89610420/0dea1089-c2d2-477d-911a-78f5bd7585a7)

> Executando o git clone

> ![image](https://github.com/MarcellyMarsura/teste-git/assets/89610420/e7bcc691-0336-4381-b872-fb675549d46d)

2. Em seguida, após avançar para a pasta do projeto (`cd nome_diretorio`), pode-se realizar a listagem das branchs existentes de forma remota e local (`git branch -a`)

> Avanço ao diretório e listagem de branchs

> ![image](https://github.com/MarcellyMarsura/teste-git/assets/89610420/f65abcb0-80bb-49a0-bc43-99305de999ea)


## Criação de uma nova branch
1. Para novas funcionalidades, é preciso criar uma nova branch para o desenvolvimento paralelo. Para isso, usa-se o comando `git branch nova_branch`

> Criação nova branch

> ![image](https://github.com/MarcellyMarsura/teste-git/assets/89610420/1624b728-de2a-4386-8799-0a1aa5055224)

2. Com o comando `git checkout nova_branch`, altera-se a branch atual com a selecionada. Com isso, os arquivos do diretório serão alterados.


## Commit de mudanças
1. Após realizar um desenvolvimento, os seguintes passos são necessários para disponibilizá-los:

> `git status`: Evidencia os arquivos alterados

> ![image](https://github.com/MarcellyMarsura/teste-git/assets/89610420/8dbe304b-851f-4921-8cb4-86bbf2987d9f)

> `git add .`: Adiciona os arquivos alterados para o Staged

> 
