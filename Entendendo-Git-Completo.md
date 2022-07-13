## Git 

Essencial para versionar o código, deixar tudo mais organizado e mais fácil para se trabalhar, embora tenha uma pequena curva de aprendizado, depois de aprender Git seus trabalhos serão muito mais otimizados.

**Comandos básicos**

```
- git clone
- git pull
- git status
- git add .
- git commit -m "Adicionando mensagem de commit"
- git push origin main (master, develop, homolog...)

```
Irei explicar cada comando separadamente e adicionar mais comandos, além de como resolver conflitos.

___
**Comando ```git clone```**

Esse comando cria uma cópia de um repositório git já existente podendo ser local ou remoto, esse repositório git completo só seu, com seu histórico e seus arquivos está isolado como um todo do repositório original.
___
**Comando ```git pull```**

Esse comando atualiza o seu repositório de acordo com o que existir no repositório originial, importante dizer que ele atualizará de acordo com a branch em que estiver, ou seja, se estiver na branch "Master" atualizará com os dados do repositório da Master, se estiver na branch "Main" atualizará com os dados do repositório da Main
___
**Comando ```git status```**

Esse comando lista todos os arquivos que foram modificados de alguma forma dentro da branch em que você está mexendo.
___
**Comando ```git add .``` ou ```git add nome-do-arquivo```**

Com o comando ```git add .``` adicionamos todas as modificações realizadas de uma só vez e o comando ```git add nome-do-arquivo``` adiciona as mudanças em algum arquivo específico
___
**Comando ```git commit```**

Esse comando é usado quando queremos capturar e salvar o estado atual do repositório, para adicionar uma mensagem neste commit podemos acrescentar -m na frente e entre aspas digitar nossa mensagem

Ex:
```git commit -m "Meu primeiro commit"```
___
**Comando ```git push```**

Esse comando é usado quando queremos enviar nossas alterações locais ao repositório remoto, nosso repositório original.
___

> Parte para correção do erro _! [rejected]   feature/my_feature_branch -> feature/my_feature_branch (non-fast-forward)_

```
git fetch
git rebase feature/my_feature_branch
git push origin feature/my_feature_branch
```
