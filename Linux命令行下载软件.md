# Linux**命令行下载软件**

**1.wget -c** http://apache.opncas.or/MySQL/MySQL-7/v7.0.67/bin/MySQL.zip就是下载该网络想的MySQL.zip压缩包

其中-c：[断点续传](https://www.baidu.com/s?wd=断点续传&tn=SE_PcZhidaonwhc_ngpagmjz&rsv_dl=gh_pc_zhidao)，如果下载中断，那么连接恢复时会从上次断点开始下载

2.**lynx** 命令是纯文本模式的网页浏览器。可以在linux命令行模式下直接输入`lynx URL`访问某个网站

首先，安装lynx
$$
yum list | grep lynx    有结果返回说明可以用yum安装


yum -y install lynx    安装
$$
lynx  http://www.baidu.com  *##  使用 -accept_all_cookies 选项可以跳过后面的操作。*

