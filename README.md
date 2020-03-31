# Estudos dos comandos GIT

## O que é?


## Como surgiu?


## Problemas que resolve?


# Comandos mais utilizados

### Clonando repositório
```
git clone <endereco-do-repositorio>

git clone git@github.com:hyagocabrall/git-estudos.git
```

### Adicionando arquivos ao stage

Adiciona um novo arquivo ao **stage** (Área temporária que indica que o arquivo está preparado para commit)

```
git add <nome-do-arquivo>
```

Adiciona todos os arquivos ao **stage**

```
git add .
```

Adiciona todos os arquivos que terminam com a extensão .txt

```
git add *.txt
```

### Visualizando status 

Exibe todos os arquivos que estão no stage e no workdir

```
git status
```

### Comitando arquivos 

Confirma as mudanças dos arquivos, além de abrir o editor de texto padrão

```
git commit
```

Confirma as mudanças dos arquivos informando a mensagem escrita

```
git commit -m "Sua mensagem"
```

Confirma as mudanças dos arquivos adicionando ao stage e informando mensagem

Obs: Somente utilizar -am com arquivos que já tenham sido adicionados anteriormente 

```
git commit -am "sua mensagem"
```

### Visualizar mudanças


### Criando branch


### Navegando entre a branch


### Excluindo branch


# Referências

https://rogerdudler.github.io/git-guide/index.pt_BR.html
