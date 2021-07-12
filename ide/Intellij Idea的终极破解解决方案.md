# Intellij Idea的终极破解解决方案
Intellij Idea是一款后端开发者瑞士军刀，但是使用过IDEA的人都知道专业版价格不菲，今天小棒就来叫大家两种无需采用破解jar的方式使用上IDEA的专业版配置。
## 方案一：IntelliJ IDEA社区版+强大插件
### 1、Smart Tomcat
* 一款可以自动加载Webapp类和库Tomcat服务器的插件，无需将类和库复制到WEB-INF/classes和WEB-INF/lib；
* 项目主页：https://github.com/zengkid/SmartTomcat

![image-20210711223841972](https://mine-doc.oss-cn-beijing.aliyuncs.com/blogimage-20210711223841972.png)



### 2、Spring Assistant

* 一款可用于快速创建SpringBoot应用的插件
* 项目主页：https://plugins.jetbrains.com/plugin/10229-spring-assistant

![img](https://mine-doc.oss-cn-beijing.aliyuncs.com/blogwatermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3h1YW44OTMw,size_16,color_FFFFFF,t_70.png)



### 3、Database Navigator

* 一款介于JDBC和Navicat之间的数据库管理插件，它提供了高级数据库连接管理、脚本执行支持、数据库对象浏览、数据和代码编辑器、数据库编译器操作支持、方法执行和调试支持、数据库对象工厂以及所有组件之间的各种导航功能。
* 项目主页：https://plugins.jetbrains.com/plugin/1800-database-navigator

![Screenshot 1](https://mine-doc.oss-cn-beijing.aliyuncs.com/blogscreenshot_17907.png)

### 4、Maven Helper

* 可以查看和管理maven依赖的插件，以列表或树的形式展示pom依赖，还可以非常直观的排查冲突和依赖
* 项目主页：https://plugins.jetbrains.com/plugin/7179-maven-helper

![Screenshot 1](https://mine-doc.oss-cn-beijing.aliyuncs.com/blogscreenshot_19711.png)

### 5、MybatisX

* MybatisX 是一款基于 IDEA 的快速开发插件，为效率而生，支持Java 与 XML 调回跳转和Mapper 方法自动生成 XML。
* 项目主页：https://plugins.jetbrains.com/plugin/10119-mybatisx

![Screenshot 1](https://mine-doc.oss-cn-beijing.aliyuncs.com/blogscreenshot_22963.png)



### 6、Lombok

* 一款可以让代码更加简洁的插件，同时还要增加dependency

  ```java
  <dependency>
      <groupId>org.projectlombok</groupId>
      <artifactId>lombok</artifactId>
      <optional>true</optional>
  </dependency>
  ```

* 项目主页：https://projectlombok.org/



**以上是个人认为社区版必备的插件，其他更多插件可详阅：**

[IntelliJ IDEA Community Edition 社区版插件汇总](https://blog.csdn.net/tangyb828/article/details/109455322)

[Intellij IDEA 实用插件推荐](https://zhuanlan.zhihu.com/p/111319829)

**这里也提供一个拥有11个插件的[Idea.Zip](https://plugins.jetbrains.com/plugin/10119-mybatisx)包，解压即可运行。**



## 方案二：试用期重续（ide-eval-resetter）

ide-eval-resetter是一款可以让你的Jetbrains全家桶无限期使用的超级插件，有两种使用方法：

#### 方法1：在线安装

* 第一步：打开Settings->Plugins->Manage Plugin Repositories

![image-20210711231145278](https://mine-doc.oss-cn-beijing.aliyuncs.com/blogimage-20210711231145278.png)

* 第二步：输入https://plugins.zhile.io

![image-20210711231250260](https://mine-doc.oss-cn-beijing.aliyuncs.com/blogimage-20210711231250260.png)

* 第三步：install

![image-20210711231349635](https://mine-doc.oss-cn-beijing.aliyuncs.com/blogimage-20210711231349635.png)

* 第四步：有效期重置

![image-20210711233612656](https://mine-doc.oss-cn-beijing.aliyuncs.com/blogimage-20210711233612656.png)







#### 方案2：离线安装

* 先离线下载插件，[点击这里](https://plugins.zhile.io/files/ide-eval-resetter-2.1.14-d2fedb86.zip)

* 然后解压，放入${IDEA_HOME/plugins目录

  ![image-20210711233119324](https://mine-doc.oss-cn-beijing.aliyuncs.com/blogimage-20210711233119324.png)

  ![image-20210711233612656](https://mine-doc.oss-cn-beijing.aliyuncs.com/blogblogimage-20210711233612656.png)

  

* gitee地址：https://gitee.com/pengzhile/ide-eval-resetter

* 备用地址：https://github.com/willcrisling/appbangjile/blob/master/asset/ide-eval-resetter-2.1.6.zip

**后台回复001，免费获取含10+插件社区版IDEA及ide-eval-resetter插件**


