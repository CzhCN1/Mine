##**mine.js**  
　　一些常用的原生js方法，并考虑了浏览器的兼容问题，且不依赖于任何的现有库。目前包括三大类：事件类、查询类、动画类。
　　
####事件类：

 1. 获取事件 `mine.getEvent(event)` 
 2. 获取事件目标`mine.getTarget(event)`
 3. 为对象绑定事件 `mine.addHandler(element，eventType，handler)`
 4. 移除对象上的指定事件 `mine.removeHandler(element，eventType，handler)`
 5. 阻止事件冒泡 `mine.cancelBubble(event)`
 6. 阻止事件默认行为 `mine.preventDefault(event)`  
 7. 用于在当前文档结构载入完毕后立即执行指定的函数`mine.ready(fn)`
   
####查询类：
 7. 通过class查找元素 `mine.getByClass(oParent，className)`
 8. 获取对象的指定属性值 `mine.getStyle(element，attr)`
  
####动画类:
 1. 简单的运动功能，改变高度、宽度、透明度、位置等属性`mine.move(obj,attrs,fn)`  
 2. 简单的拖拽功能，可设定拖拽对象和拖拽范围对象，当oWrap为空时默认拖拽范围为全部页面。`mine.drag(obj,oWrap)`
 
