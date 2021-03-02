# TRIPS - exercicios com REDUX em React

O objetivo desse exercício é criar uma aplicação para agendamento de viagens usando os conceitos do REDUX aplicados em React

## REDUX

Redux é um controlador de estados geral para sua aplicação.

Compartilhar estados entre vários componentes diferentes se torna uma coisa muito fácil quando o utilizamos. O Redux é basicamente divido em 3 partes: **store, reducers e actions.**

---

### Store

"store" é o nome dado pelo Facebook para o conjunto de estados da sua aplicação. Vamos pensar na store como um grande centro de informações, que possui disponibilidade para receber e entregar exatamente o que o seu componente requisita (seja uma função, ou uma informação propriamente dita). A store é um objeto JavaScript que possui todos os estados dos seus componentes.

### Reducers

Cada dado da store deve ter o seu próprio reducer, por exemplo: o dado "user" teria o seu reducer, chamado só para User. Um reducer é encarregado de lidar com todas as ações, como algum componente pedindo para alterar algum dado da store.

### Actions

Actions são responsáveis por requisitar algo para um reducer. Elas devem ser sempre funções puras, dizendo de uma forma leiga, ou seja elas devem APENAS enviar os dados ao reducer, nada além disso. Disparar uma ação apenas levando os dados que você deseja enviar e o reducer vai receber e usar os dados.

## Instruções

Para rodar nossa aplicação, precisaremos de dois terminais digite:

- `yarn dev` ou `npm run dev` - para rodar a aplicação em um terminal
- `yarn serve` ou `npm run serve` - para rodar a api em outro terminal

Para nossa aplicação foi instalado uma API fake, ou seja, são dados apenas para fins de estudo.

## Dependencias instaladas:

> > observação importante: como o projeto foi iniciado usando `npx create-react-app` há dependencias não citadas. No entanto como todas podem ser consultadas no arquivo package.json só achei relevante pontuar as que foram acrescentadas além dessa base.
> > Dito isso essas foram as dependencias instaladas:

- react-router-dom = `yarn add react-router-dom` ou `npm install react-router-dom`
- Axios - `yarn add axios`
- Json-server - `yarn add global json-server`
- react icons - `npm install react-icons --save`
- redux e react redux- `yarn add redux react-redux`
- immer - `yarn add immer`

# Atalho para instalar tudo:

ao invés de instalar cada dependencia separada, no terminal chamar:

- `yarn add react-router-dom axios json-server redux react-redux react-icons immer`
- `npm install -g json-server` - essa foi separada por estar em escopo global
