# 硬核！Java 基础知识常见面试题总结!（100题附答案）

## 知识点：

- **Java基础知识**
  Java数据类型
  Java字符串
  Java运算
  Java面向对象
  Java关键字
  Java反射
  Java异常
  Java泛型
  Java注解
- **Java集合框架**
  List Set Map
  ArrayList
  LinkedList
  HashMap
  HashSet
  ConcurrentHashMap
  LinkedHashMap
  WeakHashMap
  Vector
  Collection
  Queue
- **Java虚拟机-JVM**
  Java内存区域
  JVM垃圾回收
  JVM垃圾回收算法
  JVM垃圾回收器
  JDK 监控和故障处理工具
  Java类文件结构
  Java类加载过程
  Java类加载器
  Java双亲委派模型
  自定义类加载器
  程序计数器
  虚拟机栈
  本地方法栈
  jvm-堆
- Java IO
  BIO
  NIO
  AIO



## 面试题

1. Java 的8种基本数据类型 及其大小？

2. Java 基本类型与引用类型的区别？

3. 自动装箱和拆箱？

4. Int 与 Integer的区别？

5. String 转成 int 型，判断能不能转？如何转？

6. Java 语言有哪些特点?

7. short s1 = 1; s1 = s1 + 1;有什么错? short s1 = 1; s1 +=1;有什么错?

8. 字节与字符的区别？

9. 面向对象和面向过程的区别

10. JDK 和 JRE 的区别？

11. Oracle JDK 和 OpenJDK 的区别？

12. 重载和重写的区别?

13. String 和 StringBuﬀer、StringBuilder 的区别是什么？

14. String 为什 么是不可变的？

15. 字符型常量和字符串常量的区别

16. Java 面向对象编程三大特性?

17. 抽象类和接口的区别是什么？

18. 成员变量与局部变量的区别有哪些？

19. == 与 equals 的区别？

20. hashCode 与 equals ？为什么重写equals时必须重写hashCode方法？

21. ﬁnal 关键字的理解

22. Object类的常见方法总结 

23. 说一说自己对于 synchronized 关键字的理解 ？

24. 讲一下 synchronized 关键字的底层原理 ？

25. AQS 组件总结 

26. 介绍下 Java 内存区域（运行时数据区） ？

27. Java 对象的创建过程？

28. 对象的访问定位的两种方式

29. 如何判断对象是否死亡（两种方法）？

30. 简单的介绍一下强引用、软引用、弱引用、虚引用（虚引用与软引用和弱引用的区别、使用软引用能带来的好

    处）？

31. 如何判断一个常量是废弃常量 ？

32. 如何判断一个类是无用的类？

33. Java垃圾收集有哪些算法，各自的特点？ 

34. HotSpot为什么要分为新生代和老年代？ 

35. 常见的垃圾回收器有那些？ 

36. 介绍一下CMS,G1收集器？

37. Minor Gc和Full GC 有什么不同呢？ 

38. 请谈谈你对JVM的理解？

39. Java和C++的区别?

40. 什么是 Java 程序的主类 应用程序和小程序的主类有何不同?

41. Java 应用程序与小程序之间有哪些差别?

42. 构造器 Constructor 是否可被 override?

43. 在一个静态方法内调用一个非静态成员为什么是非法的?

44. 在 Java 中定义一个不做事且没有参数的构造方法的作用？

45. import java和javax有什么区别？

46. 创建一个对象用什么运算符?对象实体与对象引用有何不同?

47. 什么是方法的返回值?返回值在类的方法里的作用是什么?

48. 一个类的构造方法的作用是什么? 若一个类没有声明构造方法，该程序能正确执行吗? 为什么?

49. 构造方法有哪些特性？

50. 静态方法和实例方法有何不同

51.  对象的相等与指向他们的引用相等,两者有什么不同?

52. 在调用子类构造方法之前会先调用父类没有参数的构造方法,其目的是?

53. 为什么Java中只有值传递？

54. 简述线程、程序、进程的基本概念。以及他们之间关系是什么?

55. 线程有哪些基本状态?

56. Java 中的异常处理？

57.  Java序列化中如果有些字段不想进行序列化，怎么办？

58. 获取用键盘输入常用的两种方法？

59. Java 中 IO 流分为几种?

60. 既然有了字节流,为什么还要有字符流?

61. BIO,NIO,AIO 有什么区别?

62. static 关键字的理解？

63. this 关键字的理解？

64. super 关键字的理解

65. 深拷贝与 浅拷贝的区别？

66. BIO (Blocking I/O)？

67. NIO (New I/O)

68.  AIO (Asynchronous I/O)

69. 说说List,Set,Map三者的区别？

70. Arraylist 与 LinkedList 区别?

71. RandomAccess接口？

72. 双向链表和双向循环链表?

73. ArrayList 与 Vector 区别呢?为什么要用Arraylist取代Vector呢？

74. 说一说 ArrayList 的扩容机制吧?

75. HashMap 和 Hashtable 的区别

76. HashMap 和 HashSet区别？

77. HashSet如何检查重复

78. HashMap的底层实现?

79. HashMap 的长度为什么是2的幂次方?

80. HashMap 多线程操作导致死循环问题?

81. ConcurrentHashMap 和 Hashtable 的区别?

82. ConcurrentHashMap线程安全的具体实现方式? 底层具体实现原理?

83. comparable 和 Comparator的区别？

84. 集合框架底层数据结构总结一下？

85. 从 JVM 角度说进程和线程之间的关系

86. 程序计数器为什么是私有的?

87. 虚拟机栈和本地方法栈为什么是私有的?

88. 一句话简单了解堆和方法区

89. 说说并发与并行的区别?

90. 为什么要使用多线程?

91. 使用多线程可能带来的问题？

92. 说说线程的生命周期和状态？

93. 说说线程优先级？

94. 守护线程和用户线程的区别？

95. 什么是上下文切换?

96. 什么是线程死锁?如何避免死锁?

97. 请概述一下Java 类文件结构？

98. 请总结一下Class 文件结构？

99. JVM 配置常用参数有哪些?

100. 常用 GC 调优策略有哪些？

参考答案：http://www.mianshigee.com/topic/1000xkh/

