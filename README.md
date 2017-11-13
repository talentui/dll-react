# 使用[Webpack DllPlugin](https://webpack.js.org/plugins/dll-plugin/)打包出来的dll 基本上等于talent-libs

目前包含进去的库有：

* react
* react-dom
* prop-types
* react-router-dom
* redux
* react-redux
* react-transition-group
* immutable

使用dll方式引入基础库到项目中可以极大的增加项目打包的速度，也能很好的利用浏览器的缓存机制， 减少页面的渲染时间

# changeLog:

## 16.1.0

升级react 和 react-dom到16.1.0， 删除immutable依赖

本次版本的依赖有：
* react
* react-dom
* prop-types
* react-router-dom
* redux
* react-redux
* react-transition-group