# Comandos_Git


*Para subir um projeto existente na maquina local para o github* <br/>
git init <br/>
git remote add origin https://github.com/user/repo.git <br/>
git add . <br/>
git commit -m "primeiro commit" <br/>
git push origin master <br/>

*Para listar e trocar de branch no github* <br/>
git branch -a <br/>
git checkout nomeDaBranch <br/>

*Atualizar a branch com a main* <br/>
git checkout minhaBranch <br/>
git pull origin main --rebase <br/>

*Baixar uma branch específica* <br/>
git clone -b nome_da_branch link_do_git

*Utilizando git flow* <br/>
git flow init      //iniciando o git flow, irá iniciar a branch develop

git flow feature starts NOME_DA_BRANCH    //iniciando a branch feature a partir da develop <br/>
git flow feature publish NOME_DA_BRANCH    //Irá fazer push para develop e irá continuar <br/>
git flow feature finish NOME_DA_BRANCH    //finalizar a branch (irá excluir), após mandar para a develop <br/>


<img src="https://github.com/ElvisCostaOliveira/Comandos_Git/blob/main/image/git_flow.gif" width="620">


