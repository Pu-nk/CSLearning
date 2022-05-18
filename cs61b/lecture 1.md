---
title: lecture 1
date: 2022-05-18 15:59
---
# Lecture 1
### overview
主要目的：
- 学习如何掌握编写出高效运行代码的技巧
- 大型程序的构建、设计
    - git, intelli J, JUnit 以及其他命令行工具
- Java

### Intro, hello java
```python
print(hello)
```
```java
public class Helloworld {
    public static void main(String[] args) { 
        system.out.println(“Hello world”);
/**
1.  All code in Java must be part of a class
2.  begin and end a segments with { }
3.  must end with ; 
4.  need public static void main()
*/
    }
}
```
相比于 `python`, `java` 的所有语句必须是 `class``的一部分，这是因为 java 是用于大型软件开发的编程语言，强制面向对象编程可以得到更好的结果

对于循环来说，在 python 里可能有这样的方法:
```python
x = 0 
while (x < 10):
    print(x)
    x = x+1
```
如果我们想利用 java 作同样的事情
```java
public class Helloworld {
    public static void main(String[] args) { 
        int x = 0;
        while (x<10) {
            system.out.println(x)
            x += 1;
        }
/**
1.  java 是静态语言，定义变量前需要声明
2.  java 变量必须有指定的类型
3.  java 变量类型无法改变
4.  java 在代码运行之前要验证类型，否则无法进行编译（python 至少会运行报错）
*/
    }
}
```

在`python`中，可以通过`def`去定义函数然后去调用：
```python
def larger(x,y):
    if x > y:
        return x
    return y
```
如果需要实现同样的事情在 java 中
```java
public class LargeDemo {
    public static int larger(int x, int y){
        if (x>y) {
            return x;    
       }    
        return y;
}
    public static void main(String[] args) { 
        system.out.println(larger(5, -10));
/**
1.  在 java 中声明一个函数需要 public static
2.  函数中参数必须都指定一个对象，函数本身也需要定义返回对象
3.  所有函数必须是类的一部分
*/
    }
}

```
此外，针对不同的数据类型，java 需要重复写相同的函数，这也是静态语言存在的一种缺点（C++中有模版类）
**优点**：
1. 
