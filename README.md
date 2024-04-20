### Subindo seu repositório no GitHub através da linha de comando
Um passo a passo rápido para quem pretende subir o seu repositório no GitHub!
No GitHub, crie um novo repositório. Na tela onde pede para fazer upload ou criar aquivos, 
guarde o link HTTPS que será gerado
Abra o Git Bash ou terminal na pasta onde está o seu projeto

Inicie a pasta como um repositório do Git através do comando:
git init

git config --global user.name "Anderson Moreira da Silva"

git config --global user.email anderson.tecnicoprogramador@hotmail.com

Em seguida, adicione os arquivos de configuração para preparar o commit:
git add .

Opcional: Adicione um arquivo readme caso não tenha iniciado o repositório com ele:
git add README.md

Crie um novo commit para os arquivos que irá subir para o repositório:
git commit -m "first commit"

Suba seus arquivos utilizando a URL gerada no passo 2 no seguinte comando:
git remote add origin URL-GERADA-PELO-PASSO-2-AQUI
![LiDhHSW](https://github.com/andersontecnicoprogramador/site-pegadinha-do-mallandro/assets/68762932/f5546d0e-1ad2-4b42-85c0-b0fd1fcc688c)


Autorize o upload com seu login e senha:
git push -u origin master
