# cn.localhost01.EqualsUtil
*用于比较两个对象是否内容相同*

支持：
* 级联比较：除了比较两个对象的基本类型属性外，还会迭代比较对象属性的子属性；
* 定制比较字段：只会比较指定字段数组的字段，同时可和“级联比较”兼容，即给定的字段数组同样生效于对象属性的子属性；
* 定制忽略字段：比较时会忽略指定的字段数组的字段，同时可和“级联比较”兼容，即给定的字段数组同样生效于对象属性的子属性；

技术：
* 基于Java反射实现
