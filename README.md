# JavaScript ast demo
最简单的babel插件 -- 增加console.log的调用文件名            
阿里巴巴 sorrycc的demo      
in:
```js
function foo() {
  console.log('bar')
}
```
out: 
```js
function foo() {
  console.log("[foo]", 'bar');
}
```
# babel 插件文档
https://github.com/jamiebuilds/babel-handbook/blob/master/translations/zh-Hans/plugin-handbook.md
# 未做的事情
* 测试 学习jest
* 目录结构 参考官方插件 学习babel-plugin-import 打包发布 不急