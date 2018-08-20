### 委托模式
* 解决问题：多个dom节点上绑定同一个方法，在节点非常多的时候性能消耗严重
* 优点：只需在上层节点绑定一个事件即可，性能优越
* 缺点：通过冒泡触发，多了一或多层事件传递
* **应用场景：**
* 1. ul li
* 2. react eventhub