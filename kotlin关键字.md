#Kotlin用到的关键字

- var：定义变量
- val：定义常量
- fun：定义方法
- Unit：默认方法返回值，类似于Java中的void，可以理解成返回没什么用的值
- vararg：可变参数
- $：字符串模板(取值)
- 位运算符：or(按位或)，and(按位与)，shl(有符号左移)，shr(有符号右移)，
- ushr(无符号右移)，xor(按位异或)，inv(按位取反)
- in：在某个范围中 检查值是否在或不在(in/!in)范围内或集合中
- downTo：递减，循环时可用，每次减1
- step：步长，循环时可用，设置每次循环的增加或减少的量
- when：Kotlin中增强版的switch，可以匹配值，范围，类型与参数
- is：判断类型用，类似于Java中的instanceof()is运算符检查表达式是否是类型的实例。 如果一个不可变的局部变量或属性是指定类型，则不需要显式转换：

- private //仅在同一个文件中可见
- protected //同一个文件中或子类可见
- public //所有调用的地方都可见
- internal //同一个模块中可见

- abstract //抽象类标示
- final  //标示类不可继承，默认属性
- enum  //标示类为枚举
- open  //类可继承，类默认是final的
- annotation  //注解类
