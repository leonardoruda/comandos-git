# Comandos
## git init - cria um repositório dentro da pasta atual;
## git status - mostra alterações pendentes de commit;
## git add -A - prepara todos os arqs modificados p/ um commit (stage changes);
## git commit -m "created index.html" - commita o arq c/ a msg;
## git status, git log - mostra respectivamente infos sobre alterações e os commits recentes (aperte q para sair da tela de log!);
## git restore foo - descarta alterações não commitadas;
## git reset --soft commit_id - volta p/ o commit especif., mantendo as alterações em staged (o --mixed tira os staged também);
## git reset --hard commit_id - volta p/ o commit especif e apaga as alterações;
## git branch css - cria uma branch "css"; git branch lista as branches;
## git checkout css - acessa a branch, modificações ñ afetam o master;
## git diff - mostra todas as alterações feitas, a serem comitadas;
## git checkout HEAD -- README.md - desfaz as alterações no arq selecionado;
## git remote add origin https://github.com/user/directory-name - links git local repository w/ remote repo (SSH possibly required);
## git push -u origin master - uploads changes to the remote;
## git revert --no-edit commit_id - faz um soft reset e mantém o último commit funcional;
