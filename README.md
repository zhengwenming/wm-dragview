# wm-dragview
可以自由拖拽的悬浮view，可配置初始化位置和可以自由拖动的范围。

# 1 引入
```javascript
import wm-dragView from "wm-dragview.vue";
```

# 2 使用组件
<wm-dragview class='float-ball' :isDock="true" :x=x :y=y @clickDragView="handleClick"></wm-dragview>

# 3 样式
```javascript
.float-ball { width: 80px; height: 80px; // border-radius: 50%; }
 ```

# 4 事件
```javascript
    const handleClick = (e) => { 
        uni.navigateTo({ url: '../njhmp/kefu?fromPage=detail' })
    }
 ```
