 1. 下载并安装v2Raya，以ubuntu20.04为例：
 ```
  wget https://github.com/v2rayA/v2rayA/releases/download/v1.2.2/installer_debian_amd64_v1.2.2.deb
 ```
 ```
   sudo apt install ./installer_debian_amd64_v1.2.2.deb
 ```
 2. v2Raya只是一个图形化的界面，还需要下载v2Ray Core：
 ```
 wget https://github.com/v2ray/v2ray-core/releases/download/v4.28.2/v2ray-linux-64.zip
 ```
 3. 启动v2raya， --address 可以指定端口，--v2ray-bin指定v2ray Core.
 ```
 sudo v2raya --address 127.0.0.1:8080 --v2ray-bin ~/software/v2ray/v2ray-linux-64/v2ray
 ```
 4. 打开 127.0.0.1:8080，使用方法和windows下v2rayN 差不多啦，可以自己慢慢explore了。
