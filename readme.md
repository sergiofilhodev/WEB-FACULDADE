# Serve para iniciar um repositório localmente
    git init
# Prepara o arquivo(s) para um estado de preparação
    git add <name-with-file>
# Escrever a mensagem no commit para deixar registrado
    git commit -m "mensage commit"
# Enviar/empurrar as alterações feitas para o repositorio local ou remoto/github
    git push
# Puxar/carregar alterações do repositorio local ou feita
    git pull
# Mostra qual branch atual está
    git branch
# Criar uma branch/ramificação
    git checkout -b <name-with-branch>
    or
    git branch <name-with-branch>
# Deletar branch
    git branch -d <name-with-branch>
# Entrar na branch inserida
    git checkout <name-with-branch>
# Mesclar branch atual com a branch inserida para "clonar"
    git merge <name-with-branch-to-merge>