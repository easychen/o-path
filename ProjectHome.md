演示视频和说明文章： http://ftqq.com/2011/12/30/how-to-build-a-path-like-app-using-html5-and-phonegap/



# 安装指南 #

## 客户端，以iOS系统为例 ##
下载 http://code.google.com/p/o-path/downloads/detail?name=opath-ios-phonegap.zip 用xcode打开编译即可

## 服务器端 ##

需要使用SAE环境 http://sae.sina.com.cn/

  1. 创建应用
  1. 下载 http://code.google.com/p/o-path/downloads/detail?name=opath-php-sql.zip 并解压
  1. 初始化应用的MySQL，将app\_opath.sql导入
  1. 开启Storage,创建一个名为 upload 的公有domain，放头像和图片用。
  1. 解压 opath-sae-php-code.zip，通过SVN或者SDK部署到SAE上


## 使用客户端登录 ##

  1. login页面的domain改成你创建应用的domain。完整格式为 xxx.sinaapp.com
  1. 管理用户： admin/admin@admin.com 测试用户 guest/guest@guest.com
  1. 可以通过PHPMyAdmin向user表中添加记录来创建成员，密码为明文的MD5值。

# Install #

demo video and introduction: http://ftqq.com/2011/12/30/how-to-build-a-path-like-app-using-html5-and-phonegap/

## client , iOS as eg. ##
download  http://code.google.com/p/o-path/downloads/detail?name=opath-ios-phonegap.zip , open with xcode.

## server ##
using sina.com's cloudplatform - http://sae.sina.com.cn/

if you put those code on standard PHP runtime , the picture upload function will be disabled.

### standard PHP ###

  1. download  http://code.google.com/p/o-path/downloads/detail?name=opath-php-sql.zip and unzip it
  1. create mysql database , import the sql file and config it in  app/config/db.config.php
  1. upload the code and visit

## using client to login ##
  1. change the domain on login page to yours
  1. admin account： admin/admin@admin.com |  test account : guest/guest@guest.com
  1. use PHPMyAdmin add user by adding recored in user table , password field md5ed.
