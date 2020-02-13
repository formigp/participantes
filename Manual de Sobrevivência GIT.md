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

## Como adicionar um arquivo em específico ao repositório

Primeiro você deverá adicionar o arquivo em específico ao repositório local, você deve digitar a linha de comando abaixo:

```
git add <nome do arquivo incluindo sua extensão>
```

Importante: o comando acima apenas irá sinalizar que o arquivo foi marcado para ser enviado ao repositório.

Para confirmar o envio (comitar) do arquivo(s) marcados para o repositório você deverá digitar a linha de comando abaixo:

```
git commit -m "mensagem de referência/comentário/descritivo/etc."
```

Para atualizar o repositório remoto você deverá digitar o comando abaixo:

```
git push -u origin <nome do branch>
``` 

## Como atualizar os arquivos modificados no repositório gerando uma nova versão no repositório remoto

Para confirmar o envio (comitar) do arquivo(s) modificados para o repositório você deverá digitar a linha de comando abaixo:

```
git commit -m "mensagem de referência/comentário/descritivo/etc."
```

E para atualizar o repositório remoto você deverá digitar o comando abaixo:

```
git push -u origin <nome do branch>
``` 




