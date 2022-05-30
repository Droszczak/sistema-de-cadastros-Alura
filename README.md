# Sistema de Cadastro de jogos

> https://guilhermeonrails.github.io/manual-do-git-e-github/


> Status do Projeto: Em desenvolvimento

```
node app.js

comandos git:
clonar o projeto no seu pc: git clone  https://github.com/Droszczak/sistema-de-cadastros-Alura.git
clonar é só na primeira vez.

visualizar as pastas: ls
visualizar as modificações: git log para sair digitar q
visualizar apenas um linha da atualização: git log --oneline
para ver se tem novas atualizações: git pull https://github.com/Droszczak/sistema-de-cadastros-Alura.git

O comando git push é usado quando você deseja enviar as alterações realizadas no seu repositório local para um repositório remoto.

git add .
git commit -m "mensagem de commit"
git push origin main

Para enviarmos as alterações de um repositório local para um repositório remoto é preciso adicionar os arquivos com o git add . e depois fazer o commit com git commit. Feito isso é possível enviar/empurrar as alterações para o repositório remoto utilizando o git push origin main.
```
```
Se você deseja verificar o histórico de alterações, as mensagens de commits, o nome do autor daquele commit e outras informações sobre o projeto, existe um comando do git que pode te ajudar. Este comando é o git log.

Como já sabemos, os commits possuem hashs que os identificam de uma forma única, isto é, não existem dois commits com o mesmo hash. Com o git log podemos ver o hash e várias outras informações do commit.

Podemos visualizar todos os commits, um em cada linha com o comando:

git log --oneline
Se, em vez de menos informações, quisermos ver mais como as alterações do commit, podemos usar:

git log -p
Também podemos pesquisar as informações do autor daquele commit com o comando:

git log --author="user_name"
E pesquisar informações por data:

git log --since=1.month.ago --until=1.day.ago
No comando acima, estamos buscando as informações do commit desde um mês atrás até um dia atrás.

Você também pode formatar a visualização das informações de commit com o comando:

git log --pretty="format:%h %s"
Este traz o hash seguido da mensagem de commit. Para saber mais formas de exibir as informações de commit, aqui tem uma lista de maneiras que você pode fazer isso.

Bem legal, não é? E se eu te contar que existem vários outros parâmetros que podemos passar no git log? Se você deseja saber mais sobre como exibir as informações de seus commits, você pode conferir neste link.
```
