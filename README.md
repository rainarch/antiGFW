# antiGFW

创建目的：年纪大了，老记不住

# 服务器端
找个海外主机当服务器，比如Linode, Ucloud海外都可以。
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
* 对照着服务器端的设置
** IP:/ PORT:/ Password:/ Encryption: aes-256-cfb
* 点击 connect 就可以了。（最好save一下，以后就不用输入上面的内容了）

# 高难度问题
如果一下不好用怎么办。可以再加一层。
