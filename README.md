# cropchat

> PWA Example

## Build Setup

``` bash
#Dependencies to run Vue Project
npm install -g vue-cli
vue init pwa cropchat
npm install -g ngrok
ngrok http 8080
npm install material-design-lite --save
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run all tests
npm test

```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

Structure
build: contains webpack and vue-loader configuration files
config: contains our app config (environments, parameters…)
src: source code of our application
static: images, css and other public assets
test: unit test files propelled by Karma & Mocha