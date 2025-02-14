git config --global user.name "Seu Nome" -> inclui a credencial do seu nome.
`git config --global user.email "Fuhielb550@gmail.com"`-> inclui a credencial do seu e-mail.
git init -> iniciliza o repositório local
git status -> exibe se os arquivos/pastao estão adicionados ao repositório.
git add nome_do_arquivo -> vc adiciona o arquivo ao repositório local
git add . -> voce adiciona todos os arquivos modificados/criados no repositório local.
git branch -M main -> altera o nome da branch principal de master para main.
git commit -m "Mensagem de atualização" -> cria um comit para que seja realizado um novo versionamento.git 
git log -> lista todos os commits que foram realizados.
git log --oneline --graph --decorate -> forma compacta de exibir os commits
git remote add origin https://exemplo.com/repositorio -> realiza a sincronização do repositório local com o remoto
git push -u origin main ->  envia as informações do repositório local para o remoto