# javascript 语法

## 语句

类似python可以一行一个语句而不用加分号，同行可以用分号隔开不同语句。

```JavaScript
first statement
second statement
first statement;second statement;
```

## 注释

有三种注释，分别是类似C语言的单行注释和多行注释，以及html的注释也可以使用。

```javascript
// this is a comment
/* this
is a
commment*/
<!-- this is a comment but not suggest-->
```

## 变量

允许直接对变量进行赋值而无需声明，so...难道所有解释性语言都一样

```javascript
mood = "happy";
age = 33
//declare
var mood,age;
```

区分大小写、不允许变量名中包含除了$之外的标点符号和空格，可以使用下划线（首字母当然是不行的）

## 数据类型

强类型（strongly typed）：必须明确类型的声明

弱类型（weakly typed）：不需要进行类型声明，JavaScript即是如此

```javascript
var age = "thirty three"
age = 33
```

- 字符串：" or '  包裹

- 数值：可以是整型或浮点

- 布尔值：false/true

- 数组：用array进行声明

  ```javascript
  //method 1
  var beatles = Array(4);
  beatles[0] = "John";
  beatles[1] = "paul";
  beatles[2] = "george";
  beatles[3] = "ringo";
  //method 2 
  var beatles = Array("John","paul","george");
  var beatles = ["John","paul"];
  //method 3 
  var lennon = [ "John", 18294, false]
  //etc...
  ```

  - 关联数组

- 对象

  ```javascript
  //method 1
  var lennon = Object();
  lennon.name = "John";
  lennon.year = 1940;
  lennon.living = false;
  //method 2
  var lennon = { name:"John", year:1940, living:false};
  ```

  ​

  ​

  ​

  ​

  ​

   



