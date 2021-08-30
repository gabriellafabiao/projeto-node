# projeto-node

### Iniciar um projeto node no gitHub
Criar um repositório (private ou public) Escolher a tecnologia (.gitignore), caso disponível Escolher a opção README.md

### Clonar o projeto para o computador local
Escolher a pasta correspondente aos seus projetos Escolher um editor eficiente (VsCode, Atom, SublimeText, NetBeans, WebStorm ...)

Tendo acesso ao prompt de comando

-> git clone "endereço do projeto no git hub"

Iniciar o arquivo de configuração package.json
-> npm init -y

### instalação de dependencias e manipulação git "na escola"
  ### antes de instalar qualquer dependência (basta 1 vez)
   npm set strict-ssl false 
   npm config set resgistry https://registry.npmjs.org/
  ### antes de enviar para o gitHub(basta 1 vez)
    git config --global http.sslVerify false 


### Instalação de dependencias
Sempre pesquisar a tecnologia no site que contém a documentação oficial exemplo (npm, yarn ) Exemplo:

-> npm install express -> yarn add express

Obs: A pasta node_modules contém todas as tecnologias (dependencias) de terceiros

Desinstalando uma dependencia
Não excluir qualquer pasta dentro de node_modules

-> npm uninstall express (por exemplo)

### Instalação como devdependencies
( São tecnologias utilizadas apenas durante o desenvolvimento do projeto em específico ) npm install nodemon -D (por exemplo)

Iniciando tecnologias ou scripts utilizando atalhos
No package.json

"scripts": { "morango": "nodemon server.js" }

No prompt vc executa: npm run morango

### Token de authenticação 
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