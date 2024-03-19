<h1 align="center">Curso de Git e Github</h1>

<h2>Sobre</h2>

<p>Projeto utilizado para aprender e executar os comandos básicos do Git</p>

## Comandos
<div>
    <p>git init - inicilaizar um repositório</p>
    <p>git config --global user.name/user.emal "nomeUsuário"/"emailUsuario"  - configurar o user name e o email</p>
    <p>git add . - adicionar os arquivos para se fazer o commit</p>
    <p>git branch -M main - determinar a branch principal</p>
    <p>git commit -m "mensagem" - fazer os commits dos arquivos</p>
    <p>git remote add origin endereçoRepositorio ... - fazer a conexão entre o repositório remoto e o local</p>
    <p>git push origin main - subir as alterações do repositório local para o repositório remoto</p>
    <p>git status - verificar o status do git</p>
    <p>git log - exibe o historico de commits</p>
    <p>git revert idCommit - reverte "ctrl-z" em um commit</p>
    <p>git reset --hard idCommitAnteriror - apaga um commit</p>
    <p>git commit --amend -m "mensagem" - altera um commit</p>
</div>

<p>No curso também foi ensinado a utilizar o Source Control do VSCode</p>
<<<<<<< HEAD

## Outros comandos - Comandos
<p>git log --oneline</p>
<p>git log -p</p>
<p>git log --graph</p>
<p>git log --pretty</p>
<p>git show (hash do commit)</p>
<p>git diff</p>
<p>git diff b290d29..7515bd7  - mostra a diferença entre dois estados (entre dois commits)</p>
<p>git switch -c novo-branch   - cria um novo branch e troca para este branch criado</p>
<p>git merge novo-branch  - mescla as etapas</p>
<p>git branch -d novo-branch - remove essa branch do repósitorio local</p>
<p>git push origin :novo-branch - remove a branch do respósitorio remoto</p>
<p>git rebase main - todos os commits da main que não estiver no novo-branch e atualiza a branch</p>
<p>git stash - guarda uma alteração para recuperar depois</p>
<p>git stash list - listar as alterações guardadas</p>
<p>git stash pop - recupera a ultima alteração guardada</p>
<p>git stash clear - limpa a stach</p>
<p>git stash push -m "msg" - cria um stash com uma mensagem personalizada</p>
<p>git stash apply (índice do stach)</p>
<p>git restore . - restaura o projeto para o ultimo commit (serve para quando a alteração não foi commitada)</p>
<p>git restore --staged (arquivo) - restaura o projeto para antes do add</p>
<p>git restore --source=hash-do-commit (arquivo) - restaura o projeto para um commit especifico</p>
<p>git tag nome_tag - cria uma tag para marcar um check point</p>
<p>git push origin --tags  - envia todas as tags para o repositório remoto</p>
<p>git cherry-pick hash_commit - pega o commit de outra branch e traz para a branch atual</p>
<p>git blame (nome_arquivo) - mostra o responsável por cada commit</p>
=======
>>>>>>> 773250d8f749103d879a291cbc87960b15c6690b
