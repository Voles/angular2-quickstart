# angular2-quickstart
Angular 2 - Quickstart

## Installation

    $ npm install -g tsd
    $ tsd query angular2 --action install
    $ tsd query es6-promise --action install
    $ tsd query rx --action install
    $ tsd query rx-lite --action install
    $ npm install -g typescript@^1.5.0-beta http-server

## Run the example

    $ tsc --watch -m commonjs -t es5 --emitDecoratorMetadata app.ts
    $ http-server

Navigate to `http://localhost:8080/index.html`
