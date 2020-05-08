<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="./src/assets/logo.svg" alt="GoFinances"></a>
</p>

<h3 align="center">Front-end GoFinances</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()

  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/larabeatrizms/frontend-gofinances">

  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/larabeatrizms/frontend-gofinances">

  <img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/larabeatrizms/frontend-gofinances">

  <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/larabeatrizms/frontend-gofinances">

</div>

---

<p align="center">
    Projeto construído com conhecimentos em ReactJS, conectando-se ao back-end(Node.js).
    <br>
</p>

## 📝 Tabela de conteúdos

- [Sobre](#about)
- [Preview](#preview)
- [Testes](#tests)
- [Uso](#usage)
- [Construído utilizando](#built_using)
- [Authors](#authors)

## 🧐 Sobre <a name = "about"></a>

A aplicação de gestão de transações, a GoFinances, consiste em listar as transações do usuário e para que o usuário importe uma nova transação ele precisa importar uma arquivo CSV. Praticando conhecimentos em ReactJS, utilizando rotas e envio de arquivos por formulário.

Essa é uma aplicação que irá se conectar ao seu backend do [Backend Gofinances](https://github.com/larabeatrizms/backend-gofinances), e exibir as transações criadas e permitir a importação de um arquivo CSV para gerar novos registros no banco de dados.

### Layout da Aplicação

O layout pode ser acessado através da página do Figma, no [seguinte link](https://www.figma.com/file/EgOhyj1Inz14dhWGVhRlhr/GoFinances?node-id=1%3A863).

## 🚀 Preview<a name = "preview"></a>

<!-- [Preview ](https://youtu.be/Qec1ZO3WPJo) -->

<a href="https://youtu.be/Qec1ZO3WPJo" target="_blank" align="center">
  <img src="https://i.gyazo.com/1bb5e2f0074d288264ea4461b1ce383c.png">
</a>

### Funcionalidades

- **`Listar as transações da API`**
- **`Exibir o balance da API`**
- **`Importar arquivos CSV`**

### Requisitos para executar

Ter instalado pelo menos um gerenciador de pacotes do Node, [Npm](https://www.npmjs.com/) ou [Yarn](https://yarnpkg.com/).

### Installing

Executar na raiz do projeto o seguinte comando para instalar as dependências

```sh
yarn install
```

ou

```sh
npm install
```

## 🔧 Executando os testes <a name = "tests"></a>

```sh
yarn test
```

### Sobre os testes

- **`should be able to list the total balance inside the cards`**: Para que esse teste passe, sua aplicação deve permitir que seja exibido na sua Dashboard, cards contendo o total de `income`, `outcome` e o total da subtração de `income - outcome` que são retornados pelo balance do seu backend.

* **`should be able to list the transactions`**: Para que esse teste passe, sua aplicação deve permitir que sejam listados dentro de uma tabela, toda as transações que são retornadas do seu backend.

- **`should be able to navigate to the import page`**: Para que esse teste passe, você deve permitir a troca de página através do Header, pelo botão que contém o nome `Importar`.

- **`should be able to upload a file`**: Para que esse teste passe, você deve permitir que um arquivo seja enviado através do componente de drag-n-drop na página de `import`, e que seja possível exibir o nome do arquivo enviado para o input.

## 🎈 Uso <a name="usage"></a>

```sh
yarn start
```

## ⛏️ Construído utilizando <a name = "built_using"></a>

- [Typescript](https://www.typescriptlang.org/)
- [ReactJS](https://reactjs.org/)
- [React Router](https://github.com/ReactTraining/react-router)
- Axios

## ✍️ Authors <a name = "authors"></a>

👤 **Lara Beatriz**

- Twitter: [@LaraBeatrizMS](https://twitter.com/LaraBeatrizMS)
- Github: [@larabeatrizms](https://github.com/larabeatrizms)
- LinkedIn: [@larabeatrizms](https://linkedin.com/in/larabeatrizms)
