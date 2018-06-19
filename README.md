# Reactive Programming

[http://reactivex.io/](http://reactivex.io/)

# Installation

`gemini-david 🌴 : npm i webpack webpack-dev-server typescript typings ts-loader -D`

## Typings for RxJS

`gemini-david 🌴 : typings install dt~es6-shim`

## Errors

`gemini-david 🌴 : node_modules/.bin/typings install dt~es6-shimtypings`

```
ERR! message Attempted to compile "es6-shim" as an external module, but
 it looks like a global module. You'll need to enable the global option to continue.
typings ERR!
typings ERR! cwd /Users/v738110/Compass/compass-rxjs
typings ERR! system Darwin 15.6.0
typings ERR! command "/Users/v738110/.nvm/versions/node/v8.11.1/bin/node" "/Users/v738110/Compass/compass-rxjs/node_modules/.bin/typings" "install" "dt~es6-shim"
typings ERR! node -v v8.11.1
typings ERR! typings -v 2.1.1
typings ERR!
typings ERR! If you need help, you may report this error at:
typings ERR!   <https://github.com/typings/typings/issues>
```

## Solution 

`gemini-david 🌴 : node_modules/.bin/typings install dt~es6-shim --global --save`