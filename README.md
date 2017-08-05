# vuecli-muitipage

> multipage vuecli

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

## 在vuecli官方脚手架的基础上做了些修改
webpack.base.conf.js、webpack.dev.conf.js、webpack.prod.conf.js。

#### 修复了vue-cli生产环境vuecli忽略了10k以上图片背景图的路径问题，出现404
![annotation](http://upload-images.jianshu.io/upload_images/3402722-c8d211d5f44d1c02.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#### build时文件各种404
![annotation](http://upload-images.jianshu.io/upload_images/3402722-19592d6a85184e2c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
