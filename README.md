# ssm-crud
网址：https://www.bilibili.com/video/av21045215      基于Maven+SpringMVC+Spring+MyBatis+Bootstrap的组合，快速开发一个完整的CRUD功能，视频除过对框架组合的基本使用外，还涉及到许多的开发细节：Bootstrap搭建页面，MyBatis逆向工程使用，Rest风格的URI，@ResponseBody注解完成AJAX，AJAX发送PUT请求的问题，jQuery前端校验，JSR303

# notes
get查询 post新增 put修改 delete删除

Web.xml, spring,springmvc,mybatis，使用mybatis的逆向工程生成对应的bean以及mapper

普通查询
1.访问index.jsp页面
2.index.jsp页面发送出查询员工列表请求
3.EmployeeController来接受请求，查出数据
4.来到list.jsp页面进行展示
