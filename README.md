# electron
this is linux ssr
安装依赖

sudo apt install libcanberra-gtk-module libcanberra-gtk3-module gconf2 gconf-service libappindicator1

可选依赖(如果软件报错，请安装可选依赖)：

sudo apt-get install libssl-dev

apt-get install libsodium-dev

然后从Linux系统git clone此仓库的地址到您的计算机，deb版本debian系列可以直接安装例如：Debian，Ubuntu，Mint。redred
redhat版本可以使用deb转rpm包工具 （本人随后会在centos发布其他版本支持ssr）
deb的包可以直接打开用软件安装（当然仅限debian）。安装此ssr需要安装python2.7：wget -c https://www.python.org/ftp/python/2.7.9/Python-2.7.9.tgz 
解压安装即可。
另外安装完成后可以通过订阅地址更新订阅也可以通过gui-config.json文件来更新订阅节点。
最后一步在网络里设置一下，图片项目里面有。
