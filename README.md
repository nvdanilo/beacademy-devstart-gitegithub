# beacademy-devstart-gitgithub

# Lista de Comandos

git config --global user.name "Nome do Autor"
// Define o nome que será usado na criação de todos os repositórios.

git config --global user.email "email@email.com"
// Define o email que será usado na criação de todos os repositórios.

git
// Mostra uma lista de diversos comandos possíveis, como uma breve explicação de cada um.

git init
// Inicializa um repositório vazio.

git status
// Mostra algumas informações sobre o repositório.

git add 'Nome do Arquivo'
// Inclui o arquivo na lista do que será commitado.

git add .
// Inclui todos os arquivos não-rastreados na lista do que será commitado.

git rm --cached 'Nome do Arquivo'
// Exclui o arquivo da lista do que será commitado.

git commit -m "Nome do Commit"
// Commita os arquivos rastreados.

git log
// Mostra informações sobre commits feitos, onde foram feitos, quem fez, quando fez, e o nome do commit.

git branch
// Lista as branchs locais criadas e mostra com * qual está selecionada.

git branch nome_da_branch
// Cria uma nova branch. É aconselhável utilizar - ou _ para separar os nomes, escrever em letras minúsculas e não utilizar caracteres especiais.

git checkout nome_da_branch
// Seleciona a branch especificada.

git checkout -b nome_da_branch
// Cria uma nova branch e com o comando -b já seleciona a branch criada.

git branch -d nome_da_branch
// Deleta a branch especificada.

git merge nome_da_branch
// Substitui ou atualiza o conteúdo da branch em que se está, no momento, pela branch especificada na descrição do comando merge.

git clone endereço_do_repositório
// Clona o repositório especificado no endereço para a máquina local.

git remote -v
// Identifica a origem dos repositórios remotos.

git push
// Envia o commit para o repositório remoto.