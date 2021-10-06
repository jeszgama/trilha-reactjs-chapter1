# Trilha-ReactJS

# Criando estrutura do projeto

## Inicializando o Node.Js

### Criar o package .json:

`yarn init -y`

### ou

`npm init -y`

### Criando uma biblioteca (react):

`yarn add react`

### React dom

`yarn add react-dom`

- Forma de trabalhar com o react na web
- dom = arvore de elementos da aplicação
- utilizado para criação de interfaces

# Babel

## Babel é um compilador JavaScript

### Instalando Babel

`yarn add @babel/core @babel/cli @babel/preset-env -D`

- @babel/core = biblioteca do babel
- @babel/cli = para executar o babel atraves do terminal
- @babel/present-env = é uma extensao do babel que identifica qual ambiente a aplicação ta sendo executada para converter o codigo da melhor maneira possível

### Convertendo código

`yarn babel src/index.js --out-file dist/bundle.js`

- yarn babel = cli
- src/index.js = endereço do arquivo que quero converter
- --out-file = qual arquivo quero gerar a partir do inicial
- dist/bundle.js = criei uma pasta e um arquivpo

### Pra entender o código react :

`yarn add @babel/preset-react -D`

# Webpack

[Webpack](https://webpack.js.org/)

### Instalando Webpack

`yarn add webpack webpack-cli webpack-dev-server -D`

`yarn add babel-loader -D `

### Instalando dependencia de desenvolvimento

`yarn add html-webpack-plugin -D`

### Instalando o Webpack dev server:

`yarn add webpack-dev-server -D`

## Comandos:

`yarn`

- instala node_modules/diretórios

`yarn webpack`

- executar no browser

`yarn dev`

- ambiente dev

`yarn build`

- ambiente de produção

# Imutabilidade

- Uma variável nunca vai ter seu valor alterado, ela sempre vai receber outro valor

### Exemplo:

`usuarios = ['jessica', 'vitoria', 'gabriel']`

### quando adicionar outro usuario tenho que criar outra variavel para adicionar o valor desejado, exemplo:

`novoUsuarios = [...usuarios, 'william']`
