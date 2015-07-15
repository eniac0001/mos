# Changelog for Todo Lists by Meteor

### 2015-07-15
---

#### 1、安装配置nginx

  - wget http://nginx.org/download/nginx-1.9.3.tar.gz (cd /usr/src/)
  - tar -zxvf nginx-1.9.3.tar.gz
  - mv nginx-1.9.3 /usr/loca/nginx
  - cd /usr/local/nginx
  - ./configure --prefix=/usr/loca/nginx/
  - make && make install


### 2015-07-14
----

#### 1、NodeJS服务管理

  - npm install pm2 -g

#### 2、Meteor

  - curl https://install.meteor.com/ | sh
  - meteor create --example todos
  
#### 3、安装和配置demeteorizer
  
  - npm install demeteorizer -g
  - 转化过程有待验证


### 2015-07-13
----

#### 1、Basic environments

  - CentOS 7.0 by meituan.mos

#### 2、Basic Setting

  - 更新源：yum -y update
  - 使用 yum 安装程序或库：yum -y install gcc gcc-c++ autoconf libjpeg libjpeg-devel libpng libpng-devel freetype freetype-devel libxml2 libxml2-devel zlib zlib-devel glibc glibc-devel glib2 glib2-devel bzip2 bzip2-devel ncurses ncurses-devel curl curl-devel e2fsprogs e2fsprogs-devel krb5 krb5-devel libidn libidn-devel openssl openssl-devel openldap openldap-devel nss_ldap openldap-clients openldap-servers
  - 安装libevent, memcached 需要： yum -y install libevent libevent-devel
  
#### 3、Install Node

  - 文件放置：/usr/src
  - 获取源码：wget https://nodejs.org/dist/v0.12.7/node-v0.12.7.tar.gz
  - 解压：tar -zxf node-v0.12.7.tar.gz && cd node-v0.12.7
  - 配置、编译和安装：./configure && make && sudo make install
  - 验证：node -v
  - 代码测试：
  
