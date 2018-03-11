# JDKHistory

记录Java版本的更新历史，主要是对以下文章的结合：
* [《从java1到java9每个版本都有什么新特性？》](https://www.cnblogs.com/rese-t/p/7823378.html)
* [《Java 9正式发布》](http://blog.csdn.net/postnull/article/details/78068060?locationNum=2&fps=1)
* [《JDK 10 本周将进入候选发布阶段，新特性抢先看》](https://www.oschina.net/news/93123/jdk10-release-candidate-phase)

# JDK 11
[JDK 11](http://openjdk.java.net/projects/jdk/10/) 目前出现了4个JEP。
* [JEP 309](http://openjdk.java.net/jeps/309): 动态类文件常量。
* [JEP 318](http://openjdk.java.net/jeps/318): 低开销垃圾收集器 Epsilon。
* [JEP 320](http://openjdk.java.net/jeps/320): 移除 Java EE 和 CORBA 模块。
* [JEP 323](http://openjdk.java.net/jeps/323): Lambda 参数的本地变量语法。

# JDK 10
[JDK 10](http://openjdk.java.net/projects/jdk/10/) 按计划将于2018年3月20日发布。新特性有：
* [JEP 286](http://openjdk.java.net/jeps/286): 局部变量的类型推导。该特性在社区讨论了很久并做了调查，可查看 JEP 286 调查结果。
* [JEP 296](http://openjdk.java.net/jeps/296): 将 JDK 的多个代码仓库合并到一个储存库中。
* [JEP 304](http://openjdk.java.net/jeps/304): 垃圾收集器接口。通过引入一个干净的垃圾收集器（GC）接口，改善不同垃圾收集器的源码隔离性。
* [JEP 307](http://openjdk.java.net/jeps/307): 向 G1 引入并行 Full GC。
* [JEP 310](http://openjdk.java.net/jeps/310): 应用类数据共享。为改善启动和占用空间，在现有的类数据共享（“CDS”）功能上再次拓展，以允许应用类放置在共享存档中。
* [JEP 312](http://openjdk.java.net/jeps/312): 线程局部管控。允许停止单个线程，而不是只能启用或停止所有线程。
* [JEP 313](http://openjdk.java.net/jeps/313): 移除 Native-Header Generation Tool (javah)
* [JEP 314](http://openjdk.java.net/jeps/314): 额外的 Unicode 语言标签扩展。包括：cu (货币类型)、fw (每周第一天为星期几)、rg (区域覆盖)、tz (时区) 等。
* [JEP 316](http://openjdk.java.net/jeps/316): 在备用内存设备上分配堆内存。允许 HotSpot 虚拟机在备用内存设备上分配 Java 对象堆。
* [JEP 317](http://openjdk.java.net/jeps/317): 基于 Java 的 JIT 编译器（试验版本）。
* [JEP 319](http://openjdk.java.net/jeps/319): 根证书。开源 Java SE Root CA 程序中的根证书。
* [JEP 322](http://openjdk.java.net/jeps/322): 基于时间的版本发布模式。“Feature releases” 版本将包含新特性，“Update releases” 版本仅修复 Bug 。

# JDK 9
JDK 9 于2017年9月21日发布。新特性有：
* 模块化 —— Jigsaw
* 交互式命令行 —— JShell
* 默认的垃圾回收器 —— G1
* 进程操作改进
* 竞争锁的性能优化
* 分段代码缓存
* 优化字符串占用空间 

# Java 8
JDK 8 于2014年3月14号发布。从 Java 8 开始开发代号已经弃用了。新特性有:
* Lambda 表达式
* Pipelines 和 Streams
* Date 和 Time API
* Default 方法
* Type 注解
* Nashhorn JavaScript 引擎
* 并发计数器
* Parallel 操作
* 移除 PermGen Error
* TLS SNI

# JDK 7
开发代号是 Dolphin（海豚），于2011年7月28日发行。新特性有：
* `switch` 语句块中允许以字符串作为分支条件；
* 在创建泛型对象时应用类型推断；
* 在一个语句块中捕获多种异常；
* 支持动态语言；
* 支持 `try-with-resources`；
* 引入 Java NIO.2 开发包；
* 数值类型可以用2进制字符串表示，并且可以在字符串表示中添加下划线；
* 钻石型语法；
* `null` 值的自动处理。

# JDK 6
开发代号为 Mustang（野马），于2006年12月11日发行。新特性有：
* 支持脚本语言；
* 引入 JDBC 4.0 API；
* 引入 Java Compiler API；
* 可插拔注解；
* 增加对 Native PKI(Public Key Infrastructure)、Java GSS(Generic Security Service)、Kerberos 和 LDAP(Lightweight Directory Access Protocol) 的支持；
* 继承 Web Services；
* 做了很多优化。

# JDK 5
开发代号为Tiger（老虎），于2004年9月30日发行。新特性包有:
* 引入泛型；
* 增强循环，可以使用迭代方式；
* 自动装箱与自动拆箱；
* 类型安全的枚举；
* 可变参数；
* 静态引入；
* 元数据（注解）；
* 引入 Instrumentation。

# JDK 1.4
开发代号为 Merlin（隼），于2004年2月06日发行（首次在JCP下发行）。新特性有:
* XML 处理；
* Java 打印服务；
* 引入 Logging API；
* 引入 Java Web Start；
* 引入 JDBC 3.0 API；
* 引入断言；
* 引入 Preferences API；
* 引入链式异常处理；
* 支持 IPv6；
* 支持正则表达式；
* 引入 Image I/O slot machine API。

# JDK 1.3
开发代号为 Kestrel（红隼），于2000年5月08日发行。新特性有：
* 引入Java Sound API；
* jar 文件索引；
* 对 Java 的各个方面都做了大量优化和增强。

# JDK 1.2
开发代号为 Playground（操场），于1998年12月8日发行。新特性有：
* 引入集合（Collection）框架；
* 对字符串常量做内存映射；
* 引入 JIT（Just In Time） 编译器；
* 引入对打包的 Java 文件进行数字签名；
* 引入控制授权访问系统资源的策略工具；
* 引入 JFC（Java Foundation Classes），包括 Swing 1.0、拖放和 Java 2D 类库；
* 引入 Java 插件；
* 在 JDBC 中引入可滚动结果集、BLOB、CLOB、批量更新和用户自定义类型；
* 在 Applet 中添加声音支持。

# JDK 1.1
于 1997年2月19日发行，新特性有：
*  引入JDBC（Java Database Connectivity）；
*  支持内部类；
*  引入Java Bean；
*  引入RMI（Remote Method Invocation）；
*  引入反射（仅用于内省）。

# JDK 1.0
开发代号为Oak（橡树），于1996年1月23发行。
