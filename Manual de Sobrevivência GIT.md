# Manual de sobrevivência GIT

## Criar um repositório local

Para criar um repositório local do GIT você deverá acessar a pasta desejada a ser transoformada em repositório utilizando o GIT Bash e digitar a linha de comando:

```
git init
```

Por padrão automaticamente será criada o **branch** denominado de **master**.

Observação: ao realizar esse comando o será criado uma pasta oculta com o nome ".git", essa pasta indica a existência de um repositório git.

Importante: O fato der criar repositório não indica que os dados serão enviado para núvem no GitHub ou BitBucker.


## Associar o repositório local a um repositório remoto

Para associar um repositorio local do GIT com um repositório remoto você deverá digitar a linha de comando abaixo:

```
git remote  add origin https://github.com/formigp/participantes.git
```

Importante: Você precisar do endereço do repositório remoto.

## Como saber o endereço do repositório remoto ao qual está associado meu repositório local

Para saber o endereço do repositório remoto ao qual seu repositório local está associado, você deverá digitar a linha de comando abaixo:

```
git remote -v
```
