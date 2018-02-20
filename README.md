# selenium-studying-java
selenium在java上的实现

## catch-handle
网上下的代码。在跑selenium时，可以中途保存所打开窗口的句柄，在程序其他地方甚至用其它程序再去接手此窗口句柄以便接着操作。  
用途：比如可以先由程序打开窗口，这时由人工作一些操作，最后再交由另外的程序接着人工操作后的步骤做。  
TestTaobao.java是自己使用时的例子代码；pom.xml文件是配合引用了此jar包的maven配置文件。  
webtest是源代码，.jar是已经打包好的，可以直接使用的jar包  


## TestMyPages
用selenium测试本地的一个html网页。  
其中用到了：  
1.selenium的等待方法，一直等到所期望的标签出现再进行操作。   
2.如何在selenium代码中直接嵌入javascript  

## TestBaidu, TestTaobao
selenium基本的使用的例子。  
在TestTaobao里实现了淘宝网的拖动进度条验证登录
