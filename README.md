# ForwarderSpoof
firefox用的X-Forwarder-For攻击插件。（改编自官方插件，取消了原版对ip格式的限制，使得它不仅可以进行ip伪造，甚至可以直接用它进行sql注入，xss攻击）  
利用此插件可对X-Forwarder-For漏洞进行攻击  
使用方法（ubuntu为例）：先在官网下载X-Forwarded-For Header插件，然后进入/home/ubuntu/.mozilla/firefox/kls2gtew.default/extensions目录，用{9e00ccd0-bf33-4038-929d-833a4b8d723b}.xpi覆盖掉原文件即可。  
由于没有签名，此插件无法直接安装  
