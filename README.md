## react-fast-cli  

#### TEMPLATE

[react-fast-cli-template](https://github.com/react-fast-cli/template)


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
