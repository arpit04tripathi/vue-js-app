# Deploy vue-js-app on github pages

For this repo we use `gh-pages` branch to host on github pages.

we use gh-pages library to push changes to branch.


# Deployment using gh-pages
- `vite.config.ts` - add attribute base for path to repository.
- `package.json`
  - add `gh-pages` dependency and 
  - `deploy` script.
- Run `npm run deploy` from terminal, this creates a dist folder and commits it to branch gh-pages on github.
- gh pages deploy from branch `gh-pages`.


# Initialize this repo
- Install nvm [node version manager](https://github.com/nvm-sh/nvm){:target="_blank"}
- nvm 
  - check version - `nvm --version`
  - help - `nvm --help`
- node version
  - current used - `nvm version` or `nvm current`
  - latest LTS - `nvm ls-remote --lts`
  - install - `nvm install --lts`
  - use version - `nvm use v12.14.1`
- creating new vue-js-3 app using [quickstart](https://vuejs.org/guide/quick-start.html){:target="_blank"}
  - `npm init vue@latest` OR
  - `npm init vite@latest`, and then select `vue`.
