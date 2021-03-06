# Angular 2, d3, and TypeScript

## Use latest TypeScript compiler
TypeScript 1.5 beta will include everything you need. Until that is released,
we use a GitHub reference to the latest alpha.

    $ npm install -g mhegazy/TypeScript#v1.5-beta2

## Start up the compiler

    $ tsc -w
    message TS6042: Compilation complete. Watching for file changes.

## Use a TypeScript-aware editor
We have good experience using these editors:

* [Webstorm 10](https://www.jetbrains.com/webstorm/download/)
* [Atom](https://atom.io/) with [TypeScript plugin](https://atom.io/packages/atom-typescript)
* [Sublime Text](http://www.sublimetext.com/3) with [Typescript-Sublime-Plugin](https://github.com/Microsoft/Typescript-Sublime-plugin#installation)

## Load the app
From the directory that contains index.html:

    npm install -g serve  # Or sudo npm install -g serve
    serve                 # Creates a server at localhost:3000
    # In a browser, visit localhost:3000
