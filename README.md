# weijia

创建数据库名称；
create database dba；
显示创建得
show create database dba;
删除数据库；
drop database dba;
查询数据库所有表；
show databases;
将数据库得字符集修改为gbk mysql命令；

alter database jade1 character set gbk;

show  cerate  database dba;

切换数据库；
use dba;

查看当前使用得数据库；
select database();
创建数据表；
 create table student(
 id int,
 name varchar(20),
 gender varchar(10),
 birthday date
 );


show tables;
show create table student;  // 查看表基本信息
desc student;                     // 查看表得字段信息
alter table student rename to stu;  //修改表名
alter table stu change name sname varchar(10);  //修改字段名 MySQL命令：
alter table stu modify sname int; //修改字段数据类型
alter table stu add address varchar(50);  //增加字段
alter table stu drop address;    //删除字段
drop table stu;  //删除数据表
