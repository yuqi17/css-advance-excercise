

#### css的优化有很多种,但总的来说都是为了渲染的效率更高,不出现渲染的bug
##### 通过研究可以知道,层级越多,渲染越慢,因为渲染是从里面开始的,css 样式是从右到左执行的
##### 所以层级要尽量的少
##### 另外能够一次简写的样式尽量写一起,比如background 设置,border 设置不要分开写(这个用的少)