# Github-DNS

## 问题描述

1. github访问慢
2. github图片打不开

## 解决方案

- (Win10用户)通过配置DNS
- 打开C:\Windows\System32\drivers\etc\host
- 在尾部添加以下内容

```
185.199.108.153   github.github.io
151.101.72.133 	  assets-cdn.github.com
151.101.185.194   github.global.ssl.fastly.net
192.30.253.119    gist.github.com
199.232.28.133    assets-cdn.github.com
199.232.28.133    raw.githubusercontent.com
199.232.28.133    gist.githubusercontent.com
199.232.28.133    cloud.githubusercontent.com
199.232.28.133    camo.githubusercontent.com
199.232.28.133    avatars0.githubusercontent.com
199.232.28.133    avatars1.githubusercontent.com
199.232.28.133    avatars2.githubusercontent.com
199.232.28.133    avatars3.githubusercontent.com
199.232.28.133    avatars4.githubusercontent.com
199.232.28.133    avatars5.githubusercontent.com
199.232.28.133    avatars6.githubusercontent.com
199.232.28.133    avatars7.githubusercontent.com
199.232.28.133    avatars8.githubusercontent.com`
```
