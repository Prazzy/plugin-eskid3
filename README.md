# Plugin ESKID3

> Estructura de un plugin para Kibana con visualizaciones hechas con D3.JS

---

## Introducción

Todos los detalles de implementación y algunos aspectos importantes se encuentran en la siguiente dirección: [index.js](https://github.com/tomas-teston/plugin-eskid3/wiki)

## Como empezar

Existen varias formas de crear un plugin básico para Kibana

See the [kibana contributing guide](https://github.com/elastic/kibana/blob/master/CONTRIBUTING.md) for instructions setting up your development environment. Once you have completed that, use the following npm tasks.

  - `npm start`

    Start kibana and have it include this plugin

  - `npm start -- --config kibana.yml`

    You can pass any argument that you would normally send to `bin/kibana` by putting them after `--` when running `npm start`

  - `npm run build`

    Build a distributable archive

  - `npm run test:browser`

    Run the browser tests in a real web browser

  - `npm run test:server`

    Run the server tests using mocha

For more information about any of these commands run `npm run ${task} -- --help`.
