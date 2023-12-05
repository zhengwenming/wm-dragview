# wm-dragview
可以自由拖拽的悬浮view，可配置初始化位置和可以自由拖动的范围。

# 1 引入
```javascript
import wmdragview from  '@/components/wm-dragview/wm-dragview.vue';
```

# 2 使用组件
```javascript
const x = 200, y = 280;
<wmdragview :isDock="true" :x=x :y=y @clickDragView="handleClick">
    <image class="float-ball" src="../../static/xlc/xlc-kefu.gif"></image>
</wmdragview>
 ```

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
