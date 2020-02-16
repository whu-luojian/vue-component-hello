# Vue-component-hello

## 基本信息
the Vue UI component template(单个vue ui 组件的开发、构建、发布模板)

## 目录结构
```
|-- dist 组件开发、组件使用案例打包地址
|-- example 组件使用案例，用于开发时测试和使用说明
|-- lib 组件打包后的地址，用于npm发布
|    |-- hello.min.js 组件打包后的库文件，package.json文件入口指向地址
|-- public html模板文件和favicon.ico文件，用于开发自测
|-- src 组件源码文件
|-- webpack.dev.js 组件开发测试配置
|-- webpack.lib.js 组件打包成umd库配置
|-- webpack.prod.js 组件使用案例build配置
```

## 开发
`npm run dev`

## 发布
```
npm run lib
npm publish
```
