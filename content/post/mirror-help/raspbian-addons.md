+++
title = "raspbian-addons"
tags = ["mirror-help"]
author = "hmsjy2017"
+++

Raspbian Addons 是 Raspbian 非官方软件源，含有许多来自 GitHub 的开源软件，可作为对 Raspbian（Debian） 官方仓库的一个补充。

- 项目地址：https://github.com/chunky-milk/raspbian-addons
- 镜像地址：https://mirror.sjtu.edu.cn/raspbian-addons/

支持架构：armhf、arm64

## 使用方法
```
wget -qO- https://mirror.sjtu.edu.cn/raspbian-addons/KEY.gpg | sudo apt-key add -
echo "deb https://mirror.sjtu.edu.cn/raspbian-addons/debian/ buster main" | sudo tee /etc/apt/sources.list.d/raspbian-addons.list
sudo apt update
```