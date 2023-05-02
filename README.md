# typescript-learning
Learning from https://www.youtube.com/watch?v=imuO_bactkA&list=PLeS7aZkL6GOtUGTQ81kfm3iGlRTycKjrZ&index=3 
- install nodejs
- install nvm to node version management
- check version: node -v
Install yarn:
sudo npm install -g yarn
yarn —version
- IDE: VScode
- VScode extension:
    + Bracket Pair colorizer
    + Code Runner
    + JS (ES6) code snippets
    + Prettier - Code formatter 
    + Meterial Icon Them
- Unit test
    + Jest
    + Jest Runner
    + Jest Snippets
- Install npm packages : using yarn
    + yarn global add typescript ts-node ts-lib @types/node
    -> tsc -v
    -> tsc index.ts => gen index.js from index.ts and not run 
    => **ts-node index.ts** (convert index.ts to index.js and run)
    ---> node index.ts (error: node still understand only js syntax)
    ==> **install code runner** extension to run on UI
    + ts-node: compile typescript -> javascript to run on nodejs/browser...
    + typescript has typescript compiler to compile from typescript to js
- **prettier**: install : go to https://prettier.io/ 
    > playground > --parser: choose typescript 
    + print-width: 100
    + check --single-quote
    > click "Copy config JSON"
    + create .prettierrc file in project > paste 
    + add more line: "parser": "typescript" to .prettierrc file
    + https://stackoverflow.com/questions/52586965/why-does-prettier-not-format-code-in-vs-code 
    -> follow setting on above link to enable prettier
- Setup project:
    + yarn init
    --> gen package.json & yarn.lock
- **Setup unittest**: ts-jest
    + Installing: yarn add --dev ts-jest @types/jest
    + Creating config: yarn ts-jest config:init
    --> create jest.config.js
    + Running tests: yarn test or yarn jest
- gen config for typescript
    + tsc --init
    --> gen tsconfig.json
    

