# 装饰器模式(Decorator)

## 继承
继承是静态的。无法在运行时更改已有对象的行为，只能使用由不同子类创建的对象来替代当前的整个对象。
子类只能有一个父类。大部分编程语言不允许一个类同时继承多个类的行为。

## 组合/聚合
一个对象包含指向另一个对象的引用。
一个对象可以使用多个类的行为，包含多个指向其他对象的引用，并将各种工作委派给引用对象。