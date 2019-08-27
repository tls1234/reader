# reader

## 技术栈
```
vue vue-cli3 vue-router vuex es6 webpack axios sass mint-ui javaScript

```
### 截图
![](https://github.com/tls1234/reader/blob/master/screenshot/q1.png)
![](https://github.com/tls1234/reader/blob/master/screenshot/q2.png)
![](https://github.com/tls1234/reader/blob/master/screenshot/q3.png)
![](https://github.com/tls1234/reader/blob/master/screenshot/q4.png)
![](https://github.com/tls1234/reader/blob/master/screenshot/q5.png)
![](https://github.com/tls1234/reader/blob/master/screenshot/q6.png)
![](https://github.com/tls1234/reader/blob/master/screenshot/q7.png)
![](https://github.com/tls1234/reader/blob/master/screenshot/q8.png)
![](https://github.com/tls1234/reader/blob/master/screenshot/q9.png)

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
