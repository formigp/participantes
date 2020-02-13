# Manual de sobrevivência GIT

## Criar um repositório local

Para criar um repositório local do GIT você deverá acessar a pasta desejada a ser transoformada em repositório utilizando o GIT Bash e digitar a linha de comando:

```
git init
```

Por padrão automaticamente será criada o **branch** denominado de **master**.

Observação: ao realizar esse comando o será criado uma pasta oculta com o nome ".git", essa pasta indica a existência de um repositório git.

Importante: O fato der criar repositório não indica que os dados serão enviado para núvem no GitHub ou BitBucker.


## Associar (sincronizar) o repositório local a um repositório remoto

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
git commit <nome do arquivo incluindo sua extensão> -m "mensagem de referência/comentário/descritivo/etc."
```

Para atualizar o repositório remoto você deverá digitar o comando abaixo:

```
git push -u origin <nome do branch>
``` 

## Como atualizar os arquivos modificados no repositório gerando uma nova versão do arquivo no repositório remoto

Para confirmar o envio (comitar) do arquivo(s) modificados para o repositório você deverá digitar a linha de comando abaixo:

```
git commit -a -m "mensagem de referência/comentário/descritivo/etc."
```

E para atualizar o repositório remoto você deverá digitar o comando abaixo:

```
git push
``` 

## Como exibir as diferenças de "comite" entre meu repositório local e o repositório remoto

Para exibir as diferenças no conteúdo dos arquivos modificados no repositório local e o repositório remoto vocÊ deverá digitar o comando abaixo:

```
git diff
```

Importante: para retornar ao prompt de comando, pressione a tecla **q**.

## Como saber quais são os novos arquivos e arquivos modificados no repositório local que não foram atualizados/enviados para o repositório remoto

Para saber quais os arquivos que precisam ser adicionados ao repositório remoto, assim como os arquivos que foram modificados mas ainda não foram submetidos ao repositório remoto, digite o comando abaixo:

```
git status
```

## Como criar um nova **branch** (ramificação)

Para criar uma nova branch digite o comando abaixo:

```
git branch <nome da branch>
```

Importante: a branch será criada apenas localmente.

Se quiser enviá-la para o repositório remoto você deverá utilizar o comando:

```
git push origin <nome da branch>
```



