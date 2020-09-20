# allen-cli
项目脚手架，整合各个模板，一键生成模板。提高生产力

## 安装
```
npm i allen-cli -g
cnpm i allen-cli -g
yarn add allen-cli -g
```
## 功能
### 项目初始化
```
allen init <you project name>
```
### 帮助
```
allen help
```
### 查看版本
```
allen -V
```
## 提供模板
### 1. vue 2.0
#### 自定义配置
1. 是否使用移动端适配
2. 环境选择： 本地、开发、测试、生产、灰度、预发布  

### 2. 基于vue的活动页h5多页面
#### 自定义配置
1. 是否使用移动端适配
2. 是否兼容安卓4.4.0版本
3. 是否配置微信sdk
4. 环境选择： 本地、开发、测试、生产、灰度、预发布

### 3. 使用rollup做构建工具，适用于编写组件或库
rollup是一款专业打包js的打包工具，比起webpack打包速度更快，体积更小。适用于组件和库的开发打包。   

#### 自定义配置
-  es – 将软件包保存为ES模块文件
- cjs – CommonJS，适用于 Node 和 Browserify/Webpack
- amd 异步模块定义，用于像RequireJS这样的模块加载器
- umd – 通用模块定义，以amd，cjs 和 iife 为一体 

## 更多模板还在路上...
