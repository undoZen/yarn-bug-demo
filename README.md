# yarn-bug-demo

node version 8.2.1

with dependencies installed by yarn v0.27.5, webpack will fail with message

> Vue packages version mismatch:
>
> - vue@2.2.6
> - vue-template-compiler@2.4.2

with dependencies installed by npm 5.3.0, works fine

yarn issue:

https://github.com/yarnpkg/yarn/issues/4025
