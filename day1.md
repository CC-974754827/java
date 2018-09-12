```
java：跨平台 编译语言 面向对象
day1
一、java的安装的配置
jdk：java development kits java开发包
  |—jdk：开发者使用
    |—bin：工具
	  |—javac.exe :java的编译器 将.jav源文件--编译（javac）-->.class
	  |—java.exe :java的解释执行器
	|—lib：java开发包（jar）
	|—jre：
	 
  |—jre：java runtime enorient java运行环境  服务器使用
    |-jvm：java虚拟机
  
手动编写java程序

使用IDE工具开发java：eclipse
|—创建java项目
|—建包:英文，有意义，全小写

|—在src下创建类
  |—英文，有意义，且首字母要大写。整个命名规则使用驼峰表示法|下划线表示法 
   
二、java的数据类型
基本数据类型：byte：1个字节 < short：2个字节 < int：4个字节 < long：8个字节
              < float：4个字节 单精度类型 < double：8个字节 双精度类型
			  char：2个字节 字符类型 boolean：1个字节 布尔类型（true|false）

引用|类数据类型：String

类型转换：
 |-低精度--自动-->高精度
 |-高精度--强制-->低精度

三、java的运算符
 |-算数运算符 + - * / %(取余) 
    注意：1）+如果左右都是数值，+就是算数运算符的加的作用；
	         如果左右有一个是字符串，+的作用就是连接符 
		  2）/如果除数和被除数都是整数，结果就是整数
 |-关系运算符 >,<,>=,<=,!=，==
 |-逻辑运算符 &&与 ||或 !非
 |-位运算符:&与位运算 ~与非运算 ^异或位运算
 |—赋值符号：=
 
四、程序执行结构
 |-顺序结构
 |-分支结构
   |-单分支
      if(条件表达式){
	    满足条件执行的代码;
	  }
   |-双分支
      if(条件表达式){
	    满足条件执行的代码;
	  }else{
	    否则执行的代码;
	  }
   |-多分支 
       （1）if多分支 死胡同 能使用条件表达式
	  if(条件表达式1){
	    满足条件1执行的代码;
	  }else if(条件表达式2){
	    满足条件2执行的代码;
	  }else if(条件表达式3){
	    满足条件3行的代码;
	  }else if(条件表达式4){
	    满足条件4执行的代码;
	  }else if(条件表达式5){
	   满足条件5执行的代码;
	  }else{//提高程序的健壮性
	    所有条件都不满足执行的代码;
	  }
	  
	  （2）switch多分支 需要配合break使用 不能使用条件表达式
	    switch(变量){
		  case 值1:
		      变量=值1执行的代码;
		  case 值2:
		      变量=值2执行的代码;
		  case 值3:
		      变量=值3执行的代码;
		  case 值4:
		      变量=值4执行的代码;
		  default:
     		  变量!=值1..4执行的代码
		}
	  
五、编码集
0,1--编码-->人类可识内容	
人类可识内容--解码-->0，1		
	
acsii：英文编码集 单字节编码 最高位是1，只使用了7位
iso8859-1：欧洲编码集 单字节 使用了最高位
gb2312：简体中文  2个字节 
gbk：中文简体+繁体

unicode：通用编码集 3个字节
utf-8： 3个字节
	   gbk
我----11000011 10101010   
   
   
 
 
 
六、java学习路线图
java  
   |-j2se
    |-基本数据结构
	|-循环结构
	|-数组
	|-多方法程序设计
	|-面向对象
	|-封装、继承
	|-多态、抽象类、接口
	|-集合
	|-IO流
	|-异常
	|-jdbc
	|-静态
	|-socket
	|-线程
	|-反射
	|-正则表达式
  |-j2se
    |-Servlet
	  |-HttpSession Cookie ServletContext HttpRequest HttpResponse
	|-Jsp9大对象
	  |—session page pageContext appliation request throw 。。
	  |—EL表达式，JSTL标签库
  |-思想拔高
    |-设计模式
	  |-单例设计模式
	  |-适配器设计模式
	  |-模板设计模式
	  |-工厂设计模式
	  |-装饰设计模式
	|-连接池
	|-静态代理、动态代理
	|-Aop面向切面编程
	|-监听器、过滤器
	|-事务
  |-框架
    |-Spring
	|-SpringMVC
	|-Mybatis
前端技术
1.html
  |-html4
  |-html5
2.Css
  |-css2
  |-css3
3.JavaScript *****
4.ajax:原生ajax
5.jquery
6.vue.js ,react.js

  

  
额外补充
1.maven
2.GitHub
3.Redis
4.Nigx
5.Zookeeper

大数据

```
