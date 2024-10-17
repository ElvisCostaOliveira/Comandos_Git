# Comandos_Git

*Para subir um projeto existente na maquina local para o github* <br/>
git init <br/>
git remote add origin https://github.com/user/repo.git <br/>
git add . <br/>
git commit -m "primeiro commit" <br/>
git push origin master <br/>

## *Para listar e trocar de branch no github* <br/>
git branch -a <br/>
git checkout nomeDaBranch <br/>

## *Atualizar a branch com a main* <br/>
git checkout minhaBranch <br/>
git pull origin main --rebase <br/>

## *Baixar uma branch específica* <br/>
git clone -b nome_da_branch link_do_git

## *Utilizando git flow* <br/>
git flow init      //iniciando o git flow, irá iniciar a branch develop

git flow feature start NOME_DA_BRANCH    //iniciando a branch feature a partir da develop <br/>
git flow feature publish NOME_DA_BRANCH    //Irá fazer push para develop e irá continuar <br/>
git flow feature finish NOME_DA_BRANCH    //finalizar a branch (irá excluir), após mandar para a develop <br/>

git flow release start 1.0    //Liberar para teste com numero de versão baseada na develop <br/>
git flow release finish 1.0    //Finaliza o teste e cria um merge para a main e develop (produção) <br/>
(importante: irá abrir uma tela para comentar, pode comentar e em seguida utiliza :wq! para salvar e sair)<br/>

git flow hotfix start 1.1     //hotfix para atualizar problemas na main<br/>
*git add . , git commit , git push ou git flow publish para continuar<br/>
git flow hotfix finish    //Finaliza o teste e cria um merge para a main e develop (produção) <br/>
(importante: irá abrir uma tela para comentar, precisa ser fechado para continuar)<br/>

*git push --all*    //atualização todas as branchs, necessariamente dar esse comando ao fim do desenvolvimento.<br/>
*git tags --all*    //atualização todas as tags, necessariamente dar esse comando ao fim do desenvolvimento.<br/>




<img src="https://github.com/ElvisCostaOliveira/Comandos_Git/blob/main/image/git_flow.gif" width="620">


