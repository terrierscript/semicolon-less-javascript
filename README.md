
# Semicolon-less JavaScript

> A list of resources for **semicolon-less** JavaScript (TypeScript) coding style.

### Quick Start (How do we start semicolon-less style quickly?)

1. Install [`eslint`](https://eslint.org/doc)
  * `$ npm install -D eslint`
2. Append rule `semi` and `no-unexpected-multiline`

```js
{
  "rules": {
    "semi": [2, "never"],
    "no-unexpected-multiline": 2
  }
}
```

## Contents

* [Documentation](#documentation)
* [Tools](#tools)
* [Projects](#projects)

## Documentation

### Articles

* [An Open Letter to JavaScript Leaders Regarding Semicolons](http://blog.izs.me/post/2353458699/an-open-letter-to-javascript-leaders-regarding)
* [Semicolons in JavaScript are optional](http://mislav.net/2010/05/semicolons/)
* [JavaScript Semicolon Insertion Everything you need to know](http://inimino.org/~inimino/blog/javascript_semicolons)
* [ECMAScript® 2016 Language Specification - Automatic Semicolon Insertion](https://www.ecma-international.org/ecma-262/7.0/#sec-automatic-semicolon-insertion)
* [Semicolons in JavaScript: A preference](https://medium.com/@kentcdodds/semicolons-in-javascript-a-preference-dd8fc8b80895)
* [No, you don’t need semicolons](https://medium.com/@goatslacker/no-you-dont-need-semicolons-148d936b9cf2)
* [JavaScript Standard Style - Helpful reading](http://standardjs.com/rules.html#helpful-reading)
* [Going semi-colon-less. OR why I’m considering the NPM Style Guide.](http://blog.namangoel.com/considering-the-npm-styleguide)
* [JavaScript: The Semicolon Debate](https://blog.falafel.com/javascript-semicolon-debate/)

### Slides

* [HACKING SEMICOLONS](http://slides.com/evanyou/semicolons#/)
* [The Great Semicolon Debate](http://www.slideshare.net/anm8tr/the-great-semicolon-debate)

### Videos

* [Are Semicolons Necessary in JavaScript?](https://www.youtube.com/watch?v=gsfbh17Ax9I)
* [Semicolons cannot save you! - FunFunFunction #9](https://www.youtube.com/watch?v=Qlr-FGbhKaI)

## Tools
### Linting

* ESLint
  * Rules
    * [semi](http://eslint.org/docs/rules/semi)
    * [no-unexpected-multiline](http://eslint.org/docs/rules/no-unexpected-multiline)
  * Config
    * [eslint-config-standard](https://github.com/feross/eslint-config-standard)
      * [awesome-standard](https://github.com/feross/awesome-standard) - List of standard style
    * [eslint-config-vue](https://github.com/vuejs/eslint-config-vue)
    * [@most/eslint-config-most](https://github.com/mostjs/eslint-config-most)
    * [eslint-config-netflix-dea](https://github.com/Netflix/eslint-config-netflix-dea)
    * [eslint-config-rackt](https://www.npmjs.com/package/eslint-config-rackt) (npm published only)
* JSHint
  * [options - asi](http://jshint.com/docs/options/#asi)

### Others

* [semicolon-less.js](https://github.com/hax/semicolon-less.js/)
* [semicolons](https://github.com/isaacs/semicolons)
* [semi](https://github.com/yyx990803/semi)
* [semicolon-js](https://github.com/dchest/semicolon-js)
* [semicolon-indent](https://github.com/christophwitzko/semicolon-indent)

## Projects

List of projects that using *semicolonless* style and related documents (style guide / pull request / issue).

* [acorn](https://github.com/ternjs/acorn)
* [basic-auth](https://github.com/jshttp/basic-auth)
* [backpack](https://github.com/palmerhq/backpack)
* [body-parser](https://github.com/expressjs/body-parser)
* [budo](https://github.com/mattdesl/budo)
* [choo](https://github.com/yoshuawuyts/choo)
* [dat](https://github.com/datproject/dat)
* [data-fns](https://github.com/date-fns/date-fns)
* [danger.js](https://github.com/danger/danger-js) (TypeScript)
* [deku](https://github.com/anthonyshort/deku)
* [dotenv](https://github.com/motdotla/dotenv)
* [envify](https://github.com/hughsk/envify)
* [eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import)
* [expect](https://github.com/mjackson/expect)
* [fela](https://github.com/rofrischmann/fela)
* [fs-extra](https://github.com/jprichardson/node-fs-extra)
* [gibon](https://github.com/tunnckoCore/gibon)
* [glam](https://github.com/threepointone/glam)
* [glamor](https://github.com/threepointone/glamor)
* [history](https://github.com/mjackson/history)
* [hyperscript](https://github.com/dominictarr/hyperscript)
* [junctions](https://github.com/jamesknelson/junctions)
* [karma](https://github.com/karma-runner/karma)
* [kefir](https://github.com/rpominov/kefir)
* [Mithril](https://github.com/lhorie/mithril.js)
* [minimatch](https://github.com/isaacs/minimatch)
* [most](https://github.com/cujojs/most)
* [moxios](https://github.com/mzabriskie/moxios)
* [next.js](https://github.com/zeit/next.js)
* [node-tap](https://github.com/tapjs/node-tap)
* [node-glob](https://github.com/isaacs/node-glob)
* [npm](https://github.com/npm/npm)
  * [npm-coding-style - npm's "funny" coding style](https://docs.npmjs.com/misc/coding-style)
* [nwb](https://github.com/insin/nwb)
* [NuclearJS](https://github.com/optimizely/nuclear-js)
* [nyc](https://github.com/istanbuljs/nyc)
* [path-to-regexp](https://github.com/pillarjs/path-to-regexp)
* [optimize-js](https://github.com/nolanlawson/optimize-js)
* [react-async-component](https://github.com/ctrlplusb/react-async-component)
* [react-fix-it](https://github.com/MicheleBertoli/react-fix-it)
* [react-form](https://github.com/tannerlinsley/react-form)
* [react-media](https://github.com/ReactTraining/react-media)
* [react-redux](https://github.com/reactjs/react-redux)
* [react-router](https://github.com/ReactTraining/react-router)
* [react-static](https://github.com/nozzle/react-static)
* [react-virtualized](https://github.com/bvaughn/react-virtualized)
* [recompose](https://github.com/acdlite/recompose)
* [redux](https://github.com/reactjs/redux)
  * [#1509 - Where is repo for eslint-config-rackt exists now?](https://github.com/reactjs/redux/issues/1509)
* [redux-effects](https://github.com/redux-effects/redux-effects)
* [redux-mock-store](https://github.com/arnaudbenard/redux-mock-store)
* [redux-saga](https://github.com/yelouafi/redux-saga)
* [request](https://github.com/request/request)
* [reselect](https://github.com/reactjs/reselect)
* [Riot](https://github.com/riot/riot)
* [sheetify](https://github.com/stackcss/sheetify)
* [shrimpit](https://github.com/yamafaktory/shrimpit)
* [slate](https://github.com/ianstormtaylor/slate)
* [stylelint](https://github.com/stylelint/stylelint)
* [styled-components](https://github.com/styled-components/styled-components)
* [through2](https://github.com/rvagg/through2)
* [Twitter Bootstrap](https://github.com/twbs/bootstrap)
* [Vue.js](https://github.com/vuejs/vue)
  * [#1132 - Lost semi-colon in Vue.js source code](https://github.com/vuejs/vue/issues/1132)  
  * [Semicolon-less code - My thoughts](https://forum.vuejs.org/t/semicolon-less-code-my-thoughts/4229)
* [weex](https://github.com/alibaba/weex)
* [xtend](https://github.com/Raynos/xtend)
* [yaml](https://github.com/tj/js-yaml)
* [yo-yo](https://github.com/maxogden/yo-yo)
* [zepto](https://github.com/madrobby/zepto)
  * [CONTRIBUTING.md](https://github.com/madrobby/zepto/blob/master/CONTRIBUTING.md)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
