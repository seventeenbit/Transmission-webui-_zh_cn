## Transmission 1.6.1 中文Web-UI

```bash

sudo -i  #获取root权限

wget https://github.com/seventeenbit/Transmission-webui-_zh_cn/raw/main/transmission-web-ui-zh-cn.tar.gz  #下载汉化包

tar zxvf transmission-web-ui-zh-cn.tar.gz  #解压汉化包

mv /volume1/@appstore/transmission/share/transmission/web /volume1/@appstore/transmission/share/transmission/web.backup  #备份原始web文件夹为web.backup

mv -f web /volume1/@appstore/transmission/share/transmission  #移动汉化包到安装目录

```
