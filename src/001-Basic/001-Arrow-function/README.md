# Arrow function

ES6 arrow function（ES6 箭头函数）

## 知识点

- arrow function 默认不会做 `this` 绑定，在 arrow function 中的 `this` 继承自它的父级对象。
- 不允许使用箭头函数的情况
  - 作为构造函数，不能使用箭头函数
  - 作为一个对象的方法的时候（比如通过原型链 prototype 加一个function），不能使用箭头函数
  - 真正需要使用this的时候
    - 给 Button 添加了一个 click 事件的回调函数，然后需要用 this 关键字 操作该 Button 对象
    - 需要使用 arguments 的时候

## 参考资料

- [var,let,const use cases（视频）](https://www.codecasts.com/series/es6-from-scratch/episodes/4)
- [Mozilla JavaScript let,const 临时性死区的说明](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/this)
