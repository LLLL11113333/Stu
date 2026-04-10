# MySQL概述

## 数据库相关概念

<img src="assets/image-20260207174425310.png" alt="image-20260207174425310" style="zoom: 33%;" />

## MySQL安装

<img src="assets/image-20260207174621067.png" alt="image-20260207174621067" style="zoom: 25%;" />



安装可以查询相关内容，`注意要配置mysql的环境变量，否则无法在命令行使用`

## 启动停止

<img src="assets/image-20260207180229948.png" alt="image-20260207180229948" style="zoom: 25%;" />

<img src="assets/image-20260207180154354.png" alt="image-20260207180154354" style="zoom: 25%;" />





## 客户端连接

方式一：使用MySQL提供的客户端命令行工具

<img src="assets/image-20260207180102735.png" alt="image-20260207180102735" style="zoom: 25%;" />

方式二：使用系统自带的命令行工具执行指令

<img src="assets/image-20260207180330101.png" alt="image-20260207180330101" style="zoom: 25%;" />

## 数据模型

### 关系型数据库

<img src="assets/image-20260207180616788.png" alt="image-20260207180616788" style="zoom:25%;" />

### 数据模型

MySQL是关系型数据库，是基于二维表进行数据存储的，具体的结构图下：

<img src="assets/image-20260207164843087.png" alt="image-20260207164843087" style="zoom: 50%;" />

- 我们可以通过MySQL客户端连接数据库管理系统DBMS，然后通过DBMS操作数据库。
- 可以使用SQL语句，通过数据库管理系统操作数据库，以及操作数据库中的表结构及数据。 
- 一个数据库服务器中可以创建多个数据库，一个数据库中也可以包含多张表，而一张表中又可以包含多行记录
