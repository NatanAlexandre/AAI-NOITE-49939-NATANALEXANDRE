# AAI-NOITE-49939-NATANALEXANDRE
AAI-NOITE-49939-NATAN ALEXANDRE DE JESUS BRAZ
<hr>
<h1>1 - Como criar uma documentação detalhada com o passo a passo para "como criar um projeto React Native do zero e subir no GitHub":</h1>

<h2>// Comandos React Native:</h2>
  // Preparando o ambiente para o projeto com Expo (instalando o Expo através do Node.JS):
  npm install --global expo-cli

  // Após a instalação é necessário dar inicio ao seu projeto Expo:
  expo init NomeDoProjeto

  // Verificar se o projeto foi instalado e configurado corretamente iniciando o projeto Expo
  // Entrar no repositório do projeto:
  expo start

<h2>// Comandos Github:</h2>
  // subir projeto no Github (no diretório do projeto):
  git init

  // Para adicionar todos os arquivos e mudanças do projeto no repositório git:
  git add .

  // Criando README.md (Opcional):
  git add README.md

  // criar commit para subir o projeto para o git:
  git commit -m "nome commit"

  // conectar git ao github para subir o repositório:
  gir remote add origin URL-DO-GIT

  // subir projeto na branch master:
  git push -u origin master

  // após esses passos é só iniciar seu projeto:
  npm run start
  <hr>

<h1>2 - Como clonar o projeto da nossa aula e rodá-lo (O processo que seguimos no início de cada aula):</h1>

// Comandos:
  // Previamente buscar no github a URL do repositório que quer clonar (estamos usando o link "https://github.com/GuilhermeCamargo744/aula-fecaf-noite-dog-ever-match.git" para ilustrar):
  git clone https://github.com/GuilhermeCamargo744/aula-fecaf-noite-dog-ever-match.git

  // para acessar o projeto use o change directory para a raiz do projeto:
  cd C://RAIZDOPROJETO

  // Após estar na Raiz do projeto, mude para a branch desejada:
  git checkout branchDesejada
  
<hr>
<h1>Extra</h1>
Para atualizar o projeto react (com Expo) clonado com as atualizações feitas no github

(Necessário commitar ou descartar mudanças feitas previamente no código)

// Abra a Raiz do projeto e use o comando git:
  git pull

// Para mudar para a branch para a branch nova:
  git checkout branchNova

// Instalar as dependências do Node.JS:
  npm install

// Rodar projeto
  npm run start
