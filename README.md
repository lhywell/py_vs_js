# python vs javascript

> python与javascript语法的精炼



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
