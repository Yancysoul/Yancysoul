---
title: class
date: 2020-09-15 20:24:06
tags:
---
# class

## 简介

### 类的由来

- JavaScript语言中，生成实例对象的方法是通过构造函数。

```javascript
fucntion Point(x, y) {
    this.x = x;
    this.y = y;
}
Point.prototype.toString = function() {
    return '(' + this.x + ',' + this.y +')'
}
var p = new Point(1, 2)
```

