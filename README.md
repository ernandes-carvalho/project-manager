# README #

# Configura��es do novo repositorio git #
Baixar e instalar o git bash vers�o 2.14.1 para windows, o programa vai permitir configurar o ambiente
link: https://git-scm.com/downloads 
Ap�s fazer a instala��o: navegar at� a pasta do projeto pelo promp e executar os comando abaixo, tenha certeza que est� dentro do diret�rio.

git init
git remote add origin '{local onde se encontra o projeto}'
git flow init
git fetch && git checkout master
git push -u origin master
git config core.autocrlf true
git pull


# Comandos Git Bash #

# Exemplo  -  mensagem #
git pull 	=> Pegar os arquivos e atualiza��es do reposit�rio remoto;
git add  	=> Adiciona os arquivos alterados no reposit�rio local para ser enviados ao reposit�rio remoto;
git commit -m "mensagem" => Comita os arquivos que foram adicionados;  
git push 	=> Envia as altera��es do reposit�rio local para o reposit�rio remoto.

OBS: Sempre que for executado em um commit � necess�rio executar o git push.     
