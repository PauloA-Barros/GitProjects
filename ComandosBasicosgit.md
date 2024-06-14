Vamos descrever cada um dos comandos do Git em ordem, explicando seu propósito e uso.

1. git init
O comando git init é usado para inicializar um novo repositório Git. Ele cria um diretório .git que contém todos os arquivos necessários para o repositório.

2. git remote add
O comando git remote add é usado para adicionar um repositório remoto ao seu projeto local. Isso permite que você interaja com repositórios remotos.

3. git add
O comando git add é usado para adicionar arquivos ao índice (staging area), preparando-os para um commit.

4. git commit
O comando git commit grava as mudanças adicionadas no índice (staging area) no repositório local. Ele cria uma nova revisão/commit no histórico do projeto.

5. git branch
O comando git branch é usado para listar, criar ou excluir ramos (branches).

6. git push
O comando git push é usado para enviar commits locais para um repositório remoto. Ele atualiza o repositório remoto com os commits do repositório local.

7. git pull
O comando git pull é usado para buscar e integrar (merge) mudanças de um repositório remoto para a branch atual do repositório local.

8. git log
O comando git log é usado para visualizar o histórico de commits. Ele mostra uma lista detalhada de todos os commits.
O comando git log --oneline é uma variação que mostra o histórico de commits em uma linha por commit, fornecendo uma visão mais concisa.

9. git stash
O comando git stash é usado para salvar mudanças temporárias de trabalho que você não deseja fazer commit imediatamente. Ele armazena as mudanças em uma pilha de stashes.

10. git stash pop
O comando git stash pop aplica as mudanças do stash mais recente e remove-o da pilha de stashes.

11. git restore
O comando git restore é usado para restaurar arquivos no diretório de trabalho. Pode ser usado para desfazer mudanças em arquivos que ainda não foram commitados.

12. git reset --hard
O comando git reset --hard redefine o índice (staging area) e o diretório de trabalho para o estado do commit especificado, descartando todas as mudanças locais.

13. git reset --soft
O comando git reset --soft redefine o HEAD para o commit especificado, mas mantém as mudanças no índice (staging area) e no diretório de trabalho.

14. git merge
O comando git merge é usado para unir duas ou mais branches em uma única branch. Ele integra as mudanças da branch especificada na branch atual.