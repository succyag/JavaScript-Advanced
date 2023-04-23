#### this是什么

* 任何函数本质上都是通过某个对象来调用的，如果没有直接指定就是window
* 所有函数内部都有一个变量this
* 它的值是调用函数的当前对象

#### 如何确定this的值

* test()：window
* p.test()：p
* new test()：新创建的对象
* p.call(obj)：obj