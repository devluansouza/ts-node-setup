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

Adicionando a dependência <b>typescript</b>

```sh
npm install typescript -D
```

A execução desse comando irá criar o arquivo [package-lock.json](./package-lock.json) e a pasta <b>node_modules</b>. Importante: Colocar a pasta <b>node_modules</b> no arquivo [.gitignore](./.gitignore).

Adicionando a dependência <b>@types/node</b>

```sh
npm install @types/node -D
```

Criar o arquivo tsconfig.json.

```sh
npx tsc --init
```

A execução desse comando irá criar o arquivo [tsconfig.json](./tsconfig.json) com algumas configurações já predefinidas. Observação: O arquivo tsconfig.json deste repositório deve servir para a maioria dos projetos.
