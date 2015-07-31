# yafi: yet another Flux implementation

* based on facebook [Flux](https://github.com/facebook/flux)
* it supports `waitFor`
* inspired by [Alt](https://alt.js.org)
* less than 150 lines of code
* written in ES6 ([ECMAScript 2015](http://www.ecma-international.org/ecma-262/6.0/index.html))
* 100% test covered with [Jest](http://facebook.github.io/jest)
* helpers to easily support ES5 without pain

## WARNING:
*this is not (yet) intended for production use.* It's actually the result of few hours of hacking. It still needs some minor changes to be easily usable in different scenarios (it actually works flawlessy *if you use ES6 syntax*). A [NPM](https://npmjs.org) package will be published when ready. For now, enjoy :-)

## Usage
_TODO_

## Example
See [examples](examples/). There's a porting of the [original flux todomvc example](https://github.com/facebook/flux/tree/master/examples/flux-todomvca) that uses `yafi` to define `TodoActions` and `TodoStore`, all other files were left untouched (except `TodoApp` component, because of a little change I made to `TodoStore`).

## TODO
* add better description to README
* add _Usage_ to README
* publish to [NPM](https://npmjs.org)
* find a better name
* _ideas and PRs are welcome_
