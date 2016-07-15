###5.6.1 Boolean 类型

Booleanl 类型是与布尔值对应的引用类型。

```
var falseObject = neww Boolean(false);
var result  = falseObject && true;
alert(result); //true

var falseValue = false;
result = falseValue && true;
alert(result); //false
```
建议有永远不要使用 Boolean 类型