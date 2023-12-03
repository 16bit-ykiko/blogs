# C++ 话题索引
在知乎上浏览`C++`相关话题很久了，收藏夹里面也收藏了很多了。但是由于知乎不能对收藏夹分类，而且对于一些比较久远的文章搜索优先级不高，特以此文做一些记录。本文主要记录一些优秀的`C++`相关回答，文章，主要内容来源是知乎，如果你有好的内容，也欢迎分享，其中若干内容是作者本人的文章。

- [C++ 话题索引](#c-话题索引)
- [工具](#工具)
- [必读](#必读)
- [常见](#常见)
- [宏（Macro）](#宏macro)
- [虚函数相关](#虚函数相关)
- [模板（Template）](#模板template)
- [反射](#反射)
- [优化](#优化)
- [实现解析](#实现解析)
- [趣味阅读](#趣味阅读)
- [杂项](#杂项)
 

# 工具
- [cppreference](https://cppreference.com/w/)
  - `C++`参考手册，包含了`C++`的各种语法，标准库，以及各种语言特性的介绍

- [godbolt](https://godbolt.org/)
  - 在线编译器，可以查看`C++`代码的汇编，以及各种平台的编译，运行结果，可用于代码分享
- [cppinsight](https://cppinsights.io/)
  - 可以对`C++`代码进行解糖

# 必读
- [谈谈 C++ Undefined Behavior](https://zhuanlan.zhihu.com/p/391088391)
  - 从各个角度谈论了`C++`中的未定义行为，标准，原因，作用，不可多得的好文！

# 常见
- [inline 的作用](https://www.zhihu.com/question/419304773/answer/1453712022)
  - `inline`不是强制内联的作用！

- [volatile 的作用](https://zhuanlan.zhihu.com/p/33074506)
  - `volatile`不是用来保证线程安全的！

- [trivial/pod 的意思](https://www.zhihu.com/question/472942396/answer/2009365067)
  - 介绍了`trivial/pod`的概念和作用 

- [值类别，移动语义，完美转发](https://www.zhihu.com/question/363686723/answer/1976488046)
  - 全面详细的介绍了`C++`的移动语义和值类别

- [成员指针的使用和实现](https://zhuanlan.zhihu.com/p/659510753)
  - 介绍了`C++`中的成员指针（`pointer to member`）的使用以及常见编译器的实现

- [C++ 和 Rust 关于移动实现的对比](https://www.zhihu.com/question/369738529/answer/1006022667)
  - 对比了这两种语言关于移动操作的优点和缺点

# 宏（Macro）

- [C/C++ 宏编程的艺术](https://zhuanlan.zhihu.com/p/152354031)
  - 详细而全面的介绍了`C/C++`中各种宏的用法

# 虚函数相关
- [C++ 虚函数表虚继承内存模型](https://zhuanlan.zhihu.com/p/41309205)
  - 对不同编译器关于虚函数表的构造进行了详细的讨论

- [虚函数一定式运行期才绑定吗？](https://www.zhihu.com/question/491602524/answer/2165605549)
  - 对常见的错误认知进行详细讨论并且斧正

- [C++ 虚函数是否多余](https://www.zhihu.com/question/280968276/answer/421051100)
  - 对于侵入式多态和非侵入式多态的讨论

- [Rust 和 C++ 中的虚函数相关比较](https://www.zhihu.com/question/444822225/answer/2775163146)
  - 对于`C++`中的`dyn trait`与`enum`和`C++`中的`virtual`与`variant`的讨论

- [dynamic_cast的实现和性能分析](https://zhuanlan.zhihu.com/p/580330672)
  - 对于`C++`的`dynamic_cast`的实现做了分析和性能测试

# 模板（Template）
- [真正意义上的理解 C++ 模板](https://zhuanlan.zhihu.com/p/655902377)
  - 对`C++`中的`Template`进行的详细而全面的**综述**

- [C++ 模板元编程教程](https://zhuanlan.zhihu.com/p/378355217)
  - **从零开始**学习`C++`模板元编程、】=【-0

- [可变参数](https://zhuanlan.zhihu.com/p/104450480)
  - 对`C`语言的可变参数和`C++`的可变参数模板的讨论

- [C++ 的模板技术越来越复杂，这是否会是一个误区？](https://www.zhihu.com/question/600808314/answer/3027252107)
  - 对不同语言中元编程的讨论和对比，包括`C++`

# 反射
- [遍历结构体成员](https://www.zhihu.com/question/598203489/answer/3153384431)
  - 通过特殊的技巧，实现对聚合类型结构体的遍历    

- [获取枚举值的名字](https://zhuanlan.zhihu.com/p/649810772)
  - 利用编译器扩展和模板实例化，获取枚举值对应的名字

- [写给 C++ 程序员的反射教程](https://zhuanlan.zhihu.com/p/669358870)
  - 探讨反射这一概念以及可能的实现方式

- [一个完整的 C++ 静态反射的实现](https://zhuanlan.zhihu.com/p/136561745)
  - 可以实践中使用的静态反射实现 

# 优化
- [C++ 性能压榨之 switch](https://zhuanlan.zhihu.com/p/38139553)
  - 对`switch`的常见实现做了解析

# 实现解析
- [fbstring的实现解析](https://www.zhihu.com/question/54664311/answer/1978680475)
  -  全面解析了fbstring的实现，介绍了一些常见的概念，如`sso`，`cow`等

# 趣味阅读
- [C++ 有多难？](https://www.zhihu.com/question/30196513/answer/563560938)
  - 从**构造函数**的编写作为切入点，论证了`C++`的**难**

- [为什么不想再碰 C++ ?](https://zhuanlan.zhihu.com/p/24328534)
  - 看了你就懂了

- [合法访问 C++ 的私有成员](https://www.zhihu.com/question/521898260/answer/2394522797)
  - 通过模板实例化检查的漏洞非侵入的访问`C++`的私有成员

- [C++ 中的状态元编程](https://zhuanlan.zhihu.com/p/646752343)
  - 通过友元注入，给编译期计算引入全局状态！

# 杂项
- [什么是开洞?](https://zhuanlan.zhihu.com/p/348365662)
  - 介绍了`C++`中各种开洞实现
