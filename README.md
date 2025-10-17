# webcomponent-x6
This repository contains a reusable web component for the popular JavaScript diagramming library X6

- [Antv X6 – Official site](https://x6.antv.antgroup.com/)

Antv X6 version: `2.18.1`

## Setup

Install dependencies:

```bash
npm i
```

Install the TypeScript definitions for the lodash-es library as a development dependency

```bash
npm install --save-dev @types/lodash-es
```

## Build

This sample uses the TypeScript compiler to produce JavaScript that runs in modern browsers.

To build the JavaScript version of your component:

```bash
npm run build
```

## Dev Server

This sample uses open-wc's [es-dev-server](https://github.com/open-wc/open-wc/tree/master/packages/es-dev-server) for previewing the project without additional build steps. ES dev server handles resolving Node-style "bare" import specifiers, which aren't supported in browsers. It also automatically transpiles JavaScript and adds polyfills to support older browsers.

To run the dev server and open the project in a new browser tab:

```bash
npm run serve
```

There is a development HTML file located at `/dev/index.html` that you can view at http://localhost:8000/dev/index.html.
