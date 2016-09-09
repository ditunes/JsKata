# range 迭代器

实现 range 迭代器，可以遍历数组或者对象的键值。

行为如下：

```js
let o = {a: 1, b: 2, c: 3};

for(let [k, v] of range(o)) {
  console.log(`${k} => ${v}`);
}
/*
Output:

a => 1
b => 2
c => 3
*/


let a = [1, 2, 3];
for(let [i, v] of range(a)) {
  console.log(`${i} => ${v}`);
}
/*
Output:

0 => 1
1 => 2
2 => 3
*/
```

# 参考资料

+ [Iteration protocol](https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Iteration_protocols#Builtin_iterables)
+ [ES6 Generators](https://davidwalsh.name/es6-generators)
+ [for ... of](https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Statements/for...of)


