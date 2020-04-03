# Estudos dos comandos GIT

## O que é o GIT?

**Git** é um sistema de controle de versão de arquivos. Através dele podemos desenvolver projetos no quais diversas pessoas podem contribuir simultaneamente, Editanto,  cricando novos arquivos e criando novos permitindo que os mesmos possam existir sem o risco de suas alterações serem sovrescritas.

## O que é o Github?

O **Github** é um serviço web que oferece diversas funcionalidades extras aplicadas ao git. De forma resumida ele é um repositório gratuito bastante utilziado pela comunidade open source

## Como surgiu?

**Git** surgiu a partir da necessidade de fazer o controle e gerenciamento das versões do kernel do linux, na época utilizavam o BitKeeper, entretando precisavam de uma ferramenta gratuita, tendo em vista os principios dos desenvolvedores e toda a metodologia envolvida. Torvalds (engenheiro de software), foi o desenvolvedor da ferramenta, que a colocou em uso em menos de 1 mês após seu desenvolvimento. Posteriormente passou entregou a Junio Hamano, para manter a ferramenta operante e realizar suas devidas manutenções.

## Problemas que resolve?

Dentre as muitas vantagens de se utilizar controladores de versões, Você consegue verificar quem foi o ultimo a alterar o projeto e quais foram as alterações introduzidas, consegue retornar o projeto a estados anteriores salvos, e restaurar outras versões do mesmo projeto com pouquissimo trabalho, ele permite também o trabalho em paralelo, por diferentes equipes em um mesmo projeto.

# Comandos mais utilizados

### Clonando repositório
```
git clone <endereco-do-repositorio>

git clone git@github.com:hyagocabrall/git-estudos.git
```

### Adicionando arquivos ao stage

Adiciona um novo arquivo ao **stage** (Área temporária que indica que o arquivo está preparado para commit).

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

Mostra as alterações realizadas no arquivo

```
git diff
```

### Criando branch

Cria uma nova branch e marca ela como selecionada

```
git checkout -b <nome_da_branch>
```

### Navegando entre a branch

Permite mudar a branch selecionada

```
git checkout <nome_da_branch>
```

### Excluindo branch

Exclui a branch selecionada

```
git checkout -d <nome_da_branch>
```

# Referências

https://rogerdudler.github.io/git-guide/index.pt_BR.html

# Autor
### Hyago Cabral
