# Git

Git é um sistema de controle de versões distribuído, usado principalmente no desenvolvimento de software, ele pode ser usado para registrar histórico de alterações de qualquer tipo de **ARQUIVO** (Exemplo: alguns livros digitais são disponibilizados no GitHub e escrito aos poucos publicamente). O Git foi inicialmente projetado e desenvolvido por **Linus Torvalds** para o desenvolvimento do kernel Linux, mas foi adotado por muitos outros projetos e hoje é um dos maiores e melhores modelos de versionamento que existe.

> Fonte: https://pt.wikipedia.org/wiki/Git
  
## Documentação Oficial

https://git-scm.com/

## Livro Git
https://git-scm.com/book/pt-br/v2
https://github.com/progit/progit2-pt-br/releases/download/2.1.46/progit.pdf
  
## Download
https://git-scm.com/download/

## Onde aprender Git
https://git-scm.com/book/pt-br/v2
 
## Cursos Gratuitos
https://comunidade.ada.tech/cursos/37f4b5d2-dbab-4c45-ab61-aac1ba2c7d19
  

## Github
Apesar de ser possível criarmos nosso próprio servidor de Git, neste documento iremos abordar o uso com base no github que hoje é a maior plataforma do git como serviço.

## Comandos de uso diário
Este guia apresenta uma breve explicação dos comandos básicos do Git para iniciantes.

## git clone \<repo name\>

O comando `git clone` é usado para criar uma cópia local de um repositório remoto existente. Basta fornecer o nome do repositório que você deseja clonar. Por exemplo:

```ssh
git clone https://github.com/usuario/nome-do-repositorio.git
```

## git commit -m 'my message'
O comando `git commit` é usado para salvar as alterações realizadas nos arquivos do repositório. Você precisa adicionar uma mensagem que descreva as alterações feitas usando a opção `-m`. Por exemplo:
```ssh
git commit -m "Corrigido um bug na função de login"
```

## git add \<file add\>

O comando `git add` é usado para adicionar arquivos ao índice do Git, preparando-os para serem incluídos no próximo commit. Você pode adicionar arquivos específicos ou usar um curinga para adicionar vários arquivos de uma vez. Por exemplo:
```ssh
git add arquivo.txt
```

## git status

O comando `git status` exibe o estado atual do seu repositório. Ele mostra quais arquivos foram modificados, adicionados ou removidos, e se estão prontos para serem commitados.
```ssh
git status
```

## git push origin \<branch name\>

O comando `git push` é usado para enviar as alterações locais para um repositório remoto. Você precisa especificar o nome do repositório remoto e o nome do branch para onde deseja enviar as alterações. Por exemplo:
```ssh
git push origin main
```

## git pull

O comando `git pull` é usado para buscar e mesclar as alterações remotas em seu repositório local. Isso atualiza seu repositório local com as últimas alterações do repositório remoto. Por exemplo:
```ssh
git pull origin main
```

## git branch

O comando `git branch` é usado para listar, criar ou excluir branches. Quando usado sem argumentos, ele lista todas as branches existentes no repositório. Por exemplo:
```ssh
git checkout develop
```

## git branch

O comando `git branch` é usado para listar, criar ou excluir branches. Quando usado sem argumentos, ele lista todas as branches existentes no repositório. Por exemplo:
```ssh
git branch
```