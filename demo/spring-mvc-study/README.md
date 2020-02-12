一个spring  mvc  的 简单 demo  

运行方式
其内部已经引入了 jetty插件 
执行   
`mvn  jetty:run  方法 `

相关测试的地址如下   
传统样式的 url  
http://localhost:8080/courses/view?courseId=123  
restFul样式的url  
http://localhost:8080/courses/view2/123342  
传统的servletRequest的形式来获取参数  
http://localhost:8080/courses/view3?courseId=123

一个编辑界面  
http://localhost:8080/courses/admin?add  


文件上传   
http://localhost:8080/courses/upload

http://localhost:8080/courses/doUpload