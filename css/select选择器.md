```
    a b // a的后代b
    a > b // a的子元素b
    a + b // a的兄弟元素b
    a - b // a的相邻兄弟元素b
    .a.b // 同时有a b 两个class的
    // 伪类
    div:first-child {  // 这是first-child是指选择到的结果里面的first-child
        color: red
    }
    // 属性选择器
    input[type=submit] {
    }
    input[readonly] {
    }
    div span:nth-child(2n+1) {  // div下面的span, 如果span正好是div的第2n+1个元素
    }
```
