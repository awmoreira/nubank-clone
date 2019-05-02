<!--
*** Obrigado por estar vendo o nosso README. Se você tiver alguma sugestão
*** que possa melhorá-lo ainda mais dê um fork no repositório e crie uma Pull
*** Request ou abra uma Issue com a tag "sugestão".
*** Obrigado novamente! :D
-->

<!-- PROJECT SHIELDS -->

[![GitHub issues](https://img.shields.io/github/issues-raw/rocketseat/react-native-template-rocketseat-basic.svg)](https://github.com/awmoreira/nubank-clone/issues)
[![GitHub last commit](https://img.shields.io/github/last-commit/rocketseat/react-native-template-rocketseat-basic.svg)](https://github.com/awmoreira/nubank-clone/commits/master)
[![NPM](https://img.shields.io/npm/l/react-native-template-rocketseat-basic.svg)](https://choosealicense.com/licenses/mit)

<!-- PROJECT LOGO -->
<br />
<p align="center">
   <h3 align="center">Nubank App (React Native)</h3>
</p>
<p align="center">
   <a href="https://ibb.co/vmyGDvT"><img src="https://i.ibb.co/DkcyLgv/screenshot-2019-05-02-15-45-11-767.png" alt="screenshot-2019-05-02-15-45-11-767" border="0"></a>
</p>

<!-- ABOUT THE PROJECT -->

## Sobre o Projeto

Este projeto foi desenvolvido através de um vídeo publicado pela Rocketseat, onde é feito a interface do app da Nubank e suas animações.
De uma forma simples, a finalidade é disponibilizar o projeto para estudo e aprendizado.

### Feito Com

Abaixo segue o que foi utilizado na criação deste app:

- [React Native](http://facebook.github.io/react-native/) - O React Native é um framework que permite o desenvolvimento de aplicações mobile usando Javascript e React;
- [React Navigation](https://reactnavigation.org/) - O React Navigation surgiu da necessidade comunidade do React Native de uma navegação de forma fácil de se usar, e escrita toda em Javascript;
- [React Native Gesture Handler](https://kmagiera.github.io/react-native-gesture-handler/) - API declarativa que permite a manipulação de toques e gestos no React Native;
- [Styled-components](https://www.styled-components.com/) - O Styled-component permite utilizar a sintaxe CSS real dentro de seus componentes (CSS-in-JS);
- [React Navtive Vector Icons](https://oblador.github.io/react-native-vector-icons/) - Perfeito para botões, logos, barras de navegação, ícones. Fácil de utilizar em seu projeto;
- [Axios](https://github.com/axios/axios) - O Axios é um cliente HTTP baseado em Promises para Browser e NodeJS;
- [Prop Types](https://github.com/facebook/prop-types) - Verificação de tipo em tempo de execução para propriedades (props) React e objetos semelhantes;
- [Reactotron](https://github.com/infinitered/reactotron) - O Reactotron é um app Desktop para inspecionar projetos em React ou React Native. Está disponível para macOS, Linux e Windows;
  - [reactotron-react-native](https://github.com/infinitered/reactotron/blob/master/docs/quick-start-react-native.md) - Plugin para configurar o Reactotron para se conectar ao projeto React Native;
- [Babel](https://babeljs.io/) - O Babel é um compilador JavaScript gratuito e de código aberto e transpiler configurável usado no desenvolvimento de aplicações Javascript;
  - [babel-eslint](https://github.com/babel/babel-eslint) - Este pacote é um _wrapper_ do parser do Babel para o ESLint;
  - [babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) - Esse plugin do Babel permite que sejam feitos imports e requires em caminhos baseados em uma raiz(root);
- [Eslint](https://eslint.org/) - O ESLint é uma ferramenta de lint plugável para JavaScript e JSX;
  - [eslint-config-airbnb](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb) - Este pacote fornece o .eslintrc do Airbnb como uma configuração compartilhada extensível;
  - [eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) - Plugin do ESLint com regras para ajudar na validação de imports;
  - [eslint-plugin-jsx-a11y](https://github.com/evcohen/eslint-plugin-jsx-a11y) - Verificador estático AST das regras do a11y em elementos JSX;
  - [eslint-plugin-react](https://github.com/yannickcr/eslint-plugin-react) - Regras de linting do ESLint específicas do React;
  - [eslint-plugin-react-native](https://github.com/Intellicode/eslint-plugin-react-native) - Regras de linting do ESLint específicas do React Native;
  - [eslint-import-resolver-babel-plugin-root-import](https://github.com/olalonde/eslint-import-resolver-babel-root-import) - Um resolver da lib _babel-root-import_ para a lib _eslint-plugin-import_;
- [EditorConfig](https://editorconfig.org/) - O EditorConfig é um formatador de arquivos e coleções em forma de Plugin para Editores de código/texto com o objetivo de manter um padrão de código consistente entre diferentes editores, IDE's ou ambientes;

<!-- GETTING STARTED -->

## Começando

Para conseguir utilizar o app, é necessário apenas que você possua uma conta no (http://github.com).

### Pré-requisitos

Antes de seguirmos para as configurações e uso do app, é ideal que você tenha o ambiente configurado para criar e testar aplicativos em React Native, para isso você pode seguir o guia do link abaixo:

[Ambiente React Native (Android/iOS)](https://github.com/Rocketseat/ambiente-react-native)

### Estrutura de Arquivos

A estrutura de arquivos está da seguinte maneira:

```bash
rocketseat-basic
├── src/
│   ├── config/
│   │   └── ReactotronConfig.js
│   ├── components/
│   │   └── Header
│   │       └── index.js
│   │       └── styles.js
│   ├── components/
│   │   └── Header
│   │   │    └── index.js
│   │   │    └── styles.js
│   │   │── Menu
│   │   │    └── index.js
│   │   │    └── styles.js
│   │   └── Tabs
│   │       └── index.js
│   │       └── styles.js
│   ├── pages/
│   │   └── Main/
│   │       └── index.js
│   │       └── styles.js
│   ├── Routes/
│   │   └── index.js
│   ├── services/
│   │   └── api.js
│   └── index.js
├── .editorconfig
├── .eslintrc.json
├── .gitignore
├── babel.config.js
├── dependencies.json
├── devDependencies.json
├── index.js
├── jsconfig.js
├── LICENSE
├── package.json
└── README.md
```

### Instalação

1. Para instalar e utilizar esse app o processo é bem simples, basta clonar o repositório utilizando o comando:

```sh
git clone https://github.com/awmoreira/nubank-clone.git
```

1. Depois do projeto clonado você deve executar a instalação dentro da pasta para dar continuidade:

```sh
yarn
```

ou

```sh
npm install
```

Com isso o projeto será instalado com todas as dependências do app devidamente instaladas e linkadas, tal como os arquivos de configuração que são copiados para o projeto.

<!-- CONTRIBUTING -->

## Contribuição

Contribuições são o que fazem a comunidade open source um lugar incrível para aprender, inspirar e criar. Qualquer contribuição que você fizer será **muito apreciada**.

1. Faça um Fork do projeto
2. Crie uma Branch para sua Feature (`git checkout -b feature/FeatureIncrivel`)
3. Adicione suas mudanças (`git add .`)
4. Comite suas mudanças (`git commit -m 'Adicionando uma Feature incrível!`)
5. Faça o Push da Branch (`git push origin feature/FeatureIncrivel`)
6. Abra uma Pull Request

<!-- LICENSE -->

## Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.

<!-- CONTACT -->

## Contato

Allan Winckler - [Github](https://github.com/awmoreira) - **awmoreira@gmail.com**
