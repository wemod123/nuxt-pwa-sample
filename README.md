# Reproduce of nuxt-pwa sample

> My posh Nuxt.js project

## Build Setup

``` bash
# install dependencies
$ yarn

# serve with hot reload at localhost:3000
$ nuxt

```
expected output:

```
  × error TypeError: getRouteParams is not a function
  at ModuleContainer.generateIcons (C:\nodeproj\nuxt-pwa-sample\node_modules\@nuxtjs\icon\index.js:29:26)
  at hook (C:\nodeproj\nuxt-pwa-sample\node_modules\@nuxtjs\icon\index.js:8:26)
  at fn (C:\Users\wemod\AppData\Roaming\npm\node_modules\nuxt\dist\nuxt.js:2296:50)
  at promise.then (C:\Users\wemod\AppData\Roaming\npm\node_modules\nuxt\dist\nuxt.js:151:43)
  at process._tickCallback (internal/process/next_tick.js:68:7)
  at Function.Module.runMain (internal/modules/cjs/loader.js:745:11)
  at startup (internal/bootstrap/node.js:283:19)
  at bootstrapNodeJSCore (internal/bootstrap/node.js:743:3)

```
