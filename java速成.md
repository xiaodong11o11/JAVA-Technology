### Markdown

一、java语言基础（4天）

      这个阶段不要用IDE，多做练习。快速的看完，大致明白即可。以后在开发中逐步熟悉与提升
      
  1、配置环境
  
        jdk 配置与使用，配置pycharm时已经配置过了，就是设置环境变量，例如：
        export JAVA_HOME=/work/software/jdk1.7.0_79
        export JDK_HOME=$JAVA_HOME
        export JRE_HOME=$JAVA_HOME/jre
        export CLASSPATH=.:$JAVA_HOME/lib:$JRE_HOME/lib:$CLASSPATH
        export PATH=$JAVA_HOME/bin:$JRE_HOME/bin:$PATH
        export PATH
        
  2、快速了解
  
        http://www.cnblogs.com/happyframework/p/3332243.html
        
  3、Java初级知识
  
        http://www.code123.cc/606.html
        
  4、Java进阶知识（GUI相关的不用看）
  
        http://www.code123.cc/1001.html
        
  5、学习java编程规范
  
        https://github.com/waylau/java-code-conventions
        
###二、工具链熟悉（1天）

      IDE，很多教学是Eclipse, 建议用IntelliJ IDEA，与pycharm一个公司的产品 
      https://github.com/judasn/IntelliJ-IDEA-Tutorial
      了解Ant、Maven，现在是推荐用Gradle 
      
###三、java常用库的熟悉（2天）

      jdbc、Log4j、Apache Commons、Fastjson、JUnit
      去www.oschina.net、www.iteye.com上边搜，很多资料
      
###三、学习开发WEB项目（16天） 

      Java SSH（Struts Spring Hibernate）是曾经的经典web框架，不过现在：
      struts 已经被淘汰，建议使用Spring MVC。如果你们外包的公司用struts，你就哭吧
      Hibernate 太重，建议看ibatis（已经改名mybatis），阿里系的在用ibatis。一样的，新手去接手Hibernate会被搞残的
      Java框架都太重，现在出现一些小巧的框架方便快速开发：jfinal、blade等
      一些教学中会教：
          JSP、EL、JSTL，已经淘汰或者说过时了，不建议学了
      现在有2条路线可以选择：
          1、比较传统的组合
                Spring MVC、mybatis（ORM）、FreeMarker（模板引擎）或者Velocity
                书：
                Spring 实战(第3版)
                http://item.jd.com/1809007861.html
                要是英语好
                http://www.mkyong.com/tutorials/spring-mvc-tutorials/
                也可以看看国内应用参考示例（有些庞大）
                http://springside.io/index.html
                Java Web高级编程
                http://item.jd.com/11723338.html
                mybatis、FreeMarker、Velocity
                看网上教学
          2、选择轻量级的jfinal（自己的项目，我推荐这个）
                介绍
                http://www.csdn.net/article/2013-12-06/2817738-JFinal-Java-MVC-ORM-Framework
                学习官方例子，熟悉用到的第三方库和软件
                看别人的作品http://www.oschina.net/p/jfinalbbs
四、JAVA生态圈熟悉（1天）
          https://github.com/jobbole/awesome-java-cn
五、自己做一个blog（4天）
          做一个blog程序，放到github上，让别人点评
六、深入（4天）
            快速过一遍，留个印象，以后有空了慢慢看
        1、java语言深入
            Java编程思想（第4版）
            看前21章，图形化不用看
        2、web开发
            深入分析Java Web技术内幕（修订版）
            http://item.jd.com/11520670.html
        3、看下其它知识
            Spring boot
            TDD
            https://github.com/qibaoguang/Study-Step-by-Step
七、其它参考资料：
        视频教学
        http://www.maiziedu.com/course/java/
        Java 语言基础
        Java Web基础-servlet
        Java Web基础-JDBC
        Java Web基础-Tomcat
        Java Web进阶-Spring
        Java Web扩展-Freemarker
        Java Web进阶-Mybatis
        Java Web扩展-Maven
        Java Web拓展-Spring MVC
八、看完了，多做练习，有空了把上边列的书再看一遍
        培训机构的视频教学（这类的教学有点啰嗦，有些地方可以跳过去，图形(AWT、Swing等)，Java的事件处理机制，Java Applet这些都不用看）
        http://www.itcast.cn/news/20141107/10494252523.shtml
        http://java.itcast.cn/news/e393b086/ebce/4f94/9d48/94ed86bcf5ef.shtml
        http://www.oschina.net/p/jfinal?fromerr=ja39Wpik
