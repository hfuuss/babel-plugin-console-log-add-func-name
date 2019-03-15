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
# babel 插件
https://github.com/jamiebuilds/babel-handbook/blob/master/translations/zh-Hans/plugin-handbook.md