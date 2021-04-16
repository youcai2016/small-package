![kenzo’s github stats](https://github-readme-stats.vercel.app/api?username=BlueskyClouds&show_icons=true&theme=merko)
<div align="center">
<h1 align="center">small_action</h1>
<img src="https://img.shields.io/github/issues/BlueskyClouds/My-Actions?color=green">
<img src="https://img.shields.io/github/stars/BlueskyClouds/My-Actions?color=yellow">
<img src="https://img.shields.io/github/forks/BlueskyClouds/My-Actions?color=orange">
<img src="https://img.shields.io/github/license/BlueskyClouds/My-Actions?color=ff69b4">
<img src="https://img.shields.io/github/languages/code-size/BlueskyClouds/My-Actions?color=blueviolet">
</div>


#### small-package

*  常用OpenWrt软件包源码合集，同步上游更新！

*  18.06版luci请使用18.06分支

*  19.07版luci请使用19.07分支

*  关于指定19.07分支下载示例:

```bash
 git clone -b 19.07 https://github.com/kenzok8/small-package
```

*  lean源码用18.06分支

*  官方源码用19.07分支


##### 更新日志



#### 使用方式（三选一）：

1. 先cd进package目录，然后执行

```bash
 git clone https://github.com/kenzok8/small-package
```
2. 或者添加下面代码到feeds.conf.default文件

```bash
 src-git small8 https://github.com/kenzok8/small-package
```
3. lede/下运行 或者openwrt/下运行

```bash
git clone https://github.com/kenzok8/small-package package/small-package
```



