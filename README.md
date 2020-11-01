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

### 方法1

修改 `raw.githubusercontent.com` 为 `raw.staticdn.net`

### 方法2

在 [https://site.ip138.com/raw.Githubusercontent.com/](https://site.ip138.com/raw.Githubusercontent.com/) 输入raw.githubusercontent.com查询IP地址,然后修改host：

```
sudo vi /etc/hosts
```

```
# GitHub Start
52.74.223.119 github.com
192.30.253.119 gist.github.com
54.169.195.247 api.github.com
185.199.111.153 assets-cdn.github.com
151.101.76.133 raw.githubusercontent.com
151.101.108.133 user-images.githubusercontent.com
151.101.76.133 gist.githubusercontent.com
151.101.76.133 cloud.githubusercontent.com
151.101.76.133 camo.githubusercontent.com
151.101.76.133 avatars0.githubusercontent.com
151.101.76.133 avatars1.githubusercontent.com
151.101.76.133 avatars2.githubusercontent.com
151.101.76.133 avatars3.githubusercontent.com
151.101.76.133 avatars4.githubusercontent.com
151.101.76.133 avatars5.githubusercontent.com
151.101.76.133 avatars6.githubusercontent.com
151.101.76.133 avatars7.githubusercontent.com
151.101.76.133 avatars8.githubusercontent.com
```

## 其他修改`hosts`的方法（备用）

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
