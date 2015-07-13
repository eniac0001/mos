# Changelog for Todo Lists by Meteor


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
  - 解压：tar -zvxf node-v0.12.7.tar.gz && cd node-v0.12.7
  - 配置、编译和安装：./configure --prefix=/usr/local/nodejs/ && make && make install
  - 验证：node -v
  - 代码测试：
  
