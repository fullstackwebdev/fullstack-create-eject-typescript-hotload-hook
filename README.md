# fullstack-create-eject-typescript-hotload-hook$

Minimalistic create-react-app Typescript hotloading via eject, with hooks
---


### Recipe

```sh
npx create-react-app my-eject

yarn eject

npm install --save react-hot-loader

# edit package.json babelrc

npm install babel-loader --save

# edit config/webpack.conf.dev.js

yarn add typescript @types/node @types/react @types/react-dom @types/jest  @babel/plugin-transform-react-jsx  @babel/plugin-transform-react-jsx-source  @babel/plugin-transform-react-jsx-self

yarn add react@next react-dom@next

yarn add @types/node --save-dev

# edit src/custom.d.ts to add svg

```

### To run

```
npm install
yarn start
```

### To do

* Non-eject version
* Yarn install fails

