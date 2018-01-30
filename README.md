### Learn SQL
- 学习Oracle基本的语法
- 练习Oracle DDL,DCL,TCL,DML语句
- 练习函数和存储过程的书写
#### 如何使用
- Basic_Tabel部分是基本的表定义和表数据
- Other部分为db2的脚本和语句
- Part部分为Oracle练习语句


#### 刚开始安装Oracle时权限不足的情况解决办法
- 电脑 -> 管理 -> 本地用户和组 -> 组 -> ora_dba -> 添加
- 然后找到当前Windows登录用户，不是数据库的用户名，手打加入进去就行，例如ragrok,Administrator
- 执行cmd命令行，执行 `sqlplus / as sysdba` 测试通过即可

#### 登录Oracle
- 执行cmd命令行，执行 `sqlplus / as sysdba` 匿名用户登录
- 执行cmd命令行，执行 `sqlplus scott/tiger as sysdba` 用户密码登录
