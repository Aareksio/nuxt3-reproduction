## @nuxt/bridge

Error after fresh install of `nuxt-edge` + `@nuxt/bridge`:

```
npm install
npm run dev
```

```
 ERROR  Failed to compile with 6 errors                                                                                                                                                                                                                       friendly-errors 22:18:43


 ERROR  in ./node_modules/ohmyfetch/dist/index.mjs                                                                                                                                                                                                            friendly-errors 22:18:43

Can't import the named export 'c' from non EcmaScript module (only default export is available)                                                                                                                                                               friendly-errors 22:18:43
                                                                                                                                                                                                                                                              friendly-errors 22:18:43

 ERROR  in ./node_modules/ohmyfetch/dist/index.mjs                                                                                                                                                                                                            friendly-errors 22:18:43

Can't reexport the named export 'F' from non EcmaScript module (only default export is available)                                                                                                                                                             friendly-errors 22:18:43
                                                                                                                                                                                                                                                              friendly-errors 22:18:43

 ERROR  in ./node_modules/ohmyfetch/dist/index.mjs                                                                                                                                                                                                            friendly-errors 22:18:43

Can't reexport the named export 'a' from non EcmaScript module (only default export is available)                                                                                                                                                             friendly-errors 22:18:43
                                                                                                                                                                                                                                                              friendly-errors 22:18:43

 ERROR  in ./node_modules/ohmyfetch/dist/index.mjs                                                                                                                                                                                                            friendly-errors 22:18:43

Can't reexport the named export 'c' from non EcmaScript module (only default export is available)                                                                                                                                                             friendly-errors 22:18:43
                                                                                                                                                                                                                                                              friendly-errors 22:18:43

 ERROR  in ./node_modules/ohmyfetch/dist/index.mjs                                                                                                                                                                                                            friendly-errors 22:18:43

Can't reexport the named export 's' from non EcmaScript module (only default export is available)                                                                                                                                                             friendly-errors 22:18:43
                                                                                                                                                                                                                                                              friendly-errors 22:18:43

 ERROR  in ./node_modules/ohmyfetch/dist/chunks/fetch.mjs                                                                                                                                                                                                     friendly-errors 22:18:43

Module parse failed: Unexpected token (59:105)                                                                                                                                                                                                                friendly-errors 22:18:43
You may need an appropriate loader to handle this file type, currently no loaders are configured to process this file. See https://webpack.js.org/concepts#loaders
|         request = withQuery(request, opts.params);
|       }
>       if (opts.body && opts.body.toString() === "[object Object]" && payloadMethods.includes(opts.method?.toLowerCase() || "")) {
|         opts.body = JSON.stringify(opts.body);
|         setHeader(opts, "content-type", "application/json");
                                                                                                                                                                                                                                                              friendly-errors 22:18:43
 @ ./node_modules/ohmyfetch/dist/index.mjs 1:0-54 2:0-110 2:0-110 2:0-110 2:0-110 2:0-110 24:15-26
 @ ./.nuxt/nitro.client.mjs
 @ ./.nuxt/index.js
 @ ./.nuxt/client.js
 @ multi ./node_modules/@nuxt/bridge/dist/runtime/capi.plugin.mjs ./node_modules/eventsource-polyfill/dist/browserify-eventsource.js (webpack)-hot-middleware/client.js?reload=true&timeout=30000&ansiColors=&overlayStyles=&path=%2F__webpack_hmr%2Fclient&name=client ./.nuxt/client.js
```
