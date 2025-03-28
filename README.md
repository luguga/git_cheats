# git_cheats
cheats for using GIT for anyone

using git switch insted git checkout
usando git switch ao invés de git checkout

nova feature: git switch -c branch/nome_feature
só trocar: tirar o parametro "-c"

isso funciona bem no lugar do git checkout -B ou o git checkout sem parametro.

processos de criação

dentro da master usar o comando para sincronizar a master 
git pull
na sequência digitar o comando de criação
git switch -c branch/nova_feature

pronto para desenvolver

durante o desenvolvimento verifique as mudanças, aparecerão em vermelho
git status

adicione as mudanças
git add (nome da mudança)

finalizar
git commit -m "nome_feature | título do que mudou"

sincronize com a nuvem (origin)
git push
