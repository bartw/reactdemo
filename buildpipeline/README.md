# Build pipeline

```shell
npm init
npm install --save-dev webpack webpack-dev-server
New-Item webpack.config.js
npm install --save-dev babel-loader babel-core babel-preset-react babel-preset-es2015
New-Item .babelrc
npm install --save-dev eslint
.\node_modules\.bin\eslint.cmd --init
npm install --save react react-dom
mkdir public
New-Item public/index.html
mkdir src
New-Item src/index.js
```
