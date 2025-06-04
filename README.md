一、mitmproxy安装

Windows安装： https://mitmproxy.org/

pthon包安装：   pip3 install mitmproxy


二、mitmproxy运行，推荐用mitmweb

mitmproxy：提供一个命令行界面，用户可以实时看到发生的请求，并通过命令过滤请求，查看请求数据。

mitmweb  ：提供一个 web 界面，用户可以实时看到发生的请求，并通过 GUI 交互来过滤请求，查看请求数据。

mitmdump：没有界面，程序默默运行，所以 mitmdump 无法提供过滤请求、查看数据的功能，只能结合自定义脚本。


三、证书安装

1.Windows设置代理

地址：127.0.0.1 端口：8080

2.Windows端证书安装（需运行mitmproxy）

Windows端浏览器输入 https://mitm.it/，下载Windows端证书并安装

3.手机端证书安装（需运行mitmproxy）

手机wifi与Windows同局域网，修改wifi代理服务器：手动-WindowsIP-8080

手机端浏览器输入 https://mitm.it/，下载Android/iOS端证书并安装
