# Angular 2 - Quickstart

## Installation

    $ npm install -g tsd typescript@^1.5.0-beta http-server
    $ tsd query angular2 es6-promise rx rx-lite --action install

## Run the example

    $ tsc --watch -m commonjs -t es5 --emitDecoratorMetadata app.ts
    $ http-server

Navigate to `http://localhost:8080/index.html`
