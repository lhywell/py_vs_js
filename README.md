# python vs javascript

> python与javascript语法的精炼比较



## 金字塔的不同表示

``` python
for i in range(10):
    print(i*'h')
```

``` js
var str = '';
for (var i = 0; i < 10; i++) {
    str += 'h';
    console.log(str);
}
```

``` console
h
hh
hhh
hhhh
hhhhh
hhhhhh
hhhhhhh
hhhhhhhh
hhhhhhhhh
```

## 序列链接和重复
``` python
x=[1,2,3,4,5,6,7,8,9]
y=['a','b']
print(x+y)
print(x*2)
```

``` js
var x = [1, 2, 3, 4, 5, 6, 7, 8, 9];
var y = ['a', 'b'];
console.log(x.concat(y))
console.log(x.concat(x))
```


``` console
[1, 2, 3, 4, 5, 6, 7, 8, 9, 'a', 'b']
[1, 2, 3, 4, 5, 6, 7, 8, 9, 1, 2, 3, 4, 5, 6, 7, 8, 9]
```