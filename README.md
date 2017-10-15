# antiGFW

创建目的：年纪大了，老记不住

# 服务器端

## 安装
Debian / Ubuntu:

apt-get install python-pip

pip install shadowsocks

## 启动服务

/usr/local/bin/ssserver -s 10.8.81.82 -p $myport -k $mypwd -m aes-256-cfb 


# 客户端

## 安装 yingwa （Windows）

* 解压
* 用管理员身份运行 yingwa.exe
* 设置见网页
    IP:/ PORT:/ Password:/ Encryption: aes-256-cfb
* 点击 connect 就可以了。（最好save一下，以后就不用输入上面的内容了）
