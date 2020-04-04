# Java-ABC
## 关于JAVA的学习笔记和心得 

## Java 的安装和基础知识

（For more information, please go to
***[Alan D. Chen](https://github.com/Alan-D-Chen/Java-ABC)*** ,
upgrading~~）<br>

_**[简单粗暴理解JAVA_SE 、EE、ME 三者的区别](https://blog.csdn.net/ns__l/article/details/78299781)**_
<br>
> >>Java SE(Java Platform,Standard
> >>Edition)，应该先说这个，因为这个是标准版本。<br> Java EE (Java
> >>Platform，Enterprise Edition)，java 的企业版本.<br> Java ME(Java
> >>Platform，Micro Edition)，java的微型版本。<br>
<br>
JavaSE 可以开发和部署在桌面、服务器、嵌入式环境和实时环境中使用的 Java 应用程序。是EE，和ME的基础。一般就是指JDK。就是Java的基础语法（变量、方法、类之间的调用、关系，继承、接口、线程之类的），工具包（java.util.* ）,或者其他的一些封装，是学习其他的基础。
JavaEE，其实是一套规范，就是用java语言做企业开发（目前看来就是开发一些动态网站，或者对外提供调用服务的网站，或者其他没接触过的。。。）中的一整套规范，比如类怎么封装，网页的请求要用什么方法处理，语言编码一类的处理，拦截器啊什么的定义，请求返回得有什么信息。。。（具体看servlet的接口就知道了）
比如：tomcat就是按照这套规范开发的容器软件，还有什么weblogic，JBoss、Resin等等.<br>
正因为我们开发网站（使用JSP，Servelet。。或者封装了这些的框架：SSH。。。）可以放在tomcat，也可以放在JBoss。。。。，因为都是按照一个规范开发的东西，实际使用的还是JavaSE的那些东西，多出来的就是EE的一些规范类的封装代码。
JavaME 是微型版本，顾名思义，使用在手机啊，小设备啊上面的Java版本，特点就是小，相比JavaSE精简了很大一部分东西，（增加了一些小设备上的专有API，这个不是很确定）。
安卓中既然用的是Java，那么Java的语法应该都是适用的。所以SE是核心基础。其他的都是使用方法方式不同。
========================================================================  
<br>

_**[JDK介绍与安装](https://blog.csdn.net/shuaigexiaobo/article/details/85280084)**_

（一）JDK简介 <br>
 JDK Java SE Development kit(JDK) java开发工具包<br>
JDK全称Java SE Development kit(JDK)，即java标准版开发包，是Oracle提供的一套用于开发java应用程序的开发包，它提供编译，运行java程序所需要的各种工具和资源，包括java编译器，java运行时环境，以及常用的java类库等。
<br>
?JRE?? Java Runtime Environment(JRE) Java运行环境
<br>
Java运行环境，它的全称Java Runtime Environment(JRE) ，因此也被称为JRE，它是运行java的必需条件。
<br>
JVM ?Java Virtual Machine
<br>
Java虚拟机，JRE包含JVM。JVM是运行java程序的核心虚拟机，还需要其他的类加载器，字节码校验器，以及大量的基础类库。JRM除了包含JVM之外，还包含运行java程序的其它环境支持。
