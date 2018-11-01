# shiro-rest
spring mvc + shiro + jwt 实现rest api

(一)功能点:
/public/** 可匿名访问

/rest/** 必须带token验证

/auth/token 利用用户名与密码获取token

(二)运行截图

(1)访问公开api
![image](http://github.com/zhenfeii/shiro-rest/raw/master/images/public.jpg)




(2)访问须认证的api,不带token
![image](http://github.com/zhenfeii/shiro-rest/raw/master/images/rest_notauth.jpg)



(3)获取token
![image](http://github.com/zhenfeii/shiro-rest/raw/master/images/token.jpg)



(4)带token访问rest api
![image](http://github.com/zhenfeii/shiro-rest/raw/master/images/rest.jpg)





(三)技术栈

(1)spring spring mvc

(2)shiro

(3)jwt生成token

(4)DruidDataSource连接池


