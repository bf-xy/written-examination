# JS 使用和基本编程

## 写代码

请完成以下文件中的编码需求：

- [查看 `clone.js`](./clone.js)
- [查看 `get-host.js`](./get-host.js)
- [查看 `get-sum.js`](./get-sum.js)

## 方法论

如果你有一定的开发经验，并且追求代码的质量。  
那么你一定知道一些实践技巧，简答 3 ～ 10 条即可。

例如：

> 面向对象编程，代码逻辑可以内聚。
> 禁止使用 var，不可变数据用 const 声明，可变数据用 let 声明。

答：
> 封装可复用方法
> 私有方法或变量以_开头命名
> 尽量编写可扩展性代码,为后期扩展做好准备
> 在let与const声明达到同等效果时,尽量使用const

## 请问以下代码做了什么事情

```js
const getLoglevel = () => {
  return localStorage.loglevel ?? 'INFO';
};
```

答：返回的是 `localStorage.loglevel`这个属性 有就返回,没有就返回`'INFO'`
