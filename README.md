# vue-element-quick-start

> A Vue.js and Element-ui project, powered by Vue2.0 and Element-ui.

This is a vue2.0 quick start project, you can clone it and start your project quickly. It includes Element-ui, which is a full features UI components library, and Vuex, a state management tools. If any problems, you can commit your issues on the github.

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:3000
npm run dev

# build for production with minification
npm run build

# serve with backend mock data at localhost:8080
npm run server

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For detailed explanation on how things work, checkout the
[project guide](http://vuejs-templates.github.io/webpack/).

More docs:
[doc for vue 2](http://vuejs.org/guide/)
[docs for vue-router 2](http://router.vuejs.org/en/index.html)
[docs for element-ui](http://element.eleme.io)
[docs for vuex](http://vuex.vuejs.org/en/index.html)

## Page Screen Shot
![Screen Shot](http://7xqacx.com1.z0.glb.clouddn.com/backend_managment.png)

## Project Structure

```
.
├── build/                        # webpack config files
│   └── ...
├── config/
│   ├── index.js                  # main project config
│   └── ...
├── server/                       # node server files
│   ├── controller                # node controller files
│       └── ...
│   ├── model                     # node model files or mock data files
│       └── ...
│   └── server.js                 # node start file
├── src/
│   ├── assets/                   # other static files
│   │   └── ...
│   ├── actions/                  # Vuex actions file
│   │   └── ...
│   ├── modules/                  # Vuex modules file
│   │   └── ...
│   ├── store/                    # Vuex store file
│   │   └── ...
│   ├── helpers/                  # helper files(e.g：Ajax)
│   │   └── ...
│   ├── components/               # component files
│   │   └── ...
│   ├── main.js                   # app entry file
│   ├── routes.js                 # app router
│   ├── App.vue                   # app main component
│   └── ...
├── static/                       # pure static assets (directly copied)
├── test/
│   └── unit/                     # unit tests
│   │   ├── specs/                # test spec files
│   │   ├── index.js              # test build entry file
│   │   └── karma.conf.js         # test runner config file
│   └── e2e/                      # e2e tests
│   │   ├── specs/                # test spec files
│   │   ├── custom-assertions/    # custom assertions for e2e tests
│   │   ├── runner.js             # test runner script
│   │   └── nightwatch.conf.js    # test runner config file
├── .babelrc                      # babel config
├── .editorconfig.js              # editor config
├── .eslintrc.js                  # eslint config
├── index.html                    # index.html template
└── package.json                  # build scripts and dependencies

```
