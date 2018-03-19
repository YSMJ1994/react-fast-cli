## react-fast-cli  

[![npm](https://img.shields.io/badge/downloads-250%2Fmonth-brightgreen.svg)](https://www.npmjs.com/package/react-fast-cli)
[![npm](https://img.shields.io/badge/npm-1.0.6-brightgreen.svg)](https://www.npmjs.com/package/react-fast-cli)
[![Build Status](https://travis-ci.org/react-fast-cli/react-fast-cli.svg?branch=master)](https://travis-ci.org/react-fast-cli/react-fast-cli)

#### TEMPLATE

[react-fast-cli-template](https://github.com/react-fast-cli/template)

#### 使用此 cli 构建的项目

[古诗文查询](https://gushi.stickmy.cn)  

[github](https://github.com/poetry-cn/poetry-web)


#### USAGE

```bash
npm install react-fast-cli -g

react-fast-cli test

cd test

npm run dev
```


#### ISSUES

打包后, 访问不到静态资源目录  
放开 `src/index.html` 中的这一行, 给定一个 `base` 根目录  

```html
<base href="/" />
```
