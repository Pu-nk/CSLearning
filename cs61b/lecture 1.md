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


