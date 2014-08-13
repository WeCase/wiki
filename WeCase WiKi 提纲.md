##	WeCase WiKi 提纲

###	WeCase 项目简介
	
*	WeCase 是关于什么的

WeCase 是一款专注于 Linux 平台的新浪微博客户端,快速、轻巧、操作简单，适合大多数 Linux 桌面用户使用，还有关键词过滤，没有关键词数量限制，而且相对于网页版微博， WeCase 还做到了无页面广告的视觉骚扰，免除了微博使用 Adobe®Flash Player® 造成的页面崩溃，还降低了内存占用。

*	WeCase 项目发起时间

发起年月日

*	WeCase 项目目前的成果

0.06-beta8 发布

*	WeCase 项目主要开发人员

参考 GitHub

###	WeCase 安装方式

####	自源代码

#####	WeCase 主程序依赖

*	Python 3, `python3`

*	Python Qt4 Bindings, `python3-qt4`

*	Python Sina Weibo API, `rpweibo`

*	Development tools for PyQt / Qt

#####	WeCase Make依赖

*	Make

*	Automake

#####	WeCase 可选依赖

*	Python-notify2, `python3-notify2`

#####	安装代码

```
git clone git://github.com/WeCase/WeCase.git

# 编译和安装
./bootstrap.sh
mkdir build
cd build
../configure
make
sudo make install

# 运行
wecase
```

####	自发行版

*	Anthon

`apt-get install wecase`

*	Arch

`yaourt -S wecase`

*	Fedora

```
sudo su -c "wget -O- http://download.opensuse.org/repositories/home:/biergaizi/Fedora_$(rpm -E %fedora)/home:biergaizi.repo > /etc/yum.repos.d/wecase.repo"
sudo yum install WeCase
```

*	Ubuntu

```
sudo apt-get install python-software-properties 
sudo add-apt-repository ppa:wecase/ppa 
sudo apt-get update 
sudo apt-get install wecase 
```

*	Gentoo

```
layman -a gentoo-zh
emerge net-misc/WeCase
```

###	WeCase 卸载方式

*	在源码目录以根用户执行`make uninstall`

###	WeCase FAQ

###	WeCase 更新日志

###	WeCase 开发指南

###	WeCase 联系方式