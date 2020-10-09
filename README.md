# Biblioteca Numero por Extenso

Componente React que retorna número por extenso

- HTML
= JS
- React



[![npm](https://img.shields.io/npm/v/libreactjsnumeroporextenso)](https://www.npmjs.com/package/libreactjsnumeroporextenso) ![NPM](https://img.shields.io/npm/l/libreactjsnumeroporextenso)

o
## Como instalar

Abaixo as formas de como instalar essa biblioteca utilizando o npm ou yarn:

```
npm install libreactjsnumeroporextenso
# ou
yarn add libreactjsnumeroporextenso
```

## Como usar

Uma forma básica de como utilizar o componente:

```jsx
import React,{useState} from "react";
import ReactDOM from "react-dom";
import ReactInputPorExtenso from "../lib";

const App=()=>{
    const [numero,setNumero]=useState("");
    return (
        <>
        <ReactInputPorExtenso 
        tipoExtenso="monetario"
        onChange={numeroExtenso=>setNumero(numeroExtenso)}
        />
        <p>
            <strong>Numero por extenso</strong>: {numero}
        </p>
        </>

    )
}

ReactDOM.render(<App />, document.getElementById("root"));
```

## Propriedades

Esse componente é uma abstração de um componente input do tipo numérico,
todas as propriedades de um input estão disponíveis.

| Propriedade | Valor inicial | Tipo   | Descrição                     |
| ----------- | ------------- | ------ | ----------------------------- |
| tipoExtenso | normal        | string | Formato de extensão do número |

<em>

Biblioteca desenvolvida durante [aula prática](https://www.youtube.com/watch?v=5zgrL9XGASM) da [Digital Innovation One](https://digitalinnovation.one/)

</em>

## Comados que podem ajudar aos iniciantes
   1 yarn add react react-dom prop-typess
   2 yarn add react react-dom prop-types
   4 yarn add  @babel/core @babel/cli @babel/preset-env @babel/preset-react
   7 yarn add -D webpack webpack-cli webpack-dev-server html-webpack-plugin babel-loader
   8 npm insall
   9 yarn init
  52 yarn build
  53 npm publish
