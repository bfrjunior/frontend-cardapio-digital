# Cardápio Digital - Aplicação Frontend

Este projeto é um simples simples protótipo de um Cardápio Digital desenvolvido durante o tutorial da https://github.com/Fernanda-Kipper/frontend-cardapio-digital A aplicação foi desenvolvida usando React, Typescript e React Query.

![Alt text](public/menu.PNG)


## 🚀 Começando

Primeiro, você deve clonar o projeto na sua máquina, para isso você pode colar o seguinte comando em seu terminal.

```
git clone
https://github.com/bfrjunior/frontend-cardapio-digital

cd frontend-cardapio-digital
```
Para instalar as dependências, execute o seguinte comando:
```
npm install
```

Por fim, para executar o projeto basta rodar o seguinte:
```
npm run dev
```








# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
   parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
   },
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
