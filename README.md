# Configuração para projetos Node JS.

Configuração para começar a desenvolver projetos <b>[Node JS](https://nodejs.org/en/)</b>, utilizando <b>[TypeScript](https://www.typescriptlang.org/)</b>, <b>[ESLint](https://eslint.org/)</b> e <b>[Prettier](https://prettier.io/)</b>.

<b>Importante: </b> Estou utilizando o gerenciador de pacotes <b>[npm](https://www.npmjs.com/)</b>.

## Inicializando o projeto

Para inicializar o projeto, utilize o seguinte comando:

```sh
npm init -y
```

A execução desse comando irá criar o arquivo [package.json](./package.json) com algumas configurações já predefinidas.

## Configurando o TypeScript

1º - Adicionada a dependência `typescript`.

```sh
npm install typescript -D
```

A execução desse comando irá criar o arquivo [package-lock.json](./package-lock.json) e a pasta `node_modules`.

<b>Importante:</b> A pasta node_modules deve ser colocada no arquivo [.gitignore](./.gitignore).

2º - Adicionando a dependência `@types/node`

```sh
npm install @types/node -D
```

3º - Criar o arquivo `tsconfig.json`.

```sh
npx tsc --init
```

A execução desse comando irá criar o arquivo [tsconfig.json](./tsconfig.json) com algumas configurações já predefinidas. Observação: O arquivo tsconfig.json deste repositório deve servir para a maioria dos projetos.
