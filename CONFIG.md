# Configuração do GIT

## Identificação ##

A primeira coisa que você deve fazer ao instalar o **Git** é configurar seu nome de usuário e endereço de e-mail. Isto é importante por que cada commit usa estas informações, e ela é carimbada de forma imutável nos commits que você começa a criar.

### Listando as configurações
```
git config --list
```

### Configurando o usuário do commit
```
git config --global user.email "seu@e-mail"

git config --global user.name "seu nome"

```
## Editor ##

Agora que sua identidade está configurada, você pode escolher o editor de texto padrão que será chamado quando **Git** precisar que você digite alguma mensagem. Por padrão o editor é o Vim.

```
git config --global core.editor "nome_editor"
```

