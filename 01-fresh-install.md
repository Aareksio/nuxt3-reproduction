## @nuxt/bridge fresh install

```
node -v
v16.12.0

npm -v
7.11.1
```

```
npm ERR! code ERESOLVE
npm ERR! ERESOLVE unable to resolve dependency tree
npm ERR!
npm ERR! Found: vue@2.6.14
npm ERR! node_modules/vue
npm ERR!   peer vue@">= 2.5 < 3" from @vue/composition-api@1.2.4
npm ERR!   node_modules/@vue/composition-api
npm ERR!     @vue/composition-api@"^1.2.4" from @nuxt/bridge@3.0.0-27248715.54549cf
npm ERR!     node_modules/@nuxt/bridge
npm ERR!       dev @nuxt/bridge@"npm:@nuxt/bridge-edge@latest" from the root project
npm ERR!
npm ERR! Could not resolve dependency:
npm ERR! peerOptional vue@"3.2.20" from @nuxt/nitro@3.0.0-27248715.54549cf
npm ERR! node_modules/@nuxt/nitro
npm ERR!   @nuxt/nitro@"npm:@nuxt/nitro-edge@3.0.0-27248715.54549cf" from @nuxt/bridge@3.0.0-27248715.54549cf
npm ERR!   node_modules/@nuxt/bridge
npm ERR!     dev @nuxt/bridge@"npm:@nuxt/bridge-edge@latest" from the root project
npm ERR!
npm ERR! Fix the upstream dependency conflict, or retry
npm ERR! this command with --force, or --legacy-peer-deps
npm ERR! to accept an incorrect (and potentially broken) dependency resolution.
npm ERR!
npm ERR! See C:\Users\Mole\AppData\Local\npm-cache\eresolve-report.txt for a full report.

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\Mole\AppData\Local\npm-cache\_logs\2021-10-22T20_23_54_713Z-debug.log
```
