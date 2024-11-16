<h1 style="color: #e98528">Card básico com foto  e animação usando HTML e SASS</h1>

[![Node.js](https://img.shields.io/badge/Node.js-16.x-339933.svg)](https://nodejs.org/) 
[![Sass](https://img.shields.io/badge/Sass-1.50.0-CC6699.svg)](https://sass-lang.com/)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=&logo=html5&logoColor=white)

<img src="https://i.imgur.com/NjAqIkj.gif" alt="Yumi">

Este projeto utiliza <b style="color: #e98528">Sass</b> para estilização.
Para executar este projeto, você precisará ter o <b style="color: #e98528">Node.js</b> e o <b style="color: #e98528">Sass</b> instalados em sua máquina.

<h3 style="color: #e98528">Requisitos</h3>

Antes de rodar o projeto, você precisa garantir que as seguintes ferramentas estejam instaladas:

- <b style="color: #e98528">Node.js</b>: A versão mais recente do Node.js pode ser baixada e instalada [aqui](https://nodejs.org/).
- <b style="color: #e98528">Sass</b>: Sass é uma linguagem de folhas de estilo que permite escrever CSS de forma mais eficiente. Para usá-lo, é necessário instalá-lo globalmente.

<h3 style="color: #e98528">Instalando o Node.js</h3>

1. Acesse o site oficial do [Node.js](https://nodejs.org/).
2. Faça o download e instale a versão recomendada (LTS) para o seu sistema operacional.
3. Após a instalação, abra o terminal e verifique se o Node.js foi instalado corretamente com o comando:

   ```bash
   node -v

<h3 style="color: #e98528">Instalando o SASS</h3>

1. Abra o terminal e digite o comando:
   ```bash
   npm install -g sass
2. Após a instalção ainda com o terminal aberto digite o comando:
   ```bash
   sass --version

<h3 style="color: #e98528">Iniciando o Projeto</h3>

1. Abra o terminal e navegue até a pasta do seu projeto.
2. Execute o comando abaixo para começar a compilar o arquivo Sass automaticamente:
   ```bash
   sass --watch styles.sass:styles.css

- O comando <b style="color: #e98528">sass --watch</b> faz com que o Sass "observe" o arquivo <b style="color: #e98528">styles.scss</b> e automaticamente gere o arquivo <b style="color: #e98528">styles.css</b> sempre que o arquivo Sass for alterado.
- <b style="color: #e98528">styles.scss:styles.css</b>: Define o arquivo de entrada <b style="color: #e98528">styles.scss</b> e o arquivo de saída <b style="color: #e98528">styles.css</b>.

1. Agora, você pode abrir o arquivo <b style="color: #e98528">index.html</b> no seu navegador para ver o projeto em funcionamento. A cada modificação no arquivo <b style="color: #e98528">styles.scss</b>, o Sass irá gerar o arquivo <b style="color: #e98528">styles.css</b> automaticamente e você verá as alterações no navegador ao atualizar a página.

<h3 style="color: #e98528">Estrutura do Projeto</h3>

O projeto contém os seguintes arquivos principais:

- <b style="color: #e98528">index.html</b>: O arquivo HTML principal com a estrutura da página.
- <b style="color: #e98528">tyles.sass</b>: O arquivo Sass que contém os estilos da página.
- <b style="color: #e98528">styles.css</b>: O arquivo CSS gerado a partir do arquivo <b style="color: #e98528">styles.sass</b>.