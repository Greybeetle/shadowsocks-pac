# shadowsocks-pac
该文件是由`Genpac`和`gfwlist2pac`两个工具生成。生成过程如下：
  1. 安装genpac。安装命令为`sudo pip3 install genpac`，如没有安装pip3或python3，也可以用python2进行安安装。
  2. 生存pac文件。命令如下：  
  ```
    genpac --proxy="SOCKS5 127.0.0.1:1080" --gfwlist-proxy="SOCKS5 127.0.0.1:1080" -o autoproxy.pac --gfwlist-url="https://raw.githubusercontent.com/gfwlist/gfwlist/master/gfwlist.txt"
    ```
