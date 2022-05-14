# Devstart Paylivre

Lista de comandos Git passados durante as aulas do programa Devstart.


## Lista de Comandos

**git config --global user.name "Nome do Autor"**
>Define o nome que será usado na criação de todos os repositórios.

**git config --global user.email "email@email.com"**
>Define o email que será usado na criação de todos os repositórios.

**git**
>Mostra uma lista de diversos comandos possíveis, como uma breve explicação de cada um.

**git init**
>Inicializa um repositório vazio.

**git status**
>Mostra algumas informações sobre o repositório.

**git add 'Nome do Arquivo'**
>Inclui o arquivo na lista do que será commitado.

**git add .**
>Inclui todos os arquivos não-rastreados na lista do que será commitado.

**git rm --cached 'Nome do Arquivo'**
>Exclui o arquivo da lista do que será commitado.

**git commit -m "Nome do Commit"**
>Commita os arquivos rastreados.

**git log**
>Mostra informações sobre commits feitos, onde foram feitos, quem fez, quando fez, e o nome do commit.

**git log --oneline**
>Abre a log de commits feitos, com informações em uma linha.

**git branch**
>Lista as branchs locais criadas e mostra com * qual está selecionada.

**git branch nome_da_branch**
>Cria uma nova branch. É aconselhável utilizar - ou _ para separar os nomes, escrever em letras minúsculas e não utilizar caracteres especiais.

**git checkout nome_da_branch**
>Seleciona a branch especificada.

**git checkout -b nome_da_branch**
>Cria uma nova branch e com o comando -b já seleciona a branch criada.

**git branch -d nome_da_branch**
>Deleta a branch especificada.

**git merge nome_da_branch**
>Substitui ou atualiza o conteúdo da branch em que se está, no momento, pela branch especificada na descrição do comando merge.

**git clone endereço_do_repositório**
>Clona o repositório especificado no endereço para a máquina local.

**git remote -v**
>Identifica a origem dos repositórios remotos.

**git push**
>Envia o commit para o repositório remoto.

**git push --set-upstream origin nome_do_novo_repositorio**
>Envia o commit para o repositório remoto criando uma nova branch.

**git stash**
>Reserva os arquivos alterados para serem commitados em outro momento.

**git stash --include-untracked**
>Reserva os arquivos alterados para serem commitados em outro momento, incluindo os untracked.

**git stash list**
>Lista os stashs disponíveis.

**git stash pop**
>Retorna com os arquivos para branch.

**git stash pop stach@{número_da_stash}**
>Caso haja mais de uma stash salva, pode-se definir qual stash retornar, selecionando pelo número dela.

**git pull**
>Baixa o repositório remoto para máquina local.

**git revert código_hash_do_commit**
>Reverte para o commit selecionado através da hash que é apresentada no comando git log.

**git revert --abort**
>Aborta o reverte que estava sendo feito.