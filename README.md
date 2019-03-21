# weixinProgram_learning
学习资源：

https://www.bilibili.com/video/av33678966/?p=27



### 一、HTML5

> 开发工具：[WebStorm](https://www.jetbrains.com/webstorm/)









### 二、CSS3







### 三、 JavaScript

1. 原生js

- ECMAScipt

  规定了js语言核心语法的标准。

- DOM

  专门操作网页内容的API。

- BOM

  专门操作浏览器窗口的API。

注意：

1. 给未声明的变量强行赋值（禁止使用）

（1）普通模式：不会报错！会自动在全局创建该变量。（但是会造成全局污染）

（2）ESS：严格模式（在当前代码段的顶部先插入'use strict')

2. ReferenceError

   变量没找到。

```javascript
> b
< Uncaught ReferenceError: b is not defined
```

3. null和underfined

```js
> null == underfined
< true
```

underfined 是程序自动为一个变量赋的空值。

null是专门给程序员用于手动清空一个变量使用的。

4. toString和String() 转字符串方法

```javascript
> null.toString()
< Uncaught TypeError: Cannot read property 'toString' of null
underfined.toString()
< Uncaught TypeError: Cannot read property 'toString' of undefined

> String(null)
< "null"
> String(undefined)
< "undefined"
```

5. "==" 与 "==="

"=="为带隐式转换的等于比较，比如会把undefined自东转换为null

"==="为不带隐式转换的等于比较。

```javascript
> null === underfined
< false
```

6. NaN

判断是否NaN，用IsNaN()函数。不能用"=="和"==="

```javascript
> a = NaN
> a == NaN
< false
> a === NaN
< false
> isNaN(a)
< true
```



> [js高级总结](https://www.cnblogs.com/signheart/p/d6c229a5a758ee1dc21ad5ca2042ab8f.html)



### 四、 Vue.js



### 五、微信小程序



### 六、微信小程序框架





