npm install -g gatsby-cli

## installs the node version stated in .nvmrc
nvm install
yarn

## this is required dependency to execute command `"deploy": "gatsby build && gh-pages -d public -b main"` from package-json
npm install --save-dev gh-pages

## the below packages were install due to error in deployment
npm install lodash
npm insall prop-types


## do not forget to
git add
git commit
git push

## deploys the content to github pages
npm run deploy
