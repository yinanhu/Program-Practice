

### [资源导航站代码]

人人影视大概在2013年的1月份时(大概是这个时间吧..)说需要人帮忙写一个资源导航站.. <br />
发邮件要了素材之后就再没回复, 因为对工作量错误估计, 以为两天就能做好.. <br />
然后就直接开始做了.. <br />
结果搞了2个星期才做完了, 之后再问的时候发现人家已经和另外的人谈好了. <br />
是我自己太2了...应该先谈好再开写的..代码虽然已经搞定了可没人用. <br />
放在硬盘里烂掉也不是回事儿..所以就扔上来了 <br />


<br>
### [一些说明]:
#### 关于编程语言
* 语言 PHP
* 数据库 MySQL
* 登录验证 Session
* 首页做了静态化.

<br />
#### 关于个别目录的说明:
tool/    存放一些函数工具.   目前只有一个MySQL_Helper.php  它可以帮助简化数据库链接的相关操作.  
42/                                 所有和后台相关的文件都放在里面  
42/Handle_Insert_Modify_Delete      负责处理后台以ajax发送的 [增][删][改][查] 操作  






<br />
####  本站使用的外部工具库:

jQuery      一个JS库  
Bootstrap   一个前端开发的工具包  
reset.css   用于重置样式  
mootools    用于实现拖放操作  



<br />
#### 使用说明:
1. 把整个文件夹放到你的Apache服务器目录里
2. 导入 db.sql 到 MySQL 数据库, 可以用 sqlbuddy 或者 phpMyDdmin 或者 手工导入
3. 可以访问使用了 :D



<br />
#### 关于后台密码:
42/Handle_Login.php     用户名和密码都已经写死在里面了

默认用户名是:   yyets  
密码是:    superadmin  
均为小写, 可自行在Handle_Login.php文件里修改. 代码在第22行  
