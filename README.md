## 简介
基于springmvc、spring、mybatis-plus、shiro、easyui、Log4j2简单实用的权限系统。

项目导入请百度`eclipse`、`myeclipse`、`idea`等IDE导入`maven web`项目。

二次开发可采用`jetty maven plugin`启动，`pom.xml`中已经配置。

如果觉得数据校验不够，请自行添加hibernate-validator在Bean上做校验！

另外，你需要根据自己的业务添加`shiro注解`，实现请求控制。

更多`shiro`的教程请参考（开涛博客`《跟我学Shiro》`）：http://jinnianshilongnian.iteye.com/category/305053

另外欢迎`Pull Requests`给我们一起完善该项目！

## 运行环境
`jdk7 + tomcat7`或以上！

线上环境使用`mvn`打包时添加`-Pproduction`变量则会使用`src/main/conf/production`目录下的配置文件。

线上`production`请注意添加一份`cofing/application.properties`配置文件（由于开源，使用`.gitignore`进行了屏蔽）

## 效果图
<p>
<img src="http://static.oschina.net/uploads/img/201512/06161620_HLY6.jpg"/>
</p>
<p>
<img src="http://static.oschina.net/uploads/img/201512/06161621_NIlr.jpg"/>
</p>
<p>
<img src="http://static.oschina.net/uploads/img/201512/06161621_63ZV.jpg"/>
</p>
<p>
<img src="http://static.oschina.net/uploads/img/201512/06164718_18nx.jpg"/>
</p>
<p>
<img src="http://static.oschina.net/uploads/img/201512/06161621_NiiM.jpg"/>
</p>

## 鸣谢
<p>
<a href="http://my.oschina.net/qq596392912" target="_blank">@Dreamlu</a>&nbsp;
<a href="http://my.oschina.net/u/993551" target="_blank">@刘晓枫</a>
</p>

## 演示效果
<p>
<a href="http://shiro.dreamlu.net" target="_blank">http://shiro.dreamlu.net</a> 账号：test 密码：test
</p>

## 技术咨询
<p>
QQ群：523720304 &nbsp; 不提供全权限账号，人多手杂，维护时间有限，可本地导入项目运行，admin密码和test一样，谢谢。
</p>
<p>
git地址：<a href="https://git.oschina.net/wangzhixuan/spring-shiro-training.git" target="_blank">https://git.oschina.net/wangzhixuan/spring-shiro-training.git</a>
</p>
<p>
欢迎star、fork，不好的地方，接受狂喷，本着共同学习的心态。
</p>

## 捐助共勉
<p>
<img src="http://ww2.sinaimg.cn/small/907f4c96jw1f3sjdhn1dcj208w0aiq3d.jpg" alt="微信" />
<img src="http://ww3.sinaimg.cn/small/907f4c96jw1f3sjdhkn0rj20by0byq33.jpg" alt="支付宝" />
</p>

### 捐助记录



## 更新记录
> 2016-12-20 v1.1.1 修改若干`bug`，cache改为spring-cache，shiro添加密码错误次数限制，密码加密改为shiro处理。

> 2016-10-11 v1.1.0 采用`mybatis-plus`简化数据库，去除主从数据库，老版本升级需要执行`database/update_xxxx.sql`。

> 2016-10-01 v1.0.0 升级Spring版本更改log为Log4j2。

`注`: `v1.0.0`等老版源码请见Git Tag。

## License

( The MIT License )