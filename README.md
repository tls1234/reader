# reader

## 技术栈
```
vue vue-cli3 vue-router vuex es6 webpack axios sass mint-ui javaScript

```


### 第三方接口跨域在本地vue-cli3脚手架中的vue.config.js中配置如下代码
```
devServer: {
    disableHostCheck: true,
    proxy: {
      '/api': {
        target: 'http://www.api.zhuishushenqi.com',
        ws: true,
        changeOrigin: true,
        pathRewrite: {
          '^/api': ''
        }
      },
      '/content': {
        target: 'http://chapter2.zhuishushenqi.com',
        changeOrigin: true,
        ws: true,
        pathRewrite: {
          '^/content': ''
        }
      }
    }
  }
```
