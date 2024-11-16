# Card básico com foto usando HTML e SASS

[![Node.js](https://img.shields.io/badge/Node.js-16.x-339933.svg)](https://nodejs.org/) 
[![Sass](https://img.shields.io/badge/Sass-1.50.0-CC6699.svg)](https://sass-lang.com/)
[![Html](https://img.shields.io/badge/html.svg)]

Este projeto utiliza **Sass** para estilização.
Para executar este projeto, você precisará ter o **Node.js** e o **Sass** instalados em sua máquina.

## Requisitos

Antes de rodar o projeto, você precisa garantir que as seguintes ferramentas estejam instaladas:

- **Node.js**: A versão mais recente do Node.js pode ser baixada e instalada [aqui](https://nodejs.org/).
- **Sass**: Sass é uma linguagem de folhas de estilo que permite escrever CSS de forma mais eficiente. Para usá-lo, é necessário instalá-lo globalmente.

### Instalando o Node.js

1. Acesse o site oficial do [Node.js](https://nodejs.org/).
2. Faça o download e instale a versão recomendada (LTS) para o seu sistema operacional.
3. Após a instalação, abra o terminal e verifique se o Node.js foi instalado corretamente com o comando:

   ```bash
   node -v

### Instalando o SASS

1. Abra o terminal e digite o comando:
   ```bash
   npm install -g sass
2. Após a instalção ainda com o terminal aberto digite o comando:
   ```bash
   sass --version

### Iniciando o Projeto

1. Abra o terminal e navegue até a pasta do seu projeto.
2. Execute o comando abaixo para começar a compilar o arquivo Sass automaticamente:
   ```bash
   sass --watch styles.sass:styles.css
- O comando **sass --watch** faz com que o Sass "observe" o arquivo **styles.scss** e automaticamente gere o arquivo **styles.css** sempre que o arquivo Sass for alterado.
- **styles.scss:styles.css**: Define o arquivo de entrada **styles.scss** e o arquivo de saída **styles.css**.

3. Agora, você pode abrir o arquivo **index.html** no seu navegador para ver o projeto em funcionamento. A cada modificação no arquivo **styles.scss**, o Sass irá gerar o arquivo **styles.css** automaticamente e você verá as alterações no navegador ao atualizar a página.

### Estrutura do Projeto

O projeto contém os seguintes arquivos principais:

- **index.html**: O arquivo HTML principal com a estrutura da página.
- **tyles.sass**: O arquivo Sass que contém os estilos da página.
- **styles.css**: O arquivo CSS gerado a partir do arquivo **styles.sass**.