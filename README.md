# OneOaaS-CMDB Community Edition

说明:本项目版本归OneOaaS所有，不遵循开源协议，但可以让所有企业免费使用，无需担心版权问题，如有更复杂需求，可以联系使用企业版  

## 功能概要

### 数据中心资源
- 数据中心管理
- 机房管理
- 机柜管理
- 带宽管理
- 硬件管理
- 服务器管理

### 业务资源
- 业务模块

### 供应商资源
- 供应商


## 使用方法

### 配置说明

```
关键说明(以下配置项用户可以根据自己情况进行修改):
httpport 应用端口配置
dbtype  数据库类型配置，当前仅测试过mysql
dbuser  数据库用户配置
dbpass  数据库密码配置
dbhost  数据库主机地址配置
dbport  数据库端口配置
dbname  数据库名称配置

```
### 安装说明

```
安装要求:
1.mysql5.6以上
2.linux 2.6.32 以上

第一步解压安装包：tar -xvf oneoaas-cmdb.2.4.20170509-18.community.linux-2.6.32-504.el6.x86_64.tar.gz
第二步创建数据库：CREATE DATABASE if not exists oneoaas_cmdb  CHARSET utf8 COLLATE utf8_general_ci;
第三步导入数据库：mysql -h localhost -u root -p oneoaas_cmdb < community_edition.sql
第四步启动应用： sh start.sh
第五步访问应用： http://

```

### 界面截图
![cmdb-login](screenshot/cmdb-login.jpeg?raw=true)
![cmdb-datacenter](screenshot/cmdb-datacenter.jpeg?raw=true)
![cmdb-room](screenshot/cmdb-room.jpeg?raw=true)
![cmdb-rack](screenshot/cmdb-rack.jpeg?raw=true)
![cmdb-supplier](screenshot/cmdb-supplier.jpeg?raw=true)
![cmdb-app](screenshot/cmdb-app.jpeg?raw=true)



## 项目合作

- 请联系 support#oneoaas.com(#替换成@)
- 公司官网[www.oneoaas.com](http://www.oneoaas.com)