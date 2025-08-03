---
layout: default
title: JavaScript基础语法
subtitle: 变量、数据类型和运算符
date: 2023-10-20
categories: 前端开发
---

# JavaScript基础语法

## 一、变量声明

在JavaScript中，我们可以使用`var`、`let`和`const`来声明变量：

```javascript
// 使用var声明变量（函数作用域）
var name = "John";

// 使用let声明变量（块级作用域）
let age = 30;

// 使用const声明常量（块级作用域，不可重新赋值）
const PI = 3.14159;
```

## 二、数据类型

JavaScript有以下几种基本数据类型：

1. **字符串(String)**：用于表示文本数据
   ```javascript
   let message = "Hello, World!";
   ```

2. **数字(Number)**：用于表示数值
   ```javascript
   let score = 95.5;
   ```

3. **布尔值(Boolean)**：表示真或假
   ```javascript
   let isPassed = true;
   ```

4. **空值(Null)**：表示一个空值
   ```javascript
   let emptyValue = null;
   ```

5. **未定义(Undefined)**：表示变量未被赋值
   ```javascript
   let undefinedValue;
   ```

6. **对象(Object)**：用于存储复杂数据
   ```javascript
   let person = {
     name: "Alice",
     age: 25
   };
   ```

## 三、运算符

### 1. 算术运算符
```javascript
let a = 10;
let b = 5;

console.log(a + b);  // 15
console.log(a - b);  // 5
console.log(a * b);  // 50
console.log(a / b);  // 2
console.log(a % b);  // 0
```

### 2. 比较运算符
```javascript
console.log(5 > 3);  // true
console.log(5 < 3);  // false
console.log(5 == "5");  // true（仅比较值）
console.log(5 === "5");  // false（比较值和类型）
```

### 3. 逻辑运算符
```javascript
let x = true;
let y = false;

console.log(x && y);  // false
console.log(x || y);  // true
console.log(!x);  // false
```

## 四、函数

函数是一段可重用的代码块：

```javascript
// 函数声明
function greet(name) {
  return "Hello, " + name + "!";
}

// 函数调用
console.log(greet("Bob"));  // 输出：Hello, Bob!

// 箭头函数（ES6+）
const multiply = (a, b) => a * b;
console.log(multiply(4, 5));  // 输出：20
```

## 五、学习心得

JavaScript是一门灵活多变的语言，掌握基础语法是学习更高级概念的关键。建议多写代码练习，加深对概念的理解。