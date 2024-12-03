## Instruções de utilização
#### Pré requisitos:
1.  Dispor previamente ou instalar o [NPM](https://docs.npmjs.com/cli/v10/commands/npm-install "NPM") e o [Node.js](https://nodejs.org/en/download/package-manager/current "Node.js") (versões compatíveis a partir da v12.0.0) na máquina que executará a aplicação.
2. Para pleno uso do software, dispor previamente ou instalar o [MySQL](https://www.mysql.com/downloads/ "MySQL"). 

#### Instalação
1. Realizar o clone do repositório no diretório de sua preferência:

     `git clone https://github.com/lucio-alves/ProjFinalProjSoftware.git`

2. Acessar o SGBD MySQL pela intarface de sua preferência e executar o script [init_BD.sql](https://github.com/lucio-alves/ProjFinalProjSoftware/tree/main/drink-up/Codigo/BD/init_BD.sql "init_BD.sql") por completo. O Script encontra-se disponível no caminho:

    `ProjetoFinalProjStoftware/drink-up/Codigo/BD`

3. Via terminal, acessar a pasta backend, sugerido o comando abaixo:

	`cd /`***{caminho até o diretório onde realizou o clone}***`/ProjetoFinalProjStoftware/drink-up/Codigo/backend`

4. Após o passo 3, executar o comando abaixo para inicialização do servidor Node.js:

	`node app.js`

###### **Uma vez que os passos anteriores foram seguidos e o servidor Node.js foi executado com sucesso, a aplicação encontra-se pronta para uso!**

> Para melhor experiência, sugerimos o uso através da interface Web. Ao inicializar o servidor com o comando do passo 4, acesse a Home da aplicação digitando o caminho abaixo através de um navegador:
http://127.0.0.1:5500/Codigo/frontend/views/Home.html
