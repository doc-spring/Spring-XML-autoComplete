#Eclipse 添加Spring XML配置文件的提示
####1、【window】->【preference】..->【xml】-> 【xml catalog】
  
####2、选中 user specified entried
####3、选择左边【Add..】按钮
           Location：请选择本地文件系统上的SPRING_HOME\dist\resources\spring-beans-2.5.xsd
           key type：Schema Location  
           key：http://www.springframework.org/schema/beans/spring-beans-2.5.xsd
####4、点击确定
####5、关闭源配置文件，重新打开即可
 
XML文件的打开方式最好选择【XML Editor】，其中包括design,source两种模式，选择source模式。某些XML编辑器有可能不支持Spring提示。
