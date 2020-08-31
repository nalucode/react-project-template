# Template de Projeto React

Esse repositório contém um projeto React utilizando loaders, webpack, babel, e outras ferramentas que uso para desenvolver.

## Como começar

Essa sessão de instrui como clonar esse projeto para sua máquina e rodar o projeto.

### Pré-requisitos

É necessário que tenha o `nodejs` e o `npm` ou `yarn` instalados em sua máquina.

#### Verificando se o nodejs está instalado.

```
node -v
```
#### Verificando se o npm está instalado.

```
npm -v
```
#### Verificando se o yarn está instalado.

```
yarn -v
```

### Instalação

Nesta sessão você tem um guia passo a passo de como rodar o projeto em sua máquina

Acessando no terminal o diretório em que quer instalar o projeto, execute o seguinte comando:
 

```
$ git clone git@github.com:nalucode/react-project-template.git
```

Acesse a pasta que foi criada no seu diretório

```
$ cd react-project-template
```

Agora você já tem o projeto em sua máquina para executar.


### Iniciando servidor de desenvolvimento

Com o diretório do projeto aberto no seu terminal, execute o comando

```
yarn dev
```
ou
```
npm dev
```
Com isso, um servidor live-reload será aberto em `localhost:8080`

<hr/>

## Deploy

Com o projeto pronto para publicar, você poderá executar o passo a passo para gerar o projeto otimizado para produção.

Com o projeto aberto no seu terminal, execute o seguinte comando para criar os arquivos otimizados:

```
$ yarn build
```
Após isso, um arquivo `bundle.js` será criado no diretório `public` dentro do seu projeto.

Caso queria testar localmente, com o `python` instalado em sua máquina, dentro da pasta `public` do seu projeto execute o seguinte comando

```
$ python http.server 8000
```

Agora basta acessar `localhost` em seu navegador e o projeto otimizado 

<hr/>

## Extras

Há dois scripts dedicados ao lint disponíveis:

- ```yarn lint``` irá procurar em todo o conteúdo de `/src` por erros de código ou pattern

- ```yarn lint:fix``` irá corrigir erros em todo o conteúdo de `/src`

<hr/>

## Feito com

* [Webpack](https://webpack.js.org/) - Module bundler
* [ReactJs](https://reactjs.org/) - Framework web
* [Babel](https://rometools.github.io/rome/) - Javascript compiler
* [ESLint](https://eslint.org/) - Javascript/JSX lint
* [Prettier](https://prettier.io/) - Code formatter

