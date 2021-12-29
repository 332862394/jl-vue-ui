# jl-vue-ui 一个vue组件库
## 介绍
作者：JL
这是我自己封装的一个Vue UI框架。
## 开始使用

1. 添加CSS样式
  使用本框架前，请在CSS中开启border-box
  ```
  *,*::before,*::after{box-sizing:border-box;}
  ```
  IE 8 及以上浏览器都支持此样式。

  你还需要设置默认颜色等变量（后续会改为SCSS变量）
  ```
  html {
        --button-height: 32px;
        --font-size: 14px;
        --button-bg: white;
        --button-active-bg: #eee;
        --border-radius: 4px;
        --color: #333;
        --border-color: #999;
        --border-color-hover: #666;
      }
  ```
  IE 15 及以上浏览器都支持此样式。
2. 安装
   ```
   npm i --save jl-vue-ui
   ```
3. 引入
   ```
   import {Button} from 'jl-vue-ui'
   import 'jl-vue-ui/dist/index.css'
   export default{
       name:'app',
       components:{
           'g-button':Button
           }
   }
   ```



## 文档
## 提问
## 变更记录
## 联系方式
## 贡献代码