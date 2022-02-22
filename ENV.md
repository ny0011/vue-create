 $ npm install -g @vue/cli
```shell
~/work
$ npm install -g @vue/cli
npm WARN deprecated graphql-tools@4.0.8: This package has been deprecated and now it only exports makeExecutableSchema.\nAnd it will no longer receive updates.\nWe recommend you to migrate to scoped packages such as @graphql-tools/schema, @graphql-tools/utils and etc.\nCheck out https://www.graphql-tools.com to learn what package you should use instead
npm WARN deprecated apollo-cache-control@0.14.0: The functionality provided by the `apollo-cache-control` package is built in to `apollo-server-core` starting with Apollo Server 3. See https://www.apollographql.com/docs/apollo-server/migration/#cachecontrol for details.
npm WARN deprecated apollo-tracing@0.15.0: The `apollo-tracing` package is no longer part of Apollo Server 3. See https://www.apollographql.com/docs/apollo-server/migration/#tracing for details
npm WARN deprecated graphql-extensions@0.15.0: The `graphql-extensions` API has been removed from Apollo Server 3. Use the plugin API instead: https://www.apollographql.com/docs/apollo-server/integrations/plugins/
npm WARN deprecated urix@0.1.0: Please see https://github.com/lydell/urix#deprecated
npm WARN deprecated resolve-url@0.2.1: https://github.com/lydell/resolve-url#deprecated
C:\Users\ny\AppData\Roaming\npm\vue -> C:\Users\ny\AppData\Roaming\npm\node_modules\@vue\cli\bin\vue.js

> core-js-pure@3.21.1 postinstall C:\Users\ny\AppData\Roaming\npm\node_modules\@vue\cli\node_modules\core-js-pure
> node -e "try{require('./postinstall')}catch(e){}"

Thank you for using core-js ( https://github.com/zloirock/core-js ) for polyfilling JavaScript standard library!

The project needs your help! Please consider supporting of core-js:
> https://opencollective.com/core-js
> https://patreon.com/zloirock
> https://paypal.me/zloirock
> bitcoin: bc1qlea7544qtsmj2rayg0lthvza9fau63ux0fstcz

Also, the author of core-js ( https://github.com/zloirock ) is looking for a good job -)


> @apollo/protobufjs@1.2.2 postinstall C:\Users\ny\AppData\Roaming\npm\node_modules\@vue\cli\node_modules\@apollo\protobufjs
> node scripts/postinstall

+ @vue/cli@5.0.1
added 873 packages from 530 contributors in 45.654s
```
$ vue create hello-world
기본 설정으로 Vue3사용, babel, eslint 설치
```shell
$ vue create hello-world
? Please pick a preset: (Use arrow keys)
? Please pick a preset: Default ([Vue 3] babel, eslint)
✨  Creating project in C:\Users\ny\work\hello-world.
🗃  Initializing git repository...
⚙️  Installing CLI plugins. This might take a while...


> yorkie@2.0.0 install C:\Users\ny\work\hello-world\node_modules\yorkie
> node bin/install.js

setting up Git hooks
done


> core-js@3.21.1 postinstall C:\Users\ny\work\hello-world\node_modules\core-js
> node -e "try{require('./postinstall')}catch(e){}"

added 858 packages from 462 contributors and audited 859 packages in 18.464s

91 packages are looking for funding
  run `npm fund` for details

found 4 moderate severity vulnerabilities
  run `npm audit fix` to fix them, or `npm audit` for details
🚀  Invoking generators...
📦  Installing additional dependencies...

added 96 packages from 96 contributors and audited 955 packages in 9.335s

101 packages are looking for funding
  run `npm fund` for details

found 4 moderate severity vulnerabilities
  run `npm audit fix` to fix them, or `npm audit` for details
⚓  Running completion hooks...

📄  Generating README.md...

🎉  Successfully created project hello-world.
👉  Get started with the following commands:

 $ cd hello-world
 $ npm run serve

```
