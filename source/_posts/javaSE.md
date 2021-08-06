---
title: 类型变量
date: 2021-02-05 22:33:08
tags: javaSE
tap: javaSE
---

一个类可以包含以下类型变量：<!--more-->

- **局部变量**：**在方法、构造方法或者语句块中定义的变量被称为局部变量**。变量声明和初始化都是在方法中，方法结束后，变量就会自动销毁。
- **成员变量**：**成员变量是定义在类中，方法体之外的变量。**这种变量在创建对象的时候实例化。成员变量可以被类中方法、构造方法和特定类的语句块访问。
- **类变量**：**类变量也声明在类中，方法体之外，但必须声明为     static 类型**。

一个类可以拥有多个方法，在上面的例子中：eat()、run()、sleep() 和 name() 都是 Dog 类的方法。

```java
Public class Dog{  // Dog类
	String bread; // 成员变量
	Int size;
	String colour;
	Int age;
	
	Void eat(){    //   方法
		Int a  = 0;     //  局部变量
	}
	
	Void run(){
	
	}
	
	Void sleep(){
	
	}
	
	Void name(){
	
	}
}

```

 

