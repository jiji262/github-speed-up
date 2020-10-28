# github-speed-up
在国内优雅快速的使用Github的方法

## Github 镜像

https://github.com.cnpmjs.org

https://hub.fastgit.org

## Github加速下载

https://gh.api.99988866.xyz

https://g.ioiox.com

http://toolwa.com/github/

https://github.zhlh6.cn

也可以曲线救国，在Gitee中导入Github项目，然后再下载。

## 工具：Chrome插件

商店内搜索“Github加速” （翻墙）

## 访问 `githubusercontent.com`

修改 `raw.githubusercontent.com` 为 `raw.staticdn.net`

## 修改`hosts`

首先获得要用的IP地址：

访问 `http://github.global.ssl.fastly.net.ipaddress.com/#ipinfo` 得到 `IP1`

访问 `https://github.com.ipaddress.com/#ipinfo` 得到`IP2`

然后用获取到的两个IP修改hosts
```
# sudo vim /etc/hosts
```
```
# github
199.232.69.194 github.global.ssl.fastly.net
140.82.112.4 github.com
```
